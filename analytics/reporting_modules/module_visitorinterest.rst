.. highlight:: js
.. default-domain:: js

VisitorInterest.getNumberOfVisitsPerVisitDuration
`````````````````````````````````````````````````
TODO

.. function:: VisitorInterest.getNumberOfVisitsPerVisitDuration(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "0-10s",
        "nb_visits": "335"
      },
      {
        "label": "11-30s",
        "nb_visits": "11"
      },
      {
        "label": "31-60s",
        "nb_visits": "12"
      },
      {
        "label": "1-2 min",
        "nb_visits": "13"
      },
      {
        "label": "2-4 min",
        "nb_visits": "15"
      },
      {
        "label": "4-7 min",
        "nb_visits": "13"
      },
      {
        "label": "7-10 min",
        "nb_visits": "6"
      },
      {
        "label": "10-15 min",
        "nb_visits": "7"
      },
      {
        "label": "15-30 min",
        "nb_visits": "8"
      },
      {
        "label": "30+ min",
        "nb_visits": "4"
      }
    ]

VisitorInterest.getNumberOfVisitsPerPage
````````````````````````````````````````
TODO

.. function:: VisitorInterest.getNumberOfVisitsPerPage(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "1 page",
        "nb_visits": "301"
      },
      {
        "label": "2 pages",
        "nb_visits": "68"
      },
      {
        "label": "3 pages",
        "nb_visits": "19"
      },
      {
        "label": "4 pages",
        "nb_visits": "8"
      },
      {
        "label": "5 pages",
        "nb_visits": "9"
      },
      {
        "label": "6-7 pages",
        "nb_visits": "9"
      },
      {
        "label": "8-10 pages",
        "nb_visits": "4"
      },
      {
        "label": "11-14 pages",
        "nb_visits": "2"
      },
      {
        "label": "15-20 pages",
        "nb_visits": "1"
      },
      {
        "label": "21+ pages",
        "nb_visits": "1"
      }
    ]

VisitorInterest.getNumberOfVisitsByDaysSinceLast
````````````````````````````````````````````````
TODO

.. function:: VisitorInterest.getNumberOfVisitsByDaysSinceLast(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "New visits",
        "nb_visits": "335"
      },
      {
        "label": "0 days",
        "nb_visits": "84"
      },
      {
        "label": "1 day",
        "nb_visits": "3"
      },
      {
        "label": "2 days",
        "nb_visits": "0"
      },
      {
        "label": "3 days",
        "nb_visits": "0"
      },
      {
        "label": "4 days",
        "nb_visits": "0"
      },
      {
        "label": "5 days",
        "nb_visits": "0"
      },
      {
        "label": "6 days",
        "nb_visits": "0"
      },
      {
        "label": "7 days",
        "nb_visits": "0"
      },
      {
        "label": "8-14 days",
        "nb_visits": "0"
      },
      {
        "label": "15-30 days",
        "nb_visits": "0"
      },
      {
        "label": "31-60 days",
        "nb_visits": "0"
      },
      {
        "label": "61-120 days",
        "nb_visits": "0"
      },
      {
        "label": "121-364 days",
        "nb_visits": "0"
      },
      {
        "label": "365+ days",
        "nb_visits": "0"
      }
    ]

VisitorInterest.getNumberOfVisitsByVisitCount
`````````````````````````````````````````````
TODO

.. function:: VisitorInterest.getNumberOfVisitsByVisitCount(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "1 visit",
        "nb_visits": "336",
        "nb_visits_percentage": "80%"
      },
      {
        "label": "2 visits",
        "nb_visits": "38",
        "nb_visits_percentage": "9%"
      },
      {
        "label": "3 visits",
        "nb_visits": "17",
        "nb_visits_percentage": "4%"
      },
      {
        "label": "4 visits",
        "nb_visits": "6",
        "nb_visits_percentage": "1%"
      },
      {
        "label": "5 visits",
        "nb_visits": "5",
        "nb_visits_percentage": "1%"
      },
      {
        "label": "6 visits",
        "nb_visits": "2",
        "nb_visits_percentage": "0%"
      },
      {
        "label": "7 visits",
        "nb_visits": "1",
        "nb_visits_percentage": "0%"
      },
      {
        "label": "8 visits",
        "nb_visits": "1",
        "nb_visits_percentage": "0%"
      },
      {
        "label": "9-14 visits",
        "nb_visits": "9",
        "nb_visits_percentage": "2%"
      },
      {
        "label": "15-25 visits",
        "nb_visits": "1",
        "nb_visits_percentage": "0%"
      },
      {
        "label": "26-50 visits",
        "nb_visits": "5",
        "nb_visits_percentage": "1%"
      },
      {
        "label": "51-100 visits",
        "nb_visits": "1",
        "nb_visits_percentage": "0%"
      },
      {
        "label": "101-200 visits",
        "nb_visits": "0",
        "nb_visits_percentage": "0%"
      },
      {
        "label": "201+ visits",
        "nb_visits": "0",
        "nb_visits_percentage": "0%"
      }
    ]