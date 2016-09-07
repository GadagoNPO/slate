
# Lists

## Get lists of available lists of events

```shell
curl "https://api.tokyoartbeat.com/api/v1/lists/:id?locale=:locale"

or

curl -H Accept-language:en https://localhost:3000/api/v0/lists/genre

or

curl -H Accept-language:ja https://localhost:3000/api/v0/lists/genre
```

> The above command returns JSON structured like this when id = en and lang = genre

```json
{
  "lists" : [
    { "id" : "graphics", "text" :  "Graphics" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/graphics"},
    { "id" : "illustration", "text" :  "Illustration" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/illustration"},
    { "id" : "painting", "text" :  "Painting" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/painting"},
    { "id" : "drawing", "text" :  "Drawing" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/drawing"},
    { "id" : "manga", "text" :  "Manga" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/manga"},
    { "id" : "nihonga", "text" :  "Nihonga" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/nihonga"},
    { "id" : "photography", "text" :  "Photography" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/photography"},
    { "id" : "prints", "text" :  "Prints" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/prints"},
    { "id" : "architecture", "text" :  "Architecture" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/architecture"},
    { "id" : "sculpture", "text" :  "Sculpture" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/sculpture"},
    { "id" : "installation", "text" :  "Installation" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/installation"},
    { "id" : "fashion", "text" :  "Fashion" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/fashion"},
    { "id" : "product", "text" :  "Product" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/product"},
    { "id" : "crafts", "text" :  "Crafts" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/crafts"},
    { "id" : "ceramics", "text" :  "Ceramics" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/ceramics"},
    { "id" : "video_and_film", "text" :  "Video and Film" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/video_and_film"},
    { "id" : "animation", "text" :  "Animation" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/animation"},
    { "id" : "media_arts", "text" :  "Media Arts" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/media_arts"},
    { "id" : "sound", "text" :  "Sound" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/sound"},
    { "id" : "performance_art", "text" :  "Performance Art" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/performance_art"},
    { "id" : "art_festival", "text" :  "Art Festival" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/art_festival"},
    { "id" : "art_fair", "text" :  "Art Fair" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/art_fair"},
    { "id" : "artist_in_residence", "text" :  "Artist in Residence" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/artist_in_residence"},
    { "id" : "art_competition", "text" :  "Art Competition" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/art_competition"},
    { "id" : "party", "text" :  "Party" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/party"},
    { "id" : "workshops", "text" :  "Workshops" , "order" : "1..n" , "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/workshops"},
    { "id" : "talks", "text" :  "Talks", "order" : "1..n", "link" : "https://api.tokyoartbeat.com/api/v1/events/genre/talks"  }
  ],
  "lastUpdate" : "some timestamp"
}
```

> The above command returns JSON structured like this when id = en and lang = area


```json
{
  "lists" : [
      { "id" : "ginza", "text" : "Ginza, Marunouchi", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/ginza" },
      { "id" : "ueno", "text" : "Ueno, Yanaka", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "kyobachi", "text" : "Kyobashi, Nihonbashi", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "omotesando", "text" : "Omotesando, Aoyama", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "shinjuku", "text" : "Shinjuku", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "shibuya", "text" : "Shibuya", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "roppongi", "text" : "Roppongi, Nogizaka", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "ebisu", "text" : "Ebisu, Daikanyama", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "musashino", "text" : "Musashino, Tama", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "bakurocho", "text" : "Bakurocho", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "shirokane", "text" : "Shirokane, Hiroo", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "chiyoda", "text" : "Chiyoda", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "odaiba", "text" : "Odaiba, Kachidoki", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "kiyosumi", "text" : "Kiyosumi, Ryogoku", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "ichigaya", "text" : "Ichigaya, Kagurazaka", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "setagaya", "text" : "Setagaya, Kawasaki", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "yokohama", "text" : "Yokohama, Kanagawa", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "tokyo_others", "text" : "Tokyo: Others", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" },
      { "id" : "kanto_others", "text" : "Kanto: Others", "link" : "https://api.tokyoartbeat.com/api/v1/events/area/:id" }
    ],
  "lastUpdate" : "some timestamp"
}
```


> The above command returns JSON structured like this when id = en and lang = smart


```json
{
  "lists" : [
      { "id" : "most_popular", "text" : "Most Popular" , "link" : "https://api.tokyoartbeat.com/v1/events/smart/most_popular" },
      { "id" : "ending_soon", "text" : "Ending Soon" , "link" : "https://api.tokyoartbeat.com/v1/events/smart/:id" },
      { "id" : "discount", "text" : "Discount" , "link" : "https://api.tokyoartbeat.com/v1/events/smart/:id" },
      { "id" : "starting_soon", "text" : "Starting Soon" , "link" : "https://api.tokyoartbeat.com/v1/events/smart/:id" },
      { "id" : "just_started", "text" : "Just Started" , "link" : "https://api.tokyoartbeat.com/v1/events/smart/:id" },
      { "id" : "opening_receptions", "text" : "Opening Receptions" , "link" : "https://api.tokyoartbeat.com/v1/events/smart/:id" }
    ],
  "lastUpdate" : "some timestamp"
}
```

The endpoint gets the different existing lists of events. THIS IS A NEW API TO BUILD.

### HTTP Request

`GET http://api.tokyoartbeat.com/api/v1/lists/:id?locale=:locale`

### Query Parameters

Parameter  | Description
---------  | -----------
id  | id must be one of : genre, area, smart
locale | option : "en" or "ja"
