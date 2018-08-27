{
  "info": {
    "name": "Launch Darkly Get a webhook by ID",
    "_postman_id": "23d689cd-dc0b-4402-8a7d-7a026adc5649",
    "description": "Get a webhook by id.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "de7b639c-666d-4c34-a1ee-8cb7f7cbc301",
          "name": "getRoot",
          "request": {
            "url": "http://app.launchdarkly.com/api/v2/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the root resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5126f731-a2f7-4f7a-a26c-6ce7affa3316"
            }
          ]
        }
      ]
    },
    {
      "name": "Auditlog",
      "item": [
        {
          "id": "86d93c9e-f590-4bb4-ad10-3bef4cf8f434",
          "name": "getAuditLogEntries",
          "request": {
            "url": "http://app.launchdarkly.com/api/v2/auditlog",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Fetch a list of all webhooks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ad885306-63af-4a1f-a045-93e1d6c994e9"
            }
          ]
        },
        {
          "id": "abe68338-1214-4772-857a-c0b3386705ed",
          "name": "getAuditLogEntry",
          "request": {
            "url": {
              "protocol": "http",
              "host": "app.launchdarkly.com",
              "path": [
                "api",
                "v2",
                "auditlog/:resourceId"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "resourceId",
                  "value": "resourceId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get a webhook by id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45034826-92f6-47e3-bc8f-fe8f1c96fd4b"
            }
          ]
        }
      ]
    }
  ]
}