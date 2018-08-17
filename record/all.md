# GET /record.

Get records.

## Resource URL

https://api.mountaintopdata.com/record

## Request parameters

| Field      | Type   | Required | Description               |
| ---------- | ------ | -------- | ------------------------- |
| city       | String |          |                           |
| country    | String |          |                           |
| domain     | String |          |                           |
| state      | String |          |                           |
| Industry   | String |          | the industry id           |
| size       | String |          | the size id               |
| Title      | String |          | the title id              |
| IT         | Number |          | is IT (0: false, 1: true) |
| marketing  | Number |          | is marketing              |
| sales      | Number |          | is sales                  |
| top        | Number |          | is top                    |
| operations | Number |          | is operations             |
| financial  | Number |          | is financial              |
| HR         | Number |          | is HR                     |

## Request example

```bash
curl -H ... \
    "https://api.mountaintopdata.com/record?IT=1"
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
      "li99_id": 8,
      "Company": "Google",
      "first_name": "Jeremy",
      "last_name": "Joslin",
      "Title": "Software Engineer",
      "Phone": "4157360000",
      "Email": "jjoslin@google.com",
      "domain": "google.com",
      "address": "345 Spear St",
      "city": "San Francisco",
      "state": "CA",
      "Zip": "94105",
      "size": "10,001+ employees",
      "Revenue": "1B+",
      "Industry": "Internet",
      "SIC": "7371",
      "title_level": 5,
      "url": "http://www.linkedin.com/in/jcjoslin",
      "id_size": 8,
      "id_industry": 58,
      "country": "US",
      "IT": 1,
      "operations": null,
      "financial": null,
      "sales": null,
      "top": null,
      "HR": null,
      "marketing": null
    },
    {
      "li99_id": 45,
      "Company": "Natera",
      "first_name": "Jonathan",
      "last_name": "Sheena",
      "Title": "Founder and CTO",
      "Phone": "6507804744",
      "Email": "jsheena@genesecurity.net",
      "domain": "genesecurity.net",
      "address": "201 Industrial Road, Suite 410",
      "city": "San Carlos",
      "state": "CA",
      "Zip": "94063",
      "size": "201-500 employees",
      "Revenue": "20M - 50M",
      "Industry": "Biotechnology",
      "SIC": "8734",
      "title_level": 1,
      "url": "http://www.linkedin.com/in/jonathan-sheena-b51",
      "id_size": 5,
      "id_industry": 122,
      "country": "US",
      "IT": 1,
      "operations": null,
      "financial": null,
      "sales": null,
      "top": 1,
      "HR": null,
      "marketing": null
    },
    ...
  ],
  "volume": 988
}
```
