Django Server-Sent Events (SSE) Demo
This is a simple Django application demonstrating how to implement Server-Sent Events (SSE) for real-time communication between a Django server and a web client.

How It Works
The SSE functionality is implemented using Django's StreamingHttpResponse and a custom view that generates and streams events to connected clients.

The client-side JavaScript uses the EventSource API to establish a connection to the SSE endpoint and listen for incoming events.
