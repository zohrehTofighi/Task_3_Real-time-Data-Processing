WebSocket is a powerful communication protocol that enables real-time, full-duplex communication between clients and servers over a single, long-lived connection. It is commonly used in web development for applications requiring instant updates, notifications, and interactive features. 
This task is divided into two parts:

Client Side:
Connects to a WebSocket server running locally on ws://127.0.0.1:7890.
Sends a greeting message to the server upon connection.
Listens for incoming messages from the server continuously.

Server Side:
Listens on port 7890 for incoming WebSocket connections.
Maintains a set of connected clients.
Echoes back any received message to all connected clients except the sender.
