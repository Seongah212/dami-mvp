# DAMI — Busan K-Beauty Gift Kits (Demo MVP)

An English-language, mobile-first prototype for a startup competition. **Demo only: it does not charge customers, take payments, reserve real inventory, or operate a pickup location.**

## Features

- Home: cruise ship and Busan arrival date selection
- Gift Kits: Discovery ₩14,900, Daily ₩24,900, Premium ₩34,900; quantity steppers and total price
- Gift Planner: budget- and recipient-based kit recommendations
- My Order: cart summary and simulated order placement
- Pickup: mock pickup information, demo order ID and clearly marked non-redeemable QR code
- Local browser storage for demo state

## Run locally

Open `index.html` in a web browser. No install, account, server, or npm required.

## Deploy via GitHub + Vercel

1. Create a GitHub repository, for example `dami-mvp`.
2. Upload `index.html`, `README.md`, and the `assets` folder. Keep the file names and structure unchanged.
3. Go to https://vercel.com/new and sign in with GitHub.
4. Import `dami-mvp`, choose **Framework Preset: Other**, leave build command empty, and click **Deploy**.
5. Check the deployed page on mobile. Copy the Production URL and repository URL for the competition entry.

Alternative: https://app.netlify.com/drop (drag the **unzipped** `dami-mvp` folder). Note that Netlify Drop creates a deployment but does **not** automatically create a GitHub repository.

## Notes before real customer use

- Add a secure backend and genuine order persistence (localStorage is per-device only).
- Integrate a verified payment provider and deploy only after payment and privacy compliance review.
- Confirm authorization and accurate pickup location, times, cruise schedules and inventory.
- Replace demo artwork and product descriptions with cleared licensed product materials and real brand sourcing data.
- Use actual QR codes linked to the order database, with one-time redemption and access controls.

Visual mockup imagery used from the DAMI design concepts supplied in the ChatGPT conversation. This code and design are a prototype, not a launched service.
