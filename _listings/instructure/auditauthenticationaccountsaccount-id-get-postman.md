{
  "info": {
    "name": "Instructure Canvas Audit API Query by account.",
    "_postman_id": "2778de2d-3061-4fdf-a037-969de9d55cda",
    "description": "Query by account..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audit",
      "item": [
        {
          "id": "f362fd9c-f151-4257-83ea-75ec7d994275",
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
              "id": "abbf558c-33ca-481e-b824-8a4e25e52570"
            }
          ]
        }
      ]
    }
  ]
}