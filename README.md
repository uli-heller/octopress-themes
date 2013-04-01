# Octopress Themes

This project contains my personal octopress themes. They are derived from these sources:

* xxx

* yyy

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
