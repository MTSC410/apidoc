# POST /register

Register

## Resource URL

https://api.mountaintopdata.com/register

## Request parameters

| Field    | Type   | Required | Description |
| -------- | ------ | -------- | ----------- |
| email    | string | yes      |             |
| password | string | yes      |             |

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/register" \
    --data-binary '{"email":"a@a.com","password":"123456"}'
```

## Response parameters

| Field | Type   | Description     |
| ----- | ------ | --------------- |
| data  | object | User basic data |

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
    "email": "a@a.com",
    "token": "e33ce437489fd15b261769a73c58151e46081e0f8317f7b108c5ab9086dab38c",
    "created_at": "2017-10-30T22:11:05.982Z",
    "updated_at": "2017-10-30T22:11:05.995Z",
    "query": {
      "count": 0
    },
    "wallet": {
      "volume": 0
    }
  }
}
```
