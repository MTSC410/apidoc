# POST /login

Login

## Resource URL

https://api.mountaintopdata.com/login

## Request parameters

| Field    | Type   | Required | Description |
| -------- | ------ | -------- | ----------- |
| email    | string | yes      |             |
| password | string | yes      |             |

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/login" \
    --data-binary '{"email":"a@a.com","password":"123456"}'
```

## Response parameters

| Field | Type   | Description                |
| ----- | ------ | -------------------------- |
| data  | object | User basic data with token |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": {
    "uuid": "5dfda0ec-a77e-441f-847c-6335a209ef33",
    "level": null,
    "email": "a@a.com",
    "token": "343848147262be76f70ea278ea495d1d3d1d025b81e6af5158460de3f636a7f3",
    "created_at": "2017-10-30T22:11:05.000Z",
    "updated_at": "2017-10-30T22:17:55.087Z",
    "query": {
      "count": 0
    },
    "wallet": {
      "volume": 0
    }
  }
}
```
