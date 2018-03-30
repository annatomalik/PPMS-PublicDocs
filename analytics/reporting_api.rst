Reporting API
=============
This API gives access to your analytics reports.

.. warning::
    Requests using insecure protocol (**HTTP**) send over untrusted networks can be used by eavesdropper to steal
    your authentication token (``token_auth``). It's recommended to always use secure protocol (**HTTPS**).

.. todo::
    Make sure that HTTPS is always available and check if this API requires it. If that can be guaranteed - this warning
    can be removed.

.. openapi:: ../_static/api/analytics_reporting_api.json

.. raw:: html

    <redoc spec-url="../_static/api/analytics_reporting_api.json" expand-responses="" sticky-sidebar="">
    </redoc>

Module API
----------
TODO

API.getMatomoVersion
````````````````````
TODO

.. function:: API.getMatomoVersion()
    :returns: TODO

Report example::
    {"value":"3.4.0-rc2"}

API.getIpFromHeader
```````````````````
TODO

.. function:: API.getIpFromHeader()
    :returns: TODO

Report example::
    {"value":"172.31.255.255"}

API.getSegmentsMetadata
```````````````````````
TODO

.. function:: API.getSegmentsMetadata(idSites)
    :param idSites: TODO
    :returns: TODO

Report example::

   {"result":"error","message":"You can't access this resource as it requires 'view' access for the website id = 1."}

API.getMetadata
```````````````
TODO

.. function:: API.getMetadata(idSite, apiModule, apiAction, apiParameters, language, period, date, hideMetricsDocs, showSubtableReports)
    :param idSite: TODO
    :param apiModule: TODO
    :param apiAction: TODO
    :param apiParameters: TODO
    :param language: TODO
    :param period: TODO
    :param date: TODO
    :param hideMetricsDocs: TODO
    :param showSubtableReports: TODO
    :returns: TODO

Report example::

    [
      {
        "category": "Visitors",
        "subcategory": "Locations",
        "name": "Country",
        "module": "UserCountry",
        "action": "getCountry",
        "dimension": "Country",
        "documentation": "This report shows which country your visitors were in when they accessed your website.",
        "metrics": {
          "nb_visits": "Visits",
          "nb_uniq_visitors": "Unique visitors",
          "nb_actions": "Actions"
        },
        "metricsDocumentation": {
          "nb_visits": "If a visitor comes to your website for the first time or if they visit a page more than 30 minutes after their last page view, this will be recorded as a new visit.",
          "nb_uniq_visitors": "The number of unduplicated visitors coming to your website. Every user is only counted once, even if they visit the website multiple times a day.",
          "nb_actions": "The number of actions performed by your visitors. Actions can be page views, internal site searches, downloads or outlinks.",
          "nb_actions_per_visit": "The average number of actions (page views, site searches, downloads or outlinks) that were performed during the visits.",
          "avg_time_on_site": "The average duration of a visit.",
          "bounce_rate": "The percentage of visits that only had a single pageview. This means, that the visitor left the website directly from the entrance page.",
          "conversion_rate": "The percentage of visits that triggered a goal conversion."
        },
        "processedMetrics": {
          "nb_actions_per_visit": "Actions per Visit",
          "avg_time_on_site": "Avg. Time on Website",
          "bounce_rate": "Bounce Rate"
        },
        "metricsGoal": {
          "nb_conversions": "Conversions",
          "revenue": "Revenue"
        },
        "processedMetricsGoal": {
          "revenue_per_visit": "Revenue per Visit"
        },
        "imageGraphUrl": "index.php?module=API&method=ImageGraph.get&idSite=7&apiModule=UserCountry&apiAction=getCountry&token_auth=anonymous&period=day&date=today",
        "imageGraphEvolutionUrl": "index.php?module=API&method=ImageGraph.get&idSite=7&apiModule=UserCountry&apiAction=getCountry&token_auth=anonymous&period=day&date=2018-03-01,2018-03-30",
        "uniqueId": "UserCountry_getCountry"
      }
    ]

API.getReportMetadata
`````````````````````
TODO

