# ACML 2016

Code for generating the website for ACML 2016 conference.
Uses [Nikola](https://getnikola.com/) static site generator.

Website/code is released under [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).


## Nikola

This folder contains the source used to generate a static site using Nikola.

Installation and documentation at https://getnikola.com/. If you want
to create a *site* instead of a *blog*, check out https://getnikola.com/creating-a-site-not-a-blog-with-nikola.html.

Configuration file for the site is `conf.py`. Relevant parameters to 
adjust for deployment to a different site:

* `SITE_URL`
* `DEPLOY_COMMANDS`

To build the site:
```
    nikola build
```

To see it:
```
    nikola serve -b
```

To check all available commands:
```
    nikola help
```

