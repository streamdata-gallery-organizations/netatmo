{
  "info": {
    "name": "Netatmo Get Getlasteventof",
    "_postman_id": "25a76443-dd70-48dd-ada1-3e1c07d40e8c",
    "description": "Returns most recent events.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "431aff97-6d5e-4ad1-9955-b99380dacde3",
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
              "id": "3315f472-443c-4339-968c-f4b1a8cfaef2"
            }
          ]
        },
        {
          "id": "15f515be-e59c-498e-9d48-0346463f703e",
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
              "id": "0f7279cd-2c2b-4575-95de-726fcd8173f7"
            }
          ]
        },
        {
          "id": "8054e430-ba90-4059-b0de-780eb0cac1d7",
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
              "id": "ac6ba362-032b-452f-9ac0-20a4887cb33c"
            }
          ]
        },
        {
          "id": "05211576-bf18-4023-98ef-abbe6611b721",
          "name": "getlasteventof",
          "request": {
            "url": "http://api.netatmo.net/api/getlasteventof?home_id=%7B%7D&offset=%7B%7D&person_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns most recent events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d08a0955-24e2-4d3b-9443-862dee78060f"
            }
          ]
        }
      ]
    }
  ]
}