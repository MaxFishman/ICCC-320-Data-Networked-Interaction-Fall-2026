# Week 05 – Homework

## Assignment 05: OSC Messenger — Open Sound Control for Cross-Application Communication

**Duration:** 1.5 Weeks (Week 5–6) · **Tools:** Node.js · osc.js · p5.js · Web OSC

### Overview

OSC (Open Sound Control) is the lingua franca of live performance and installation. Build a system where data flows over OSC between at least two applications—for example, p5.js → Max/MSP, p5.js → SuperCollider, or two Node.js processes. Focus on address pattern design and the precision of typed OSC arguments.

---

### Undergraduate Requirements

- Build a Node.js OSC server and a browser-based sender using osc.js (via WebSocket bridge).
- Design at least 6 OSC address patterns following a logical namespace (e.g., `/sketch/color`, `/sketch/tempo`).
- Send OSC messages from p5.js interactions; visualize received messages in a second p5.js sketch.
- Display a live OSC message log on screen (address, args, timestamp).
- Document all OSC addresses in a routing table (address, type tag, range, meaning).

### Graduate Extensions

- Design a full OSC namespace for a performance system with hierarchical addresses (`/system/module/parameter`).
- Implement bidirectional OSC with feedback prevention (message de-duplication or origin tagging).
- Bridge OSC to WebSocket: build a relay server that translates between OSC UDP and WS clients.
- Integrate with an external application (Max, TouchDesigner, SuperCollider, Ableton via LiveOSC).
- Write a 500-word technical analysis: when is OSC preferable to WebSocket or MQTT for your use case?

---

### Deliverables

- GitHub repo
- OSC routing table
- Video demo (60–90s)
- Analysis (500 words grad)

### Critique Criteria

Namespace design, type accuracy, integration robustness, documentation
