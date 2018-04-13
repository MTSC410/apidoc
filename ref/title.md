# GET /ref/titlelevel

Get reference of title levels.  

## Resource URL

https://api.mountaintopdata.com/ref/titlelevel

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/titlelevel
```

## Response parameters

| Field   | Type   | Description           |
| ------- | ------ | --------------------- |
| data    | array  | title level data list |
| data[i] | object |                       |

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
