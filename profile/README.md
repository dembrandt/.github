![Banner](dembrandt-og.png)

## Extract Design Systems In Seconds

One command extracts any site's full design system instantly.
Perfect for audits, competitor research, and documentation.

---

## Tools

### [Dembrandt CLI](https://github.com/dembrandt/dembrandt)

Extract any website's design system into design tokens: logo, colors, typography, spacing, borders, shadows, and more.

```bash
npx dembrandt stripe.com
```

**NEW** - W3C Design Tokens (DTCG) format export with `--dtcg`

**Install:**
```bash
npm install -g dembrandt
dembrandt bmw.de --save-output --dtcg
```

**Flags:** `--dark-mode` • `--mobile` • `--slow` • `--debug`
**Requires:** Node.js 18+

### [DTCG Validator](https://github.com/dembrandt/dtcg-validator)

Web-based validator for W3C Design Tokens Community Group format.
Real-time validation with support for all 13 token types, references, and circular detection.

[**Try it live →**](https://dembrandt.github.io/dtcg-validator/)

---

## How it all started

Over my 15 year design career, I've spent countless hours manually inspecting websites with DevTools: **1-3 hours per brand** plus additional sites to benchmark.

Designers struggle to dissect brands from websites—it's not just about extracting colors (that's the easy part). **The real challenge is understanding what truly matters in a brand system.** Developers also feel the pain when designs lack proper color values.

Dembrandt saves me hours every week. Just dissect the brand with 1 command and use the design tokens in your preferred design systems.

---

## What's Next

Upcoming features and enhancements:

- **Multi-page Analysis** — Extract design systems across multiple pages
- **Accessibility Audit** — Automated WCAG compliance scoring
- **Figma Integration** — Export design tokens directly to Figma
- **Browser Extension** — Extract on-the-fly while browsing
- **Gradient Analysis** — Detect complex gradient patterns
- **Tone of Voice** — Analyze brand voice and messaging patterns

[**Participate in development →**](https://github.com/dembrandt/dembrandt/discussions)
