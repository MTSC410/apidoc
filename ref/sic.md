# GET /ref/sic

Get reference of sic

## Resource URL

https://api.mountaintopdata.com/ref/sic

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/sic
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | sic data list |
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
      "value": "1541"
    },
    {
      "value": "3571"
    },
    ...
  ]
}
```
