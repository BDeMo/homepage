# Homepage project guidance

## Purpose

This repository contains Mingjia (Samuel Jayden) Shi's academic homepage. Keep
the site concise, professional, current, and personable.

## Current research positioning

- The primary research focus is **Efficient AI**.
- Relevant background and collaboration themes include efficient training and
  inference, model and data efficiency, multimodal learning, AI-native
  efficiency, optimization, generalization, and systems-aware AI.
- Do not describe the author as "exploring research directions"; that was an
  earlier stage.
- Do not maintain a "Works in hands" list for the previously listed directions;
  those works have been published.
- Keep the invitation for research collaborations and joint proposals.

## Editorial conventions

- Use polished, natural American English rather than literal translations.
- Prefer direct academic language, while retaining a small amount of the
  author's informal personality.
- Avoid inflated claims, unnecessary jargon, and vague phrases such as
  "resource preserving and ...".
- Use **Efficient AI** consistently as the umbrella term.
- Use **multimodal** as one word and **AI-native** with a hyphen.
- In reviewer-service lists, prioritize conferences covered by CSRankings, then
  list other conferences and journals separately. Preserve ACL Rolling Review
  (ARR) service and mention ACL, EMNLP, and NAACL as representative ARR venues.

## Visual direction

- Use a premium, minimalist technology aesthetic: deep navy surfaces, restrained
  cyan accents, subtle gradients, fine borders, and generous spacing.
- Keep visual effects quiet and functional. Avoid loud neon colors, excessive
  animation, dense decoration, and anything that reduces academic readability.
- Preserve responsive behavior, accessible contrast, reduced-motion support,
  and the existing Jekyll content structure.
- Put site-specific visual overrides in `_sass/_custom.scss`; avoid editing the
  upstream theme structure unless necessary.

## News maintenance

- News from December 2024 or earlier should remain in `_pages/about.md` for
  provenance but must be hidden from the rendered page with HTML comments.
- New news should be placed above older entries in reverse chronological order.
- Keep News entries in regular weight; do not bold paper titles or venues there.
- Do not delete historical news unless explicitly requested.

## Homepage utilities

- Keep the footer RSS/Feed link hidden unless explicitly requested again.

## Verification

- After editing, inspect the rendered homepage or run the Jekyll build when the
  local toolchain is available.
- Check links, Markdown/HTML comment boundaries, headings, and the mobile-facing
  sidebar biography.
