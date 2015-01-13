# Analytics plugin for Kirby

## What is it?

Adds a Google Analytics code automatically as soon as the site is not running on localhost.

## Why use it?

I have often forgotten to (re)activate the Google Analytics snippet after pushing to the development server.

## How to use it?

Put the plugin in `/site/plugins` and add a Google Analytics id to your config:

```PHP
c::set('google.analytics_id', '<analytics_id>');
```

Then you can simply call it from a template or snippet:

```PHP
<?php echo analytics() ?>
```

## Author
Iksi, <http://www.iksi.cc>
