# GET /user/total `Admin only`

Get sum of total user

## Resource URL

https://api.mountaintopdata.com/user/total

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/user/total"
```

## Response parameters

| Field | Type   | Description           |
| ----- | ------ | --------------------- |
| data  | number | Amount of total users |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": 4
}
```
