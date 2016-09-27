# angularConfusionGulp

Installing Gulp
Install globally Gulp
sudo npm install -g gulp

Now locally

If you are behind proxy
  Proxy adding to work with Gulp
  npm config set proxy http://proxyhostname:proxyport
  npm config set https-proxy http://proxyhostname:proxyport

npm install gulp —-save-dev

Then gulp plugins
npm install gulp-jshint jshint-stylish gulp-imagemin gulp-concat 
gulp-uglify gulp-minify-css gulp-usemin gulp-cache gulp-rev gulp-rename 
gulp-changed gulp-notify browser-sync del --save-dev

npm install gulp-ng-annotate —-save-dev

After installing to to the project directory and execute:
gulp
or 
gulp watch
