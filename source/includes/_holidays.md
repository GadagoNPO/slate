# Holidays

## Check if current or next day is a holiday

```shell
curl "http://api.tokyoartbeat.com/api/v1/holidays"
```

> The above command returns JSON structured like this 

```json
{
  "holidays":[
    {
    "today":{
      "is_holiday":true,
      "date":"2016-08-11",
      "name":"山の日"
      }
    },
    {
    "tomorrow":{
      "is_holiday":false,
      "date":"2016-08-12"
      }
    },
    {
    "next_holiday":{
      "date":"2016-09-19",
      "name":"敬老の日"
      }
    }
  ]
}
```

This endpoint check if current day or/and next next day is a holiday <del>THIS IS A NEW API TO BUILD</del> : DONE!

Note :

1 - I added next_holiday because... I could. Not sure it has any value

2 - name will be only in Japanese, the the GEM does not provide English version, maybe we could fork the repo and offer translation ability... or not.

### HTTP Request

`GET http://api.tokyoartbeat.com/api/v1/holidays`

### URL Parameters

Parameter | Description
--------- | -----------
There is no parameter.
