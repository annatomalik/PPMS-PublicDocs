.. highlight:: js
.. default-domain:: js

Resolution.getResolution
````````````````````````

TODO

.. function:: Resolution.getResolution(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "1920x1080",
        "nb_uniq_visitors": 57,
        "nb_visits": 63,
        "nb_actions": 89,
        "nb_users": 0,
        "max_actions": 5,
        "sum_visit_length": 1791,
        "bounce_count": 46,
        "nb_visits_converted": 0,
        "segment": "resolution==1920x1080"
      },
      {
        "label": "1366x768",
        "nb_uniq_visitors": 42,
        "nb_visits": 43,
        "nb_actions": 50,
        "nb_users": 0,
        "max_actions": 5,
        "sum_visit_length": 162,
        "bounce_count": 39,
        "nb_visits_converted": 0,
        "segment": "resolution==1366x768"
      }
    ]

Resolution.getConfiguration
```````````````````````````

TODO

.. function:: Resolution.getConfiguration(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Windows / Chrome / 1920x1080",
        "nb_uniq_visitors": 34,
        "nb_visits": 35,
        "nb_actions": 48,
        "nb_users": 0,
        "max_actions": 5,
        "sum_visit_length": 1317,
        "bounce_count": 27,
        "nb_visits_converted": 0
      },
      {
        "label": "Windows / Chrome / 1366x768",
        "nb_uniq_visitors": 29,
        "nb_visits": 30,
        "nb_actions": 37,
        "nb_users": 0,
        "max_actions": 5,
        "sum_visit_length": 162,
        "bounce_count": 26,
        "nb_visits_converted": 0
      }
    ]