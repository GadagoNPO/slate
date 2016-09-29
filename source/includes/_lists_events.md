## Get lists of available lists of events

```shell
curl "https://staging-api.tokyoartbeat.com/api/v0/lists/genre?locale=en"

or

curl "https://staging-api.tokyoartbeat.com/api/v0/lists/genre?locale=ja"

or

curl -H Accept-language:en "https://api-staging.tokyoartbeat.com/api/v0/lists/genre"

or

curl -H Accept-language:ja "https://api-staging.tokyoartbeat.com/api/v0/lists/genre"
```

> The above command returns JSON structured like this when locale = en and id = genre

```json
{
"lists:" [
  {
  "code": "graphicdesign",
  "name": "Graphic Design",
  "order": "1.0",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/graphicdesign",
  "nb_of_events": 14
  },
  {
  "code": "illustration",
  "name": "Illustration",
  "order": "2.0",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/illustration",
  "nb_of_events": 25
  },
  {
  "code": "drawing",
  "name": "Drawing",
  "order": "3.0",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/drawing",
  "nb_of_events": 26
  },
  {
  "code": "photo",
  "name": "Photography",
  "order": "5.0",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/photo",
  "nb_of_events": 83
  },
  {
  "code": "prints",
  "name": "Prints",
  "order": "6.0",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/prints",
  "nb_of_events": 17
  },
  {
  "code": "architecture",
  "name": "Architecture",
  "order": "8.0",
  "group": {
    "name": "3D",
    "code": "3d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/architecture",
  "nb_of_events": 10
  },
  {
  "code": "ceramics",
  "name": "Ceramics",
  "order": "14.0",
  "group": {
    "name": "3D",
    "code": "3d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/ceramics",
  "nb_of_events": 11
  },
  {
  "code": "fashion",
  "name": "Fashion",
  "order": "12.0",
  "group": {
    "name": "3D",
    "code": "3d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/fashion",
  "nb_of_events": 8
  },
  {
  "code": "product",
  "name": "Product",
  "order": "12.0",
  "group": {
    "name": "3D",
    "code": "3d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/product",
  "nb_of_events": 14
  },
  {
  "code": "installation",
  "name": "Installation",
  "order": "10.0",
  "group": {
    "name": "3D",
    "code": "3d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/installation",
  "nb_of_events": 47
  },
  {
  "code": "crafts",
  "name": "Crafts",
  "order": "13.0",
  "group": {
    "name": "3D",
    "code": "3d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/crafts",
  "nb_of_events": 32
  },
  {
  "code": "sculpture",
  "name": "Sculpture",
  "order": "9.0",
  "group": {
    "name": "3D",
    "code": "3d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/sculpture",
  "nb_of_events": 75
  },
  {
  "code": "film",
  "name": "Video and Film",
  "order": "17.0",
  "group": {
    "name": "Screen",
    "code": "screen"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/film",
  "nb_of_events": 27
  },
  {
  "code": "painting",
  "name": "Painting",
  "order": "2.5",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/painting",
  "nb_of_events": 123
  },
  {
  "code": "competition",
  "name": "Art Competition",
  "order": "33.0",
  "group": {
    "name": "Misc.",
    "code": "misc"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/competition",
  "nb_of_events": 1
  },
  {
  "code": "performance",
  "name": "Performance Art",
  "order": "24.0",
  "group": {
    "name": "Misc.",
    "code": "misc"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/performance",
  "nb_of_events": 14
  },
  {
  "code": "media",
  "name": "Media Arts",
  "order": "22.0",
  "group": {
    "name": "Misc.",
    "code": "misc"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/media",
  "nb_of_events": 14
  },
  {
  "code": "manga",
  "name": "Manga",
  "order": "3.5",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/manga",
  "nb_of_events": 7
  },
  {
  "code": "nihonga",
  "name": "Nihonga",
  "order": "3.7",
  "group": {
    "name": "2D",
    "code": "2d"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/nihonga",
  "nb_of_events": 20
  },
  {
  "code": "animation",
  "name": "Animation",
  "order": "20.0",
  "group": {
    "name": "Screen",
    "code": "screen"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/animation",
  "nb_of_events": 3
  },
  {
  "code": "sound",
  "name": "Sound",
  "order": "23.0",
  "group": {
    "name": "Misc.",
    "code": "misc"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/sound",
  "nb_of_events": 10
  },
  {
  "code": "artfestival",
  "name": "Art Festival",
  "order": "25.0",
  "group": {
    "name": "Misc.",
    "code": "misc"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/artfestival",
  "nb_of_events": 5
  },
  {
  "code": "artfair",
  "name": "Art Fair",
  "order": "27.0",
  "group": {
    "name": "Misc.",
    "code": "misc"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/artfair",
  "nb_of_events": 1
  },
  {
  "code": "residence",
  "name": "Artist in Residence",
  "order": "29.0",
  "group": {
    "name": "Misc.",
    "code": "misc"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/residence",
  "nb_of_events": 2
  },
  {
  "code": "party",
  "name": "Party",
  "order": "40.0",
  "group": {
    "name": "Participatory",
    "code": "participatory"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/party",
  "nb_of_events": 58
  },
  {
  "code": "workshops",
  "name": "Workshops",
  "order": "41.0",
  "group": {
    "name": "Participatory",
    "code": "participatory"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/workshops",
  "nb_of_events": 24
  },
  {
  "code": "talks",
  "name": "Talks",
  "order": "42.0",
  "group": {
    "name": "Participatory",
    "code": "participatory"
  },
  "link": "https://api-staging.tokyoartbeat.com/api/v1/events/genre/talks",
  "nb_of_events": 63
  }
]
}
```

