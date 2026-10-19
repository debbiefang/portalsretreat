# Portals waitlist page — template

This branch is the Portals waitlist landing page exactly as it ran on
portals.theheartbased.co until 18 October 2026, when that domain was
redirected to portalsretreat.com. The tag `waitlist-site-2026-10-18`
points at the same version, untouched.

Use it as the starting point for a future waitlist page.

## What's here

- `index.html` — the whole page (inline CSS and JS). Its waitlist forms post
  to the Waitlist Apps Script.
- `application.html` — the application form, served at `/application`.
- `_redirects` — the single rule that serves `/application`.
- `robots.txt`, `sitemap.xml`, `llms.txt` — SEO and AI files.

## Before reusing it

1. Replace every `portals.theheartbased.co` with the new domain (canonical
   tag, Open Graph tags, JSON-LD, robots.txt, sitemap.xml, llms.txt).
2. Update the dates, prices, rooms and facilitators.
3. Check the waitlist and application forms still post to live Apps Script URLs.
4. Don't deploy it to a domain that duplicates portalsretreat.com, or the two
   will compete in search.

Do not merge this branch into `main`: `main` holds the redirect.
