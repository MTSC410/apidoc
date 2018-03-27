# GET /me

Get self data

## Resource URL

https://api.mountaintopdata.com/me

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/me
```

## Response parameters

| Field | Type   | Description     |
| ----- | ------ | --------------- |
| data  | object | User basic data |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": {
    "uuid": "007e08cd-0314-4f23-b8d8-62574d5c0dac",
    "level": 255,
    "email": "a@b.com",
    "created_at": "2017-10-30T19:54:52.000Z",
    "updated_at": "2017-10-30T20:04:22.000Z",
    "query": {
      "count": 0
    },
    "wallet": {
      "volume": 100
    }
  }
}
```
