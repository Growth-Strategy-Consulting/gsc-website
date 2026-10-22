# Growth Strategy Consulting — Website

Static site for growthstrategyconsulting.org. Plain HTML/CSS, no build step.

## Files
- `index.html` — the homepage (v2, Oct 2026: one-page landing, Growth Audit from $997, Calendly booking)
- `assets/` — images, logos (swap the placeholder photos here)

## Local preview
Just open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy
Hosted on **Netlify** (free tier). Connected to this GitHub repo —
every push to `main` auto-deploys.

## Tracking & SEO (added Oct 22, 2026)
- Google Analytics 4: Measurement ID `G-XZYD2TFHSL` (account "Growth Strategy Consulting" on corraoconsulting@gmail.com). The Google tag sits right after `<head>` on every page. Any new page needs the same snippet.
- Google Search Console: property for https://growthstrategyconsulting.org/ (same Google login).
- `sitemap.xml` lists the public pages (the checklist is noindex, so it's left out). Add new pages there. `robots.txt` points to it.

## Brand (v2, Oct 2026)
- Headline (Oct 7): Put AI to work. Build the systems. Get your time back.
- Fonts: Fraunces (headlines) · DM Sans (body) · DM Mono (labels, numbers)
- Colors: Paper #F6F0E6 · Espresso #3A2A1F · Terracotta #B5552F · Olive #5E6B3A · Sand #D9CBB3
- Mark: the 3×3 "found cell" grid with cell 6 lit
- Booking: https://calendly.com/corraoconsulting/30min (set as BOOKING_URL at the bottom of index.html)
- Source of truth: the "GSC Brand Guide" design canvas
- Pages: index.html (homepage, with the "Where does most of your week go?" quiz), ai-time-back-checklist.html (the free checklist the quiz gives away; quiz signups go to the same HubSpot form as the leak check), profit-leak-scorecard.html (the 2-minute leak check), put-claude-to-work.html (free Claude guide for owners; email-gated, signups go to MailerLite form 200792049752999189; Calendly embedded at the bottom), privacy.html. The old v1 pages were removed Oct 1, 2026.
