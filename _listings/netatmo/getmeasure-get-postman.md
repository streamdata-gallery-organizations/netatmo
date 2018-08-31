{
  "info": {
    "name": "Netatmo Get Getmeasure",
    "_postman_id": "72f29445-45d6-43e4-9264-20bfdf3325ec",
    "description": "The method getmeasure returns the measurements of a device or a module.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devices",
      "item": [
        {
          "id": "8df7bc10-7ed3-431e-8505-bc50dc27e988",
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
              "id": "9bb17224-f5f5-4001-9cfb-15e80e558e5d"
            }
          ]
        },
        {
          "id": "76a60ee7-8b3e-4e35-a6c2-9658c81dd293",
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
              "id": "f091d203-411a-4194-9ce2-e602b1ebd219"
            }
          ]
        },
        {
          "id": "cdafb241-a044-4d5b-939a-16ecca45b320",
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
              "id": "bd0aec16-0e64-45b4-a0da-1cfc74ec8b13"
            }
          ]
        },
        {
          "id": "d1e24093-2f23-425d-9bd8-dfa47127f260",
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
              "id": "7c479e1f-266e-4f6e-9e6e-b34f7376222e"
            }
          ]
        },
        {
          "id": "de2260f5-141b-4548-8171-f30df98959c1",
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
              "id": "fc288ccf-d967-4453-96cc-6ba05892c59e"
            }
          ]
        }
      ]
    }
  ]
}