## List of events by area

```shell
curl "https://api-staging.tokyoartbeat.com/api/v1/events/area/ginza_marunouchi?locale=en "
```

> The above command returns JSON structured like this when id = ginza_marunouchi and lang = en

```json
[
  {
  id: "2013/9373",
  href: "http://www.tokyoartbeat.com/event/2013/9373",
  name: "MADE IN UMUT - The University of Tokyo Collection",
  venue: {
  href: "http://www.tokyoartbeat.com/venue/B3279C43",
  name: "Intermediatheque",
  type: "Museum",
  address: "2F, 3F JP Tower, 2-7-2 Marunouchi, Chiyoda-ku, Tokyo 100-7003",
  phone: "03-5777-8600",
  fax: null,
  access: "1 minute walk from the Marunouchi South exit of JR Tokyo Station.",
  area: "Ginza, Marunouchi",
  opening_hour: "11:00:00",
  closing_hour: "18:00:00",
  days_closed: {
  mon: "1",
  tue: "0",
  wed: "0",
  thu: "0",
  fri: "0",
  sat: "0",
  sun: "0",
  hol: "0"
  },
  schedule_details: "fridays closinghour 20:00, saturdays closinghour 20:00",
  schedule_note: "Open on a public holiday Monday but closed the following day. Closed over the New Year holidays."
  },
  external_link: {
  href: "http://www.intermediatheque.jp/en/schedule/view/id/IMT0001"
  },
  description: "Since its foundation in 1877, the University of Tokyo has accumulated a considerable scientific and cultural heritage. Such historical specimens are most certainly an important heritage from the past. However, at the same time, they constitute a resource which we should activate now while facing the future. In order to demonstrate this, we have collected as much historical heritage as possible, and modified its design for a new use, in accordance with our contemporary needs, in the name of a process called ReDESIGN+. Just as the Intermediatheque is built on the reincarnation and inheritance of the former Central Post Office, we have renovated this ancient building and given it a new life as a museum. Nevertheless, this does not imply that we have to consider ReDESIGN+ as a bare revamp activity. In the same way as the etymological meaning of the word design, ReDESIGN+ deals with the problem of appearance at the same time as it raises epistemological issues on our view of things and our view of the world. As for the spatial distribution of the exhibits, we deliberately avoided the common method of setting up a visiting route. What the Intermediatheque aims at is providing a museum space where visitors, and especially younger generations, can experience a direct visual contact with exhibits, in an encounter full of discoveries and astonishment. Considering the fact that the architecture of the former Post Office building is representative of early Showa modernism, the permanent and semi-permanent exhibition spaces were designed so as to produce a retromodern atmosphere. Respecting the building’s original design, we have adopted an eclectic design principle stimulating our twenty-first century sensitivity, tentatively named retrofuturism. We thus intend to present to our visitors a period bridging three centuries, from the 19th to the 21st Century. Such is the base of our design strategy for the Intermediatheque. With such a scheme in mind, we have actively redesigned and reused the prewar wooden furniture that was accumulated in our museum. On the other hand, a modern sensitivity is created through the use of showcases made of thick green glass and designed in a retromodern style. These are a fruit of the research conducted in product design at the Intermediatheque. Venue：COLONNADE 2 COLONNADE 3 *The period of the Special Exhibitions of Intermediatheque are unconfirmed and so the final date recorded on TAB is only a temporary guideline",
  image: [
  {
  src: "http://www.tokyoartbeat.com/media/event/2013/9373-30",
  width: "30"
  },
  {
  src: "http://www.tokyoartbeat.com/media/event/2013/9373-80",
  width: "80"
  },
  {
  src: "http://www.tokyoartbeat.com/media/event/2013/9373-170",
  width: "170"
  }
  ],
  karma: "0.944044",
  price: "Free",
  date_start: "2013-03-21",
  date_end: "2017-01-29",
  schedule_note: null,
  days_before_end: "122",
  permanent_event: "0",
  distance: "0",
  datum: "tokyo",
  latitude: "35.676599",
  longitude: "139.767953",
  link: "https://api-staging.tokyoartbeat.com/api/v1/events/2013/9373"
  },
  { ... }
]
```

This endpoint retrieves the list of events by area. We already have an API on current system giving us an XML answer, we will use it to produce this json result.  

### HTTP Request

`GET https://api-staging.tokyoartbeat.com/api/v0/events/area/:id?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
id | one of the existing area (shibuya, etc...) retrieved from Lists API
locale | "en" or "ja"
