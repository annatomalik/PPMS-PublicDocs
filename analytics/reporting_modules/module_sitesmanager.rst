.. highlight:: js
.. default-domain:: js

SitesManager.getJavascriptTag
`````````````````````````````

TODO

.. function:: SitesManager.getJavascriptTag(idSite, piwikUrl, mergeSubdomains, groupPageTitlesByDomain, mergeAliasUrls, visitorCustomVariables, pageCustomVariables, customCampaignNameQueryParam, customCampaignKeywordParam, doNotTrack, disableCookies, trackNoScript, crossDomain)

    :param idSite: TODO
    :param piwikUrl: TODO
    :param mergeSubdomains: TODO
    :param groupPageTitlesByDomain: TODO
    :param mergeAliasUrls: TODO
    :param visitorCustomVariables: TODO
    :param pageCustomVariables: TODO
    :param customCampaignNameQueryParam: TODO
    :param customCampaignKeywordParam: TODO
    :param doNotTrack: TODO
    :param disableCookies: TODO
    :param trackNoScript: TODO
    :param crossDomain: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getImageTrackingCode
`````````````````````````````````

TODO

.. function:: SitesManager.getImageTrackingCode(idSite, piwikUrl, actionName, idGoal, revenue)

    :param idSite: TODO
    :param piwikUrl: TODO
    :param actionName: TODO
    :param idGoal: TODO
    :param revenue: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getSitesFromGroup
``````````````````````````````

TODO

.. function:: SitesManager.getSitesFromGroup(group)

    :param group: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getSitesGroups
```````````````````````````

TODO

.. function:: SitesManager.getSitesGroups()

    :param group: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getSiteFromId
``````````````````````````

TODO

.. function:: SitesManager.getSiteFromId(idSite)

    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getSiteUrlsFromId
``````````````````````````````

TODO

.. function:: SitesManager.getSiteUrlsFromId(idSite)

    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getAllSites
````````````````````````

TODO

.. function:: SitesManager.getAllSites()

    :returns: TODO

Report example::

    TODO

SitesManager.getAllSitesId
``````````````````````````

TODO

.. function:: SitesManager.getAllSitesId()

    :returns: TODO

Report example::

    TODO

SitesManager.getSitesWithAdminAccess
````````````````````````````````````

TODO

.. function:: SitesManager.getSitesWithAdminAccess(fetchAliasUrls, pattern, limit)

    :param fetchAliasUrls: TODO
    :param pattern: TODO
    :param limit: TODO
    :returns: TODO

Report example::

    []

SitesManager.getSitesWithViewAccess
```````````````````````````````````

TODO

.. function:: SitesManager.getSitesWithViewAccess()

    :returns: TODO

Report example::

    [
      {
        "idsite": "3",
        "name": "virtual-drums.com",
        "main_url": "http://www.virtual-drums.com",
        "ts_created": "2008-01-27 01:41:53",
        "timezone": "America/New_York",
        "currency": "USD",
        "exclude_unknown_urls": "1",
        "excluded_ips": "",
        "excluded_parameters": "",
        "excluded_user_agents": "",
        "sitesearch": "1",
        "sitesearch_keyword_parameters": "",
        "sitesearch_category_parameters": "",
        "group": "",
        "type": "website",
        "keep_url_fragment": "0",
        "ecommerce": "0"
      },
    ]

SitesManager.getSitesWithAtLeastViewAccess
``````````````````````````````````````````

TODO

.. function:: SitesManager.getSitesWithAtLeastViewAccess(limit)

    :param limit: TODO
    :returns: TODO

Report example::

        [
          {
            "idsite": "3",
            "name": "virtual-drums.com",
            "main_url": "http://www.virtual-drums.com",
            "ts_created": "2008-01-27 01:41:53",
            "timezone": "America/New_York",
            "currency": "USD",
            "exclude_unknown_urls": "1",
            "excluded_ips": "",
            "excluded_parameters": "",
            "excluded_user_agents": "",
            "sitesearch": "1",
            "sitesearch_keyword_parameters": "",
            "sitesearch_category_parameters": "",
            "group": "",
            "type": "website",
            "keep_url_fragment": "0",
            "ecommerce": "0"
          }
        ]

