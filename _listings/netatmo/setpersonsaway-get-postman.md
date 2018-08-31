{
  "info": {
    "name": "Netatmo Get Setpersonsaway",
    "_postman_id": "d0c83ac4-c0c8-41ea-b412-01da0437ab37",
    "description": "Sets a person as 'Away' or the Home as 'Empty'. The event will be added to the user???s timeline.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "c9258b49-0dd0-46d8-9912-bceb3aa3d9dc",
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
              "id": "3caef96e-5441-4f57-85db-d338d07fa6c6"
            }
          ]
        },
        {
          "id": "742ed843-e37d-40ab-9b96-73cbd3d23e8a",
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
              "id": "b36aa013-83c6-4115-8233-61d91fc33356"
            }
          ]
        },
        {
          "id": "d2e9a573-5f8a-4541-9133-f8e64f1d15d3",
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
              "id": "80bf7ad1-4af1-44b9-b11e-634d42c917b5"
            }
          ]
        },
        {
          "id": "3052e555-019b-412f-b9c8-910db89792c7",
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
              "id": "11fc6658-fd7c-4508-842b-a6d5fb1ba35b"
            }
          ]
        },
        {
          "id": "98801520-8ede-4f86-b66d-12b8c9a79af7",
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
              "id": "fcf574a4-d610-43a2-88c0-cdaf630eae50"
            }
          ]
        },
        {
          "id": "8e5e3c34-b3bd-4bab-9659-bd5775ac66c0",
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
              "id": "595f28c0-369b-4ae0-8f53-7a0605edcd83"
            }
          ]
        },
        {
          "id": "1669a68b-0c0d-4d00-91df-8772fea25709",
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
              "id": "a850cdcc-0fd5-40cd-a43e-e83e54e17017"
            }
          ]
        },
        {
          "id": "11e39246-8301-4773-b30b-81a60bc1f35f",
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
              "id": "e4748444-2755-40a0-b917-32bf2de4c016"
            }
          ]
        },
        {
          "id": "e579c312-eefc-48eb-ba58-8fa03f997f80",
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
              "id": "806d71a6-82f8-4c94-b015-0d097eb134db"
            }
          ]
        }
      ]
    }
  ]
}