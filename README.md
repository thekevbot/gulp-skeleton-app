#Generic App Skeleton
This is my app skeleton for setting up a new app project. It uses Gulp + BrowserSync to spin up a simple server and watches for changes to your HTML/SCSS/JS files.

To get started, clone this repo and run:

````
npm install
````

To start watching for changes to your .scss, .js, and .html files and spin up a dev server run:

````
gulp
````

###Build for Production
To run the built in build tasks for a production site (which includes optimizing images, concatenating + minifying your JS and CSS, copying fonts over, and cleaning up old files) run:

````
gulp build
````

You can also run any of the build tasks separately as needed:

`minify`: Minifies & Uglifies JS and CSS

`images`: Optimizes image files and copies them to /dist

`clean`: Cleans up any old files in /dist

`fonts`: Copies fonts to /dist
