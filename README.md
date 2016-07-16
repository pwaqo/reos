# Reos

Reos theme is a responsive theme for [Pelican](http://getpelican.com)

## FEATURES

- responsive
- syntax highlighting for pre blocks
- supports google analytics
- custom list of links

## INSTALL

Clone the [repository](https://github.com/riki319/reos),
edit your `pelicanconf.py` and modify the `THEME` variable to make it 
point to the downloaded theme location, or install it 
with the `pelican-themes` command tool.

## PELICANCONF.PY

Supports a number of common global variables but patches are welcomed if you need better support.


- `USER_LOGO`
- `DISQUS_SITENAME` set this to enable disqus comments in articles
- `COLLAPSE_COMMENTS` set to `True` to have article comments hidden by default. Clicking on the `comments` link will toggle visibility.
- `TAGLINE` some text rendered right below the logo
