{
  "info": {
    "name": "Netatmo Get Getthermostatsdata",
    "_postman_id": "8f1960cc-696d-40ef-b1d4-751966905fa4",
    "description": "The method getthermostatsdata returns information about user's thermostats such as their last measurements.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "a4e20bea-adb4-40d6-9248-18c47a872739",
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
              "id": "fe6df00c-9d9e-485a-9708-98e865206be6"
            }
          ]
        },
        {
          "id": "c1ea0c71-fedc-48a4-bacc-8c3b865d2259",
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
              "id": "c1b571c6-624c-4f8c-8a63-870e4eb76eb6"
            }
          ]
        },
        {
          "id": "bcaace46-cfbc-44b3-9c85-aa0efb670ded",
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
              "id": "6e7a94d5-6a8e-449a-b0e0-263b18d45531"
            }
          ]
        },
        {
          "id": "dac26111-ba7e-4094-890d-eb6f1ff1e533",
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
              "id": "d0d3362b-f5aa-496c-af1d-ad17832a0e5b"
            }
          ]
        },
        {
          "id": "338493ca-5db0-4e39-b483-0da10d5b1ea1",
          "name": "getmeasure",
          "request": {
            "url": "http://api.netatmo.net/api/getmeasure?date_begin=%7B%7D&date_end=%7B%7D&device_id=%7B%7D&limit=%7B%7D&module_id=%7B%7D&optimize=%7B%7D&real_time=%7B%7D&scale=%7B%7D&type=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The method getmeasure returns the measurements of a device or a module."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "34b45e25-82b7-4031-a8f1-82fe9e5ab677"
            }
          ]
        },
        {
          "id": "462167b1-d675-4416-b568-821b5961abc5",
          "name": "getnextevents",
          "request": {
            "url": "http://api.netatmo.net/api/getnextevents?event_id=%7B%7D&home_id=%7B%7D&size=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns previous events."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1988b442-e9df-4bab-95c7-9efbfdc4b6b8"
            }
          ]
        },
        {
          "id": "426f0988-c150-497c-b376-1bbdd357ed85",
          "name": "getthermostatsdata",
          "request": {
            "url": "http://api.netatmo.net/api/getthermostatsdata?device_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The method getthermostatsdata returns information about user's thermostats such as their last measurements."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "890bd992-07e6-4040-b345-b0618d3049ba"
            }
          ]
        }
      ]
    }
  ]
}