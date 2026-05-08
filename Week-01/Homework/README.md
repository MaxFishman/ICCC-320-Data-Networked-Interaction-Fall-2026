# Week 01 – Homework

## Assignment 01: Hello, Data — Fetching and Rendering a Live API

**Duration:** 1 Week (Week 1–2) · **Tools:** p5.js · fetch() · JSON · REST API

### Overview

Your first encounter with live data. Connect to a public REST API, parse the JSON response, and render at least three data fields as a visual composition in p5.js. The goal is not decoration—it is legibility: can a viewer understand what the data is just by looking at your sketch?

---

### Undergraduate Requirements

- Choose one public API (weather, open transit, astronomy, air quality, etc.).
- Use `fetch()` to retrieve live data every 10 seconds; handle loading and error states visually.
- Map at least 3 JSON fields to distinct visual properties (color, size, position, opacity).
- Include a visible timestamp showing when data was last updated.
- Write a 200-word process note: what surprised you about the data's shape?

### Graduate Extensions

- Design and document a data schema diagram before writing any code—identify field types, units, and edge cases.
- Build a reusable `fetchJSON(url, interval, callback)` utility with retry logic and exponential backoff.
- Layer two heterogeneous APIs (e.g., weather + seismic) and visualize their intersection.
- Include a debug panel toggled with a keypress that exposes raw JSON alongside the visual.
- Write a 500-word critical reflection: how does the API's data model encode assumptions about the world?

---

### Deliverables

- Hosted sketch link (p5.js Editor or GitHub Pages)
- Process note (200 words undergrad / 500 words grad)

### Critique Criteria

Legibility, data accuracy, visual–data coherence, error handling
