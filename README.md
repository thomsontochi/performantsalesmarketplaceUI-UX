# PromptEdit — Sales Page Redesign

A performant, production-quality sales page redesign for [PromptEdit.com](https://promptedit.com), submitted as part of the Front End Developer application at ContentCreator.com.

## Live Demo

[View live on Netlify →](https://your-netlify-url.netlify.app)

## Brief

Redesign the existing PromptEdit marketplace sales page to be more intuitive, visually compelling, and conversion-focused — inspired by the design quality of Epidemic Sound, Motion Array, Artlist, Higgsfield, and Envato Elements.

## Design Decisions

- **Warm editorial aesthetic** — parchment background (`#f2efe8`) over dark, inspired by Epidemic Sound's approachable tone and Artlist's premium feel
- **Instrument Serif + Inter + JetBrains Mono** — display, body, and label type pairing for editorial depth
- **Section labels with dot prefix** — `01 — Marketplace`, `02 — Why sell here` — gives the page a structured, magazine-quality hierarchy
- **Diagonal lime tape accent** — used sparingly on the hero headline for visual punctuation without noise
- **Corner dot frames** on testimonial cards — small typographic detail that signals intentional design craft
- **Striped placeholder backgrounds** — diagonal texture for asset preview areas, avoids generic grey boxes
- **Asymmetric 12-column grid** — content never centred generically, varies between full-width and offset layouts
- **Native `<details>` FAQ** — no JS dependency, fully accessible, lightweight
- **No reveal-on-scroll animations** — removed entirely to prevent sections hiding on slow connections or file:// loads
- **Full pricing section** — three tiers with a featured dark card, designed to convert

## Tech Stack

- **Tailwind CSS** via CDN — utility-first, no build step, demonstrates inline design thinking
- **Vanilla JS** — marquee cloning, smooth scroll, FAQ toggle only. No frameworks.
- **Google Fonts** — Instrument Serif, Inter, JetBrains Mono
- Pure HTML, no dependencies

## Skills Demonstrated

- Design system thinking with CSS variables
- Typography pairing and editorial layout
- Conversion-focused copywriting and CTA hierarchy
- Responsive layout without a framework
- Tailwind utility class fluency
- Accessibility-first component choices

## Author

**Austin Opia** — Senior Laravel & PHP Engineer, Frontend Lead  
[austinopia.aidevelopia.com](https://austinopia.aidevelopia.com) · [linkedin.com/in/developia](https://linkedin.com/in/developia) · [github.com/thomsontochi](https://github.com/thomsontochi)
