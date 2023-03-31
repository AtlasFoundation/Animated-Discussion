# ReadMe

Animated Discussion listens to your conversations and paints them in real time. It can also listen to podcasts, join you in a clubhouse room, or paint your narrated story. It is a project by [Thomas Davis](http://github.com/thomasdavis) and [Lisa Watts](http://github.com/davincidreams). The AI Painter is an open source project and we have opted to use open source models and an MIT license. We hope that this project will inspire others to create their own visions.
## About

Painted Conversations was based on Thomas Davis's earlier work on the [Omega project](), a turing test bot for Clubhouse that utilized GPT-3 and google voice.   

## Installation

```
npm i

npm start
```

## Requirements
* Sox

* chocolatey

* [PM2](https://pm2.keymetrics.io/docs/usage/application-declaration/)- If you’re on Linux, Windows, Mac, or using a Docker container (yes, it supports Docker as well):

```npm install pm2 -g```

```pm2 start ecosystem.config.js --only "api-app,worker-app"```

* node record

## To do

*how to start ngrok to host it

*sox version

*https://github.com/gillesdemey/node-record-lpcm16/issues/58

*https://github.com/chocolatey/choco/issues/2398
