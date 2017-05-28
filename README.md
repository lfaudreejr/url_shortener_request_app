# url_shortener_request_app

## URL Shortener Microservice

#### User stories:

+  I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
+  When I visit that shortened URL, it will redirect me to my original link.

User Stories:
I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
When I visit that shortened URL, it will redirect me to my original link.
Example creation usage:
https://url-shortener-true.herokuapp.com/new/www.google.com

https://url-shortener-true.herokuapp.com/ryKoFuwZW


Example creation output:
{ original_url: "http://www.google.com", short_url: "url-shortener-true.herokuapp.com/ryKoFuwZW" }


Usage:
https://url-shortener-true.herokuapp.com/ryKoFuwZW


Will redirect to:
https://www.google.com/