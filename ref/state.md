# GET /ref/state

Get reference of state

## Resource URL

https://api.mountaintopdata.com/ref/state

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```http
GET https://api.mountaintopdata.com/ref/state
```

## Response parameters

| Field   | Type   | Description    |
| ------- | ------ | -------------- |
| data    | array  | state data list |
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
      "value": "BC"
    },
    {
      "value": "CA"
    },
    ...
  ]
}
```
