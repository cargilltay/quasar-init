# Quasar App

> A Quasar project

## Build Setup

``` bash

# this assumes
# -quasar project is initialized
# -npm intalled and updated

# install dependencies
$ npm install

# build for production with minification
$ quasar build

# wrap cordova for mobile
$ quasar wrap cordova

# add ios/android
$ cd cordova
$ cordova platform add ios

# build ios
$ cordova build --release ios

# run ios emulator or plug in phone
$ cordova run ios

```

## Additional commands
``` bash

# serve with hot reload at localhost:8080
$ quasar dev

# lint code
$ quasar lint

# cannot read property 'replace' of undefined?
$ cd platforms/ios/cordova && npm install ios-sim

```

## Workflow
``` bash

$ quasar build
$ cd cordova
$ cordova run ios

```
