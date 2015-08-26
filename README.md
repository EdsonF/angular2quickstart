# angular2quickstart
based on https://angular.io/docs/js/latest/quickstart.html

## requirements

The samples require the following packages to be isntalled globally.

`npm install -g http-server typescript tsd jspm`

## ts-web
Loads all 3rd party libraries from web hosted servers. Not suitable for more than a demo.

## ts-systemjs-npm
Uses npm to install 3rd party libraries and system.js to load the modules. Works great, loads just what is needed.

## ts-systemjs-jspm
Uses jspm to install 3rd party libraries and system.js to load the modules. Currently loads way too much: 2.8mb overall.