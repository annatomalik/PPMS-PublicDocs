.. highlight:: js
.. default-domain:: js

Insights.canGenerateInsights
````````````````````````````
TODO

.. function:: Insights.canGenerateInsights(date, period)

    :param date: TODO
    :param period: TODO
    :returns: TODO

Report example::

    {"value":true}

Insights.getInsightsOverview
````````````````````````````
TODO

.. function:: Insights.getInsightsOverview(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {
      "Page URLs": [
        {
          "label": "t",
          "nb_visits": 545,
          "growth_percent": "-23.5%",
          "growth_percent_numeric": "-23.5",
          "grown": false,
          "value_old": 712,
          "value_new": 545,
          "difference": -167,
          "importance": 167,
          "isDisappeared": false,
          "isNew": false,
          "isMover": true,
          "isMoverAndShaker": false
        }
      ],
      "Page titles": [
        {
          "label": "Page Name not defined",
          "nb_visits": 43,
          "growth_percent": "-40.3%",
          "growth_percent_numeric": "-40.3",
          "grown": false,
          "value_old": 72,
          "value_new": 43,
          "difference": -29,
          "importance": 29,
          "isDisappeared": false,
          "isNew": false,
          "isMover": true,
          "isMoverAndShaker": false
        }
      ],
      "Downloads": [
        {
          "label": "example.com/file.png",
          "nb_visits": 1,
          "growth_percent": "100%",
          "growth_percent_numeric": "100",
          "grown": true,
          "value_old": 0,
          "value_new": 1,
          "difference": 1,
          "importance": 1,
          "isDisappeared": false,
          "isNew": true,
          "isMover": false,
          "isMoverAndShaker": false
        }
      ],
      "Websites": [
        {
          "label": "ahrefs.com",
          "nb_visits": 1,
          "growth_percent": "100%",
          "growth_percent_numeric": "100",
          "grown": true,
          "value_old": 0,
          "value_new": 1,
          "difference": 1,
          "importance": 1,
          "isDisappeared": false,
          "isNew": true,
          "isMover": false,
          "isMoverAndShaker": false
        }
      ],
      "Campaigns": [],
      "Social Networks": [],
      "Search Engines": [
        {
          "label": "Google",
          "nb_visits": 366,
          "growth_percent": "-25.3%",
          "growth_percent_numeric": "-25.3",
          "grown": false,
          "value_old": 490,
          "value_new": 366,
          "difference": -124,
          "importance": 124,
          "isDisappeared": false,
          "isNew": false,
          "isMover": true,
          "isMoverAndShaker": false
        }
      ],
      "Country": [
        {
          "label": "Germany",
          "nb_visits": 56,
          "growth_percent": "43.6%",
          "growth_percent_numeric": "43.6",
          "grown": true,
          "value_old": 39,
          "value_new": 56,
          "difference": 17,
          "importance": 17,
          "isDisappeared": false,
          "isNew": false,
          "isMover": true,
          "isMoverAndShaker": false
        }
      ]
    }

Insights.getMoversAndShakersOverview
````````````````````````````````````
TODO

.. function:: Insights.getMoversAndShakersOverview(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {
      "Page URLs": [
        {
          "label": "u",
          "nb_visits": 5,
          "growth_percent": "-72.2%",
          "growth_percent_numeric": "-72.2",
          "grown": false,
          "value_old": 18,
          "value_new": 5,
          "difference": -13,
          "importance": 13,
          "isDisappeared": false,
          "isNew": false,
          "isMover": true
        }
      ],
      "Page titles": [
        {
          "label": " test site",
          "nb_visits": 7,
          "growth_percent": "-69.6%",
          "growth_percent_numeric": "-69.6",
          "grown": false,
          "value_old": 23,
          "value_new": 7,
          "difference": -16,
          "importance": 16,
          "isDisappeared": false,
          "isNew": false,
          "isMover": true
        }
      ],
      "Downloads": [],
      "Websites": [],
      "Campaigns": [],
      "Social Networks": [],
      "Search Engines": [],
      "Country": [
        {
          "label": "Italy",
          "nb_visits": 9,
          "growth_percent": "200%",
          "growth_percent_numeric": "200",
          "grown": true,
          "value_old": 3,
          "value_new": 9,
          "difference": 6,
          "importance": 6,
          "isDisappeared": false,
          "isNew": false,
          "isMover": true
        }
      ]
    }

Insights.getMoversAndShakers
````````````````````````````
TODO

.. function:: Insights.getMoversAndShakers(idSite, period, date, reportUniqueId, segment, comparedToXPeriods, limitIncreaser, limitDecreaser)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param reportUniqueId: TODO
    :param segment: TODO
    :param comparedToXPeriods: TODO
    :param limitIncreaser: TODO
    :param limitDecreaser: TODO
    :returns: TODO

Report example::

    TODO

Insights.getInsights
````````````````````
TODO

.. function:: Insights.getInsights(idSite, period, date, reportUniqueId, segment, limitIncreaser, limitDecreaser, filterBy, minImpactPercent, minGrowthPercent , comparedToXPeriods, orderBy)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param reportUniqueId: TODO
    :param segment: TODO
    :param limitIncreaser: TODO
    :param limitDecreaser: TODO
    :param filterBy: TODO
    :param minImpactPercent: TODO
    :param minGrowthPercent: TODO
    :param comparedToXPeriods: TODO
    :param orderBy: TODO
    :returns: TODO

Report example::

    TODO

