.. highlight:: js
.. default-domain:: js

Actions.get
```````````
TODO

.. function:: Actions.get(idSite, period, date, segment, columns)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param columns: TODO
    :returns: TODO

Report example::

    {
      "nb_pageviews": 390,
      "nb_uniq_pageviews": 342,
      "nb_downloads": 0,
      "nb_uniq_downloads": 0,
      "nb_outlinks": 17,
      "nb_uniq_outlinks": 16,
      "nb_searches": 13,
      "nb_keywords": 9,
      "avg_time_generation": 0.938
    }

Actions.getPageUrls
```````````````````
TODO

.. function:: Actions.getPageUrls(idSite, period, date, segment, expanded, idSubtable, depth, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :param depth: TODO
    :param flat: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "t",
        "nb_visits": 292,
        "nb_hits": 321,
        "sum_time_spent": 18435,
        "nb_hits_with_time_generation": 320,
        "min_time_generation": "0.005",
        "max_time_generation": "23.618",
        "entry_nb_visits": 237,
        "entry_nb_actions": 331,
        "entry_sum_visit_length": 17429,
        "entry_bounce_count": 185,
        "exit_nb_visits": 238,
        "nb_hits_following_search": 4,
        "avg_time_on_page": 57,
        "bounce_rate": "78%",
        "exit_rate": "82%",
        "avg_time_generation": 0.946,
        "idsubdatatable": 1
      },
    ]

Actions.getPageUrlsFollowingSiteSearch
``````````````````````````````````````
TODO

.. function:: Actions.getPageUrlsFollowingSiteSearch(idSite, period, date, segment, expanded, idSubtable)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "t",
        "nb_visits": 292,
        "nb_hits": 321,
        "sum_time_spent": 18435,
        "nb_hits_with_time_generation": 320,
        "min_time_generation": "0.005",
        "max_time_generation": "23.618",
        "entry_nb_visits": 237,
        "entry_nb_actions": 331,
        "entry_sum_visit_length": 17429,
        "entry_bounce_count": 185,
        "exit_nb_visits": 238,
        "nb_hits_following_search": 4,
        "avg_time_on_page": 57,
        "bounce_rate": "78%",
        "exit_rate": "82%",
        "avg_time_generation": 0.946,
        "idsubdatatable": 1
      },
    ]

Actions.getPageTitlesFollowingSiteSearch
````````````````````````````````````````
TODO

.. function:: Actions.getPageTitlesFollowingSiteSearch(idSite, period, date, segment, expanded, idSubtable)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :returns: TODO

Report example::

    [
      {
        "label": " PPMS main site",
        "nb_visits": 20,
        "nb_uniq_visitors": 20,
        "nb_hits": 34,
        "sum_time_spent": 3404,
        "nb_hits_following_search": "3",
        "nb_hits_with_time_generation": "34",
        "min_time_generation": "0.246",
        "max_time_generation": "4.537",
        "entry_nb_uniq_visitors": "12",
        "entry_nb_visits": "12",
        "entry_nb_actions": "44",
        "entry_sum_visit_length": "5801",
        "entry_bounce_count": "5",
        "exit_nb_uniq_visitors": "13",
        "exit_nb_visits": "13",
        "avg_time_on_page": 100,
        "bounce_rate": "42%",
        "exit_rate": "65%",
        "avg_time_generation": 0.996
      }
    ]

Actions.getEntryPageUrls
````````````````````````
TODO

.. function:: Actions.getEntryPageUrls(idSite, period, date, segment, expanded, idSubtable)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "t",
        "nb_visits": 292,
        "nb_hits": 321,
        "sum_time_spent": 18435,
        "nb_hits_with_time_generation": 320,
        "min_time_generation": "0.005",
        "max_time_generation": "23.618",
        "entry_nb_visits": 237,
        "entry_nb_actions": 331,
        "entry_sum_visit_length": 17429,
        "entry_bounce_count": 185,
        "exit_nb_visits": 238,
        "nb_hits_following_search": 4,
        "avg_time_on_page": 57,
        "bounce_rate": "78%",
        "exit_rate": "82%",
        "avg_time_generation": 0.946,
        "idsubdatatable": 1
      },
    ]

