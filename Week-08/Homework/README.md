# Week 08 – Homework

## Assignment 08: Publish / Subscribe — MQTT for IoT and Multi-Device Messaging

**Duration:** 1.5 Weeks (Week 8–9) · **Tools:** MQTT.js · Node.js · p5.js · HiveMQ or Mosquitto broker

### Overview

MQTT's publish/subscribe model decouples senders and receivers in ways WebSocket cannot. Using a public or self-hosted broker, build a multi-device messaging system where at least two clients publish to topics and at least two subscribe. The focus is on topic design, QoS levels, and retained messages.

---

### Undergraduate Requirements

- Connect two browser clients (separate tabs or machines) to a public MQTT broker via MQTT.js over WSS.
- Design a topic hierarchy with at least 3 levels (e.g., `dni/[room]/[sensor]/[value]`).
- One client publishes sensor-like data (simulated or real); the other subscribes and visualizes.
- Use wildcard subscriptions (`#`) and demonstrate how they work with a visible subscriber log.
- Document your topic tree and explain your QoS choices (0, 1, or 2) for each topic.

### Graduate Extensions

- Implement retained messages and Last Will and Testament (LWT) for device presence tracking.
- Build a topic-based access control simulation: certain topics are read-only for some clients.
- Integrate a physical sensor (phone accelerometer via a mobile MQTT client, or any IoT board).
- Compare MQTT QoS 0, 1, 2 empirically: measure and visualize message loss at each level under simulated network stress.
- 500-word architecture document: when would you choose MQTT over WebSocket or OSC for an installation?

---

### Deliverables

- GitHub repo
- Topic tree diagram
- QoS analysis
- Architecture doc (500 words grad)

### Critique Criteria

Topic design, QoS understanding, multi-device function, documentation quality
