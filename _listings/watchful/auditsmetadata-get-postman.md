{
  "info": {
    "name": "Watchful Get The List Of Fields",
    "_postman_id": "dfd71be1-d7a0-43ee-b88a-5a794164f258",
    "description": "Returns a list of fields",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audits",
      "item": [
        {
          "id": "3f879b7e-283a-4073-b7cd-8ecf1dcff0ea",
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
              "id": "643c5fd2-e833-411f-96ad-c2f42e4c18f5"
            }
          ]
        }
      ]
    }
  ]
}