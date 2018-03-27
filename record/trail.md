# GET /trial/record

Get trial records (for free)

## Resource URL

https://api.mountaintopdata.com/trial/record

## Request parameters

!> same as `GET /record`

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/trial/record?IT=1"
```

## Response parameters

| Field   | Type   | Description         |
| ------- | ------ | ------------------- |
| volume  | volume | User current volume |
| data    | array  | Record data list    |
| data[i] | object |                     |

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
      "first_name": "Jeremy",
      "last_name": "Joslin",
      "company": "Google",
      "title": "Software Engineer",
      "li99_id": "****",
      "Company": "****",
      "Title": "****",
      "Phone": "****",
      "Email": "****",
      "domain": "****",
      "address": "****",
      "city": "****",
      "state": "****",
      "Zip": "****",
      "size": "****",
      "Revenue": "****",
      "Industry": "****",
      "SIC": "****",
      "title_level": "****",
      "url": "****",
      "id_size": "****",
      "id_industry": "****",
      "country": "****",
      "IT": "****",
      "operations": "****",
      "financial": "****",
      "sales": "****",
      "top": "****",
      "HR": "****",
      "marketing": "****"
    },
    ...
  ]
}
```
