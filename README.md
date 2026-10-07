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

## Brand (v2, Oct 2026)
- Headline (Oct 7): Put AI to work. Build the systems. Get your time back.
- Fonts: Fraunces (headlines) · DM Sans (body) · DM Mono (labels, numbers)
- Colors: Paper #F6F0E6 · Espresso #3A2A1F · Terracotta #B5552F · Olive #5E6B3A · Sand #D9CBB3
- Mark: the 3×3 "found cell" grid with cell 6 lit
- Booking: https://calendly.com/corraoconsulting/30min (set as BOOKING_URL at the bottom of index.html)
- Source of truth: the "GSC Brand Guide" design canvas
- Pages: index.html (homepage), profit-leak-scorecard.html (the 2-minute leak check), privacy.html. The old v1 pages were removed Oct 1, 2026.