.. function:: API.getReportMetadata(idSites, period, date, hideMetricsDoc, showSubtableReports, idSite)
    :param idSites: TODO
    :param period: TODO
    :param date: TODO
    :param hideMetricsDoc: TODO
    :param showSubtableReports: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    [
      {
        "category": "All Websites",
        "name": "All Websites dashboard",
        "module": "MultiSites",
        "action": "getAll",
        "dimension": "Website",
        "metrics": {
          "nb_visits": "Visits",
          "nb_actions": "Actions",
          "nb_pageviews": "Pageviews",
          "revenue": "Revenue",
          "nb_conversions": "Conversions",
          "orders": "Ecommerce Orders",
          "ecommerce_revenue": "Product Revenue"
        },
        "metricsDocumentation": {
          "nb_visits": "If a visitor comes to your website for the first time or if they visit a page more than 30 minutes after their last page view, this will be recorded as a new visit.",
          "nb_actions": "The number of actions performed by your visitors. Actions can be page views, internal site searches, downloads or outlinks.",
          "nb_pageviews": "The number of times this page was visited."
        },
        "processedMetrics": {
          "visits_evolution": "Visits Evolution",
          "actions_evolution": "Actions Evolution",
          "pageviews_evolution": "Pageviews Evolution",
          "revenue_evolution": "Revenue Evolution",
          "nb_conversions_evolution": "Conversions Evolution",
          "orders_evolution": "Ecommerce Orders Evolution",
          "ecommerce_revenue_evolution": "Product Revenue Evolution"
        },
        "imageGraphUrl": "index.php?module=API&method=ImageGraph.get&idSite=7&apiModule=MultiSites&apiAction=getAll&token_auth=anonymous&period=day&date=today",
        "imageGraphEvolutionUrl": "index.php?module=API&method=ImageGraph.get&idSite=7&apiModule=MultiSites&apiAction=getAll&token_auth=anonymous&period=day&date=2018-03-01,2018-03-30",
        "uniqueId": "MultiSites_getAll"
      },
    ]

API.getProcessedReport
``````````````````````
TODO

.. function:: API.getProcessedReport(idSite, period, date, apiModule, apiAction, segment, apiParameters, idGoal, language, showTimer, hideMetricsDoc, idSubtable, showRawMetrics, format_metrics, idDimension)
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param apiModule: TODO
    :param segment: TODO
    :param apiParametrs: TODO
    :param idGoal: TODO
    :param language: TODO
    :param showTimer: TODO
    :param hideMetricsDoc: TODO
    :param idSubtable: TODO
    :param showRawMetrics: TODO
    :param format_metrics: TODO
    :param idDimension: TODO
    :returns: TODO

