## List of events by genre

```shell
curl "https://api-staging.tokyoartbeat.com/api/v1/events/genre/graphicdesign?locale=en"
```

> The above command returns JSON structured like this when id = graphicdesign and lang = en

```json
[
  {
  id: "2016/A2E2",
  href: "http://www.tokyoartbeat.com/event/2016/A2E2",
  name: "Keith Haring ”Glowing - Evolving Forms“",
  venue: {
  href: "http://www.tokyoartbeat.com/venue/B4DF46FE",
  name: "Nakamura Keith-Haring Collection",
  type: "Museum",
  address: "10249-7 Kobuchizawamachi, Kitamori-shi, Yamanashi 408-0044",
  phone: "0551-36-8712",
  fax: null,
  access: "From JR Kobuchizawa station, take the Yatsugatake Kogen Resort bus and get off at Nakamura Keith-Haring Bijutsukan.",
  area: "Kanto: others",
  opening_hour: "10:00:00",
  closing_hour: "17:00:00",
  days_closed: {
  mon: "0",
  tue: "0",
  wed: "0",
  thu: "0",
  fri: "0",
  sat: "0",
  sun: "0",
  hol: "0"
  },
  schedule_details: null,
  schedule_note: "Closed during the winter holidays."
  },
  media: [
  "2D: Graphics",
  "2D: Painting",
  "2D: Drawing"
  ],
  description: "An exhibition surveying the ever expanding and evolving forms of Keith Haring’s work, especially in the late 1980s, featured alongside day glow paintings produced in collaboration with graffiti writer LAII. ",
  image: [
  {
  src: "http://www.tokyoartbeat.com/media/event/2016/A2E2-30",
  width: "30"
  },
  {
  src: "http://www.tokyoartbeat.com/media/event/2016/A2E2-80",
  width: "80"
  },
  {
  src: "http://www.tokyoartbeat.com/media/event/2016/A2E2-170",
  width: "170"
  }
  ],
  karma: "0.733079",
  price: "Adults ¥1000, University Students and Seniors over 65 ¥800, High, Junior High and Elementaly School Students ¥600, Infants free.",
  date_start: "2016-04-24",
  date_end: "2017-01-31",
  schedule_note: "Exbition Hours: 9:00-17:00, Open everyday throughout the exhibition",
  days_before_end: "124",
  permanent_event: "0",
  distance: "0",
  datum: "tokyo",
  latitude: "35.884436",
  longitude: "138.321879",
  link: "https://api-staging.tokyoartbeat.com/api/v1/events/2016/A2E2"
  },
  { ... }
]
```

This endpoint retrieves the list of events by genre. We already have an API on current system giving us an XML answer, we will use it to produce this json result.  

### HTTP Request

`GET https://api-staging.tokyoartbeat.com/api/v0/events/genre/:id?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
id | one of the existing genre (graphicdesign, etc...) retrieved from Lists API
locale | "en" or "ja"
