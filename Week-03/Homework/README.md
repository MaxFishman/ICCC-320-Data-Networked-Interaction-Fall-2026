# Week 03 – Homework

## Assignment 03: Event Horizon — Introduction to Event-Driven Architecture with Node.js

**Duration:** 1.5 Weeks (Week 3–4) · **Tools:** Node.js · EventEmitter · WebSockets (ws) · p5.js

### Overview

Move off the browser. Write a Node.js server that emits custom events and build a browser client that responds to them in real time. This is your introduction to the server–client model and the pub/sub pattern that underlies most networked interaction systems.

---

### Undergraduate Requirements

- Build a Node.js server using the `ws` library that emits a custom JSON event on a schedule (e.g., every 2s).
- Build a p5.js browser client that connects via WebSocket and visualizes incoming events.
- Handle connection, disconnection, and reconnection states visually.
- The server must accept at least one message type from the client (e.g., a parameter change).
- Document your event schema: event name, payload fields, direction (server→client or client→server).

### Graduate Extensions

- Design a full event taxonomy with at least 5 distinct event types; document as a typed schema (TypeScript interfaces or JSON Schema).
- Implement a message broker pattern: server routes messages between multiple clients by topic/channel.
- Add server-side event logging to a file with timestamps; build a playback mode that replays a session.
- Profile latency: measure and display round-trip time for events; discuss tradeoffs in a 400-word write-up.
- Research question: compare WebSocket, SSE, and long-polling for your use case.

---

### Deliverables

- GitHub repo (server + client)
- Event schema document
- Reflection

### Critique Criteria

Architecture clarity, schema design, error handling, real-time responsiveness
