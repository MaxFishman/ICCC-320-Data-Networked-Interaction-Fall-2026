# Week 04 – Homework

## Assignment 04: Shared Canvas — Collaborative Drawing Over WebSockets

**Duration:** 1.5 Weeks (Week 4–5) · **Tools:** Node.js · WebSockets · p5.js · HTML Canvas

### Overview

What does it mean to share a surface? Build a multi-user drawing tool where every connected client sees every other client's marks in real time. You will confront the fundamental problems of networked interaction: latency, conflict, identity, and presence.

---

### Undergraduate Requirements

- Server broadcasts all draw events (`mouseX`, `mouseY`, color, brushSize) to all connected clients.
- Each client is assigned a unique color on connection; display a live count of connected users.
- Implement a clear-canvas event that all clients receive simultaneously.
- Strokes must feel responsive locally (optimistic update) even before server confirmation.
- Reflect in 250 words: how does the shared canvas change drawing behavior?

### Graduate Extensions

- Implement a conflict resolution strategy for simultaneous edits (last-write-wins, operational transform, or CRDT-lite)—document your choice.
- Add persistent canvas state: new clients receive the current canvas on join (server-side snapshot).
- Build a 'rooms' system: clients can create or join named rooms with isolated canvases.
- Add cursor presence: display other users' cursors with name labels in real time.
- 500-word critical essay: cite one historical collaborative networked artwork and compare it to yours.

---

### Deliverables

- Live deployed URL (Glitch, Railway, Render, etc.)
- GitHub repo
- Written reflection (250 words undergrad / 500 words grad)

### Critique Criteria

Responsiveness, presence design, conflict handling, deployment