SitesManager.getSitesIdWithAdminAccess
``````````````````````````````````````

TODO

.. function:: SitesManager.getSitesIdWithAdminAccess()

    :returns: TODO

Report example::

    []

SitesManager.getSitesIdWithViewAccess
`````````````````````````````````````

TODO

.. function:: SitesManager.getSitesIdWithViewAccess()

    :returns: TODO

Report example::

    ["3","7","33","44"]

SitesManager.getSitesIdWithAtLeastViewAccess
````````````````````````````````````````````

TODO

.. function:: SitesManager.getSitesIdWithAtLeastViewAccess()

    :returns: TODO

Report example::

    ["3","7","33","44"]

SitesManager.getSitesIdFromSiteUrl
``````````````````````````````````

TODO

.. function:: SitesManager.getSitesIdFromSiteUrl(url)

    :param url: TODO
    :returns: TODO

Report example::

    []

SitesManager.addSite
````````````````````

TODO

.. function:: SitesManager.addSite(siteName, urls, ecommerce, siteSearch, searchKeywordParameters, searchCategoryParameters, excludedIps, excludedQueryParameters, timezone, currency, group, startDate, excludedUserAgents, keepURLFragments, type, settingValues, excludeUnknownUrls)

    :param siteName: TODO
    :param urls: TODO
    :param ecommerce: TODO
    :param siteSearch: TODO
    :param searchKeywordParameters: TODO
    :param searchCategoryParameters: TODO
    :param excludedIps: TODO
    :param excludedQueryParameters: TODO
    :param timezone: TODO
    :param currency: TODO
    :param group: TODO
    :param startDate: TODO
    :param excludedUserAgents: TODO
    :param keepURLFragments: TODO
    :param type: TODO
    :param settingValues: TODO
    :param excludeUnknownUrls: TODO
    :returns: TODO

Report example::

    []

SitesManager.getSiteSettings
````````````````````````````

TODO

.. function:: SitesManager.getSiteSettings(idSite)

    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.deleteSite
```````````````````````

TODO

.. function:: SitesManager.deleteSite(idSite)

    :param idSite: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.addSiteAliasUrls
`````````````````````````````

TODO

.. function:: SitesManager.addSiteAliasUrls(idSite, url)

    :param idSite: TODO
    :param url: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.addSiteAliasUrls
`````````````````````````````

TODO

.. function:: SitesManager.addSiteAliasUrls(idSite, url)

    :param idSite: TODO
    :param url: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getIpsForRange
```````````````````````````

TODO

.. function:: SitesManager.getIpsForRange(ipRange)

    :param ipRange: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.setGlobalExcludedIps
`````````````````````````````````

TODO

.. function:: SitesManager.setGlobalExcludedIps(excludedIps)

    :param excludedIps: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.setGlobalSearchParameters
``````````````````````````````````````

TODO

.. function:: SitesManager.setGlobalSearchParameters(searchKeywordParameters, searchCategoryParameters)

    :param searchKeywordParameters: TODO
    :param searchCategoryParameters: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getSearchKeywordParametersGlobal
`````````````````````````````````````````````

TODO

.. function:: SitesManager.getSearchKeywordParametersGlobal()

    :returns: TODO

Report example::

    TODO

SitesManager.getSearchCategoryParametersGlobal
``````````````````````````````````````````````

TODO

.. function:: SitesManager.getSearchCategoryParametersGlobal()

    :returns: TODO

Report example::

    TODO

SitesManager.getExcludedQueryParametersGlobal
`````````````````````````````````````````````

TODO

