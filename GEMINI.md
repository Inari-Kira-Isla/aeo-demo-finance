# aeo-demo-finance

## Overview
AEO (Answer Engine Optimization) demo template tailored for the finance industry. It demonstrates how to structure financial content using semantic HTML, JSON-LD (Schema.org), and `llms.txt` to ensure maximum compatibility and visibility with AI agents and LLMs.

## Tech Stack
- **Core:** HTML5
- **Structured Data:** JSON-LD (Schema.org for Finance)
- **AI Optimization:** `llms.txt`
- **Deployment:** Vercel

## Architecture
- `index.html`: Main landing page containing semantic content, FAQs, and embedded Schema.org data.
- `llms.txt`: A dedicated text file describing the site structure for Large Language Models.
- **Schema Focus:** Utilizes `FinancialProduct`, `FAQPage`, and `BreadcrumbList` schemas.

## Commands
- **Development:** Open `index.html` in a browser or use a static server (e.g., `npx serve`).
- **Deployment:** Connect repository to Vercel for automatic deployment on push.
- **Local Test:** Use `vercel dev` if utilizing any server-side generation.

## Coding Style
- Strict semantic HTML5 markup is required.
- All financial data must be represented in valid JSON-LD.
- Content should be concise and structured (headings, lists) to aid AI parsing.
- Ensure high accessibility (WCAG) standards.

## Important Rules
- **Mandatory SEO:** Do not remove or minify the JSON-LD scripts; they are the core of this demo.
- **Content Integrity:** Financial disclaimers and data must be accurate.
- **AI Accessibility:** Avoid blocking crawlers in `robots.txt` if `llms.txt` is to be utilized.