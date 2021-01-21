Heroku buildpack: Static
=======================

This is a very simple static buildpack for Heroku using Python's builtin SimpleHTTPServer module.

It simply generates a Procfile containing the following :

    web: python -m http.server $PORT
