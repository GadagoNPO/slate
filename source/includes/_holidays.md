# Holidays

## Check if current or next day is a holiday

```shell
curl "http://api.tokyoartbeat.com/api/v1/holidays/:lang"
```

> The above command returns JSON structured like this 

```json
{
  "holidays" : [
    { "today" : { "status" : true, "date" : "2016-08-11", "text" : "yama  no hi" } },
    { "tomorrow" : { "status" : false, "date" : "2016-08-12" } }
  ]
}
```

This endpoint check if current day or/and next next day is a holiday THIS IS A NEW API TO BUILD

### HTTP Request

`GET http://api.tokyoartbeat.com/api/v1/holidays/:lang`

### URL Parameters

Parameter | Description
--------- | -----------
lang | "en" or "ja"
