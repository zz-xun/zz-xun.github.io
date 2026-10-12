# 变量studio · Products & Experiments

Live portfolio: https://zz-xun.github.io/

A quiet bilingual portfolio with two independently built products:

- **StaySim Studio:** a reviewable LangGraph workflow for pedestrian simulation, run locally. Source: https://github.com/zz-xun/staysim-agent
- **Dilemma Arena / 纠结擂台:** a browser-based interactive decision game. Play: https://zz-xun.github.io/dilemma-arena/

The page includes animated project and language switches, restrained scroll reveals, and an accessible full-image viewer. Reduced-motion preferences are respected. Visible branding is 变量studio; GitHub account and repository URLs retain the actual `zz-xun` username.

## Screenshots

`assets/staysim-studio-full.png` is an uncropped full-page browser capture of the existing local StaySim Studio application, using a real offline rule-mode demo and loaded results. It replaces the old cropped `studio-preview.png`. This capture is presentation material, not evidence of LLM accuracy or a hosted Agent service.

`assets/dilemma-arena-full.png` is captured from the existing local production build of Dilemma Arena, replacing the previous illustrated mockup. The portfolio and viewer display its central upper content in a compact frame, omitting the empty background below and beside the form.

## Development and publishing

No dependencies or build step: serve this directory with a static HTTP server. GitHub Pages publishes the root of `main`. Commit `index.html`, `README.md`, and `assets/` together.
