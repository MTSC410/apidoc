# GET /search/title

Search title

## Resource URL

https://api.mountaintopdata.com/search/title

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |
| q     | string| yes | at least 3 characters |

## Request example

```http
GET https://api.mountaintopdata.com/search/title?q=ceo%20programer
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | posible title values |
| data[i] | string |                |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": [
    "ceo",
    "programer",
    "programerrrrr"
  ]
}
```
