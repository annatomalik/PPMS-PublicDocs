.. highlight:: js
.. default-domain:: js

UserLanguage.getLanguage
````````````````````````
TODO

.. function:: UserLanguage.getLanguage(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "English",
        "nb_uniq_visitors": 172,
        "nb_visits": 180,
        "nb_actions": 292,
        "nb_users": 0,
        "max_actions": 22,
        "sum_visit_length": 12789,
        "bounce_count": 140,
        "nb_visits_converted": 0,
        "segment": "languageCode==en,languageCode=@en-"
      },
    ]

UserLanguage.getLanguageCode
````````````````````````````
TODO

.. function:: UserLanguage.getLanguageCode(idSite, period, date, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    [
      {
        "label": "English - United States (en-us)",
        "nb_uniq_visitors": 143,
        "nb_visits": 151,
        "nb_actions": 251,
        "nb_users": 0,
        "max_actions": 22,
        "sum_visit_length": 11915,
        "bounce_count": 118,
        "nb_visits_converted": 0,
        "segment": "languageCode==en-us"
      }
    ]