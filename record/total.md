# GET /total

Get sum of records

## Resource URL

https://api.mountaintopdata.com/total

## Request parameters

| Field | Type   | Required | default | Description    |
| ----- | ------ | -------- | ------- | -------------- |
| field | string |          | Email   | distinct field |

## Request example

```http
GET https://api.mountaintopdata.com/total
```

## Response parameters

| Field | Type   | Description |
| ----- | ------ | ----------- |
| data  | number |             |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": 219527
}
```