> The above command returns JSON structured like this when id = en and lang = area


```json
{
"lists:" [
{
"code": "ginza_marunouchi",
"name": "Ginza, Marunouchi",
"alt_name": "Ginza",
"order": "1.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/ginza_marunouchi",
"nb_of_events": 38
},
{
"code": "ueno_yanaka",
"name": "Ueno, Yanaka",
"alt_name": "Ueno",
"order": "2.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/ueno_yanaka",
"nb_of_events": 18
},
{
"code": "aoyama_omotesando",
"name": "Omotesando, Aoyama",
"alt_name": "Omotesando",
"order": "3.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/aoyama_omotesando",
"nb_of_events": 23
},
{
"code": "shinjuku",
"name": "Shinjuku",
"alt_name": "Shinjuku",
"order": "4.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/shinjuku",
"nb_of_events": 20
},
{
"code": "shibuya_setagaya",
"name": "Shibuya",
"alt_name": "Shibuya",
"order": "5.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/shibuya_setagaya",
"nb_of_events": 17
},
{
"code": "akasaka_roppongi",
"name": "Roppongi, Nogizaka",
"alt_name": "Roppongi",
"order": "6.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/akasaka_roppongi",
"nb_of_events": 18
},
{
"code": "ebisu_nakame_daikan",
"name": "Ebisu, Daikanyama",
"alt_name": "Ebisu",
"order": "7.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/ebisu_nakame_daikan",
"nb_of_events": 22
},
{
"code": "musashino_tama",
"name": "Musashino, Tama",
"alt_name": "Musashino",
"order": "8.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/musashino_tama",
"nb_of_events": 17
},
{
"code": "kanagawa",
"name": "Yokohama, Kanagawa",
"alt_name": "Yokohama",
"order": "18.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/kanagawa",
"nb_of_events": 16
},
{
"code": "other",
"name": "Kanto: others",
"alt_name": "Others",
"order": "20.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/other",
"nb_of_events": 29
},
{
"code": "koto_odaiba",
"name": "Odaiba, Kachidoki",
"alt_name": "Kiyosumi-Shirakawa",
"order": "12.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/koto_odaiba",
"nb_of_events": 7
},
{
"code": "nihonbashi",
"name": "Kyobashi, Nihonbashi",
"alt_name": "Kyobashi",
"order": "3.5",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/nihonbashi",
"nb_of_events": 20
},
{
"code": "chiyoda",
"name": "Chiyoda",
"alt_name": "Chiyoda",
"order": "10.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/chiyoda",
"nb_of_events": 13
},
{
"code": "shirokane_hiroo",
"name": "Shirokane, Hiroo",
"alt_name": "Shirokane",
"order": "11.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/shirokane_hiroo",
"nb_of_events": 6
},
{
"code": "ichigaya_kagurazaka",
"name": "Ichigaya, Kagurazaka",
"alt_name": "Ichigaya",
"order": "14.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/ichigaya_kagurazaka",
"nb_of_events": 6
},
{
"code": "bakurocho",
"name": "Bakurocho",
"alt_name": "Bakurocho",
"order": "9.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/bakurocho",
"nb_of_events": 10
},
{
"code": "setagaya_kawasaki",
"name": "Setagaya, Kawasaki",
"alt_name": "Setagaya, Kawasaki",
"order": "15.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/setagaya_kawasaki",
"nb_of_events": 8
},
{
"code": "kiyosumi_ryogoku",
"name": "Kiyosumi, Ryogoku",
"alt_name": "Kiyosumi",
"order": "13.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/kiyosumi_ryogoku",
"nb_of_events": 6
},
{
"code": "tokyo_other",
"name": "Tokyo: Others",
"alt_name": "Tokyo: Others",
"order": "19.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/area/tokyo_other",
"nb_of_events": 16
}
]
}
```


> The above command returns JSON structured like this when id = en and lang = smart


```json
{
lists: [
{
"code": "most_popular",
"name": "Most Popular",
"order": "1.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/most_popular",
"nb_of_events": "20"
},
{
"code": "starting_soon",
"name": "Starting Soon",
"order": "2.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/starting_soon",
"nb_of_events": 0
},
{
"code": "event_opening",
"name": "Opening Receptions",
"order": "3.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/event_opening",
"nb_of_events": 0
},
{
"code": "just_started",
"name": "Just Started",
"order": "4.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/just_started",
"nb_of_events": "29"
},
{
"code": "closing_soon",
"name": "Closing Soon",
"order": "5.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/closing_soon",
"nb_of_events": 0
},
{
"code": "free",
"name": "Free Entrance",
"order": "6.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/free",
"nb_of_events": "181"
},
{
"code": "kids",
"name": "For Kids Too",
"order": "7.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/kids",
"nb_of_events": "7"
},
{
"code": "open_late",
"name": "Open Late",
"order": "8.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/open_late",
"nb_of_events": "253"
},
{
"code": "permanent",
"name": "Permanent",
"order": "9.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/permanent",
"nb_of_events": "22"
},
{
"code": "discount",
"name": "Discounts from Mupon",
"order": "10.0",
"link": "https://api-staging.tokyoartbeat.com/api/v1/events/smart/discount",
"nb_of_events": "29"
}
]
}
```

The endpoint gets the different existing lists of events. <del>THIS IS A NEW API TO BUILD.</del> : Done!

### HTTP Request

`GET http://api-staging.tokyoartbeat.com/api/v0/lists/:id?locale=:locale`

### Query Parameters

Parameter  | Description
---------  | -----------
id  | id must be one of : genre, area, smart
locale | option : "en" or "ja"
