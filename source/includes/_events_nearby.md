## List of events nearby

```shell
curl "http://api.tokyoartbeat.com/api/v1/events/nearby/:long/:lat?locale=en"
```

> The above command returns JSON structured like this :

```json
{
  "events" : [
      {
      "lang": "en",
      "id": "2016/A2E2",
      "link" : "https://api.tokyoartbeat",
      "href": "http://www.tokyoartbeat.com/event/2016/A2E2",
      "name": "Keith Haring ”Glowing - Evolving Forms“",
      "venue": {
        "href": "http://www.tokyoartbeat.com/venue/B4DF46FE",
        "name": "Nakamura Keith-Haring Collection",
        "type": "Museum",
        "address": "10249-7 Kobuchizawamachi, Kitamori-shi, Yamanashi 408-0044",
        "phone": "0551-36-8712",
        "access": "From JR Kobuchizawa station, take the Yatsugatake Kogen Resort bus and get off at Nakamura Keith-Haring Bijutsukan.",
        "area": {
          "id": "other",
          "text": "Kanto: others"
        },
        "openingHour": "10:00:00",
        "closingHour": "17:00:00",
        "daysClosed": {
          "mon": "0",
          "tue": "0",
          "wed": "0",
          "thu": "0",
          "fri": "0",
          "sat": "0",
          "sun": "0",
          "hol": "0"
        },
        "scheduleNote": "Closed during the winter holidays."
      },
      "media": [
        "2D: Graphics",
        "2D: Painting",
        "2D: Drawing"
      ],
      "description": "An exhibition surveying the ever expanding and evolving forms of Keith Haring’s work, especially in the late 1980s, featured alongside day glow paintings produced in collaboration with graffiti writer LAII. ",
      "image": [
        {
          "src": "http://www.tokyoartbeat.com/media/event/2016/A2E2-30",
          "width": "30"
        },
        {
          "src": "http://www.tokyoartbeat.com/media/event/2016/A2E2-80",
          "width": "80"
        },
        {
          "src": "http://www.tokyoartbeat.com/media/event/2016/A2E2-170",
          "width": "170"
        }
      ],
      "karma": "0.749931",
      "price": {
        "free": "0",
        "text": "Adults ¥1000, University Students and Seniors over 65 ¥800, High, Junior High and Elementaly School Students ¥600, Infants free."
      },
      "dateStart": "2016-04-24",
      "dateEnd": "2017-01-31",
      "scheduleNote": "Exbition Hours: 9:00-17:00, Open everyday throughout the exhibition",
      "daysBeforeEnd": "193",
      "permanentEvent": "0",
      "distance": "0",
      "datum": "tokyo",
      "latitude": "35.884436",
      "longitude": "138.321879"
    },
    { ... },
    { ... }
    ]
}
```

This endpoint retrieves the list of events nearby. We already have an API on current system giving us an XML answer, we will use it to produce this json result.

--- Present JSON object might change - WIP ---

### HTTP Request

`GET https://api-staging.tokyoartbeat.com/api/v0/events/nearby/:long/:lat?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
long | longitude (format TBD)
lat | latitude (format TBD)
locale | "en" or "ja"

