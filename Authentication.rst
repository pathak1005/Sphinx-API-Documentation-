AUTHENTICATION
==============

Authentication is in place on api.nasa.gov to enable developer’s greater
access to backend resources. Although api.nasa.gov web services can be
accessed without an API key, this introduces limitations related to rate
limiting of calls. To understand how to use your API key to sign calls,
details about web service and DEMO\_KEY rate limits, and viewing current
usage, please visit the API authentication sec-tion on the NASA API
listing page for detailed information.

Web Service Rate Limits
-----------------------

Limits are placed on the number of API requests you may make using your
API key. Rate limits may vary by service, but the defaults are:

.. raw:: html

   <p>

Hourly Limit: 1,000 requests per hour For each API key, these limits are
applied across all api.nasa.gov API requests. Ex-ceeding these limits
will lead to your API key being temporarily blocked from making further
requests. The block will automatically be lifted by waiting an hour. If
you need higher rate limits, contact us at contakt@nasa.gov.in. ##
DEMO\_KEY Rate Limits In documentation examples, the special DEMO\_KEY
api key is used. This API key can be used for initially exploring APIs
prior to signing up, but it has much lower rate limits, so you’re
encouraged to sign up for your own API key if you plan to use the API
(signup is quick and easy). The rate limits for the DEMO\_KEY are:

Hourly Limit: 30 requests per IP address per hour.

.. raw:: html

   <p> 

Daily Limit: 50 requests per IP address per day.