.. function:: SitesManager.getExcludedQueryParametersGlobal()

    :returns: TODO

Report example::

    TODO

SitesManager.getExcludedUserAgentsGlobal
````````````````````````````````````````

TODO

.. function:: SitesManager.getExcludedUserAgentsGlobal()

    :returns: TODO

Report example::

    TODO

SitesManager.setGlobalExcludedUserAgents
````````````````````````````````````````

TODO

.. function:: SitesManager.setGlobalExcludedUserAgents(excludedUserAgents)

    :param excludedUserAgents: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.isSiteSpecificUserAgentExcludeEnabled
``````````````````````````````````````````````````

TODO

.. function:: SitesManager.isSiteSpecificUserAgentExcludeEnabled()

    :returns: TODO

Report example::

    TODO

SitesManager.setSiteSpecificUserAgentExcludeEnabled
```````````````````````````````````````````````````

TODO

.. function:: SitesManager.setSiteSpecificUserAgentExcludeEnabled(enabled)

    :param enabled: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getKeepURLFragmentsGlobal
``````````````````````````````````````

TODO

.. function:: SitesManager.getKeepURLFragmentsGlobal()

    :returns: TODO

Report example::

    TODO

SitesManager.setKeepURLFragmentsGlobal
``````````````````````````````````````

TODO

.. function:: SitesManager.setKeepURLFragmentsGlobal(enabled)

    :param enabled: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.setGlobalExcludedQueryParameters
`````````````````````````````````````````````

TODO

.. function:: SitesManager.setGlobalExcludedQueryParameters(excludedQueryParameters)

    :param excludedQueryParameters: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getExcludedIpsGlobal
`````````````````````````````````

TODO

.. function:: SitesManager.getExcludedIpsGlobal()

    :returns: TODO

Report example::

    TODO

SitesManager.getDefaultCurrency
```````````````````````````````

TODO

.. function:: SitesManager.getDefaultCurrency()

    :returns: TODO

Report example::

    TODO

SitesManager.setDefaultCurrency
```````````````````````````````

TODO

.. function:: SitesManager.setDefaultCurrency(currency)

    :param currency: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getDefaultTimezone
```````````````````````````````

TODO

.. function:: SitesManager.getDefaultTimezone()

    :returns: TODO

Report example::

    TODO

SitesManager.setDefaultTimezone
```````````````````````````````

TODO

.. function:: SitesManager.setDefaultTimezone(defaultTimezone)

    :param defaultTimezone: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.updateSite
```````````````````````

TODO

.. function:: SitesManager.updateSite(idSite, siteName, urls, ecommerce, siteSearch, searchKeywordParameters, searchCategoryParameters, excludedIps, excludedQueryParameters, timezone, currency, group, startDate, excludedUserAgents, keepURLFragments, type, settingValues, excludeUnknownUrls)

    :param idSite: TODO
    :param siteName: TODO
    :param urls: TODO
    :param ecommerce: TODO
    :param siteSearch: TODO
    :param searchKeywordParameters: TODO
    :param searchCategoryParameters: TODO
    :param excludedIps: TODO
    :param excludedQueryParameters: TODO
    :param timezone: TODO
    :param currency: TODO
    :param group: TODO
    :param startDate: TODO
    :param excludedUserAgents: TODO
    :param keepURLFragments: TODO
    :param type: TODO
    :param settingValues: TODO
    :param excludeUnknownUrls: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getCurrencyList
````````````````````````````

TODO

.. function:: SitesManager.getCurrencyList()

    :returns: TODO

Report example::

    [
      {
        "USD": "US dollar ($)",
        "EUR": "Euro (€)",
        "JPY": "Japanese yen (¥)",
        "GBP": "British pound (£)",
        "CHF": "Swiss franc (Fr)",
      }
    ]

