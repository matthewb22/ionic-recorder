# ionic-recorder

Sound recording mobile / browser hybrid app, based on the Ionic framework,
the Web Audio Interface and IndexedDB.

## Introduction

This app combines
* [Ionic 2.x](http://ionicframework.com/docs/v2/)
* [Web Audio Interface](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) and 
  [MediaRecorder](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder_API)
* [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

to build
* A simple recording app (hybrid app that can run either in your browser or 
  as an ios/android native app)
* Useful real-time visualizations, stats and data-analysis of the recorded 
  audio signal

## Requirements
* This apps runs only in browsers that implement
  [MediaRecorder](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder_API).
  and a late version of IndexedDB that supports the `onupgradeended` event.
  
## Installation and getting started
In a shell, do

    git clone https://github.com/tracktunes/ionic-recorder
    cd ionic-recorder
    ./bin/recreate_app.sh

Now check the output of the file `typescript` at the end of this long process.

If all tests passed, you can type

    npm start

and a web browser window will pop up with the app running in it after it has been compiled from sources.

To start coding, just open the root project with VSCode.

## Version
The current version name is [here](https://github.com/tracktunes/ionic-recorder/blob/master/VERSION).

It corresponds to a git tag by the same name.

## License

This software is licensed under the [GNU General Public License, version 2 (GPL-2.0)](https://opensource.org/licenses/GPL-2.0)

## Copyright

Copyright (C) 2015, 2016 Tracktunes Inc.
