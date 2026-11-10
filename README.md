# I-WORKS v4.3 — Deep Audit & Responsive Fix

Static website, no build step. Unzip the package into the website repository root (where index.html is located).

## Audited and corrected
- Mobile grid sizing and viewport overflow, including 320px Android devices.
- 701–900px navigation collision: hamburger menu now appears before links become cramped.
- Phone and telemetry flex sizing; small-camera labels and long text wrapping.
- Mobile tap targets and small-screen dashboard readability.
- Simulation log translations (EN/MK/SQ/RU), escape-to-close navigation, click-outside menu.
- localStorage access gracefully handled when unavailable.
- Accessibility labels for demo visualizations and menu.

## Remaining limitations
- No physical-device/browser automation run; test in Android Chrome, iOS Safari, and desktop.
- Static demo illustrations are not live systems; StellarECC phone UI is an illustrative source-based reconstruction, not an app screenshot.
- Some decorative and static dashboard labels remain in English; a complete localization pass is still needed.
- No analytics, server backend, or real contact form; content is static.

## Preview
`python -m http.server 8084 --bind 127.0.0.1`
