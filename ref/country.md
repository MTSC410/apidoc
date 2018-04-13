# GET /ref/country

Get reference of country. Country abreviations are used. 

## Resource URL

https://api.mountaintopdata.com/ref/country

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/country
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | country data list |
| data[i] | object |                |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": [
    {
      "value": "AU"
    },
    {
      "value": "CA"
    },
    ...
  ]
}
```
