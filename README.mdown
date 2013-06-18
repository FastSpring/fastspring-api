FastSpring API
==============

The FastSpring API follows the REST principles as much as possible. Check out our [wrappers](#wrappers-and-example-code) and [API endpoint documentation](#api-endpoints).

In addition to the REST APIs, there are also "push" notifications / IPN postback's available for subscription activation and deactivation.  It is typical to use both the rest API and push notifications for a complete solution.  Please see the [notification documentation](https://support.fastspring.com/entries/236490-notifications-overview) for more information.


Wrappers and example code
-------------------------

* [Ruby](http://github.com/fastspring/fastspring-ruby)
* [PHP](http://github.com/fastspring/fastspring-php)


Authentication
--------------

All requests require authentication. This can be either through HTTP Basic authentication or URL parameters. This is secure since all requests use SSL. [More...](http://github.com/fastspring/fastspring-api/blob/master/sections/authentication.mdown)


Making a request
---------------

* All URLs start with `https://api.fastspring.com/company/{company}` and must be made through SSL (HTTPS). Plain HTTP requests will be rejected.
* Make sure to set the `Content-Type` header to `application/xml` for `PUT` and `POST` requests which will identify the format of the data being sent.
* Check out our API endpoints below for further details


API Endpoints
-------------

* [Subscriptions](http://github.com/fastspring/fastspring-api/blob/master/sections/subscriptions.mdown)
* [Orders](http://github.com/fastspring/fastspring-api/blob/master/sections/orders.mdown)
* [Miscellaneous](http://github.com/fastspring/fastspring-api/blob/master/sections/misc.mdown)
