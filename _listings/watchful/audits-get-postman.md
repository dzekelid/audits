{
  "info": {
    "name": "Watchful Get A List Of Audits",
    "_postman_id": "c194749e-30a0-4eb8-bfbf-46ccd079df1d",
    "description": "Returns a list of audits",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Audits",
      "item": [
        {
          "id": "3870ec94-2040-4c71-9d14-400691497566",
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
              "id": "f915a286-2589-4f2b-ae07-8902790a07eb"
            }
          ]
        }
      ]
    }
  ]
}