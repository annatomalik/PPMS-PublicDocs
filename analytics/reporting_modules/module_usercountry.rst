.. highlight:: js
.. default-domain:: js

UserCountry.getCountry
``````````````````````
TODO

.. function:: UserCountry.getCountry(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "United States",
        "nb_uniq_visitors": 53,
        "nb_visits": 54,
        "nb_actions": 92,
        "nb_users": 0,
        "max_actions": 9,
        "sum_visit_length": 2511,
        "bounce_count": 34,
        "nb_visits_converted": 0,
        "code": "us",
        "logo": "plugins/Morpheus/icons/dist/flags/us.png",
        "segment": "countryCode==us",
        "logoHeight": 16
      }
    ]

UserCountry.getContinent
````````````````````````
TODO

.. function:: UserCountry.getContinent(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Europe",
        "nb_uniq_visitors": 143,
        "nb_visits": 154,
        "nb_actions": 328,
        "nb_users": 0,
        "max_actions": 17,
        "sum_visit_length": 21237,
        "bounce_count": 95,
        "nb_visits_converted": 0,
        "code": "Europe"
      }
    ]


UserCountry.getRegion
`````````````````````
TODO

.. function:: UserCountry.getRegion(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Unknown",
        "nb_uniq_visitors": 95,
        "nb_visits": 97,
        "nb_actions": 190,
        "nb_users": 0,
        "max_actions": 17,
        "sum_visit_length": 5699,
        "bounce_count": 59,
        "nb_visits_converted": 0,
        "region": "xx",
        "country": "xx",
        "country_name": "Unknown",
        "region_name": "Unknown",
        "logo": "plugins/Morpheus/icons/dist/flags/xx.png"
      }
    ]

UserCountry.getCity
```````````````````
TODO

.. function:: UserCountry.getCity(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Unknown",
        "nb_uniq_visitors": 95,
        "nb_visits": 97,
        "nb_actions": 190,
        "nb_users": 0,
        "max_actions": 17,
        "sum_visit_length": 5699,
        "bounce_count": 59,
        "nb_visits_converted": 0,
        "city_name": "Unknown",
        "city": "xx",
        "region": "xx",
        "country": "xx",
        "country_name": "Unknown",
        "region_name": "Unknown",
        "logo": "plugins/Morpheus/icons/dist/flags/xx.png"
      }
    ]

UserCountry.getCountryCodeMapping
`````````````````````````````````
TODO

.. function:: UserCountry.getCountryCodeMapping()

    :returns: TODO

Report example::

    [
      {
        "ad": "Andorra",
        "ae": "United Arab Emirates",
        "af": "Afghanistan",
      }
    ]

UserCountry.getLocationFromIP
`````````````````````````````
TODO

.. function:: UserCountry.getLocationFromIP(ip, provider)

    :param ip: TODO
    :param provider: TODO
    :returns: TODO

Report example::

    [
      {
        "country_code": "PL",
        "region_code": "72",
        "city_name": "Wroclaw",
        "area_code": null,
        "continent_code": "eur",
        "continent_name": "Europe",
        "country_name": "Poland",
        "region_name": "Dolnoslaskie",
       }
    ]

UserCountry.setLocationProvider
```````````````````````````````
TODO

.. function:: UserCountry.setLocationProvider(providerId)

    :param providerId: TODO
    :returns: TODO

Report example::

    TODO

UserCountry.getNumberOfDistinctCountries
````````````````````````````````````````
TODO

.. function:: UserCountry.getNumberOfDistinctCountries(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example:

    {"value":54}