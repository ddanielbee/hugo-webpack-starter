# hugo-webpack-starter
Starting Hugo Boilerplate with Webpack js / scss compilation

## Usage
Everything inside the `./site` folder is Hugo's domain and works just like in any other Hugo project. 
Everything inside the `./src` folder will get compiled into the `./site/static` folder.
## JS
Use `./src/js/app.js` as an entry point that will get compiled to `./site/static/bundle.js`. 
## CSS
Use `./src/scss/styles.scss` as an entry point for .scss that will get injected by Webpack using CSS in JS. 

## TODO
Prod Config that: 
* Externalizes CSS into it's own file. 
* Builds HTML partials for header / footer that get their CSS / JS dependencies injected (using a hash for cache busting).
* Builds the Hugo static files.