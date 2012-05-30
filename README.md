
# SVBTLE

Svbtle theme is a close copy of [Svbtle.com](http://www.svbtle.com) with a few minor changes for use with [Pelican](http://pelican.notmyidea.org).

## SCREENSHOT

![theme screenshot](https://raw.github.com/wting/pelican-svbtle/master/screenshot.png)

## FEATURES

- syntax highlighting for code blocks
- Google Analytics
- Disqus commenting
- custom list of links

## MISSING FEATURES

- pages
- custom menu
- index page date format is coded via JavaScript and ignores DEFAULT_DATE_FORMAT
- tag cloud
- translations

## INSTALL

Please refer to Pelican theme [install instructions](http://pelican.notmyidea.org/en/latest/pelican-themes.html).

## SETTINGS.PY

These are the Pelican global variables currently supported by the theme:

- GOOGLE_ANALYTICS
- DISQUS_SITENAME
- LINKS(('name1', 'url1'), ('name2', 'url2'))

## MODIFICATION

- Accent color can be changed by editing `@accent` in `./static/css/style.less`.

- A different Pygmentize theme can be used by editing `./Makefile` and running `make pygments`.

## SOURCE CODE

Code can be found at this GitHub [repo](https://github.com/wting/pelican-svbtle).

## AUTHOR

William Ting

## LICENSE

Released under MIT License, full details in `LICENSE` file.
