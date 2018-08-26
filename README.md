# signaling-server
Socket.io based signaling server for WebRTC connections.

## Installation
* From the root directory run `npm install`

## Run Server

### Development
* `nodemon index.js`

### Production
* Install `pm2` with `ǹpm install -g pm2`
* Run with `pm2 start index.js`
* Configure a startup script with `pm2 startup systemd`
* Stop server: `pm2 stop index`
* Restart server: `pm2 restart index`
* Info: `pm2 info index`

#### Additional Commands from PM2
* List applications: `pm2 list`
* Monitor pm2 applications: `pm2 stop index`
* Tail logs `pm2 logs index`
