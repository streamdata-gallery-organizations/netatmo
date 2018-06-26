{
  "info": {
    "name": "Netatmo Get Gethomedata",
    "_postman_id": "eac0d2a7-84c1-449b-bbdc-c852d4ee0f48",
    "description": "Returns information about users homes and cameras.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "387b8c6e-a65f-41d0-828c-958a40190509",
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
              "id": "175bdb01-2b3c-40d3-8cb8-31371f9bac54"
            }
          ]
        },
        {
          "id": "dd9e9729-60bd-431a-8fef-4ed06601283a",
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
              "id": "0a0d7ea9-1816-445d-8ffa-a01752a79dac"
            }
          ]
        },
        {
          "id": "9cfc05d1-3aad-46b8-85ac-92616279fce0",
          "name": "gethomedata",
          "request": {
            "url": "http://api.netatmo.net/api/gethomedata?home_id=%7B%7D&size=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about users homes and cameras."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb4be9d9-f663-4aba-acc1-28abcea6d6ad"
            }
          ]
        }
      ]
    }
  ]
}