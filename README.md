Create a beatiful `redoc` or `swagger` specification for your `scrapyd` based API. 

# HOW-TO

Just add `redoc.html` to your `scrapyd` based API, and yoou will have an interactive `scrapyd` documentation. [DEMO](https://htmlpreview.github.io/?https://raw.githubusercontent.com/zero0nee/scrapyd_openapi/master/redoc.html).

```
<!DOCTYPE html>
<html>
  <head>
    <title>ReDoc</title>
    <!-- needed for adaptive design -->
    <meta charset="utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://fonts.googleapis.com/css?family=Montserrat:300,400,700|Roboto:300,400,700" rel="stylesheet">

    <!--
    ReDoc doesn't change outer page styles
    -->
    <style>
      body {
        margin: 0;
        padding: 0;
      }
    </style>
  </head>
  <body>
    <redoc spec-url='https://raw.githubusercontent.com/zero0nee/scrapyd_openapi/master/open_api.yaml'></redoc>
    <script src="https://cdn.jsdelivr.net/npm/redoc@next/bundles/redoc.standalone.js"> </script>
  </body>
</html>
```

# CREDITS
This project has samply converted the official `scrapyd` [documentation](https://scrapyd.readthedocs.io/en/latest/api.html#addversion-json) to `openapi-spec` format. 

