# Kishore & Nivethitha — Wedding Website

A complete responsive single-page wedding invitation inspired by the clean structure of the reference wedding site, with an original South Indian plum/champagne/ivory visual theme.

## Included
- Hero invitation
- Live countdown to 11 Nov 2026, 4:30 AM IST
- Wedding + reception details
- Google Maps buttons
- RSVP form with WhatsApp integration
- Responsive mobile layout
- Scroll animations

## Customize
### 1. RSVP WhatsApp
Open `script.js` and set:
```js
const RSVP_PHONE = '91XXXXXXXXXX';
```
Use digits only, including the country code.

### 2. Deploy on Vercel
This is a static site and needs no backend.
- Upload the folder to a GitHub repository.
- Import the repository into Vercel.
- Framework preset: Other / Static.
- Build command: leave blank.
- Output directory: `.`

You can also deploy the folder using Vercel CLI.

## Notes
The wedding venue links use Google Maps search URLs rather than a hard-coded pin, so they remain useful even if the exact map listing changes.
