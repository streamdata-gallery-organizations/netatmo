{
  "info": {
    "name": "Netatmo Get Gethomecoachsdata",
    "_postman_id": "a096f43d-50af-43aa-8c4a-c67e5b35c46c",
    "description": "The method gethomecoachsdata Returns data from a user Healthy Home Coach Station (measures and device specific data).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "d3ec4b3c-e370-4d03-89f1-969dca6d7e77",
          "name": "devicelist",
          "request": {
            "url": "http://api.netatmo.net/api/devicelist?app_type=%7B%7D&device_id=%7B%7D&get_favorites=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The method devicelist returns the list of devices owned by the user, and their modules.\nA device is identified by its _id (which is its mac address) and each device may have one, several or no modules, also identified by an _id."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b57c51be-67e0-4736-bbab-85810e5f708a"
            }
          ]
        },
        {
          "id": "904f7aa3-27ba-46eb-ad30-25926aeef5b6",
          "name": "gethomecoachsdata",
          "request": {
            "url": "http://api.netatmo.net/api/gethomecoachsdata?device_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The method gethomecoachsdata Returns data from a user Healthy Home Coach Station (measures and device specific data)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6125dce1-236e-40a4-91e6-c95df860fbd6"
            }
          ]
        }
      ]
    }
  ]
}