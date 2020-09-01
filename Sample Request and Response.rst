# Sample Request and Response

.. raw:: html

   <p>

NASA APOD (NASA Astronomy Picture of Day). One of the most popular
websites at NASA. In fact, this website is one of the most popular
websites across all federal agencies. This endpoint structures the APOD
imagery and associated metadata so that it can be repurposed for other
applications.

.. raw:: html

   <p>

 

.. raw:: html

   </p>

HTTP Sample Request
-------------------

+---------------+-----------------------------------------------------------+
| Request       | URI                                                       |
+===============+===========================================================+
| \ **GET**\    | https://api.nasa.gov/planetary/apod?api\_key=DEMO\_KEY.   |
+---------------+-----------------------------------------------------------+

.. raw:: html

   <p>

 

.. raw:: html

   </p>

Request Break down
------------------

.. raw:: html

   <p>

 

.. raw:: html

   </p>

+-----------------------+------------------------+-----------------------------------------------------------------------------------------------------------------------+
| Resource Components   | Value                  | Description                                                                                                           |
+=======================+========================+=======================================================================================================================+
| Method                | *GET*                  | Fetches the value.                                                                                                    |
+-----------------------+------------------------+-----------------------------------------------------------------------------------------------------------------------+
| URL                   | https://api.nasa.gov   | Base URI                                                                                                              |
+-----------------------+------------------------+-----------------------------------------------------------------------------------------------------------------------+
| Resource              | /planetary/apod        | The resource typically refers to some object or set of objects that are exposed at an API endpoint                    |
+-----------------------+------------------------+-----------------------------------------------------------------------------------------------------------------------+
| Parameters            | ?api\_key=DEMO\_KEY    | Options you can pass with the endpoint (such as specifying the response format or the amount returned) to influence   |
+-----------------------+------------------------+-----------------------------------------------------------------------------------------------------------------------+

.. raw:: html

   <p>

 

.. raw:: html

   </p>

Query Parameters
----------------

