---
name: Netatmo
x-slug: netatmo
description: We develop groundbreaking, intuitive and beautifully-designed connected
  consumer electronics. Truly smart, our innovative products provide a seamless experience
  that helps users create a safer, healthier and more comfortable home. We carefully
  design the mechanics, electronics and embedded software of all our products to the
  highest standards. Our mobile and web applications are designed to be simple to
  operate, yet deliver a rich user experience.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Netatmo
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/apis.md
specificationVersion: "0.14"
apis:
- name: Netatmo Get Addwebhook
  x-api-slug: netatmo
  description: Links a callback url to a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//addwebhook
  tags: Web Hooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/addwebhook-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/addwebhook-get-openapi.md
- name: Netatmo Post Createnewschedule
  x-api-slug: netatmo
  description: The method createnewschedule creates a new schedule stored in the backup
    list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//createnewschedule
  tags: Schedules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/createnewschedule-post-openapi.md
- name: Netatmo Get Devicelist
  x-api-slug: netatmo
  description: |-
    The method devicelist returns the list of devices owned by the user, and their modules.
    A device is identified by its _id (which is its mac address) and each device may have one, several or no modules, also identified by an _id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//devicelist
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/devicelist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/devicelist-get-openapi.md
- name: Netatmo Get Dropwebhook
  x-api-slug: netatmo
  description: Dissociates a webhook from a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//dropwebhook
  tags: Web Hooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/dropwebhook-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/dropwebhook-get-openapi.md
- name: Netatmo Get Getcamerapicture
  x-api-slug: netatmo
  description: Returns the snapshot associated to an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getcamerapicture
  tags: Cameras,ictures
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getcamerapicture-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getcamerapicture-get-openapi.md
- name: Netatmo Get Geteventsuntil
  x-api-slug: netatmo
  description: Returns the snapshot associated to an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//geteventsuntil
  tags: Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/geteventsuntil-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/geteventsuntil-get-openapi.md
- name: Netatmo Get Gethomecoachsdata
  x-api-slug: netatmo
  description: The method gethomecoachsdata Returns data from a user Healthy Home
    Coach Station (measures and device specific data).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//gethomecoachsdata
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/gethomecoachsdata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/gethomecoachsdata-get-openapi.md
- name: Netatmo Get Gethomedata
  x-api-slug: netatmo
  description: Returns information about users homes and cameras.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//gethomedata
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/gethomedata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/gethomedata-get-openapi.md
- name: Netatmo Get Getlasteventof
  x-api-slug: netatmo
  description: Returns most recent events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getlasteventof
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getlasteventof-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getlasteventof-get-openapi.md
- name: Netatmo Get Getmeasure
  x-api-slug: netatmo
  description: The method getmeasure returns the measurements of a device or a module.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getmeasure
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getmeasure-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getmeasure-get-openapi.md
- name: Netatmo Get Getnextevents
  x-api-slug: netatmo
  description: Returns previous events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getnextevents
  tags: Devices,Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getnextevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getnextevents-get-openapi.md
- name: Netatmo Get Getstationsdata
  x-api-slug: netatmo
  description: The method getstationsdata Returns data from a user Weather Stations
    (measures and device specific data).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getstationsdata
  tags: Weather,Stations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getstationsdata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getstationsdata-get-openapi.md
- name: Netatmo Get Getthermostatsdata
  x-api-slug: netatmo
  description: The method getthermostatsdata returns information about user's thermostats
    such as their last measurements.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getthermostatsdata
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getthermostatsdata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getthermostatsdata-get-openapi.md
- name: Netatmo Get Getthermstate
  x-api-slug: netatmo
  description: The method getthermstate returns the last Thermostat measurements,
    its current weekly schedule, and, if present, its current manual temperature setpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getthermstate
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getthermstate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getthermstate-get-openapi.md
- name: Netatmo Get Getuser
  x-api-slug: netatmo
  description: The method getuser returns information about a user such as prefered
    language, prefered units, and list of devices.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//getuser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/getuser-get-openapi.md
- name: Netatmo Get Partnerdevices
  x-api-slug: netatmo
  description: The method partnerdevices returns the list of device_id to which your
    partner application has access to.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//partnerdevices
  tags: Partners
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/partnerdevices-get-openapi.md
- name: Netatmo Get Setpersonsaway
  x-api-slug: netatmo
  description: "Sets a person as 'Away' or the Home as 'Empty'. The event will be
    added to the user\u2019s timeline."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//setpersonsaway
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/setpersonsaway-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/setpersonsaway-get-openapi.md
- name: Netatmo Post Setthermpoint
  x-api-slug: netatmo
  description: The method setthermpoint changes the Thermostat manual temperature
    setpoint.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//setthermpoint
  tags: Devices
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/setthermpoint-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/setthermpoint-post-openapi.md
- name: Netatmo Post Switchschedule
  x-api-slug: netatmo
  description: The method switchschedule switches the Thermostat's schedule to another
    existing schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//switchschedule
  tags: Schedules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/switchschedule-post-openapi.md
- name: Netatmo Post Syncschedule
  x-api-slug: netatmo
  description: The method syncschedule changes the Thermostat weekly schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api//syncschedule
  tags: Schedules
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/syncschedule-post-openapi.md
- name: Netatmo
  x-api-slug: netatmo
  description: Netatmo offers wireless thermostats and air quality measuring devices
    that can be accessed over the internet. Their Private API allows device owners
    to grant third party applications access to their devices in order to retrieve
    the data the devices have recorded. In the near future, developers will also have
    access to the Netatmo Public API, which will allow third party applications to
    retrieve data that has been marked as public by the device&#039;s owner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/netatmo-logo.png
  humanURL: http://www.netatmo.com
  baseURL: https://api.netatmo.net//api
  tags: Netatmo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/netatmo/master/_listings/netatmo/openapi.md
x-common:
- type: x-website
  url: http://www.netatmo.com
- type: x-documentation
  url: https://dev.netatmo.com/resources/technical/reference
- type: x-github
  url: https://github.com/netatmo
- type: x-twitter
  url: https://twitter.com/netatmo
- type: x-website
  url: http://netatmo.net
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---