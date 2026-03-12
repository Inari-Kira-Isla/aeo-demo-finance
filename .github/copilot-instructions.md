# aeo-demo-finance

## Project
Finance industry AEO (AI Engine Optimization) demo template using HTML with Schema.org, llms.txt, FAQ, and AI-friendly markup.

## Conventions
- Use semantic HTML5 elements (header, main, footer, article, section)
- Include Schema.org JSON-LD in `<script type="application/ld+json">` tags
- Keep llms.txt with clear section headings
- Place FAQ in proper list structure
- Use lowercase filenames with hyphens

## Naming
- Use descriptive, lowercase filenames with hyphens (e.g., my-page.html)
- Schema.org types: proper capitalization (e.g., Organization, FAQPage)
- CSS classes: semantic naming (e.g., .faq-item, .schema-data)

## Architecture
- Single-page HTML template
- Inline CSS in `<style>` tag for portability
- Schema.org structured data embedded in HTML
- llms.txt at root level for AI crawling
- FAQ section using `<dl>`, `<dt>`, `<dd>` or `<details>`/`<summary>`

## Commands
- No build commands required (pure HTML)
- Deploy to Vercel or any static hosting provider

## Do Not
- Avoid JavaScript unless absolutely necessary
- Do not use non-semantic div soup
- Do not add unnecessary frameworks or libraries
- Do not omit Schema.org structured data
- Do not use unclear or generic class names