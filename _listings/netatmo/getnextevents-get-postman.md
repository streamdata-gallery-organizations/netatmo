{
  "info": {
    "name": "Netatmo Get Getnextevents",
    "_postman_id": "22934579-e34c-4abf-8935-9d2a673e056f",
    "description": "Returns previous events.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "244a7418-5018-471c-b58b-a4262862fb9d",
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
              "id": "912c9785-aa87-4257-9f69-bb7794b6e289"
            }
          ]
        },
        {
          "id": "ed6c274a-02f0-4b64-8dc0-11e2f89b81da",
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
              "id": "0bc08f50-8be1-4ee7-acc3-75b83ca60c92"
            }
          ]
        },
        {
          "id": "de103bd7-3658-4ed9-9e73-ccf41e31107b",
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
              "id": "63d83eb0-2a0d-4700-84b3-afd2b092e5f9"
            }
          ]
        },
        {
          "id": "6a83475c-d74d-49fd-9ae6-8190f70ea481",
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
              "id": "d53f78d5-66a5-4306-84fc-c334b038c976"
            }
          ]
        },
        {
          "id": "76023f1f-9de0-43f4-9264-2131c0930a8b",
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
              "id": "652ff6df-9a43-480d-b7f3-1ef7f84be3a4"
            }
          ]
        },
        {
          "id": "f03c7cb1-fdac-4087-995a-39e71b4f030e",
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
              "id": "b6b3110f-b328-4cf9-b98c-75475fca10e2"
            }
          ]
        }
      ]
    }
  ]
}