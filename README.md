# Webpack Boilerplate
This repository contains Webpack and SCSS boilerplate code to quickly get started on building a webpage following a simplified version of the 7-1 pattern.

## SASS folder structure
It contains these folders : 

- `abstracts` : functions, variables
- `base` : reset, typography,
- `components` : buttons, form
- `layout` : footer, header, nav, breadcrumb
- `pages` : contact, home,
- `themes` : theme
- `vendors` : bootstrap, fontawesome


## Included Framework and Libraries
- `fontawesome` - Font Library


## Webpack Dependencies
- Babel
- CSS Loader
- File Loader
- Mini CSS Extractor Plugin
- Node SASS
- Purge CSS
- SASS Loader
- Webpack


### Installing

- Run `npm install`

### Running the app

Run `npm run dev`. Your browser should automatically open a new tab where you can see your app.

*Note :* live reload is enabled so just modify your files and it will be reflected on the app instantly.

### Building the app

Run `npm run build`. It will automatically add vendor prefixes to CSS rules and compress all your `.scss` files into one `style.css` file located in your `dist` folder.



