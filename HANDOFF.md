# HANDOFF: ROMEL Mobile Command Gate

Approved prototype for Tom to productionize. Keep the UX identical, integrate core state handling/API routing under the hood.

## Assets & Specs
- **Live Interactive Reference:** https://ry12n.github.io/romel-agent-mobile/
- **Stitch Project ID:** `270406492680683525`
- **Aesthetic:** Strictly Hard-Edge Industrial (0px radius, no shadows, no gradients, tonal layering only).
- **Core Theme Shades:** Base `#080C12`, Surface `#0D1117`, Borders `#1F2937`, Accent `#3D8EF0` (steel blue).

## Screen Inventory
1. **Screen 1: Passcode Verification Gate**
   - Flow: System locks on reload/wake. Entering passcode `2026` / `0000` (bypass) triggers sound cues and grants access.
2. **Screen 2: Terminal Console & Dynamic Waveform**
   - Flow: Live multi-vector canvas represents signal frequency. Scrolling logs populate with system updates. Command entry handles `/help`, `/status`, `/clear`, `/nodes`, `/time`. Scrollable node selector at bottom.
3. **Screen 3: Node Specifications (Agent Detail)**
   - Flow: Shows selected agent profiles, latency metrics, clearance levels, and security handshake triggers.
4. **Screen 4: Cluster Settings**
   - Flow: Functional toggles for system clicks, audio feedback, and high-fidelity rendering.
