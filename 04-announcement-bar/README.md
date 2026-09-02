# 04 - Announcement Bar

Rotating announcement bar at the top of the page. Messages are read from a metafield list when available; otherwise a fallback array is used.

Usage
- Copy `snippet.liquid` into your theme (e.g., include at the top of `layout/theme.liquid`).

Customization
- Messages source: ``
- Rotation speed is controlled in `snippet.liquid` setInterval (4000ms).

Accessibility
- Respects `prefers-reduced-motion` and falls back to a static announcement.

Demo
- demo.gif placeholder pending — please record and add `demo.gif` in this folder.
