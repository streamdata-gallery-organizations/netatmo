{
  "info": {
    "name": "Netatmo Get Getcamerapicture",
    "_postman_id": "c2f59048-8738-4098-814c-2d9867466035",
    "description": "Returns the snapshot associated to an event.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Cameras",
      "item": [
        {
          "id": "b5bc654a-fd1f-48eb-b836-7a5546593f17",
          "name": "getcamerapicture",
          "request": {
            "url": "http://api.netatmo.net/api/getcamerapicture?image_id=%7B%7D&key=%7B%7D",
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
              "id": "47a44a48-4b1a-4e44-a9f8-ff1742bf2f9f"
            }
          ]
        }
      ]
    }
  ]
}