Actions.getExitPageUrls
```````````````````````
TODO

.. function:: Actions.getExitPageUrls(idSite, period, date, segment, expanded, idSubtable)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "t",
        "nb_visits": 292,
        "nb_hits": 321,
        "sum_time_spent": 18435,
        "nb_hits_with_time_generation": 320,
        "min_time_generation": "0.005",
        "max_time_generation": "23.618",
        "entry_nb_visits": 237,
        "entry_nb_actions": 331,
        "entry_sum_visit_length": 17429,
        "entry_bounce_count": 185,
        "exit_nb_visits": 238,
        "nb_hits_following_search": 4,
        "avg_time_on_page": 57,
        "bounce_rate": "78%",
        "exit_rate": "82%",
        "avg_time_generation": 0.946,
        "idsubdatatable": 1
      }
    ]

Actions.getPageUrl
``````````````````
TODO

.. function:: Actions.getPageUrl(pageUrl, idSite, period, date, segment)

    :param pageUrl: TODO
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "/index",
        "nb_visits": 18,
        "nb_uniq_visitors": 18,
        "nb_hits": 31,
        "sum_time_spent": 3104,
        "nb_hits_following_search": "2",
        "nb_hits_with_time_generation": "31",
        "min_time_generation": "0.269",
        "max_time_generation": "1.993",
        "entry_nb_uniq_visitors": "16",
        "entry_nb_visits": "16",
        "entry_nb_actions": "74",
        "entry_sum_visit_length": "7103",
        "entry_bounce_count": "5",
        "exit_nb_uniq_visitors": "9",
        "exit_nb_visits": "9",
        "avg_time_on_page": 100,
        "bounce_rate": "31%",
        "exit_rate": "50%",
        "avg_time_generation": 0.795,
        "url": "https://piwik.pro/"
      }
    ]

Actions.getPageTitles
`````````````````````
TODO

.. function:: Actions.getPageTitles(idSite, period, date, segment, expanded, idSubtable, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :param flat: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Page Name not defined",
        "nb_visits": 24,
        "nb_uniq_visitors": 23,
        "nb_hits": 29,
        "sum_time_spent": 0,
        "nb_hits_with_time_generation": "29",
        "min_time_generation": "0.005",
        "max_time_generation": "16.318",
        "avg_time_on_page": 0,
        "bounce_rate": "0%",
        "exit_rate": "0%",
        "avg_time_generation": 1.238
      },
    ]

Actions.getEntryPageTitles
``````````````````````````
TODO

.. function:: Actions.getEntryPageTitles(idSite, period, date, segment, expanded, idSubtable)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :returns: TODO

Report example::

    [
      {
        "label": " PPMS main site",
        "nb_visits": 21,
        "nb_uniq_visitors": 21,
        "nb_hits": 35,
        "sum_time_spent": 3404,
        "nb_hits_following_search": "3",
        "nb_hits_with_time_generation": "35",
        "min_time_generation": "0.016",
        "max_time_generation": "4.537",
        "entry_nb_uniq_visitors": "13",
        "entry_nb_visits": "13",
        "entry_nb_actions": "45",
        "entry_sum_visit_length": "5801",
        "entry_bounce_count": "6",
        "exit_nb_uniq_visitors": "14",
        "exit_nb_visits": "14",
        "avg_time_on_page": 97,
        "bounce_rate": "46%",
        "exit_rate": "67%",
        "avg_time_generation": 0.968
      }
    ]

