{
  "info": {
    "name": "Netatmo Get Geteventsuntil",
    "_postman_id": "24289793-f169-4eea-8a1e-f0d2d422e4fc",
    "description": "Returns the snapshot associated to an event.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Events",
      "item": [
        {
          "id": "1559976d-478c-47ee-86d1-a3959fef26bc",
          "name": "geteventsuntil",
          "request": {
            "url": "http://api.netatmo.net/api/geteventsuntil?event_id=%7B%7D&home_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the snapshot associated to an event."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "76074884-b8f0-491d-b6f9-afddf8ec94b4"
            }
          ]
        }
      ]
    }
  ]
}