# QueryLogic — AI Website Architect & Auditor

Audit any website across 5 dimensions and get AI-written code fixes in under 30 seconds.

Live: **https://theodorluke1-debug.github.io/QueryLogic/**

---

## What it does

QueryLogic performs a forensic audit of any website and generates the exact code fix for every issue it finds. No technical background required.

- Paste a URL, drop an HTML file, or paste raw source code
- AI analyzes 5 critical dimensions: SEO, UX, Accessibility, Performance, Conversion Psychology
- Every issue gets a prioritized severity rating (Critical / High / Medium / Info)
- One click generates a copy-paste-ready code fix for each problem
- Your HTML never leaves your browser — only the audit prompt is sent to Gemini

---

## Audit dimensions

| Dimension | What gets analyzed |
|---|---|
| **SEO & Findability** | Meta tags, heading structure, keyword density, Open Graph, canonical URLs |
| **User Experience** | Layout logic, CTA placement, navigation clarity, reading flow |
| **Accessibility (A11y)** | WCAG compliance, contrast ratios, ARIA labels, alt texts, keyboard navigation |
| **Performance** | Estimated load time, render-blocking resources, inline scripts, image handling |
| **Conversion Psychology** | Trust signals, social proof, urgency cues, cognitive load |

---

## How to use

1. Open the app at **https://theodorluke1-debug.github.io/QueryLogic/app.html**
2. Get a free Gemini API key at [aistudio.google.com](https://aistudio.google.com/app/apikey) — takes 30 seconds
3. Enter a URL, upload an HTML file, or paste source code
4. Click **Run Deep Audit**
5. Review the scored report and click **Generate code fix** on any issue
6. Copy the fix and apply it to your codebase

---

## Tech stack

- Vanilla JavaScript (no frameworks)
- Gemini API (free tier — `gemini-1.5-flash`)
- Google Fonts (DM Serif Display, Inter, JetBrains Mono)

---

## Built by

A 15-year-old developer.
