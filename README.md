# react-async

react-async is a async example for Single Page Apps using React, Reduxt, Babel, and Webpack.

## React-hot-loader
The configuration of react-hot-loader is essential for redux development, as it won't lost state. While webpack's HotModuleReplacementPlugin might lost state.
* react-hot-loader Please refer to [react-hot-loader](https://github.com/gaearon/react-hot-loader) for the details of the confiuration.
* hot-module-replacement Please refer to [hot-module-replacement](https://webpack.js.org/guides/hot-module-replacement/) for the details of the confiuration.

**Notes**
```react-hot-loader``` is based on ```hot-module-replacement```, ```webpack hot-module-replacement``` must be setup and configured first to use ```react-hot-loader```.

## Getting Started

_(Note: this project was created in Node v8.11.2)_

Clone this repo and install dependencies with `npm install`.

### Starting The Dev Server

To start the server and start hacking, run

```BASH
npm start
```

This starter uses webpack-dev-server to spin up an Express server with Hot-Reloading capability. Changes to code in `.src` should cause pages to reload.

## Static Assets

Static Assets are served from the `/public` folder.

## Styling

Stylesheets are bundled along with project files in the `.src` folder, so you can divide your stylesheets by component (or any other configuration you plan)

## Bundling

To bundle your files, run

```BASH
npm run build
```

This will bundle your files at `<projectRoot>/dist/bundle.js`. `index.html` already references this location, allowing you build and open `index.html` without having to start the server. Note that there are no optimizations in place at this time.

#### Additional Credits

The swiss army knife svg is by [Delapouite](http://game-icons.net/delapouite/originals/swiss-army-knife.html) under CC BY 3.0
