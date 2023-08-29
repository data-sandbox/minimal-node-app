# Simple Node App and REST API

🚀 Streamlined approach to initializing a modern JS application and REST API.

Inspiration from [@rwieruch](https://github.com/rwieruch/minimal-node-application).

### Installation

- `npm install`
- `npm start`

### REST API Usage

- View all messages:
  `curl http://localhost:3000/messages` (or whatever port is set to in `.env`)
- View specific message details: `curl http://localhost:3000/messages/:messageId`
- Add message: `curl -X POST -H "Content-Type:application/json" http://localhost:3000/messages -d '{"text":"Hi again, World"}'`
- Delete message: `curl -X DELETE http://localhost:3000/messages/:messageId`
