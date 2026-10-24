# Make Fetch Happen app

A mobile web app for [Make Fetch Happen Dog Training](https://www.makefetchhappen.co.uk), South Manchester.

Live: https://scottwilkins02.github.io/make-fetch-happen-app/

## Features
- **Booking requests** sent to Janey by WhatsApp
- **Progress** for each client's dog: XP and 8 levels, streaks with a weekly rest day, weekly goal ring, daily challenge, skill mastery (Bronze 5 / Silver 15 / Gold 30 days), puppy socialisation checklist, 24 badges, confetti celebrations and a shareable progress card
- **QR codes**: scan flyers, homework cards and trainer sign-off cards; generate branded codes
- **Trainer tools** (PIN in `index.html`, `TRAINER_PIN`): make homework and sign-off cards
- Installable to the Home Screen (manifest, icons, offline service worker)

Progress is stored on each client's own phone (localStorage). Clearing browser data clears it.

Single static site, no build step. Hosted on GitHub Pages.
