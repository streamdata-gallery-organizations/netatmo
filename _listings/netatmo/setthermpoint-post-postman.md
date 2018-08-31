{
  "info": {
    "name": "Netatmo Post Setthermpoint",
    "_postman_id": "d1baea1a-72a5-41b8-919d-ebf78c280783",
    "description": "The method setthermpoint changes the Thermostat manual temperature setpoint.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "f0a4b54e-370c-419f-beb1-d4b097261198",
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
              "id": "700abab5-4bc5-47e4-b2e5-7ae40f87f169"
            }
          ]
        },
        {
          "id": "2ea6ccbb-539a-4358-b522-d308edc28dc1",
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
              "id": "49210511-fa45-4d42-9546-0babbe07b27c"
            }
          ]
        },
        {
          "id": "b04a0a40-98a7-494b-8821-3f6e7e663a22",
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
              "id": "28c69f97-f33d-4a93-b6ed-d0c06110a5ad"
            }
          ]
        },
        {
          "id": "54d121bf-0792-48f7-86d3-4689a08487a7",
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
              "id": "5c3a1af9-6031-444c-a6d0-68ff5cd3b8ee"
            }
          ]
        },
        {
          "id": "d9806d0b-5eb7-4fff-af99-c1356cb31f41",
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
              "id": "023c059a-9cf3-4c6e-81ae-5b1662451bd4"
            }
          ]
        },
        {
          "id": "ad70a2e6-d459-4499-baf0-bc664ade4ef3",
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
              "id": "1dd6ec7c-5849-4791-bddb-ddd48ddefdc0"
            }
          ]
        },
        {
          "id": "ac7fe629-2d78-467f-ae02-08a6c1ba3314",
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
              "id": "55d10439-956a-443a-bab5-a30a86b49f8e"
            }
          ]
        },
        {
          "id": "bdb7625d-0206-4399-937f-497245b389d1",
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
              "id": "828d5317-74e7-4bf2-ae61-7f48fef1906c"
            }
          ]
        },
        {
          "id": "89f87990-c10e-4db4-87a4-c138314360a5",
          "name": "setpersonsaway",
          "request": {
            "url": "http://api.netatmo.net/api/setpersonsaway?home_id=%7B%7D&person_id=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets a person as 'Away' or the Home as 'Empty'. The event will be added to the user???s timeline."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e38f80dc-ff52-485b-8534-5fee0286d85b"
            }
          ]
        },
        {
          "id": "a44a5e73-3d04-4ea1-b198-0e6bc5103e70",
          "name": "setthermpoint",
          "request": {
            "url": "http://api.netatmo.net/api/setthermpoint?device_id=%7B%7D&module_id=%7B%7D&setpoint_endtime=%7B%7D&setpoint_mode=%7B%7D&setpoint_temp=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The method setthermpoint changes the Thermostat manual temperature setpoint."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "803e4f68-6b0c-4f69-b456-69130c56bd1e"
            }
          ]
        }
      ]
    }
  ]
}