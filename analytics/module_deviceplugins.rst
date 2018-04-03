.. highlight:: js
.. default-domain:: js

DevicesDetection.getType
````````````````````````
TODO

.. function:: DevicesDetection.getType(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Desktop",
        "nb_uniq_visitors": 295,
        "nb_visits": 323,
        "nb_actions": 541,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 27153,
        "bounce_count": 234,
        "nb_visits_converted": 0,
        "segment": "deviceType==desktop",
        "logo": "plugins/Morpheus/icons/dist/devices/desktop.png"
      },
      {
        "label": "Smartphone",
        "nb_uniq_visitors": 9,
        "nb_visits": 9,
        "nb_actions": 10,
        "nb_users": 0,
        "max_actions": 2,
        "sum_visit_length": 124,
        "bounce_count": 8,
        "nb_visits_converted": 0,
        "segment": "deviceType==smartphone",
        "logo": "plugins/Morpheus/icons/dist/devices/smartphone.png"
      }
    ]

DevicesDetection.getBrand
`````````````````````````
TODO

.. function:: DevicesDetection.getBrand(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Unknown",
        "nb_uniq_visitors": 297,
        "nb_visits": 325,
        "nb_actions": 544,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 27223,
        "bounce_count": 235,
        "nb_visits_converted": 0,
        "logo": "plugins/Morpheus/icons/dist/brand/unk.png",
        "segment": "deviceBrand==Unknown"
      },
      {
        "label": "Samsung",
        "nb_uniq_visitors": 4,
        "nb_visits": 4,
        "nb_actions": 5,
        "nb_users": 0,
        "max_actions": 2,
        "sum_visit_length": 92,
        "bounce_count": 3,
        "nb_visits_converted": 0,
        "logo": "plugins/Morpheus/icons/dist/brand/Samsung.png",
        "segment": "deviceBrand==Samsung"
      }
    ]

DevicesDetection.getModel
`````````````````````````
TODO

.. function:: DevicesDetection.getModel(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Unknown",
        "nb_uniq_visitors": 297,
        "nb_visits": 325,
        "nb_actions": 544,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 27223,
        "bounce_count": 235,
        "nb_visits_converted": 0,
        "segment": "deviceBrand==Unknown;deviceModel=="
      },
      {
        "label": "Apple - iPhone",
        "nb_uniq_visitors": 2,
        "nb_visits": 2,
        "nb_actions": 2,
        "nb_users": 0,
        "max_actions": 1,
        "sum_visit_length": 0,
        "bounce_count": 2,
        "nb_visits_converted": 0,
        "segment": "deviceBrand==Apple;deviceModel==iPhone"
      }
    ]

DevicesDetection.getOsFamilies
``````````````````````````````
TODO

.. function:: DevicesDetection.getOsFamilies(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Windows",
        "nb_uniq_visitors": 201,
        "nb_visits": 222,
        "nb_actions": 388,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 19253,
        "bounce_count": 157,
        "nb_visits_converted": 0,
        "logo": "plugins/Morpheus/icons/dist/os/WIN.png"
      },
      {
        "label": "Mac",
        "nb_uniq_visitors": 53,
        "nb_visits": 57,
        "nb_actions": 88,
        "nb_users": 0,
        "max_actions": 9,
        "sum_visit_length": 5142,
        "bounce_count": 44,
        "nb_visits_converted": 0,
        "logo": "plugins/Morpheus/icons/dist/os/MAC.png"
      }
    ]

DevicesDetection.getOsVersions
``````````````````````````````
TODO

.. function:: DevicesDetection.getOsVersions(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Windows 10",
        "nb_uniq_visitors": 105,
        "nb_visits": 113,
        "nb_actions": 216,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 13251,
        "bounce_count": 78,
        "nb_visits_converted": 0,
        "segment": "operatingSystemCode==WIN;operatingSystemVersion==10",
        "logo": "plugins/Morpheus/icons/dist/os/WIN.png"
      },
      {
        "label": "Windows 7",
        "nb_uniq_visitors": 76,
        "nb_visits": 86,
        "nb_actions": 143,
        "nb_users": 0,
        "max_actions": 10,
        "sum_visit_length": 5599,
        "bounce_count": 62,
        "nb_visits_converted": 0,
        "segment": "operatingSystemCode==WIN;operatingSystemVersion==7",
        "logo": "plugins/Morpheus/icons/dist/os/WIN.png"
      }
    ]

DevicesDetection.getBrowsers
````````````````````````````
TODO

.. function:: DevicesDetection.getBrowsers(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Chrome",
        "nb_uniq_visitors": 209,
        "nb_visits": 227,
        "nb_actions": 336,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 13670,
        "bounce_count": 172,
        "nb_visits_converted": 0,
        "logo": "plugins/Morpheus/icons/dist/browsers/CH.png",
        "segment": "browserCode==CH"
      },
      {
        "label": "Firefox",
        "nb_uniq_visitors": 58,
        "nb_visits": 65,
        "nb_actions": 142,
        "nb_users": 0,
        "max_actions": 10,
        "sum_visit_length": 10471,
        "bounce_count": 42,
        "nb_visits_converted": 0,
        "logo": "plugins/Morpheus/icons/dist/browsers/FF.png",
        "segment": "browserCode==FF"
      }
    ]

DevicesDetection.getBrowserVersions
```````````````````````````````````
TODO

.. function:: DevicesDetection.getBrowserVersions(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Chrome 65.0",
        "nb_uniq_visitors": 166,
        "nb_visits": 181,
        "nb_actions": 268,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 10635,
        "bounce_count": 134,
        "nb_visits_converted": 0,
        "segment": "browserCode==CH;browserVersion==65.0",
        "logo": "plugins/Morpheus/icons/dist/browsers/CH.png"
      },
      {
        "label": "Firefox 59.0",
        "nb_uniq_visitors": 41,
        "nb_visits": 44,
        "nb_actions": 96,
        "nb_users": 0,
        "max_actions": 10,
        "sum_visit_length": 7751,
        "bounce_count": 28,
        "nb_visits_converted": 0,
        "segment": "browserCode==FF;browserVersion==59.0",
        "logo": "plugins/Morpheus/icons/dist/browsers/FF.png"
      }
    ]

DevicesDetection.getBrowserEngines
``````````````````````````````````
TODO

.. function:: DevicesDetection.getBrowserEngines(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Blink (Chrome, Opera)",
        "nb_uniq_visitors": 225,
        "nb_visits": 244,
        "nb_actions": 373,
        "nb_users": 0,
        "max_actions": 11,
        "sum_visit_length": 16604,
        "bounce_count": 184,
        "nb_visits_converted": 0,
        "segment": "browserEngine==Blink"
      },
      {
        "label": "Gecko (Firefox)",
        "nb_uniq_visitors": 58,
        "nb_visits": 65,
        "nb_actions": 142,
        "nb_users": 0,
        "max_actions": 10,
        "sum_visit_length": 10471,
        "bounce_count": 42,
        "nb_visits_converted": 0,
        "segment": "browserEngine==Gecko"
      }
    ]
