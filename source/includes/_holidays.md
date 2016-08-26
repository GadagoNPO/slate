# Holiday

## Check if current or next day is a holiday

```shell
curl "http://api.tokyoartbeat.com/api/v1/holidays/:lang"
```

> The above command returns JSON structured like this 

```json
{
  "holidays" : [
    { "today" :  { status : true, date: "", text :"yama  no hi" } },
    { "tomorrow" : { status : false, date: "" } } ,
  ],
}
```

This endpoint check if current day or next next day is a holiday THIS IS A NEW API TO BUILD

### HTTP Request

`GET http://api.tokyoartbeat.com/api/v1/holidays/:lang`

### URL Parameters

Parameter | Description
--------- | -----------
lang | "en" or "ja"
