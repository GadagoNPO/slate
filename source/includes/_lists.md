
# Lists


## Get list of lists

```shell
curl "https://api-staging.tokyoartbeat.com/api/v0/lists/"

or

curl "https://api-staging.tokyoartbeat.com/api/v0/lists?locale=ja"


curl -H Accept-language:en "https://api-staging.tokyoartbeat.com/api/v0/lists"

or

curl -H Accept-language:ja "https://api-staging.tokyoartbeat.com/api/v0/lists"
```

> The above command returns JSON structured like this with locale=en:

```json
{
  "lists" : [
    {
      "code": "genre",
      "name": "Genre",
      "link": "https://api-staging.tokyoartbeat.com/api/v0/lists/genre"
    },
    {
      "code": "area",
      "name": "Area",
      "link": "https://api-staging.tokyoartbeat.com/api/v0/lists/area"
    },
    {
      "code": "smart",
      "name": "Smart Lists",
      "link": "https://api-staging.tokyoartbeat.com/api/v0/lists/smart"
    }
  ]
}
```

> with locale=ja

```json
{
  "lists" : [
    {
      "code": "genre",
      "name": "ジャンル",
      "link": "https://api-staging.tokyoartbeat.com/api/v0/lists/genre"
    },
    {
      "code": "area",
      "name": "エリア",
      "link": "https://api-staging.tokyoartbeat.com/api/v0/lists/area"
    },
    {
      "code": "smart",
      "name": "スマートリスト",
      "link": "https://api-staging.tokyoartbeat.com/api/v0/lists/smart"
    }
  ]
}
```


The endpoint gets the different existing lists of lists. <del>THIS IS A NEW API TO BUILD.</del> : Done!

HTTP Request

GET http://api-staging.tokyoartbeat.com/api/v0/lists?locale=:locale

Query Parameters

Parameter Description
locale  option : “en” or “ja”