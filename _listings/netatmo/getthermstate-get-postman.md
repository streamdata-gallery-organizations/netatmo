{
  "info": {
    "name": "Netatmo Get Getthermstate",
    "_postman_id": "b749271c-b995-48f2-b9a7-5bf99f22a07d",
    "description": "The method getthermstate returns the last Thermostat measurements, its current weekly schedule, and, if present, its current manual temperature setpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "fb94df44-8f70-4461-9123-82dde648fe1b",
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
              "id": "4c3f3471-494c-4e3e-91d4-428bfd59ed09"
            }
          ]
        },
        {
          "id": "671c8426-abe3-4555-8417-9c300ead3e58",
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
              "id": "7c462b79-f17e-47f0-a222-7f9800e12a3c"
            }
          ]
        },
        {
          "id": "89410884-edac-462f-8b6d-9893afd64ccd",
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
              "id": "916657b7-3f35-4775-a75f-66d5e2bf86d4"
            }
          ]
        },
        {
          "id": "4c97c555-874a-44de-8e05-85decb5d0523",
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
              "id": "d3fb939c-c97c-4f11-ba53-61f9394d5fab"
            }
          ]
        },
        {
          "id": "c1154f39-c569-4530-993f-e8d3bfb0486e",
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
              "id": "d1fac00e-88e8-43a3-bf6b-302435e1edae"
            }
          ]
        },
        {
          "id": "f3c8baeb-3701-4900-8dcb-384c4ac93719",
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
              "id": "8e119eb5-f3cd-4a14-8fb3-f5165356c43c"
            }
          ]
        },
        {
          "id": "a159ec3e-e745-4fcc-9e3d-33aa41fd4033",
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
              "id": "866595c0-2d8b-4c31-8ce3-39a5462c4d99"
            }
          ]
        },
        {
          "id": "9b772f6a-02e5-4022-836e-5fdfb44f7130",
          "name": "getthermstate",
          "request": {
            "url": "http://api.netatmo.net/api/getthermstate?device_id=%7B%7D&module_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The method getthermstate returns the last Thermostat measurements, its current weekly schedule, and, if present, its current manual temperature setpoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "77f1fc4f-f16d-4e5f-b32b-e41eba050496"
            }
          ]
        }
      ]
    }
  ]
}