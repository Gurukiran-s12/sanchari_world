# Sanchari World — full responsive travel website

## Run it
1. Extract the ZIP.
2. Open `index.html` in a browser, or use VS Code Live Server.
3. Keep `style.css`, `script.js`, and the `assets` folder next to `index.html`.

## Included interactions
- Responsive sticky navigation and mobile menu
- Destination cards with previous/next cycling
- Trip search bar that pre-fills the enquiry form
- Vehicle cards that play local MP4 previews on hover/focus, with animated image fallback
- Vehicle/package booking dialog
- Package category filters and favourite save buttons
- Enquiry form validation that opens a prefilled email draft
- Newsletter demo signup stored in browser localStorage
- WhatsApp contact shortcut

## Add vehicle hover videos
Place your own licensed MP4 files here (16:9 works best):
- `assets/videos/sedan.mp4`
- `assets/videos/suv.mp4`
- `assets/videos/tempo-traveller.mp4`
- `assets/videos/luxury-bus.mp4`

The matching video tags are already connected. Videos play muted on hover/focus; if a clip is missing, the vehicle photo remains visible. For reliable publishing, use your own vehicle footage or licensed stock footage.

## Before publishing
- In `script.js`, change `BUSINESS_EMAIL` and `WHATSAPP_NUMBER` to your real business contacts.
- Replace sample prices, phone number, ratings and package details with verified information.
- The form is a front-end demo: it opens the visitor's email app and does not send data to a server. To collect enquiries automatically, connect a backend or form service.
- Images load from Unsplash and Google Fonts load online, so an internet connection is needed for those assets. Replace them with local licensed images for production.
