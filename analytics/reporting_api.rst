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
