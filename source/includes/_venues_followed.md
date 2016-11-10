# Venues

## Venues followed

```shell
curl "https://api-staging.tokyoartbeat.com/api/v1/venues/follows?access_token=:user_access_token&locale=en"
```

> The above command returns JSON structured like this 

```json
{
  "events": [
    {
      "event_id": "2016/B253",
      "event_title": "Nam June Paik “Who Will be Laughing in 2020 ?+?=??”",
      "artist": "Nam June Paik",
      "venue": {
        "id": "7879E100",
        "name": "Watari-um, The Watari Museum of Contemporary Art"
      },
      "schedule": {
        "date_start": 1468681200,
        "time_start": "00:00:00",
        "date_end": 1485615600,
        "time_end": "00:00:00",
        "is_permanent": false
      },
      "image": {
        "src": "http://www.tokyoartbeat.com/media/event/2016/B253-670",
        "width": "670"
      },
      "goings_count": 3,
      "link": "https://api-staging.tokyoartbeat.com/api/v1/events/2016/B253"
    }
  ],
  "pagination": {
    "total_nb_of_events": 1,
    "nb_of_pages": 1,
    "current_page": 1,
    "count_on_this_page": 1,
    "max_per_page": 20
  }
}
```

This endpoint retrieves the logged in user list of events for the corresponding followed venues.

### HTTP Request

`GET https://api-staging.tokyoartbeat.com/api/v1/venues/follow?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
locale | "en" or "ja"
access_token | user access token