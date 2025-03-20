This multi-user chat system uses socket technology with 1 server and >1 client. The connection is handled with TCP. The project is made with Node.js

The client can:
* set nickname
* connect to the server by IP address
* send text messages to other connected clients
* move between channels ("/join $CHANNEL")
* send private messages ("/private $RECEIVER message")
* show messages from other clients within the same channel or private messages
* disconnect from the server

The server can:
* Handle several client connections
* Transmit messages between clients
* move clients to other channels
