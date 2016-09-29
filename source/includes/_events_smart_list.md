# Events

## List of events for a smart list

```shell
curl "https://staging-api.tokyoartbeat.com/api/v0/events/smart/most_popular?locale=en"
```

> The above command returns JSON structured like this when id = most_popular and locale = en

```json
[
  {
  id: "2016/F3C3",
  href: "http://www.tokyoartbeat.com/event/2016/F3C3",
  name: "MOMAT Collection by Yoshitomo Nara - Modern Landscape: For the Pleasure of People and Scenery",
  venue: {
  href: "http://www.tokyoartbeat.com/venue/1AA8A2F2",
  name: "The National Museum of Modern Art, Tokyo",
  type: "Museum",
  address: "3-1 Kitanomaru Koen, Chiyoda-ku, Tokyo 102-8322",
  phone: "03-5777-8600",
  fax: null,
  access: "3 minutes walk from Exit 1B at Takebashi Station on the Tozai Line.",
  area: "Chiyoda",
  opening_hour: "10:00:00",
  closing_hour: "17:00:00",
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
  schedule_details: "fridays closinghour 20:00",
  schedule_note: "Closed on the new year holidays and during changing exhibitions. On a Public Holiday Monday, the museum is open but closed on the following Tuesday."
  },
  media: [
  "2D: Painting",
  "2D: Drawing",
  "3D: Sculpture"
  ],
  external_link: {
  href: "http://www.momat.go.jp/english/am/exhibition/nara_selection20160524/"
  },
  description: "Noted artist Yoshitomo Nara serves as guest curator for this exhibition, selecting his favorite works from the MOMAT Collection. Among his choices there is included a work by Saburo Aso, Nara’s teacher in university, and Shunsuke Matsumoto, a friend of Aso’s who also managed to survive World War II. There is also a portrait of a robust girl by Kaita Murayama, and a nude by Junnosuke Yokoyama, in which, according to Nara, the woman’s hair is the most crucial element. Selecting works that strike his fancy without any regard for art history, Nara automatically narrowed his focus to depictions of people and scenery produced between the 1910s and 1950s. Though Nara is often regarded as a painter of people, he actually considers scenery, such as streets and fields, to be just as important as human figures. Nara believes that combining people with external scenery is what makes a landscape.From well-known masterpieces to rarely seen items, the exhibition boasts a generous sampling of approximately 60 works. Some pieces are accompanied by Nara’s comments on the artist and work. Enjoy discovering the new charms of these works as seen through the eyes of Yoshitomo Nara . ",
  image: [
  {
  src: "http://www.tokyoartbeat.com/resources/images/nopic",
  width: "30"
  },
  {
  src: "http://www.tokyoartbeat.com/resources/images/nopic_80",
  width: "80"
  },
  {
  src: "http://www.tokyoartbeat.com/resources/images/nopic_170",
  width: "170"
  }
  ],
  karma: "19.7118",
  price: "Adults ¥430, University Students ¥130, High School Sudents and under, Seniors over 65, Those with a disability certificate + 1 companion free.",
  date_start: "2016-05-24",
  date_end: "2016-11-13",
  schedule_note: "Closed from Aug 8th to Aug 15th. Open until 20:00 on Fridays and Saturdays.",
  days_before_end: "45",
  permanent_event: "0",
  distance: "0",
  datum: "tokyo",
  latitude: "35.687275",
  longitude: "139.7579",
  link: "https://api-staging.tokyoartbeat.com/api/v1/events/2016/F3C3"
  },
  { ... }
]
```

This endpoint retrieves the list of events for a smart list. We already have an API on current system giving us an XML answer, we will use it to produce this json result.  

### HTTP Request

`GET https://api-staging.tokyoartbeat.com/api/v1/events/smart/:id?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
id | one of the existing smart lists (most_popular, etc...) retrieved from Lists API
locale | "en" or "ja"
