## Get one event data

```shell
curl "http://api.tokyoartbeat.com/api/v1/events/:id/:lang "
```

> The above command returns JSON structured like this when id = 2016/A2E2 and lang = en

```json
{
  "query_time": 0.67000007629395,
  "event": {
    "en": {
      "event_id": "2016\/A2E2",
      "event_status": false,
      "event_link": "http:\/\/www.tokyoartbeat.com\/event\/2016\/A2E2.en",
      "page_uri": "http:\/\/www.tokyoartbeat.com\/event\/2016\/A2E2",
      "photo": "\/media\/event\/2016\/A2E2-620",
      "name": "Keith Haring \u201dGlowing - Evolving Forms\u201c",
      "description_raw": "An exhibition surveying the ever expanding and evolving forms of Keith Haring\u2019s work, especially in the late 1980s, featured alongside day glow paintings produced in collaboration with graffiti writer LAII. ",
      "description_html": "An exhibition surveying the ever expanding and evolving forms of Keith Haring\u2019s work, especially in the late 1980s, featured alongside day glow paintings produced in collaboration with graffiti writer LAII. ",
      "artist": ["Keith Haring"],
      "artist_etc": false,
      "image_copyright": "",
      "venue": {
        "id": "B4DF46FE",
        "name": "Nakamura Keith-Haring Collection",
        "type": "Museum",
        "description": "",
        "permanent": 0,
        "contact": {
          "fee": "Adults \u00a51000, University Students and Seniors over 65 \u00a5800, High, Junior High and Elementaly School Students \u00a5600, Infants free.",
          "phone": "0551-36-8712",
          "fax": "",
          "web": "http:\/\/www.nakamura-haring.com\/pg25.html",
          "web_lang": null,
          "address": "10249-7 Kobuchizawamachi, Kitamori-shi, Yamanashi 408-0044",
          "access": "From JR Kobuchizawa station, take the Yatsugatake Kogen Resort bus and get off at Nakamura Keith-Haring Bijutsukan.",
          "discount": "0",
          "discount_details": ""
        },
        "geo": {
          "area": "other",
          "long": "138.318775",
          "lat": "35.887612"
        },
        "schedule": {
          "openinghour": "10:00",
          "closinghour": "17:00",
          "breakstart": false,
          "breakend": false,
          "openingdetails": false,
          "details": "Closed during the winter holidays.",
          "closed": {
            "mon": 0,
            "tue": 0,
            "wed": 0,
            "thu": 0,
            "fri": 0,
            "sat": 0,
            "sun": 0,
            "hol": 0
          }
        }
      },
      "categories": [{
        "id": "print_graphicdesign",
        "name": "Graphics",
        "group": "2D",
        "link": "Graphics"
      }, {
        "id": "print_painting",
        "name": "Painting",
        "group": "2D",
        "link": "Painting"
      }, {
        "id": "print_drawing",
        "name": "Drawing",
        "group": "2D",
        "link": "Drawing"
      }],
      "one_category_link": "painting",
      "one_category_name": "Painting",
      "url": "http:\/\/118.82.80.197\/news\/2016\/03\/2016.html",
      "url_lang": null,
      "fee": {
        "description": "",
        "discount": "0",
        "discount_details": ""
      },
      "schedule": {
        "permanent": false,
        "date_warning": "Ends in 193 days",
        "time_alert": false,
        "start_date": "2016-04-24",
        "start_time": false,
        "end_date": "2017-01-31",
        "end_time": false,
        "one_day_event": false,
        "party": {
          "type": "Opening reception",
          "date": false,
          "start": false,
          "end": false,
          "info": false
        },
        "extra": "Exbition Hours: 9:00-17:00, Open everyday throughout the exhibition"
      },
      "nearby_events": null
    }
  },
  "mupon": {
    "error": {
      "code": 400,
      "description": "non valid event ID"
    }
  },
  "cached_at": "2016-07-22 06:49:15"
}
```


This endpoint retrieves the data of an individual event by its id. We already have an API on current system giving us this json answer.
We don't use it in the current TAB app at the moment as the data for events are also sent in the lists of events.
This API is used on the website for /events as it offers more data.

We have to discuss if we use something like this or not for the new app.

### HTTP Request

`GET http://api.tokyoartbeat.com/api/v1/events/:id/:lang`

### URL Parameters

Parameter | Description
--------- | -----------
id | event id
lang | "en" or "ja"