SitesManager.getCurrencySymbols
```````````````````````````````

TODO

.. function:: SitesManager.getCurrencySymbols()

    :returns: TODO

Report example::

    [
      {
        "USD": "$",
        "EUR": "€",
        "JPY": "¥",
        "GBP": "£"
      }
    ]

SitesManager.isTimezoneSupportEnabled
`````````````````````````````````````

TODO

.. function:: SitesManager.isTimezoneSupportEnabled()

    :returns: TODO

Report example::

    {"value":true}


SitesManager.getTimezonesList
`````````````````````````````

TODO

.. function:: SitesManager.getTimezonesList()

    :returns: TODO

Report example::

    {
      "UTC": {
        "UTC-12": "UTC-12",
        "UTC-11.5": "UTC-11:30",
        "UTC-11": "UTC-11",
        "UTC-10.5": "UTC-10:30",
        "UTC-10": "UTC-10",
        "UTC-9.5": "UTC-9:30",
        "UTC-9": "UTC-9",
        "UTC-8.5": "UTC-8:30",
        "UTC-8": "UTC-8",
        "UTC-7.5": "UTC-7:30",
        "UTC-7": "UTC-7",
        "UTC-6.5": "UTC-6:30",
        "UTC-6": "UTC-6",
        "UTC-5.5": "UTC-5:30",
        "UTC-5": "UTC-5",
        "UTC-4.5": "UTC-4:30",
        "UTC-4": "UTC-4",
        "UTC-3.5": "UTC-3:30",
        "UTC-3": "UTC-3",
        "UTC-2.5": "UTC-2:30",
        "UTC-2": "UTC-2",
        "UTC-1.5": "UTC-1:30",
        "UTC-1": "UTC-1",
        "UTC-0.5": "UTC-0:30",
        "UTC": "UTC",
        "UTC+0.5": "UTC+0:30",
        "UTC+1": "UTC+1",
        "UTC+1.5": "UTC+1:30",
        "UTC+2": "UTC+2",
        "UTC+2.5": "UTC+2:30",
        "UTC+3": "UTC+3",
        "UTC+3.5": "UTC+3:30",
        "UTC+4": "UTC+4",
        "UTC+4.5": "UTC+4:30",
        "UTC+5": "UTC+5",
        "UTC+5.5": "UTC+5:30",
        "UTC+5.75": "UTC+5:45",
        "UTC+6": "UTC+6",
        "UTC+6.5": "UTC+6:30",
        "UTC+7": "UTC+7",
        "UTC+7.5": "UTC+7:30",
        "UTC+8": "UTC+8",
        "UTC+8.5": "UTC+8:30",
        "UTC+8.75": "UTC+8:45",
        "UTC+9": "UTC+9",
        "UTC+9.5": "UTC+9:30",
        "UTC+10": "UTC+10",
        "UTC+10.5": "UTC+10:30",
        "UTC+11": "UTC+11",
        "UTC+11.5": "UTC+11:30",
        "UTC+12": "UTC+12",
        "UTC+12.75": "UTC+12:45",
        "UTC+13": "UTC+13",
        "UTC+13.75": "UTC+13:45",
        "UTC+14": "UTC+14"
      }
    }

SitesManager.getUniqueSiteTimezones
```````````````````````````````````

TODO

.. function:: SitesManager.getUniqueSiteTimezones()

    :returns: TODO

Report example::

    TODO


SitesManager.renameGroup
````````````````````````

TODO

.. function:: SitesManager.renameGroup(oldGroupName, newGroupName)

    :param oldGroupName: TODO
    :param newGroupName: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getPatternMatchSites
`````````````````````````````````

TODO

.. function:: SitesManager.getPatternMatchSites(pattern, limit)

    :param pattern: TODO
    :param limit: TODO
    :returns: TODO

Report example::

    TODO

SitesManager.getNumWebsitesToDisplayPerPage
```````````````````````````````````````````

TODO

.. function:: SitesManager.getNumWebsitesToDisplayPerPage()

    :returns: TODO

Report example::

    {"value":15}
