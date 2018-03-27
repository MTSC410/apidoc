# GET /ref/title

Get reference of title

## Resource URL

https://api.mountaintopdata.com/ref/title

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/title
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | title data list |
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
      "id": 1,
      "value": "Partner"
    },
    {
      "id": 2,
      "value": "Vice President, Product Management"
    ...
  ]
}
```
