# Typescript chess

A simple chess game written as an exercise to learn TypeScript and some assosiated tools.

You can move and capture pieces, but moves are not validated.

## Run it

The Javascript is compiled as ES2015 to avoid need for shims for now. From quick tests it only runs in new versions of Chrome.   

## Todo

* Check
* En passant
* Casteling
* Validate moves
* Browser compability

## Setup developer enviroment

Have not tried building it outside my own enviroment yet, but should work fine.
```
npm install -g gulp 
npm install -g typescript 
npm install -g typings 
npm install
```

Build Sass and Typescript with: 
```
gulp
```

## Built with

* Typescript 1.8
* JQuery
* Visual Studio Code