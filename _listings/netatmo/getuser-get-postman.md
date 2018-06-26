{
  "info": {
    "name": "Netatmo Get Getuser",
    "_postman_id": "455ff7a9-7e62-41e5-bb0f-c978ed9c65da",
    "description": "The method getuser returns information about a user such as prefered language, prefered units, and list of devices.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Users",
      "item": [
        {
          "id": "09bc5f0e-e99a-474a-ab2a-de302452d4e5",
          "name": "getuser",
          "request": {
            "url": "http://api.netatmo.net/api/getuser",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The method getuser returns information about a user such as prefered language, prefered units, and list of devices."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "68050c4f-a617-4e6e-814f-51377c349e82"
            }
          ]
        }
      ]
    }
  ]
}