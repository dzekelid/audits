{
  "info": {
    "name": "Watchful Delete A Specific Audit",
    "_postman_id": "45323fd1-dcb7-4e31-ad76-a991f6f7d410",
    "description": "Delete a specific audit.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audits",
      "item": [
        {
          "id": "795a75d1-b63f-41de-8343-5a82a3515380",
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
              "id": "40fb91f5-dc98-49f0-942f-4b4a4a764ede"
            }
          ]
        },
        {
          "id": "56c67941-acea-484c-9691-c9ce048b06e0",
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
              "id": "20e0a6c8-2beb-4ea8-af18-01dd443c86c9"
            }
          ]
        },
        {
          "id": "a32a6c8f-af7c-4231-8502-c253ca17b190",
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
              "id": "e3bf5912-fad7-432b-a139-5a206476dd68"
            }
          ]
        }
      ]
    }
  ]
}