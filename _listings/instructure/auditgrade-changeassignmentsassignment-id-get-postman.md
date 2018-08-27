{
  "info": {
    "name": "Instructure Canvas Audit API Query by assignment.",
    "_postman_id": "f56fb11b-d1d9-4957-9222-2c5be68e9809",
    "description": "Query by assignment..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audit",
      "item": [
        {
          "id": "f4094205-91b6-44c7-b66d-3d68081db893",
          "name": "query-by-assignment",
          "request": {
            "url": {
              "protocol": "http",
              "host": "canvas.instructure.com",
              "path": [
                "api",
                "v1",
                "audit/grade_change/assignments/:assignment_id"
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
                  "id": "assignment_id",
                  "value": "assignment_id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Query by assignment.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "54c6f2cb-bac4-4200-b20f-d49226913fd4"
            }
          ]
        }
      ]
    }
  ]
}