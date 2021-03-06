# GET /ref/group

Get reference of group

## Resource URL

https://api.mountaintopdata.com/ref/group

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/group
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | group key list |
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
      "value": "IT"
    },
    {
      "value": "marketing"
    },
    {
      "value": "sales"
    },
    {
      "value": "top"
    },
    {
      "value": "operations"
    },
    {
      "value": "financial"
    },
    {
      "value": "HR"
    }
  ]
}
```
