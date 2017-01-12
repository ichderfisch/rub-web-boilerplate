# RUB Webdesign (2012)

[![Build Status](https://travis-ci.org/ichderfisch/rub-web.svg?branch=master)](https://travis-ci.org/ichderfisch/rub-web-layout)

This repository is a private fork of [public available CD Templates](http://www.ruhr-uni-bochum.de/cd/cd-2016/web.html) of Ruhr-Universität Bochum.

Using SASS instead of VanillaCSS.

Feel free to improve. Don't use on productive sites, unless you know what you are doing.

## How to use

```
git clone https://github.com/ichderfisch/rub-web-layout.git
npm install
bower install
gulp build
```

## How to use

This repository does not have any dreamweaver or other template files, as the original repository. Just look at these files or  ``public/index.html`` for living html-examples. I probably add some templates later.

After building simply add the ``main.css`` or ``main.min.css`` to your html-templates. No more need for handling several different CSS-files.

A major difference with the original templates is the usage of new classes on ``<body>``.

- ``<body class="one-col">`` for a single column layout
- ``<body class="two-col-nav-aside">`` for a two column layout with the left navigation bar
- ``<body class="two-col-margial">`` for a two column layout with a sidebar on the right
- ``<body class="three-col">`` for a three column layout with the navigation bar left an a sidebar on the right

## Note

Dropped IE 6-9 Support!

## Author
Dennis Fischer (ichderfisch)  
[Github](https://github.com/ichderfisch/)  
[Twitter](https://twitter.com/ichderfisch/)

Feel free to contact me anytime
