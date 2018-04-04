.. highlight:: js
.. default-domain:: js

VisitTime.getVisitInformationPerLocalTime
`````````````````````````````````````````
TODO

.. function:: VisitTime.getVisitInformationPerLocalTime(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "00",
        "nb_uniq_visitors": 2,
        "nb_visits": 2,
        "nb_actions": 2,
        "nb_users": 0,
        "max_actions": 1,
        "sum_visit_length": 0,
        "bounce_count": 2,
        "nb_visits_converted": 0,
        "segment": "visitLocalHour==0"
      }
    ]

VisitTime.getVisitInformationPerServerTime
``````````````````````````````````````````
TODO

.. function:: VisitTime.getVisitInformationPerServerTime(idSite, period, date, segment, hideFutureHoursWhenToday)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param hideFutureHoursWhenToday: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "00",
        "nb_uniq_visitors": 17,
        "nb_visits": 18,
        "nb_actions": 24,
        "nb_users": 0,
        "max_actions": 3,
        "sum_visit_length": 203,
        "bounce_count": 14,
        "nb_visits_converted": 0,
        "segment": "visitServerHour==0"
      }
    ]

VisitTime.getByDayOfWeek
````````````````````````
TODO

.. function:: VisitTime.getByDayOfWeek(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Monday",
        "nb_visits": 0,
        "day_of_week": 1
      },
      {
        "label": "Tuesday",
        "nb_visits": 0,
        "day_of_week": 2
      },
      {
        "label": "Wednesday",
        "nb_visits": 422,
        "nb_uniq_visitors": 394,
        "nb_actions": 727,
        "nb_users": 0,
        "sum_visit_length": 40731,
        "bounce_count": 301,
        "nb_visits_converted": 0,
        "day_of_week": 3
      },
      {
        "label": "Thursday",
        "nb_visits": 0,
        "day_of_week": 4
      },
      {
        "label": "Friday",
        "nb_visits": 0,
        "day_of_week": 5
      },
      {
        "label": "Saturday",
        "nb_visits": 0,
        "day_of_week": 6
      },
      {
        "label": "Sunday",
        "nb_visits": 0,
        "day_of_week": 7
      }
    ]