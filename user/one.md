# GET /user/:uuid `Admin only`

Get one user detail data

## Resource URL

https://api.mountaintopdata.com/user/:uuid

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/user/123f6b8e-c412-4dd9-baae-ad04057a8e25"
```

## Response parameters

| Field | Type   | Description |
| ----- | ------ | ----------- |
| data  | object | user data   |

## Response example

```http
HTTP/1.1 200 OK
```

```json
{
  "code": 0,
  "msg": "ok",
  "data": {
    "id": 1,
    "uuid": "123f6b8e-c412-4dd9-baae-ad04057a8e25",
    "email": "a@b.com",
    "token": "6184de4381e564ce593996e734eb1c6d719f89fed3489e227127bc36cb1ca601",
    "created_at": "2017-10-30T20:04:05.000Z",
    "updated_at": "2017-10-30T20:23:58.000Z",
    "query": {
      "id": 1,
      "user_id": 1,
      "count_trial": 0,
      "count": 0,
      "created_at": "2017-10-30T20:04:05.000Z",
      "updated_at": "2017-10-30T20:30:42.000Z",
      "deleted_at": null
    },
    "wallet": {
      "id": 1,
      "user_id": 1,
      "volume": 100,
      "created_at": "2017-10-30T20:04:05.000Z",
      "updated_at": "2017-10-30T20:04:06.000Z",
      "deleted_at": null
    }
  }
}
```
