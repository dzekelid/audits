{
  "info": {
    "name": "Watchful Find Audit By ID",
    "_postman_id": "c4ec1948-db89-4bca-8052-cbf6904d87e9",
    "description": "Returns a audit based on ID",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audits",
      "item": [
        {
          "id": "f7f09cbb-5dec-4b4e-adbc-617e0746ade8",
          "name": "getAudits",
          "request": {
            "url": "http://watchful.li/api/v1/audits?limit=%7B%7D&limitstart=%7B%7D&order=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of audits"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0a130a4c-9f65-47f5-a91e-a3c9d02d9646"
            }
          ]
        },
        {
          "id": "9fc51290-4368-48de-ac5a-23a0bee02ba2",
          "name": "getFieldsAudits",
          "request": {
            "url": "http://watchful.li/api/v1/audits/metadata",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of fields"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a66eae1a-202d-4fad-8f3a-1352c6581a40"
            }
          ]
        },
        {
          "id": "494108bc-7533-4854-b67f-ab3b0d1de931",
          "name": "getAuditById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "audits/:id"
              ],
              "query": [
                {
                  "key": "fields",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a audit based on ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d8694394-8939-4055-9de2-e29a153eebe6"
            }
          ]
        },
        {
          "id": "6f29cce5-acd0-493d-a2e0-206eefc20fe1",
          "name": "deleteAuditById",
          "request": {
            "url": {
              "protocol": "http",
              "host": "watchful.li",
              "path": [
                "api",
                "v1",
                "audits/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a specific audit."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9572cdaa-5676-4875-8de9-777341784e11"
            }
          ]
        }
      ]
    }
  ]
}