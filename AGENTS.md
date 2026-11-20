# Web guidance — ACE photo/effects gallery only

**Scope:** Work in `gallery/` in this `ace-photo-effects-gallery` branch only. This skill does not apply to the Android MobileClaw app, backend/infra, main Spark Detective, or Alex's DatingDetectorBot.

For HTML, CSS, client-side JS, web animations, image/video preview UI, before/after displays and browser performance:

1. Read `.agents/skills/modern-web-guidance/SKILL.md` before changing UI code.
2. Search → retrieve → apply → verify relevant official Modern Web Guidance, using `npx -y modern-web-guidance@latest` when execution/network is available.
3. Maintain existing behavior, do not rework functioning UI without a concrete request, and handle browser support/fallbacks.

No production deployment, automatic refactor, or edits outside the gallery are authorized by this installation.
