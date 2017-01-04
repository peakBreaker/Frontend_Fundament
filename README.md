# FrontEnd-Udacity

Front end project of the udacity full stack nanodegree. Bootstrap, markup, taskrunners, optimization.

# Content

root - Contains the development environment. Make changes to .html in root and .css in css/ and put images in images-src/. Never touch dist/.

dist/ - Distribution folder: This foldes includes the markup files and images for the portfolio webpage. This is the finished and built project ready for deployment. Automatically generated by gulp. No touchy!

# To deploy

Be sure to install Node.js and npm, and run '$npm install' in the root repository. This will install the dependencies.

After this, run '$gulp build' to clean up the dist folder and compile responsive images and markup to the dist folder.

Run '$gulp' to run task watchers and browserSync which will run a local webserver at localhost:3000 and autoupdate the page when changes are saved in any .html or .css files in the root repository. Don't change the code in dist, as it is autocompiled by gulp.

# About gulpfile

Gulp will create responsive images for the webpage automatically, and move HTML and CSS files to the dist folder.

# License 

This project is released under CC-BY-4.0.
