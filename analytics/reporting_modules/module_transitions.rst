.. highlight:: js
.. default-domain:: js

Transitions.getTransitionsForPageTitle
``````````````````````````````````````

TODO

.. function:: Transitions.getTransitionsForPageTitle(pageTitle, idSite, period, date, segment, limitBeforeGrouping)

    :param pageTitle: TODO
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param limitBeforeGrouping: TODO
    :returns: TODO

Report example::

    TODO

Transitions.getTransitionsForPageUrl
````````````````````````````````````

TODO

.. function:: Transitions.getTransitionsForPageUrl(pageTitle, idSite, period, date, segment, limitBeforeGrouping)

    :param pageTitle: TODO
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param limitBeforeGrouping: TODO
    :returns: TODO

Report example::

    {"result":"error","message":"NoDataForAction"}

Transitions.getTransitionsForAction
```````````````````````````````````

TODO

.. function:: Transitions.getTransitionsForAction(pageTitle, idSite, period, date, segment, limitBeforeGrouping, parts)

    :param pageTitle: TODO
    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param limitBeforeGrouping: TODO
    :param parts: TODO
    :returns: TODO

Report example::

    TODO

Transitions.getTranslations
```````````````````````````

TODO

.. function:: Transitions.getTranslations()

    :returns: TODO

Report example::

    [
      {
        "pageviewsInline": "%s pageviews",
        "loopsInline": "%s page reloads",
        "fromPreviousPages": "From Internal Pages",
        "fromPreviousPagesInline": "%s from internal pages",
        "fromPreviousSiteSearches": "From Internal Search",
        "fromPreviousSiteSearchesInline": "%s from internal searches",
        "fromSearchEngines": "From Search Engines",
        "fromSearchEnginesInline": "%s from search engines",
        "fromWebsites": "From Websites",
        "fromWebsitesInline": "%s from websites",
        "fromCampaigns": "From Campaigns",
        "fromCampaignsInline": "%s from campaigns",
        "directEntries": "Direct Entries",
        "directEntriesInline": "%s direct entries",
        "toFollowingPages": "To Internal Pages",
        "toFollowingPagesInline": "%s to internal pages",
        "toFollowingSiteSearches": "Internal Searches",
        "toFollowingSiteSearchesInline": "%s internal searches",
        "downloads": "Downloads",
        "downloadsInline": "%s downloads",
        "outlinks": "Outlinks",
        "outlinksInline": "%s outlinks",
        "exits": "Exits",
        "exitsInline": "%s exits",
        "bouncesInline": "%s bounces",
        "XOfY": "%1$s (out of %2$s)",
        "XOfAllPageviews": "%s of all views of this page",
        "NoDataForAction": "There's no data for %s",
        "NoDataForActionDetails": "Either the action had no pageviews during the period %s or it is invalid.",
        "NoDataForActionBack": "Go back to the previous action",
        "ShareOfAllPageviews": "This page had %1$s pageviews (%2$s of all pageviews)",
        "DateRange": "Date range:"
      }
    ]