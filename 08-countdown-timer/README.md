# 08 - Countdown Timer

Configurable countdown that displays days/hours/minutes/seconds until a target ISO datetime. The target is set via the section schema `end_date` setting.

Usage
- Add `snippet.liquid` as a section in your theme (copy into `sections/` if you want theme-editor configurability) so the `end_date` setting is available.

Customization
- Set the `end_date` in the section settings using ISO 8601 format (e.g. `2026-12-31T23:59:59Z`).

Behavior
- Timer updates client-side via `setInterval`. When target time passes the element hides itself.

Demo
- demo.gif placeholder pending — please record and add `demo.gif` in this folder.
