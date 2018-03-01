Demo : http://hack.chat/

## Local install

### Server

node v0.12 or higher is required to run the server.

* `git clone https://github.com/nguyenhopquang/hack.chat.git`
* `cd hack.chat`
* `npm install`
* Copy `config-sample.json` to `config.json` and edit if needed.
* `npm start` or `node server.js`

### Client
* `cd client`
* `npm install -g less jade http-server`
* `make`
* `http-server`

Change the "frontpage" text in `client.js` to your liking, and go to http://127.0.0.1:8080.
