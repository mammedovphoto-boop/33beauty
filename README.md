# 33 Beauty Centre — website

Premium one-page site for 33 Beauty Centre, a ladies-only villa salon on Al Wasl Road, Jumeirah 1, Dubai.
English and Arabic (RTL), motion design with GSAP, and a booking quiz that sends a ready request to WhatsApp.

## Run locally
Open `index.html` through any static server, e.g. `npx serve .`

## Publish with GitHub Pages
Settings → Pages → Branch: `main`, folder `/ (root)`.

## Settings
All editable settings are in the `CONFIG` block at the top of the script in `index.html`:
- `whatsapp` — salon number, digits only
- `ga4` / `metaPixel` — analytics IDs (add the official tracking snippets to `<head>` as well)
- `messages` — WhatsApp texts in English and Arabic

## Ad links
Add parameters to the site address for each ad:
`?utm_source=meta&utm_campaign=blonde-ar&utm_content=reel1&lang=ar`
The source is remembered during the visit and added to every WhatsApp message as `[ref: …]`,
together with the button the guest used. `lang=ar` opens the Arabic version.

A WhatsApp click is a booking intent, not a confirmed booking.

## Images
Real photos: villa, rooms, Omran, before/after. Atmosphere images (lattice light, hammam still life, hands, hair) are AI-generated
and marked on the site as illustrative. Replace them with the salon's own photos and videos when available.
