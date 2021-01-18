### WebSocket in python

[Getting started — websockets 8.1 documentation](https://websockets.readthedocs.io/en/stable/intro.html)

```py
python websocket-server.py
python websocket-client.py
```

### socket (BSD socket) in python

[socket — Low-level networking interface — Python 3.9.1 documentation](https://docs.python.org/3/library/socket.html#example)

```py
python socket-server.py
python socket-client.py
```

### WebSocket in javascript

[websockets/ws： Simple to use, blazing fast and thoroughly tested WebSocket client and server for Node.js](https://github.com/websockets/ws)

```shell
node websocket-server.js
node websocket-client.js
```

### socket.io in javascript

[Introduction | Socket.IO](https://socket.io/docs/v3/index.html)
> Socket.IO is NOT a WebSocket implementation.
> Although Socket.IO indeed uses WebSocket as a transport when possible,
> it adds additional metadata to each packet.
> That is why a WebSocket client will not be able to successfully connect to a Socket.IO server,
> and a Socket.IO client will not be able to connect to a plain WebSocket server either.

```shell
node socketio-index.js
```
