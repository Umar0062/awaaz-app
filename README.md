# 🌱 Awaaz App

**Your Voice for a Greener, Healthier Community**

Awaaz turns isolated tree-plantation efforts into organized, trackable and verifiable community activities. Volunteers join plantation drives, check in on site with GPS, upload photo evidence and receive a certificate that anyone can verify online.

🔗 **Live demo:** https://YOUR-LINK.vercel.app

Built for the Social Entrepreneurship Program at Superior University.

## Features

- **Three user levels:** Volunteer, Organization and Administrator, each with its own dashboard
- **Plantation sites and activities** with search, filters and an interactive SVG map
- **Registration** for individuals or groups, with capacity and deadline checks
- **GPS check-in** on site (configurable radius) and **photo evidence** upload
- **Verifiable certificates** with a unique number (`AWZ-XXXXXX`) and a public Verify page
- **Admin tools:** approvals, user suspension, certificate revocation, awareness content and an audit log
- **Volunteer levels** (Seedling, Sapling, Young Tree, Forest Guardian) and a leaderboard
- **English and Urdu** (right-to-left), light and dark mode, responsive design
- Google Calendar and WhatsApp sharing for every activity

## How it works

1. An organization registers and an administrator verifies it.
2. The organization submits plantation sites and creates activities, which the administrator approves.
3. Volunteers register for an activity and check in with GPS on the day.
4. Volunteers upload a photo of their planting.
5. The organizer reviews the photo, confirms attendance and issues a certificate.
6. Anyone can verify the certificate on the Verify page.

## Demo accounts

| Role | Email | Password |
|---|---|---|
| Volunteer | vol@awaaz.pk | vol123 |
| Organization | org@greenlahore.pk | org123 |
| Administrator | admin@awaaz.pk | admin123 |

## Tech stack

- React 18 and htm (loaded from a CDN, no build step)
- Plain CSS with custom properties
- Browser `localStorage` for data and Geolocation API for check-in
- Hosted on Vercel as a static site

## Run locally

No installation needed. Download `index.html` and open it in a browser.

## Limitations

This is a demo version. All data is stored in the user's own browser, so it is not shared between devices. A real backend and database (for example Supabase or Firebase) would be needed for production use.

## Future work

- Real backend, database and secure authentication
- Cloud photo storage
- Email and SMS notifications
- Reports and analytics (trees planted, volunteer hours)

## Author

Umar, Superior University
