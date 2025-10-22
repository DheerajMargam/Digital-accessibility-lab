
# Low Vision Accessibility Issues

## Overview
Low-vision users may have reduced acuity, color blindness, or low contrast sensitivity. They often zoom to 200%+, use high-contrast modes, or customize colors. Interfaces must remain readable and operable under these conditions.

## Common Barriers (with WCAG refs)
1. **Insufficient color contrast** — WCAG 1.4.3
2. **Color-only meaning** — WCAG 1.4.1
3. **Non-resizable text** — WCAG 1.4.4
4. **Poor focus visibility** — WCAG 2.4.7 / 2.4.13 (2.2)
5. **Reflow/layout breakage at zoom** — WCAG 1.4.10
6. **Low-contrast icons/controls** — WCAG 1.4.11

## How to Test
- Check contrast ratios (target 4.5:1 normal, 3:1 large).
- Zoom page to 200% and verify reflow/readability.
- Toggle OS/browser high-contrast modes.
- Simulate color-vision deficiencies (Chrome DevTools → Rendering).

## Demo
See `../Code-Demos/color-contrast-demo.html` for failing vs passing examples.
