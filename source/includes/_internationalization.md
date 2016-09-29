# Internationalization

You can specify the locale by setting the Accept-Language HTTP header in your request. Alternatively, you can add a locale=XXX parameter to your request but HTTP header specification is preferred. We currently support en and ja.

If accept-language HTTP header is one of en or ja, this one is used even if locale is defined differently in the url as a parameter.

If accept-language HTTP header is defined but different then en or ja, and locale is defined in the url as en or ja. Locale is used.
If locale is other than en and ja, we default to locale="en".

If no accept-language HTTP header is defined, we check for the locale parameter in the url, only en and ja are supported else we default to locale="en".

If nothing is defined we default to locale="en"

So you can check the API from the browser using the locale parameter : 

![alt tag](/images/web-request.jpg)

Or you can use the Accept-Language HTTP header (preferred method for real request from an app.) :

ex with curl :

`curl -H Accept-language:en https://api-staging.tokyoartbeat.com/api/v0/lists/smart`

![alt tag](/images/curl-request.jpg)