Actions.getExitPageTitles
`````````````````````````
TODO

.. function:: Actions.getExitPageTitles(idSite, period, date, segment, expanded, idSubtable)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :returns: TODO

Report example::

    [
      {
        "label": " PPMS main site",
        "nb_visits": 21,
        "nb_uniq_visitors": 21,
        "nb_hits": 35,
        "sum_time_spent": 3404,
        "nb_hits_following_search": "3",
        "nb_hits_with_time_generation": "35",
        "min_time_generation": "0.016",
        "max_time_generation": "4.537",
        "entry_nb_uniq_visitors": "13",
        "entry_nb_visits": "13",
        "entry_nb_actions": "45",
        "entry_sum_visit_length": "5801",
        "entry_bounce_count": "6",
        "exit_nb_uniq_visitors": "14",
        "exit_nb_visits": "14",
        "avg_time_on_page": 97,
        "bounce_rate": "46%",
        "exit_rate": "67%",
        "avg_time_generation": 0.968
      }
    ]

Actions.getPageTitle
````````````````````
TODO

.. function:: Actions.getPageTitle(pageName, idSite, period, date, segment)

    :param pageName: TODO
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

Actions.getDownloads
````````````````````
TODO

.. function:: Actions.getDownloads(idSite, period, date, segment, expanded, idSubtable, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :param flat: TODO
    :returns: TODO

Report example::

     [
      {
        "label": "github.com",
        "nb_visits": 3,
        "nb_hits": 4,
        "sum_time_spent": 0,
        "idsubdatatable": 1
      },
      {
        "label": "archive.sh",
        "nb_visits": 1,
        "nb_hits": 1,
        "sum_time_spent": 0,
        "idsubdatatable": 2
      },
      {
        "label": "khromov.wordpress.com",
        "nb_visits": 1,
        "nb_hits": 1,
        "sum_time_spent": 0,
        "idsubdatatable": 5
      },
      {
        "label": "pen-ultima.blogspot.de",
        "nb_visits": 1,
        "nb_hits": 1,
        "sum_time_spent": 0,
        "nb_hits_following_search": 1,
        "idsubdatatable": 9
      },
      {
        "label": "www.optimizesmart.com",
        "nb_visits": 1,
        "nb_hits": 1,
        "sum_time_spent": 0,
        "idsubdatatable": 7
      },
      {
        "label": "www.ssllabs.com",
        "nb_visits": 1,
        "nb_hits": 1,
        "sum_time_spent": 0,
        "idsubdatatable": 10
      }
    ]

Actions.getDownload
```````````````````
TODO

.. function:: Actions.getDownload(downloadUrl, idSite, period, date, segment)

    :param downloadUrl: TODO
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO


Actions.getOutlinks
```````````````````
TODO

.. function:: Actions.getOutlinks(idSite, period, date, segment, expanded, idSubtable, flat)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param expanded: TODO
    :param idSubtable: TODO
    :param flat: TODO
    :returns: TODO

Report example::

    TODO

Actions.getOutlink
``````````````````
TODO

.. function:: Actions.getOutlink(outlinkUrl, idSite, period, date, segment)

    :param outlinkUrl: TODO
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

Actions.getSiteSearchKeywords
`````````````````````````````
TODO

.. function:: Actions.getSiteSearchKeywords(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Android",
        "nb_visits": 1,
        "nb_hits": 1,
        "sum_time_spent": 20,
        "nb_pages_per_search": 1,
        "avg_time_on_page": 20,
        "bounce_rate": "0%",
        "exit_rate": "0%"
      },
    ]

Actions.getSiteSearchNoResultKeywords
`````````````````````````````````````
TODO

.. function:: Actions.getSiteSearchNoResultKeywords(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "Android",
        "nb_visits": 1,
        "nb_hits": 1,
        "sum_time_spent": 20,
        "nb_pages_per_search": 1,
        "avg_time_on_page": 20,
        "bounce_rate": "0%",
        "exit_rate": "0%"
      },
    ]

Actions.getSiteSearchCategories
```````````````````````````````
TODO

.. function:: Actions.getSiteSearchCategories(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO
