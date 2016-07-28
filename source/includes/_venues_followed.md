# Venues

## Venues followed

```shell
curl "http://api.tokyoartbeat.com/api/v1/venues/follow/:lang"
```

> The above command returns JSON structured like this 

```json
{
  "events" : [
    
  ]
}
```

This endpoint retrieves the logged in user list of events for the corresponding followed venues. THIS IS A NEW API TO BUILD

### HTTP Request

`GET http://api.tokyoartbeat.com/api/v1/venues/follow/:lang`

### URL Parameters

Parameter | Description
--------- | -----------
lang | "en" or "ja"
