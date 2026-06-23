# Design Spec — ROMEL Mobile Command Waveform V1

## Layout Metrics
- Ground Color: `#080C12` (Deep navy-black)
- Panel Surface: `#0D1117`
- Raised Elements: `#131922`
- Accent: `#3D8EF0` (Steel blue)
- Accent Dim: `#1E4A8A`
- Radius: `0px` (Strictly zero)
- Base Text Size: `13px`
- Metadata Labels: `10px` monospace uppercase tracking (+0.12em).

## Key Components
1. **Security Gate (Pre-auth):** Solid backdrop, high-contrast monospace code entry with localized keypad triggers.
2. **Dynamic Waveform Console:** Responsive, central active signal visualizer using WebGL or HTML5 2D Canvas.
3. **Agent Slate:** Compact inline scroll or small 2x4 grid grid of active agent slots with status indicators.
4. **Interactive Prompt:** Monospace input bar pinned to viewport bottom with terminal send button.
