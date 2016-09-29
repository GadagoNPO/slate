# Venues

## Venues followed

```shell
curl "https://api-staging.tokyoartbeat.com/api/v0/venues/follow?locale=en"
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

`GET https://api-staging.tokyoartbeat.com/api/v0/venues/follow?locale=:locale`

### URL Parameters

Parameter | Description
--------- | -----------
locale | "en" or "ja"
