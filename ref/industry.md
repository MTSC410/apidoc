# GET /ref/industry

Get reference of industry

## Resource URL

https://api.mountaintopdata.com/ref/industry

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/industry
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | industry data list |
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
      "id": 3,
      "value": "Information Technology and Services"
    },
    {
      "id": 6,
      "value": "Marketing and Advertising"
    },
    ...
  ]
}
```
