# Technical Spec — ROMEL Mobile Command Waveform

## 1. System Topology
The application is a standalone, client-side mobile web app designed to act as a simulated secure satellite link to the ROMEL agent cluster.

## 2. Key Modules
- **Haptic Sound Synthesizer (Web Audio API):** Generates sine-wave click bleeps and multi-frequency sweep hums when keys are pressed or agents are toggled.
- **Dynamic Waveform Canvas:** A canvas-based render loop rendering a triple-superimposed sine wave. Modulates frequency, amplitude, and noise when the user types, clicks, or toggles state.
- **Agent Switcher Grid:** Responsive grid of available agents matching `romel-brand.md` metadata roles. Switching agents triggers custom system handshake log entries and updates the wave signature.
- **Simulated Console Protocol:** Command line dispatch input that parses commands like `/help`, `/clear`, `/status`, `/agent <name>`, or direct message text, returning real-time simulated responses.

## 3. Dimensions and Layout
- Outer frame optimized for mobile touch heights (44px min touch target size).
- Zero border radius on all buttons, panels, and frames.
- Colors matching ROMEL cold enterprise specification.
