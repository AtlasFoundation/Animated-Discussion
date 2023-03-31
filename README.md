# Animated Discussion 
## ReadMe

Animated Discussion listens to your conversations and paints them in real time. It can also listen to podcasts, join you in a clubhouse room, or paint your narrated story. It is a project by [Thomas Davis](http://github.com/thomasdavis) and [Lisa Watts](http://github.com/davincidreams). The AI Painter is an open source project and we have opted to use open source models and an MIT license. We hope that this project will inspire others to create their own visions.
## About

Painted Conversations was based on Thomas Davis's earlier work on the [Omega project](), a turing test bot for Clubhouse that utilized GPT-3 and google voice.   

### Installation
```
npm i
npm start
```

#### Requirements
* Sox
* chocolatey
* node record
* [PM2](https://pm2.keymetrics.io/docs/usage/application-declaration/)- If you’re on Linux, Windows, Mac, or using a Docker container:
```npm install pm2 -g```
```pm2 start ecosystem.config.js --only "api-app,worker-app"```

## Examples
![2022-11-19 08 18 50](https://user-images.githubusercontent.com/64185677/229109460-469a2075-671a-49fa-ade8-a951c651c8af.png)
![2022-11-29 12 26 23-8](https://user-images.githubusercontent.com/64185677/229109794-93c2c904-e663-4c17-82f1-31c75b6d2bee.png)
![2023-03-02 06 23 15-2](https://user-images.githubusercontent.com/64185677/229110231-4e66e8c4-82fd-4eeb-a7e0-e1e77d201de0.png)
![2022-11-19 14 20 17](https://user-images.githubusercontent.com/64185677/229109592-ccec7635-cd68-4d09-957b-997f5997e79c.png)
![2022-11-29 12 26 24-2](https://user-images.githubusercontent.com/64185677/229109749-c908b059-bc62-47fd-b2d4-f0db3582153d.png)

## To do
*how to start ngrok to host it!

*sox version
*https://github.com/gillesdemey/node-record-lpcm16/issues/58
*https://github.com/chocolatey/choco/issues/2398
