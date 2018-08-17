# API Documentation

## Auth headers

Api all need `auth headers` (except public api)

| Field       | Type   | Description          |
| ----------- | ------ | -------------------- |
| x-mtd-uuid  | String | User uuid.           |
| x-mtd-token | String | Authorization token. |

> example

```bash
curl -H "x-mtd-uuid: 007e08cd-0314-4f23-b8d8-62574d5c0dac" \
     -H "x-mtd-token: 64c5e74e4a22895289f649a97c81cd3c2af228ea37e3d5987c0e52d3577a4532"
     ...
```

## Content type

Api only accept `json` format.

> example

```bash
curl -H "content-type: application/json"
    ...
```

## Response success format

Standard response status code

| Field | Type   | Description                             |
| ----- | ------ | --------------------------------------- |
| code  | number | 0 means success, others (>1) means fail |
| msg   | string | The response message                    |
| data  | (any)  |                                         |

## Response failure format

> example

```http
HTTP/1.1 400 Bad Request
```

```json
{
  "code": 400,
  "error": "ParamsMissingError"
}
```
