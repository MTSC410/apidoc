# GET /ref/city

Get reference of city

## Resource URL

https://api.mountaintopdata.com/ref/city

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/city
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | city data list |
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
      "value": "Ann Arbor"
    },
    {
      "value": "Arlington"
    },
    ...
  ]
}
```
