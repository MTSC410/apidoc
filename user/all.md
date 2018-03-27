# GET /user `Admin only`

Get all user detail data

## Resource URL

https://api.mountaintopdata.com/user

## Request parameters

| Field | Type | Required | Description |
| ----- | ---- | -------- | ----------- |

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/user"
```

## Response parameters

| Field   | Type   | Description      |
| ------- | ------ | ---------------- |
| data    | array  | data list        |
| data[i] | object | User detail data |

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
    },
    {
      "id": 2,
      "uuid": "e12a1f3f-f953-4541-ab79-26f0bfbe9162",
      "email": "a2@b.com",
      "token": "2ecaaf55ccdc973533aaf0dd1d9875b0cca6c690e89cb83c3f35c799d3dd2012",
      "created_at": "2017-10-30T20:04:05.000Z",
      "updated_at": "2017-10-30T20:04:05.000Z",
      "query": {
        "id": 2,
        "user_id": 2,
        "count_trial": 0,
        "count": 0,
        "created_at": "2017-10-30T20:04:05.000Z",
        "updated_at": "2017-10-30T20:04:05.000Z",
        "deleted_at": null
      },
      "wallet": {
        "id": 2,
        "user_id": 2,
        "volume": 100,
        "created_at": "2017-10-30T20:04:05.000Z",
        "updated_at": "2017-10-30T20:04:06.000Z",
        "deleted_at": null
      }
    },
    ...
  ]
}
```
