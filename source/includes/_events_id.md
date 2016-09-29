## Get one event data

```shell
curl "http://api.tokyoartbeat.com/api/v1/events/2016/F3C3?locale=en "
```

> The above command returns JSON structured like this when id = 2016/F3C3 and locale = en

```json
{
event: {
event_id: "2016/F3C3",
event_status: false,
event_link: "http://www.tokyoartbeat.com/event/2016/F3C3.en",
page_uri: "http://www.tokyoartbeat.com/event/2016/F3C3",
photo: "/resources/images/nopic_170",
name: "MOMAT Collection by Yoshitomo Nara - Modern Landscape: For the Pleasure of People and Scenery",
description_raw: "Noted artist Yoshitomo Nara serves as guest curator for this exhibition, selecting his favorite works from the MOMAT Collection. Among his choices there is included a work by Saburo Aso, Nara’s teacher in university, and Shunsuke Matsumoto, a friend of Aso’s who also managed to survive World War II. There is also a portrait of a robust girl by Kaita Murayama, and a nude by Junnosuke Yokoyama, in which, according to Nara, the woman’s hair is the most crucial element. Selecting works that strike his fancy without any regard for art history, Nara automatically narrowed his focus to depictions of people and scenery produced between the 1910s and 1950s. Though Nara is often regarded as a painter of people, he actually considers scenery, such as streets and fields, to be just as important as human figures. Nara believes that combining people with external scenery is what makes a landscape.From well-known masterpieces to rarely seen items, the exhibition boasts a generous sampling of approximately 60 works. Some pieces are accompanied by Nara’s comments on the artist and work. Enjoy discovering the new charms of these works as seen through the eyes of Yoshitomo Nara . ",
description_html: "Noted artist Yoshitomo Nara serves as guest curator for this exhibition, selecting his favorite works from the MOMAT Collection. Among his choices there is included a work by Saburo Aso, Nara’s teacher in university, and Shunsuke Matsumoto, a friend of Aso’s who also managed to survive World War II. There is also a portrait of a robust girl by Kaita Murayama, and a nude by Junnosuke Yokoyama, in which, according to Nara, the woman’s hair is the most crucial element. Selecting works that strike his fancy without any regard for art history, Nara automatically narrowed his focus to depictions of people and scenery produced between the 1910s and 1950s. Though Nara is often regarded as a painter of people, he actually considers scenery, such as streets and fields, to be just as important as human figures. Nara believes that combining people with external scenery is what makes a landscape.From well-known masterpieces to rarely seen items, the exhibition boasts a generous sampling of approximately 60 works. Some pieces are accompanied by Nara’s comments on the artist and work. Enjoy discovering the new charms of these works as seen through the eyes of Yoshitomo Nara .</p> <p> ",
artist: [
"Saburo Aso",
" Shunsuke Matsumoto",
" Chikatoshi Enomoto",
" Kaita Murayama",
" Yoshitomo Nara"
],
artist_etc: "et al.",
image_copyright: "",
venue: {
id: "1AA8A2F2",
name: "The National Museum of Modern Art, Tokyo",
type: "Museum",
description: "The National Museum of Modern Art, Tokyo consists of the Museum and Crafts Gallery in Kitanomaru Koen, near the Imperial Palace, and the National Film Center in Kyobashi. Activities are undertaken with the view of providing a systematic overview of modern Japanese art within the context of modern art all over the world and widely promoting an interest in art.",
permanent: 0,
contact: {
fee: "Adults ¥430, University Students ¥130, High School Sudents and under, Seniors over 65, Registered Disabled + 1 assistant free, Special Exhibition Fees may be charged separately.",
phone: "03-5777-8600",
fax: "",
web: "http://www.momat.go.jp/english/am/",
web_lang: null,
address: "3-1 Kitanomaru Koen, Chiyoda-ku, Tokyo 102-8322",
access: "3 minutes walk from Exit 1B at Takebashi Station on the Tozai Line.",
discount: "0",
discount_details: ""
},
geo: {
area: "chiyoda",
long: "139.754681",
lat: "35.690511"
},
schedule: {
openinghour: "10:00",
closinghour: "17:00",
breakstart: false,
breakend: false,
openingdetails: "fridays closinghour 20:00",
details: "Closed on the new year holidays and during changing exhibitions. On a Public Holiday Monday, the museum is open but closed on the following Tuesday.",
closed: {
mon: 1,
tue: 0,
wed: 0,
thu: 0,
fri: 0,
sat: 0,
sun: 0,
hol: 0
}
}
},
categories: [
{
id: "print_painting",
name: "Painting",
group: "2D",
link: "Painting"
},
{
id: "print_drawing",
name: "Drawing",
group: "2D",
link: "Drawing"
},
{
id: "3D_sculpture",
name: "Sculpture",
group: "3D",
link: "Sculpture"
}
],
one_category_link: "sculpture",
one_category_name: "Sculpture",
url: "http://www.momat.go.jp/english/am/exhibition/nara_selection20160524/",
url_lang: null,
fee: {
description: "Adults ¥430, University Students ¥130, High School Sudents and under, Seniors over 65, Those with a disability certificate + 1 companion free.",
discount: "0",
discount_details: ""
},
schedule: {
permanent: false,
date_warning: "Ends in 45 days",
time_alert: false,
start_date: "2016-05-24",
start_time: false,
end_date: "2016-11-13",
end_time: false,
one_day_event: false,
party: {
type: "Opening reception",
date: false,
start: false,
end: false,
info: false
},
extra: "Closed from Aug 8th to Aug 15th. Open until 20:00 on Fridays and Saturdays."
},
nearby_events: [
{
venue_id: "1AA8A2F2",
event_id: "2016/F577",
event_title: "MOMAT Collection",
distance: "Same venue",
timeleft: false,
img_src: "/resources/images/nopic_170"
},
{
venue_id: "1AA8A2F2",
event_id: "2016/E575",
event_title: "Thomas Ruff Exhibition",
distance: "Same venue",
timeleft: false,
img_src: "/media/event/2016/E575"
},
{
venue_id: "CEAC383E",
event_id: "2016/C3D7",
event_title: "Sagan Ga",
distance: "9 mins away",
timeleft: false,
img_src: "/media/event/2016/C3D7"
},
{
venue_id: "9F37AE41",
event_id: "2016/B8A9",
event_title: "Wakirou Sumi “Le Calme”",
distance: "17 mins away",
timeleft: "Ends in 2 days",
img_src: "/media/event/2016/B8A9"
},
{
venue_id: "9555AC2D",
event_id: "2016/8938",
event_title: "Firegraphy",
distance: "19 mins away",
timeleft: false,
img_src: "/media/event/2016/8938"
},
{
venue_id: "C4EC53A8",
event_id: "2016/D536",
event_title: "Carolina Ceca “Immaterial”",
distance: "19 mins away",
timeleft: false,
img_src: "/media/event/2016/D536"
}
]
},
mupon: {
error: {
code: 400,
description: "non valid event ID"
}
},
last_updated: "2016-09-29 06:45:31"
}
```

### HTTP Request

`GET https://api-staging.tokyoartbeat.com/api/v0/events/:id?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
id | event id
locale | "en" or "ja"