Report example::

    {
      "website": "Example Website",
      "prettyDate": "Friday, March 30, 2018",
      "metadata": {
        "category": "Visitors",
        "subcategory": "Locations",
        "name": "Country",
        "module": "UserCountry",
        "action": "getCountry",
        "dimension": "Country",
        "documentation": "This report shows which country your visitors were in when they accessed your website.",
        "metrics": {
          "nb_visits": "Visits",
          "nb_uniq_visitors": "Unique visitors",
          "nb_actions": "Actions"
        },
        "metricsDocumentation": {
          "nb_visits": "If a visitor comes to your website for the first time or if they visit a page more than 30 minutes after their last page view, this will be recorded as a new visit.",
          "nb_uniq_visitors": "The number of unduplicated visitors coming to your website. Every user is only counted once, even if they visit the website multiple times a day.",
          "nb_actions": "The number of actions performed by your visitors. Actions can be page views, internal site searches, downloads or outlinks.",
          "nb_actions_per_visit": "The average number of actions (page views, site searches, downloads or outlinks) that were performed during the visits.",
          "avg_time_on_site": "The average duration of a visit.",
          "bounce_rate": "The percentage of visits that only had a single pageview. This means, that the visitor left the website directly from the entrance page.",
          "conversion_rate": "The percentage of visits that triggered a goal conversion."
        },
        "processedMetrics": {
          "nb_actions_per_visit": "Actions per Visit",
          "avg_time_on_site": "Avg. Time on Website",
          "bounce_rate": "Bounce Rate"
        },
        "metricsGoal": {
          "nb_conversions": "Conversions",
          "revenue": "Revenue"
        },
        "processedMetricsGoal": {
          "revenue_per_visit": "Revenue per Visit"
        },
        "imageGraphUrl": "index.php?module=API&method=ImageGraph.get&idSite=7&apiModule=UserCountry&apiAction=getCountry&token_auth=anonymous&period=day&date=today",
        "imageGraphEvolutionUrl": "index.php?module=API&method=ImageGraph.get&idSite=7&apiModule=UserCountry&apiAction=getCountry&token_auth=anonymous&period=day&date=2018-03-01,2018-03-30",
        "uniqueId": "UserCountry_getCountry"
      },
      "columns": {
        "label": "Country",
        "nb_visits": "Visits",
        "nb_uniq_visitors": "Unique visitors",
        "nb_actions": "Actions",
        "nb_actions_per_visit": "Actions per Visit",
        "avg_time_on_site": "Avg. Time on Website",
        "bounce_rate": "Bounce Rate",
        "revenue": "Revenue"
      },
      "reportData": [
        {
          "label": "United States",
          "nb_uniq_visitors": 28,
          "nb_visits": 31,
          "nb_actions": 34,
          "nb_actions_per_visit": 1.1,
          "avg_time_on_site": "00:00:21",
          "bounce_rate": "90%",
          "revenue": "$ 0"
        },
        {
          "label": "China",
          "nb_uniq_visitors": 27,
          "nb_visits": 28,
          "nb_actions": 43,
          "nb_actions_per_visit": 1.5,
          "avg_time_on_site": "00:01:47",
          "bounce_rate": "68%",
          "revenue": "$ 0"
        },  ],
      "reportMetadata": [
        {
          "code": "us",
          "logo": "plugins/Morpheus/icons/dist/flags/us.png",
          "segment": "countryCode==us",
          "logoHeight": 16
        },
        {
          "code": "cn",
          "logo": "plugins/Morpheus/icons/dist/flags/cn.png",
          "segment": "countryCode==cn",
          "logoHeight": 16
        }
      ],
      "reportTotal": {
        "nb_visits": 221,
        "nb_uniq_visitors": 207,
        "nb_actions": 361,
        "nb_visits_converted": 0,
        "bounce_count": 166
      },
      "timerMillis": "36"
    }

API.getReportPagesMetadata
``````````````````````````
TODO

