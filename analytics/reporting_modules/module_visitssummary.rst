.. highlight:: js
.. default-domain:: js

VisitsSummary.get
`````````````````
TODO

.. function:: VisitsSummary.get(idSite, period, date, segment, columns)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param columns: TODO
    :returns: TODO

Report example::

    {
      "nb_uniq_visitors": 394,
      "nb_users": 0,
      "nb_visits": 422,
      "nb_actions": 727,
      "nb_visits_converted": 0,
      "bounce_count": 301,
      "sum_visit_length": 40731,
      "max_actions": 22,
      "bounce_rate": "71%",
      "nb_actions_per_visit": 1.7,
      "avg_time_on_site": 97
    }


VisitsSummary.getVisits
```````````````````````
TODO

.. function:: VisitsSummary.get(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":422}

VisitsSummary.getUniqueVisitors
```````````````````````````````
TODO

.. function:: VisitsSummary.getUniqueVisitors(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":394}

VisitsSummary.getUsers
``````````````````````
TODO

.. function:: VisitsSummary.getUsers(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":0}

VisitsSummary.getActions
````````````````````````
TODO

.. function:: VisitsSummary.getActions(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":727}

VisitsSummary.getMaxActions
```````````````````````````
TODO

.. function:: VisitsSummary.getMaxActions(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":22}

VisitsSummary.getBounceCount
````````````````````````````
TODO

.. function:: VisitsSummary.getBounceCount(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":301}

VisitsSummary.getVisitsConverted
````````````````````````````````
TODO

.. function:: VisitsSummary.getVisitsConverted(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":0}

VisitsSummary.getSumVisitsLength
````````````````````````````````
TODO

.. function:: VisitsSummary.getSumVisitsLength(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":40731}

VisitsSummary.getSumVisitsLengthPretty
``````````````````````````````````````
TODO

.. function:: VisitsSummary.getSumVisitsLengthPretty(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":"11 hours 18 min"}

