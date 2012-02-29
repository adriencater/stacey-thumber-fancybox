# Stacey 3.0.0

## About this fork:

I have modified Stacey to include image resizing (thumber.php) and displaying images fullscreen (FancyBox).

The major changes to the code are the modification of images.html to include the thumber.php code, and the project.html to include jquery and fancybox.

-Adrien

## Overview
Stacey takes content from `.txt` files, image files and implied directory structure and generates a website.
It is a no-database, dynamic website generator.

If you look in the `/content` and `/templates` folders, you should get the general idea of how it all works.

## Installation

Copy to server, `chmod 777 app/_cache`.

If you want clean urls, `mv htaccess .htaccess`

## Templates

Stacey uses the [Twig templating language](http://twig.sensiolabs.org/).

There are an additional two sets of templates which can be found at:
<http://github.com/kolber/stacey-template2> &
<http://github.com/kolber/stacey-template3>

## Read More

See <http://staceyapp.com> for more detailed usage information.

## Copyright/License

Copyright (c) 2009 Anthony Kolber. See `LICENSE` for details.
Except [PHP Markdown Extra](http://michelf.com/projects/php-markdown/extra/) which is (c) Michel Fortin (see `/app/parsers/markdown-parser.inc.php` for details) and
[jsmin.php](https://github.com/rgrove/jsmin-php/) which is (c) Ryan Grove (see `app/parsers/json-minifier.inc.php` for details).