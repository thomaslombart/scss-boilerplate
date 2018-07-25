# SCSS Boilerplate

This repository contains SCSS boilerplate code to quickly get started on building a webpage following a simplified version of the 7-1 pattern.

It contains these folders : 

- `abstracts` : functions, variables
- `base` : reset, typography, utilities
- `components` : buttons, form
- `layout` : footer, header, nav

### Prerequisites

* [Node.js](https://nodejs.org/en/)
* [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/lang/en/)

### Installing

- Install the `live-server` package : `npm install -g live-server`
- Run `npm install`

### Running the app

Run `npm run start`. Your browser should automatically open a new tab where you can see your app.

*Note :* live reload is enabled so just modify your files and it will be reflected on the app instantly.

### Building the app

Run `npm run build`. It will automatically add vendor prefixes to CSS rules and compress all your `.scss` files into one `style.css` file located in your `css` folder.



