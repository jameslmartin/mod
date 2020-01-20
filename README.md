# mod for Pelican

A really basic, made-from-scratch, dependency-free theme for Pelican.

## Effective use

You will need to make sure these variables are defined in your `pelicanconf.py` file:

```
AUTHOR
SITENAME
SITEURL
SITESUBTITLE

USE_FOLDER_AS_CATEGORY = True
DISPLAY_PAGES_ON_MENU = True
DISPLAY_CATEGORIES_ON_MENU = False

PAGE_URL = ('{slug}/')
PAGE_SAVE_AS = ('{slug}.html')
```

If you want to customize the nav bar, modify how you output categories and toggle the flags above.
