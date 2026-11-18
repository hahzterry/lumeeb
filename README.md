# LIVEBOOK — Influencer Livestream Booking Website

A mobile-responsive React + Vite + TypeScript redesign of the supplied art-tour website into a livestream talent booking website.

## Run locally

```bash
npm install
npm run dev
```

## Deploy to Vercel

Import the repository into Vercel. Framework: **Vite**. Build: `npm run build`. Output: `dist`. Set `VITE_BOOKING_EMAIL` to your real inbox and redeploy.

## Included

- Landing page, creator directory, search/filter, brand information, process page, creator application and booking inquiry forms.
- Preselected creator in booking inquiry URLs, e.g. `/book?creator=nova`.
- Booking and application forms open the visitor's email client with a prefilled message; they **do not** save or send submissions automatically.
- Mobile navigation and responsive design.
- Old tour-related public routes redirect at the UI level to relevant new pages.

## Before launch

1. **Replace all six demo creators.** Names, rates, audience counts and portraits are fictional/illustrative. Edit `creators` in `src/App.tsx`. Get permission to use real creators' names and images.
2. Set `VITE_BOOKING_EMAIL` in Vercel to your actual email address. The example default is not a working inbox.
3. If you want in-app submissions, scheduling, payment, creator logins, or automatic confirmations, implement and secure backend services. None are represented as operational here.
4. Replace third-party Unsplash demo images with approved assets.
5. Remove or migrate unused legacy art-tour pages and Supabase assets if you do not need them.

## Notes

This is a fully updated public-facing frontend, not a completed multi-vendor marketplace. No payment, live availability or booking confirmation is implied.