.. function:: API.getReportPagesMetadata(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    [
      {
        "uniqueId": "General_Actions.customdimension1",
        "category": {
          "id": "General_Actions",
          "name": "Actions",
          "order": 10,
          "icon": "icon-reporting-actions"
        },
        "subcategory": {
          "id": "customdimension1",
          "name": "Topic permalink",
          "order": 70
        },
        "widgets": [
          {
            "name": "Topic permalink",
            "module": "CustomDimensions",
            "action": "getCustomDimension",
            "order": 200,
            "parameters": {
              "module": "CustomDimensions",
              "action": "getCustomDimension",
              "idDimension": "1"
            },
            "uniqueId": "widgetCustomDimensionsgetCustomDimensionidDimension1",
            "isWide": false,
            "viewDataTable": "table",
            "isReport": true
          }
        ]
      },
    ]

API.getWidgetMetadata
`````````````````````
TODO

.. function:: API.getWidgetMetadata(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    [
      {
        "name": "Visitors in Real-time",
        "category": {
          "id": "Live!",
          "name": "Live!",
          "order": 2,
          "icon": ""
        },
        "subcategory": null,
        "module": "Live",
        "action": "widget",
        "order": 20,
        "parameters": {
          "module": "Live",
          "action": "widget"
        },
        "uniqueId": "widgetLivewidget",
        "isWide": false
      },
    ]

API.get
```````
TODO

.. function:: API.get(idSite, period, date, segment, columns)
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param columns: TODO
    :returns: TODO

Report example::

    {
      "nb_uniq_visitors": 207,
      "nb_visits": 221,
      "nb_users": 0,
      "nb_actions": 361,
      "max_actions": 16,
      "bounce_count": 166,
      "sum_visit_length": 21281,
      "nb_visits_returning": 50,
      "nb_actions_returning": 96,
      "nb_uniq_visitors_returning": 42,
      "nb_users_returning": 0,
      "max_actions_returning": 8,
      "bounce_rate_returning": "64%",
      "nb_actions_per_visit_returning": 1.9,
      "avg_time_on_site_returning": 140,
      "nb_conversions": 0,
      "nb_visits_converted": 0,
      "revenue": 0,
      "conversion_rate": "0%",
      "nb_conversions_new_visit": 0,
      "nb_visits_converted_new_visit": 0,
      "revenue_new_visit": 0,
      "conversion_rate_new_visit": "0%",
      "nb_conversions_returning_visit": 0,
      "nb_visits_converted_returning_visit": 0,
      "revenue_returning_visit": 0,
      "conversion_rate_returning_visit": "0%",
      "nb_pageviews": 339,
      "nb_uniq_pageviews": 294,
      "nb_downloads": 0,
      "nb_uniq_downloads": 0,
      "nb_outlinks": 10,
      "nb_uniq_outlinks": 10,
      "nb_searches": 12,
      "nb_keywords": 8,
      "nb_hits_with_time_generation": 338,
      "avg_time_generation": 0.933,
      "bounce_rate": "75%",
      "nb_actions_per_visit": 1.6,
      "avg_time_on_site": 96
    }

API.getRowEvolution
```````````````````
TODO

.. function:: API.getRowEvolution(idSite, period, date, apiModule, apiAction, label, segment, column, language, idGoal, legendAppendMetric, labelUseAbsoluteUrl, idDimension)
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param apiModule: TODO
    :param apiAction: TODO
    :param label: TODO
    :param segment: TODO
    :param column: TODO
    :param language: TODO
    :param idGoal: TODO
    :param legendAppendMetric: TODO
    :param labelUseAbsoluteUrl: TODO
    :param idDimesion: TODO
    :returns: TODO

Report example::

    {
      "result": "error",
      "message": "Row evolutions can not be processed with this combination of \\'date\\' and \\'period\\' parameters."
    }

API.getBulkRequest
``````````````````
TODO

.. function:: API.getBulkRequest(urls)
    :param urls: TODO
    :returns: TODO

Report example::

        TODO

API.isPluginActivated
`````````````````````
TODO

.. function:: API.isPluginActivated(pluginName)
    :param pluginName: TODO
    :returns: TODO

Report example::

    TODO


API.getSuggestedValuesForSegment
````````````````````````````````

.. function:: API.getSuggestedValuesForSegment(segmentName, idSite)
    :param segmentName: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    [
        "sample text",
        "sample text2"
    ]

API.getGlossaryReports
``````````````````````
TODO

.. function:: API.getGlossaryReports(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    [
      {
        "name": "All Referrers (Referrers)",
        "documentation": "This report shows all your Referrers in one unified report, listing all Websites, Search keywords and Campaigns used by your visitors to find your website."
      },
      {
        "name": "Browser Plugins (Visitors)",
        "documentation": "This report shows which browser plugins your visitors had enabled. This information might be important for choosing the right way to deliver your content."
      },
      ...
    ]

API.getGlossaryMetrics
``````````````````````
TODO

.. function:: API.getGlossaryMetrics(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    [
      {
        "name": "% Search Exits (Actions)",
        "id": "exit_rate",
        "documentation": "The percentage of visits that left the website after searching for this Keyword on your Site Search engine."
      },
      {
        "name": "Actions",
        "id": "nb_hits",
        "documentation": "The number of times this page was visited."
      },
    ]


Module AbTesting
----------------
TODO

AbTesting.getMetricsOverview
````````````````````````````
TODO

.. function:: AbTesting.getMetricsOverview(idSite, period, date, idExperiment, segment)
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param idExperment: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getMetricDetails
``````````````````````````
TODO

.. function:: AbTesting.getMetricDetails(idSite, period, date, idExperiment, successMetric, segment)
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param idExperiment: TODO
    :param successMetric: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.addExperiment
```````````````````````
TODO

.. function:: AbTesting.addExperiment(idSite, name, hypothesis, description, variations, includedTargets, successMetrics)
    :param idSite: TODO
    :param name: TODO
    :param hypothesis: TODO
    :param description: TODO
    :param variations: TODO
    :param includedTargets: TODO
    :param successMetrics: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.updateExperiment
``````````````````````````
TODO

.. function:: AbTesting.updateExperiment(idExperiment, idSite, name, description, hypothesis, variations, confidenceThreshold, mdeRelative, percentageParticipants, successMetrics, includedTargets, excludedTargets, startDate, endDate)
    :param idExperiment: TODO
    :param idSite: TODO
    :param name: TODO
    :param description: TODO
    :param hypothesis: TODO
    :param variations: TODO
    :param confidenceThreshold: TODO
    :param mdeRelative: TODO
    :param percentageParticipants: TODO
    :param successMetrics: TODO
    :param includedTargets: TODO
    :param excludedTargets: TODO
    :param startDate: TODO
    :param endDate: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.startExperiment
`````````````````````````
TODO

.. function:: AbTesting.startExperiment(idExperiment, idSite)
    :param idExperiment: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.finishExperiment
``````````````````````````
TODO

.. function:: AbTesting.finishExperiment(idExperiment, idSite)
    :param idExperiment: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.archiveExperiment
```````````````````````````
TODO

.. function:: AbTesting.archiveExperiment(idExperiment, idSite)
    :param idExperiment: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getJsIncludeTemplate
``````````````````````````````
TODO

.. function:: AbTesting.getJsIncludeTemplate()
    :returns: TODO

Report example::

    TODO

AbTesting.getJsExperimentTemplate
`````````````````````````````````
TODO

.. function:: AbTesting.getJsExperimentTemplate(idExperiment, idSite)
    :param idExperiment: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getAllExperiments
```````````````````````````
TODO

.. function:: AbTesting.getAllExperiments(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getActiveExperiments
``````````````````````````````
TODO

.. function:: AbTesting.getActiveExperiments(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getExperimentsByStatuses
``````````````````````````````````
TODO

.. function:: AbTesting.getExperimentsByStatuses(idSite, statuses)
    :param idSite: TODO
    :param statuses: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getExperiment
```````````````````````
TODO

.. function:: AbTesting.getExperiment(idExperiment, idSite)
    :param idExperiment: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.deleteExperiment
``````````````````````````
TODO

.. function:: AbTesting.deleteExperiment(idExperiment, idSite)
    :param idExperiment: TODO
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getAvailableStatuses
``````````````````````````````
TODO

.. function::  AbTesting.getAvailableStatuses(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getSuccessMetrics
```````````````````````````
TODO

.. function::  AbTesting.getSuccessMetrics(idSite)
    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

AbTesting.getAvailableTargetAttributes
``````````````````````````````````````
TODO

.. function:: AbTesting.getAvailableTargetAttributes()
    :returns: TODO

Report example::

    TODO

Module Actions
--------------
TODO

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