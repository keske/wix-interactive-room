Interactive Installation at WIX Playground
=========================

## Description

Welcome to the Interaction Room.At the web page, each guest can modify his own unique graphic element that will have a unique sound effect and will be appeared on the projection screen above the DJ.

Sound effects will go along with the DJ set, adding layers of sounds to the core musical set. 

Visuals are unique to each participant as well as the sound effect. 

[More Details](https://www.wixplaygroundpresents.com/interaction-room)

## All Project's Repos

Web Client
[https://github.com/keske/wix-interactive-room-client](https://github.com/keske/wix-interactive-room-client)

Main Server (session and render logic)
[https://github.com/keske/wix-interactive-main-server](https://github.com/keske/wix-interactive-main-server)

Audio Server (request and web socket connection to Display for samples playing)
[https://github.com/keske/wix-interactive-room-audio-server](https://github.com/keske/wix-interactive-room-audio-server)

Display
[https://github.com/keske/wix-interactive-room-display](https://github.com/keske/wix-interactive-room-display)

Three JS Helper Lib to Render Geometry
[https://github.com/keske/wix-interactive-room-threejs-helpers](https://github.com/keske/wix-interactive-room-threejs-helpers)

## Structure

![alt text][structure]

## Technology Stack

### Server

```
Express
Linux
NodeJS
WebSockets
```

### Client

```
React
React Create App
ThreeJS
Webpack
```

### Common for both sides

```
Axios
Babel
ESLint
Ramda
WebSockets
```

[structure]: https://raw.githubusercontent.com/keske/wix-interactive-room/master/public/structure.png?token=AAN5LUXGDPQCOSQATKYKHHS42CL5U "Structure"

New York. April 2019.
