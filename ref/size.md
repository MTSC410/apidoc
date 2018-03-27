# GET /ref/size

Get reference of size

## Resource URL

https://api.mountaintopdata.com/ref/size

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/size
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | size data list |
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
      "id": 2,
      "value": "1-10 employees"
    },
    {
      "id": 3,
      "value": "Myself Only"
    },
    ...
  ]
}
```
