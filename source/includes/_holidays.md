# Holidays

## Check if current or next day is a holiday

```shell
now : 

curl "https://staging-api.tokyoartbeat.com/api/v0/holidays"

later : 

curl "https://staging-api.tokyoartbeat.com/api/v1/holidays"

curl "https://api.tokyoartbeat.com/api/v1/holidays"
```

> The above command returns JSON structured like this 

```json
{
  "holidays": [
    {
      "yesterday": {
      "is_holiday": false,
      "date": "2016-09-28"
      }
    },
    {
      "today": {
      "is_holiday": false,
      "date": "2016-09-29"
      }
    },
    {
      "tomorrow": {
      "is_holiday": false,
      "date": "2016-09-30"
      }
    },
    {
      "next_holiday": {
      "date": "2016-10-10",
      "name": "体育の日"
      }
    }
  ]
}
```

This endpoint check if current day or/and next next day or previous day is a holiday <del>THIS IS A NEW API TO BUILD</del> : DONE!

Note :

1 - I added next_holiday because... I could. Not sure it has any value

2 - name will be only in Japanese, the the GEM does not provide English version, maybe we could fork the repo and offer translation ability... or not.

### HTTPS Request

`GET https://api-staging.tokyoartbeat.com/api/v0/holidays`


### URL Parameters

Parameter | Description
--------- | -----------
There is no parameter.
