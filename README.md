# Sigal - Simple Static Gallery Generator

[![CI Status](https://github.com/saimn/sigal/workflows/Run%20unit%20tests/badge.svg)](https://github.com/saimn/sigal/actions)

[![codecov.io](https://codecov.io/gh/saimn/sigal/branch/main/graph/badge.svg)](https://codecov.io/gh/saimn/sigal)

Sigal is yet another simple static gallery generator. It\'s written in
Python and it allows to build a static gallery of images with the
following features:

-   Process directories recursively.
-   Generate HTML pages using
    [Jinja2](https://palletsprojects.com/p/jinja/) templates.
-   Relative links for a portable output.
-   Support themes, videos, EXIF tags, zip download.
-   Parallel processing.
-   MIT licensed.

The idea behind Sigal is to ease the use of the javascript libraries
like [galleria](https://github.com/GalleriaJS/galleria). These libraries
do a great job to display the images, Sigal does what is missing: resize
images, create thumbnails, generate HTML pages.

Sigal requires Python 3.9+.

## Links

-   Latest documentation on the [website](http://sigal.saimon.org/)
-   Source, issues and pull requests on
    [GitHub](https://github.com/saimn/sigal/)
-   Releases on [PyPI](https://pypi.org/project/sigal/)

## Themes & Demo

Sigal comes with three themes, based on the
[colorbox](http://www.jacklmoore.com/colorbox),
[galleria](https://github.com/GalleriaJS/galleria) and
[photoswipe](http://photoswipe.com) Javascript libraries:

-   [colorbox demo](http://saimon.org/sigal-demo/colorbox/)
-   [galleria demo](http://saimon.org/sigal-demo/galleria/)
-   [photoswipe demo](http://saimon.org/sigal-demo/photoswipe/)