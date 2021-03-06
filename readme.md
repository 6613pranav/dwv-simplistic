# dwv-simplistic

Simple medical viewer using [DWV](https://github.com/ivmartel/dwv) (DICOM Web Viewer).

All coding/implementation contributions and comments are welcome. Releases should be ready for deployment.

dwv-simplistic is not certified for diagnostic use. Released under GNU GPL-3.0 license (see [license.txt](license.txt)).

[![Build Status](https://travis-ci.org/ivmartel/dwv-simplistic.svg?branch=master)](https://travis-ci.org/ivmartel/dwv-simplistic)

## Steps to run the viewer from scratch

Get the code:
```sh
git clone https://github.com/ivmartel/dwv-simplistic.git
```

Move to its folder:
```sh
cd dwv-simplistic
```

Install dependencies (using `yarn`, replace with `npm` if you prefer):
```sh
yarn install
```

Call the start script to launch the viewer on a local server:
```sh
yarn run start
```

You can now open a browser at http://localhost:8080 and enjoy!

## Available Scripts

``` bash
# install dependencies
yarn install

# serve at localhost:8080 with live reload
yarn run start

# serve a developement version at localhost:8080 with live reload
yarn run dev

# run unit tests
yarn run test
```
