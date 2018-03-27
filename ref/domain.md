# GET /ref/domain

Get reference of domain

## Resource URL

https://api.mountaintopdata.com/ref/domain

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/domain
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | domain data list |
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
      "value": "a16z.com"
    },
    {
      "value": "abscapital.com"
    },
    ...
  ]
}
```
