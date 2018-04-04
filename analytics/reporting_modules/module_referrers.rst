.. highlight:: js
.. default-domain:: js

Referrers.getReferrerType
`````````````````````````

TODO

.. function:: Referrers.getReferrerType(idSite, period, date, segment, typeReferrer, idSubtable, expanded)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param typeReferrer: TODO
    :param idSubtable: TODO
    :param expanded: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Search Engines",
        "nb_uniq_visitors": 187,
        "nb_visits": 192,
        "nb_actions": 237,
        "nb_users": 0,
        "max_actions": 5,
        "sum_visit_length": 3852,
        "bounce_count": 162,
        "nb_visits_converted": 0,
        "segment": "referrerType==search",
        "idsubdatatable": 2
      },
      {
        "label": "Direct Entry",
        "nb_uniq_visitors": 21,
        "nb_visits": 25,
        "nb_actions": 75,
        "nb_users": 0,
        "max_actions": 17,
        "sum_visit_length": 3356,
        "bounce_count": 11,
        "nb_visits_converted": 0,
        "segment": "referrerType==direct"
      }
    ]

Referrers.getAll
````````````````

TODO

.. function:: Referrers.getAll(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Keyword not defined",
        "nb_uniq_visitors": 186,
        "nb_visits": 191,
        "nb_actions": 236,
        "nb_users": 0,
        "max_actions": 5,
        "sum_visit_length": 3852,
        "bounce_count": 161,
        "nb_visits_converted": 0,
        "referer_type": 2
      }
    ]

Referrers.getKeywords
`````````````````````

TODO

.. function:: Referrers.getKeywords(idSite, period, date, segment, expanded, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param flat: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Keyword not defined",
        "nb_uniq_visitors": 186,
        "nb_visits": 191,
        "nb_actions": 236,
        "nb_users": 0,
        "max_actions": 5,
        "sum_visit_length": 3852,
        "bounce_count": 161,
        "nb_visits_converted": 0,
        "segment": "referrerType==search;referrerKeyword==",
        "idsubdatatable": 1
      },
    ]

Referrers.getKeywordsForPageUrl
```````````````````````````````

TODO

.. function:: Referrers.getKeywordsForPageUrl(idSite, period, date, url)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param url: TODO
    :returns: TODO

Report example::

    []

Referrers.getKeywordsForPageTitle
`````````````````````````````````

TODO

.. function:: Referrers.getKeywordsForPageTitle(idSite, period, date, url)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param url: TODO
    :returns: TODO

Report example::

    []

Referrers.getSearchEnginesFromKeywordId
```````````````````````````````````````

TODO

.. function:: Referrers.getSearchEnginesFromKeywordId(idSite, period, date, idSubtable, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param idSubtable: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

Referrers.getSearchEngines
``````````````````````````

TODO

.. function:: Referrers.getSearchEngines(idSite, period, date, segment, expanded, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param flat: TODO
    :returns: TODO

Report example::

        [
          {
            "label": "Google",
            "nb_uniq_visitors": 177,
            "nb_visits": 182,
            "nb_actions": 224,
            "nb_users": 0,
            "max_actions": 5,
            "sum_visit_length": 3820,
            "bounce_count": 155,
            "nb_visits_converted": 0,
            "segment": "referrerType==search;referrerName==Google",
            "url": "http://google.com",
            "logo": "plugins/Morpheus/icons/dist/searchEngines/google.com.png",
            "idsubdatatable": 2
          },
          {
            "label": "Baidu",
            "nb_uniq_visitors": 6,
            "nb_visits": 6,
            "nb_actions": 6,
            "nb_users": 0,
            "max_actions": 1,
            "sum_visit_length": 0,
            "bounce_count": 6,
            "nb_visits_converted": 0,
            "segment": "referrerType==search;referrerName==Baidu",
            "url": "http://www.baidu.com",
            "logo": "plugins/Morpheus/icons/dist/searchEngines/www.baidu.com.png",
            "idsubdatatable": 1
          }
        ]

Referrers.getKeywordsFromSearchEngineId
```````````````````````````````````````

TODO

.. function:: Referrers.getKeywordsFromSearchEngineId(idSite, period, date, idSubtable, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param idSubtable: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

Referrers.getCampaigns
``````````````````````

TODO

.. function:: Referrers.getCampaigns(idSite, period, date, segment, expanded)

    :param idSite: TODO
        :param period: TODO
        :param date: TODO
        :param segment: TODO
        :param expanded: TODO
        :returns: TODO

Report example::

    []

Referrers.getKeywordsFromCampaignId
```````````````````````````````````

TODO

.. function:: Referrers.getKeywordsFromSearchEngineId(idSite, period, date, idSubtable, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param idSubtable: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

Referrers.getWebsites
`````````````````````

TODO

.. function:: Referrers.getWebsites(idSite, period, date, segment, expanded, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param flat: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "example.com",
        "nb_uniq_visitors": 7,
        "nb_visits": 7,
        "nb_actions": 11,
        "nb_users": 0,
        "max_actions": 3,
        "sum_visit_length": 966,
        "bounce_count": 4,
        "nb_visits_converted": 0,
        "segment": "referrerName==example.com",
        "idsubdatatable": 5
      }
    ]

Referrers.getUrlsFromWebsiteId
``````````````````````````````

TODO

.. function:: Referrers.getUrlsFromWebsiteId(idSite, period, date, idSubtable, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param idSubtable: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

Referrers.getSocials
````````````````````

TODO

.. function:: Referrers.getSocials(idSite, period, date, segment, expanded, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param flat: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "GitHub",
        "nb_uniq_visitors": 1,
        "nb_visits": 1,
        "nb_actions": 1,
        "nb_users": 0,
        "max_actions": 1,
        "sum_visit_length": 0,
        "bounce_count": 1,
        "nb_visits_converted": 0,
        "url": "github.com",
        "logo": "plugins/Morpheus/icons/dist/socials/github.com.png",
        "idsubdatatable": 9
      }
    ]

Referrers.getUrlsForSocial
``````````````````````````

TODO

.. function:: Referrers.getUrlsForSocial(idSite, period, date, segment, idSubtable)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param idSubtable: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "github.com/example-com/example-project/issues/1",
        "nb_uniq_visitors": 1,
        "nb_visits": 1,
        "nb_actions": 1,
        "nb_users": 0,
        "max_actions": 1,
        "sum_visit_length": 0,
        "bounce_count": 1,
        "nb_visits_converted": 0,
        "segment": "referrerUrl==https%3A%2F%2Fgithub.com%2Fexample-com%2Fexample-project%2Fissues%2F1",
        "url": "https:/github.com/example-com/example-project/issues/1"
      }
    ]

Referrers.getNumberOfDistinctSearchEngines
``````````````````````````````````````````

TODO

.. function:: Referrers.getNumberOfDistinctSearchEngines(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":4}

Referrers.getNumberOfDistinctKeywords
`````````````````````````````````````

TODO

.. function:: Referrers.getNumberOfDistinctKeywords(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":4}

Referrers.getNumberOfDistinctCampaigns
``````````````````````````````````````

TODO

.. function:: Referrers.getNumberOfDistinctCampaigns(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":0}

Referrers.getNumberOfDistinctWebsites
`````````````````````````````````````

TODO

.. function:: Referrers.getNumberOfDistinctWebsites(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":8}

Referrers.getNumberOfDistinctWebsitesUrls
`````````````````````````````````````````

TODO

.. function:: Referrers.getNumberOfDistinctWebsitesUrls(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    {"value":16}