---
name: awesome-design-md
description: Use a curated DESIGN.md from this repository as a visual reference when implementing a website or UI in the style of a named brand or product. Load the matching design document on demand and apply its tokens, typography, layout, and component guidance.
---

# Awesome DESIGN.md

Use the design references under `design-md/` to guide UI implementation. These are reference documents, not executable code or a substitute for the user's project requirements.

1. Identify the brand or product the user requests. Find its matching directory under `design-md/` (for example, `design-md/figma/`). If the brand is unspecified, ask which reference to use or offer a few relevant choices from the available directories.
2. Read **only** that directory's `DESIGN.md` before implementing. Its palette, typography, layout, components, and responsive guidance are the source for that reference. A neighboring `README.md` may link to an online preview, but it is not the design specification.
3. Apply the selected reference to the user's actual project and framework. Prefer the project's existing structure and accessibility conventions. Adapt the guidance rather than claiming a pixel-perfect reproduction of the original website.
4. If there is no matching `DESIGN.md`, say so rather than inventing a design system or treating another brand as equivalent.

All references are bundled with this skill so they remain available when a skill manager installs the repository as a single skill. Do not copy the entire collection into the user's project unless asked.
