# News

## Get the news

```shell
curl "http://api.tokyoartbeat.com/api/v1/news?locale=en"
```

> The above command returns JSON structured like this 

```json
{
  "news" : [
    { "id" : "xxx", "feed" : "twitter", "account": "tokyoartbeat_en", "data": "what we can get from the twitter API" },
    { "id" : "xxx", "feed" : "twitter", "account": "mupon", "data": "what we can get from the twitter API" },
    { "id" : "yyy", "feed" : "instagram", "account": "tokyoartbeat", "data": "what we can get from the instagram API" },
    { "id" : "zzz", "feed" : "wordpress", "data": "what we can get from the WP API" },

    { other tweets or instagram or wordpress articles all ordered by most recent dates I guess }
  ],
  "" : ""
}
```

This endpoint retrieves the news which are an aggregation of feeds (Twitter, Instagram, Magazine (tab wordpress)). THIS IS A NEW API TO BUILD

### HTTP Request

`GET http://api.tokyoartbeat.com/api/v1/news?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
locale | "en" or "ja"
