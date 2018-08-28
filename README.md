# pink-trombone-osc
An OSC controllable Pink Trombone

![pink trombone max msp](https://i.imgur.com/pXyg6aM.jpg)

Control the amazing Pink Trombone vocal synthesizer with OSC programs such as max msp, pure data, processing etc.

This project uses a node server and to server and send OSC messages (via websocket) to a modified version of the pink trombone. The purpose is to create an interface for music and media composition programs to control the instrument.

The original pink trombone code is from http://dood.al/pinktrombone/

See original copyright notice in `src/index.html` and `src/app.js`

## Prerequisites
`node`
`yarn` or `npm`


## To Run locally
`yarn install`
`node server.js` 


## To develop
`npm start` to watch files

view app at localhost:3000


<!-- npm run start:dev to runserver -->
