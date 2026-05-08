# Week 06 – Homework

## Assignment 06: MIDI in the Browser — Web MIDI API for Hardware–Software Interaction

**Duration:** 1 Week (Week 6–7) · **Tools:** Web MIDI API · Tone.js · p5.js · JavaScript

### Overview

Connect the physical to the networked. Using the Web MIDI API, build a browser application that receives MIDI input from a hardware controller (keyboard, pad controller, or knob box) and uses it to drive both sound (via Tone.js) and visuals (via p5.js). If you do not have hardware, use a virtual MIDI device.

---

### Undergraduate Requirements

- Request MIDI access and display all available input devices; gracefully handle browsers without Web MIDI.
- Map note-on/note-off messages to Tone.js synth events with velocity-sensitive volume.
- Map at least 2 CC (Control Change) messages to visual parameters in p5.js.
- Display a piano-roll-style visual of notes received in the last 4 seconds.
- Write a 200-word MIDI mapping document: CC number → parameter → visual/audio effect.

### Graduate Extensions

- Build a full MIDI learn system: user clicks any on-screen control and moves a hardware knob to bind it.
- Serialize the MIDI map to JSON; implement save/load so sessions are reproducible.
- Route MIDI output back to hardware or virtual devices (Tone.js → MIDI out).
- Implement a MIDI clock: sync `Tone.Transport` to an incoming MIDI clock signal.
- Write a 500-word analysis: how does MIDI's 7-bit resolution (0–127) constrain or inspire your design?

---

### Deliverables

- Hosted app
- MIDI map document (200 words undergrad / 500 words grad)
- Process notes

### Critique Criteria

Hardware integration, mapping depth, error handling, sonic/visual coherence
