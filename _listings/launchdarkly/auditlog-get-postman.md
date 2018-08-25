{
  "info": {
    "name": "Launch Darkly Fetch a list of all webhooks",
    "_postman_id": "07e10b4e-2439-4e1c-bff1-310e394842c5",
    "description": "Fetch a list of all webhooks.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Folder",
      "item": [
        {
          "id": "ddf4470e-31af-45fa-af12-377fd10b2be0",
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
              "id": "4ba6d405-e0d1-4240-aeef-e2096cd89210"
            }
          ]
        }
      ]
    },
    {
      "name": "Auditlog",
      "item": [
        {
          "id": "5f7c157b-b2f6-4b96-abfc-ac4d8cdad88c",
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
              "id": "3423ec01-0da6-453a-af03-b9e4c0939b31"
            }
          ]
        }
      ]
    }
  ]
}