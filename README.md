### HTTP Client Utilities

This is a direct fork of [Wreck](https://github.com/hapijs/wreck) with the difference that POST requests with 302 redirects will not change to GET on the redirect but will use the original method.
