# NIGHTHAWK — Social Intelligence (Educational OSINT)

A static, mobile-friendly dashboard starter. It generates search links for public web indexes, lets the researcher manually record sourced findings, displays a simple evidence map, and exports/prints a report to PDF.

## Run / publish free
**Fastest:** create a GitHub repository, upload `index.html`, `style.css`, `app.js`, and `README.md`; then use GitHub Pages (Repository Settings → Pages → Deploy from branch → main / root). Or import the repository into Vercel as a static site.

No API keys, backend, or database are required for this starter.

## How it works
1. Enter a username and choose “Generate searches”.
2. Open search links. These are public search-engine queries, not guaranteed live account checks.
3. Verify a result manually, copy its public URL and record what the page actually shows.
4. Add findings; the relationship map visualizes recorded source entries, not verified real-world relationships.
5. Use “Export report / print PDF” and choose Save as PDF in the browser print dialog.

## Scope and limitations
- This does not access private accounts, bypass login, obtain hidden email/phone/IP/GPS, or identify an anonymous account owner.
- Search-engine results may be stale, incomplete, or unrelated. Verify every result at its source.
- Similar usernames, profile photos, or writing styles are leads only—not proof that accounts belong to one person.
- Keep notes factual, link each finding to its source, and avoid collecting sensitive personal data.
- The starter stores findings only in the current browser page memory; refreshing clears them. Add an authenticated database only if needed for a legitimate, consent-based class project.
