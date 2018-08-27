{
  "info": {
    "name": "Instructure Canvas Audit API Query by login.",
    "_postman_id": "4ea06d3b-4829-4a18-8c60-471fef7743fc",
    "description": "Query by login..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audit",
      "item": [
        {
          "id": "2f1ba2fd-d366-4716-8a2f-3d3e63f872b6",
          "name": "query-by-account",
          "request": {
            "url": {
              "protocol": "http",
              "host": "canvas.instructure.com",
              "path": [
                "api",
                "v1",
                "audit/authentication/accounts/:account_id"
              ],
              "query": [
                {
                  "key": "end_time",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start_time",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "account_id",
                  "value": "account_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Query by account.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "da248b39-9b8c-400e-ad3a-3fd04d870b24"
            }
          ]
        },
        {
          "id": "50bd003b-d130-4e71-b3e8-833359cf4fc8",
          "name": "query-by-login",
          "request": {
            "url": {
              "protocol": "http",
              "host": "canvas.instructure.com",
              "path": [
                "api",
                "v1",
                "audit/authentication/logins/:login_id"
              ],
              "query": [
                {
                  "key": "end_time",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "start_time",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "login_id",
                  "value": "login_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Query by login.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c74e4fe-d3b5-4798-acfe-b182b4ff7b4b"
            }
          ]
        }
      ]
    }
  ]
}