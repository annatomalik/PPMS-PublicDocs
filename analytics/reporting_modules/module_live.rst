.. highlight:: js
.. default-domain:: js

Live.getCounters
````````````````
TODO

.. function:: Live.getCounters(idSite, lastMinutes, segment, showColumns, hideColumns)

    :param idSite: TODO
    :param lastMinutes: TODO
    :param segment: TODO
    :param showColumns: TODO
    :param hideColumns: TODO
    :returns: TODO

Report example::

    [
      {
        "visits": "17",
        "actions": "39",
        "visitors": "17",
        "visitsConverted": "0"
      }
    ]

Live.getLastVisitsDetails
`````````````````````````
TODO

.. function:: Live.getLastVisitsDetails(idSite, period, date, segment, countVisitorsToFetch, minTimestamp, flat, doNotFetchActions)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param countVisitorsToFetch: TODO
    :param minTimestamp: TODO
    :param flat: TODO
    :param doNotFetchActions: TODO
    :returns: TODO

Report example::

    [
      {
        "idSite": "7",
        "idVisit": "25811492",
        "visitIp": null,
        "visitorId": false,
        "actionDetails": [
          {
            "type": "action",
            "url": "example.com/test-page",
            "pageTitle": "Example com test page",
            "pageIdAction": "2005306",
            "idpageview": "AnzhSt",
            "serverTimePretty": "Apr 4, 2018 06:54:06",
            "pageId": "111009685",
            "generationTimeMilliseconds": "670",
            "generationTime": "0.67s",
            "interactionPosition": "1",
            "icon": null,
            "timestamp": 1522824846,
            "dimension1": "test-dimension"
          }
        ],
        "goalConversions": 0,
        "siteCurrency": "USD",
        "siteCurrencySymbol": "$",
        "serverDate": "2018-04-04",
        "visitServerHour": "6",
        "lastActionTimestamp": 1522824846,
        "lastActionDateTime": "2018-04-04 06:54:06",
        "serverTimestamp": 1522824846,
        "firstActionTimestamp": 1522824846,
        "serverTimePretty": "06:54:06",
        "serverDatePretty": "Wednesday, April 4, 2018",
        "serverDatePrettyFirstAction": "Wednesday, April 4, 2018",
        "serverTimePrettyFirstAction": "06:54:06",
        "userId": null,
        "visitorType": "returning",
        "visitorTypeIcon": "plugins/Live/images/returningVisitor.png",
        "visitConverted": "0",
        "visitConvertedIcon": null,
        "visitCount": "2",
        "visitEcommerceStatus": "none",
        "visitEcommerceStatusIcon": null,
        "daysSinceFirstVisit": "1",
        "daysSinceLastEcommerceOrder": "0",
        "visitDuration": "0",
        "visitDurationPretty": "0s",
        "searches": "0",
        "actions": "1",
        "interactions": "1",
        "referrerType": "search",
        "referrerTypeName": "Search Engines",
        "referrerName": "Google",
        "referrerKeyword": "Keyword not defined",
        "referrerKeywordPosition": null,
        "referrerUrl": "https://www.google.nl/",
        "referrerSearchEngineUrl": "http://google.com",
        "referrerSearchEngineIcon": "plugins/Morpheus/icons/dist/searchEngines/google.com.png",
        "languageCode": "nl-nl",
        "language": "Language code nl-nl",
        "deviceType": "Desktop",
        "deviceTypeIcon": "plugins/Morpheus/icons/dist/devices/desktop.png",
        "deviceBrand": "Unknown",
        "deviceModel": "",
        "operatingSystem": "Mac 10.13",
        "operatingSystemName": "Mac",
        "operatingSystemIcon": "plugins/Morpheus/icons/dist/os/MAC.png",
        "operatingSystemCode": "MAC",
        "operatingSystemVersion": "10.13",
        "browserFamily": "Blink",
        "browserFamilyDescription": "Blink (Chrome, Opera)",
        "browser": "Chrome 65.0",
        "browserName": "Chrome",
        "browserIcon": "plugins/Morpheus/icons/dist/browsers/CH.png",
        "browserCode": "CH",
        "browserVersion": "65.0",
        "totalEcommerceRevenue": "0.00",
        "totalEcommerceConversions": "0",
        "totalEcommerceItems": "0",
        "totalAbandonedCartsRevenue": "0.00",
        "totalAbandonedCarts": "0",
        "totalAbandonedCartsItems": "0",
        "events": "0",
        "continent": "Europe",
        "continentCode": "eur",
        "country": "Netherlands",
        "countryCode": "nl",
        "countryFlag": "plugins/Morpheus/icons/dist/flags/nl.png",
        "region": "Zuid-Holland",
        "regionCode": "11",
        "city": "Den Haag",
        "location": "Den Haag, Zuid-Holland, Netherlands",
        "latitude": "52.093000",
        "longitude": "4.276000",
        "visitLocalTime": "08:54:06",
        "visitLocalHour": "8",
        "daysSinceLastVisit": "0",
        "customVariables": [],
        "resolution": "1920x1080",
        "plugins": "cookie, pdf",
        "pluginsIcons": [
          {
            "pluginIcon": "plugins/Morpheus/icons/dist/plugins/cookie.png",
            "pluginName": "cookie"
          },
          {
            "pluginIcon": "plugins/Morpheus/icons/dist/plugins/pdf.png",
            "pluginName": "pdf"
          }
        ],
        "provider": "Ziggo",
        "providerName": "Ziggo",
        "providerUrl": "http://www.Ziggo/"
      }
    ]

Live.getVisitorProfile
``````````````````````
TODO

.. function:: Live.getVisitorProfile(idSite, visitorId, segment, limitVisits)

    :param idSite: TODO
    :param visitorId: TODO
    :param segment: TODO
    :param limitVisits: TODO
    :returns: TODO

Report example::

    TODO

Live.getMostRecentVisitorId
```````````````````````````
TODO

.. function:: Live.getMostRecentVisitorId(idSite, segment)

    :param idSite: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":"2004d5832c108bec"}

