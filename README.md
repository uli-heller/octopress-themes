# Octopress Themes

This project contains my personal octopress themes. They are derived from these sources:

* octopress/.themes/classic

The modifications have been originally described here: [http://aijazansari.com/2012/08/27/how-to-customize-octopress-theme/](http://aijazansari.com/2012/08/27/how-to-customize-octopress-theme/)

## Installation

```
OCTOPRESS=".../octopress" # Absolute path of your octopress folder
cp -a uli "${OCTOPRESS}/.themes"
cd "${OCTOPRESS}"
rake install['uli']
```

To verify the new theme, do this:

```
rake generate
rake preview
# Open http://localhost:4000 in a browser window
```
