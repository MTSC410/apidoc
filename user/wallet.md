# PATCH /user/:uuid/wallet `Admin only`

Increse or decrese user wallet

## Resource URL

https://api.mountaintopdata.com/user/:uuid/wallet

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/user/123f6b8e-c412-4dd9-baae-ad04057a8e25/wallet" \
    --data-binary '{"volume":"1000"}'
```

## Response parameters

| Field | Type   | Description |
| ----- | ------ | ----------- |
| data  | object | Wallet data |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": {
    "volume": 1100
  }
}
```
