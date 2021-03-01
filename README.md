# sass-template

> **Author:** Michael Cabot (`cabotmichael@gmail.com`)

> **License:** GPL v3.0 `See LICENSE.md.`

SASS template for website design projects. Uses 7-1 pattern/architecture and includes bootstrap v5 source.

Found myself using the same mixins, variables, dependencies (bootstrap)  in multiple SASS projects so I created this template to start off all of my SASS projects.

**Bootstrap:** https://github.com/twbs/bootstrap 	[MIT License]

**Normalize:** https://github.com/necolas/normalize.css [MIT License]

## Structure
```
  .
  ├── abstracts
	  ├── _mixins.scss         # Mixins and functions
	  ├── _variables.scss      # Variables
  ├── base
	  ├── _base.scss           # Base styles
	  ├── _animations.scss     # Animations
	  ├── _fonts.scss          # Font styles (blank template file)
	  ├── _icons.scss          # Icon styles (blank template file)
  ├── components
	  ├── _alerts.scss         # Blank template file
  ├── layout
	  ├── _main.scss           # Blank template file
	  ├── _navbar.scss         # Blank template file
  ├── pages
	  ├── _page-name.scss      # Blank template file
  ├── themes
	  ├── _theme.scss          # Blank template file
  ├── vendors
	  ├── _bootstrap.scss      # Imports bootstrap v5.0.0-beta1 from /vendors/bootstrap/
	  ├── _normalize.scss      # Imports normalize.css v8.0.1
  ├── LICENSE
  ├── main.scss                	   # Main stylesheet file, contains only imports
  └── README.md
