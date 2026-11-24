### CODEX PROMPT #1 — SEO & PERFORMANCE AUDIT

Review this Next.js photography website for SEO and performance issues.
Current mobile Lighthouse results:
- Performance: 98
- Accessibility: 100
- Best Practices: 100
- SEO: 100
Performance metrics:
- First Contentful Paint: 1.1 s
- Largest Contentful Paint: 3.2 s
- Total Blocking Time: 370 ms
- Cumulative Layout Shift: 0
- Speed Index: 1.3 s
Lighthouse findings:
- Improve image delivery: estimated savings 1,092 KiB
- Reduce unused JavaScript: 59 KiB
- Minimize main-thread work: 2.4 s
- Four long main-thread tasks
Also review:
- Page titles and meta descriptions
- Heading structure
- Semantic HTML
- Image alt text
- Canonical URLs
- Internal links
- Sitemap
- Robots.txt
Do not modify any files yet.
Identify the most important issues,
explain why they matter,
and recommend safe improvements.
Preserve the existing design and functionality.

### CODEX PROMPT #2 — IMPLEMENT IMPROVEMENTS

Implement the safe SEO and performance improvements
identified in the audit.
Priorities:
1. Optimize image delivery using Next.js best practices.
2. Improve Largest Contentful Paint where possible.
3. Reduce unnecessary JavaScript and main-thread work.
4. Verify page titles and meta descriptions.
5. Check heading hierarchy and semantic HTML.
6. Improve image alt text where appropriate.
7. Verify canonical URLs.
8. Check internal links.
9. Create or update sitemap.xml and robots.txt
   using the actual production domain and real routes.

Important requirements:
- Preserve the existing visual design.
- Preserve the interactive photo gallery.
- Preserve the contact form.
- Do not remove features.
- Do not significantly reduce image quality.
- Do not invent SEO content or new pages.
- Do not make unrelated changes.

After implementation:
- Show which files changed.
- Run the available build and lint checks.
- Explain the improvements.
- Report any remaining issues.
