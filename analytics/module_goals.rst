.. highlight:: js
.. default-domain:: js

Goals.getGoal
`````````````
TODO

.. function:: Goals.getGoal(idSite, idGoal)

    :param idSite: TODO
    :param idGoal: TODO
    :returns: TODO

Report example::

    TODO

Goals.getGoals
``````````````
TODO

.. function:: Goals.getGoals(idSite)

    :param idSite: TODO
    :returns: TODO

Report example::

    [
      {
        "idsite": "7",
        "idgoal": "1",
        "name": "New user registration",
        "description": "",
        "match_attribute": "url",
        "pattern": "register.php",
        "pattern_type": "contains",
        "case_sensitive": "0",
        "allow_multiple": "0",
        "revenue": "3",
        "deleted": "0"
      },
      {
        "idsite": "7",
        "idgoal": "2",
        "name": "User login",
        "description": "",
        "match_attribute": "url",
        "pattern": "login.php",
        "pattern_type": "contains",
        "case_sensitive": "0",
        "allow_multiple": "0",
        "revenue": "1",
        "deleted": "0"
      }
    ]

Goals.addGoal
`````````````
TODO

.. function:: Goals.addGoal(idSite, name, matchAttribute, pattern, patternType, caseSensitive, revenue, allowMultipleConversionsPerVisit, description)

    :param idSite: TODO
    :param name: TODO
    :param matchAttribute: TODO
    :param pattern: TODO
    :param patternType: TODO
    :param caseSensitive: TODO
    :param revenue: TODO
    :param allowMultipleConversionsPerVisit: TODO
    :param description: TODO
    :returns: TODO

Report example::

    TODO

Goals.updateGoal
````````````````
TODO

.. function:: Goals.updateGoal(idSite, idGoal, name, matchAttribute, pattern, patternType, caseSensitive, revenue, allowMultipleConversionsPerVisit, description)

    :param idSite: TODO
    :param idGoal: TODO
    :param name: TODO
    :param matchAttribute: TODO
    :param pattern: TODO
    :param patternType: TODO
    :param caseSensitive: TODO
    :param revenue: TODO
    :param allowMultipleConversionsPerVisit: TODO
    :param description: TODO
    :returns: TODO

Report example::

    TODO

Goals.deleteGoal
````````````````
TODO

.. function:: Goals.deleteGoal(idSite, idGoal)

    :param idSite: TODO
    :param idGoal: TODO
    :returns: TODO

Report example::

    TODO

Goals.getItemsSku
`````````````````
TODO

.. function:: Goals.getItemsSku(idSite, period, date, abandonedCarts, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param abandonedCarts: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    []

Goals.getItemsName
``````````````````
TODO

.. function:: Goals.getItemsName(idSite, period, date, abandonedCarts, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param abandonedCarts: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    []

Goals.getItemsCategory
``````````````````````
TODO

.. function:: Goals.getItemsCategory(idSite, period, date, abandonedCarts, segment)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param abandonedCarts: TODO
    :param segment: TODO
    :returns: TODO

Report example::

    []

Goals.get
`````````
TODO

.. function:: Goals.get(idSite, period, date, segment, idGoal, columns)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param idGoal: TODO
    :param columns: TODO
    :returns: TODO

Report example::

    {
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
      "conversion_rate_returning_visit": "0%"
    }

Goals.getDaysToConversion
`````````````````````````
TODO

.. function:: Goals.getDaysToConversion(idSite, period, date, segment, idGoal)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param idGoal: TODO
    :returns: TODO

Report example::

    []

Goals.getVisitsUntilConversion
``````````````````````````````
TODO

.. function:: Goals.getVisitsUntilConversion(idSite, period, date, segment, idGoal)

    :param idSite: TODO
    :param period: TODO
    :param date: TODO
    :param segment: TODO
    :param idGoal: TODO
    :returns: TODO

Report example::

    []

