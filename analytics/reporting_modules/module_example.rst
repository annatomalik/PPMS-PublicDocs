.. highlight:: js
.. default-domain:: js

ExampleAPI.getPiwikVersion
``````````````````````````
TODO

.. function:: ExampleAPI.getPiwikVersion()

    :returns: TODO

Report example::

    {"value":"3.4.0-rc2"}

ExampleAPI.getAnswerToLife
``````````````````````````
TODO

.. function:: ExampleAPI.getAnswerToLife()

    :returns: TODO

Report example::

    {"value":42}

ExampleAPI.getObject
````````````````````
TODO

.. function:: ExampleAPI.getObject()

    :returns: TODO

Report example::

    {"result":"error","message":"The API cannot handle this data structure."}

ExampleAPI.getSum
`````````````````
TODO

.. function:: ExampleAPI.getSum(a,b)

    :param a: TODO
    :param b: TODO
    :returns: TODO

Report example::

    {"value":4}

ExampleAPI.getNull
``````````````````
TODO

.. function:: ExampleAPI.getNull()

    :returns: TODO

Report example::

    {"result":"success","message":"ok"}

ExampleAPI.getDescriptionArray
``````````````````````````````
TODO

.. function:: ExampleAPI.getDescriptionArray()

    :returns: TODO

Report example::

    [
     "web analytics",
    ]

ExampleAPI.getCompetitionDatatable
``````````````````````````````````
TODO

.. function:: ExampleAPI.getCompetitionDatatable()

    :returns: TODO

Report example::

    [{"name":"piwik","license":"GPL","logo":"logo.png"},{"name":"google analytics","license":"commercial"}]

ExampleAPI.getMoreInformationAnswerToLife
`````````````````````````````````````````
TODO

.. function:: ExampleAPI.getMoreInformationAnswerToLife()

    :returns: TODO

Report example::

    {"value":"Check http:\/\/en.wikipedia.org\/wiki\/The_Answer_to_Life,_the_Universe,_and_Everything"}

ExampleAPI.getMultiArray
````````````````````````
TODO

.. function:: ExampleAPI.getMultiArray()

    :returns: TODO

Report example::

    {
      "Limitation": [
        "Multi dimensional arrays is only supported by format=JSON",
        "Known limitation"
      ],
      "Second Dimension": [
        true,
        false,
        1,
        0,
        152,
        "test",
        {
          "42": "end"
        }
      ]
    }

