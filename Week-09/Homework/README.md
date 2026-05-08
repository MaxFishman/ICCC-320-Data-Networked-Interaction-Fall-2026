# Week 09 – Homework

## Assignment 09: Live Room — Designing Multi-Device Networked Experience

**Duration:** 2 Weeks (Week 9–10) · **Tools:** Node.js · WebSockets · p5.js · MQTT or OSC (optional)

### Overview

Design an interactive experience that requires multiple devices to work together. Each device plays a distinct role—controller, display, sensor, performer. The piece only makes sense when all devices are present. You are designing the network topology as much as the interaction itself.

---

### Undergraduate Requirements

- Build a system with at least 3 device roles (e.g., phone as controller, laptop as display, tablet as secondary view).
- Each role has a distinct UI appropriate to its function and screen size.
- The experience has a clear beginning, middle, and end—or a defined loop structure.
- Demonstrate the system live in critique with at least 3 devices connected simultaneously.
- Diagram your network topology (who sends what to whom, and when).

### Graduate Extensions

- Design the system for graceful degradation: it should partially function if one device drops.
- Implement a conductor role: one device can pause, reset, or reconfigure the entire system.
- Log all inter-device events with timestamps; build a post-session replay viewer.
- Write a 600-word design rationale: how does the distribution across devices change the experience vs. a single-screen version?
- Document the network topology formally: node types, message types, directionality, latency budget.

---

### Deliverables

- Live in-class demo
- Topology diagram
- Rationale essay (600 words grad)

### Critique Criteria

Role clarity, network robustness, experience coherence, live demo
