.. highlight:: js
.. default-domain:: js

MultiSites.getAll
`````````````````

TODO

.. function:: MultiSites.getAll(period, date, segment, enhanced, pattern, showColumns)

    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param enhanced: TODO
    :param pattern: TODO
    :param showColumns: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Example site",
        "nb_visits": 165,
        "nb_actions": 240,
        "nb_pageviews": 225,
        "revenue": 0,
        "visits_evolution": "-80.9%",
        "actions_evolution": "-84.4%",
        "pageviews_evolution": "-84.4%",
        "revenue_evolution": "0%",
        "idsite": 7,
        "group": "",
        "main_url": "http://example.com/site"
      }
    ]

MultiSites.getOne
`````````````````

TODO

.. function:: MultiSites.getAll(idSite, period, date, segment, enhanced)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param enhanced: TODO
    :returns: TODO

Report example::

    {
      "nb_visits": 165,
      "nb_actions": 240,
      "visits_evolution": "-80.9%",
      "actions_evolution": "-84.4%",
      "pageviews_evolution": "-84.4%",
      "revenue_evolution": "0%",
      "nb_pageviews": 225,
      "revenue": 0
    }
