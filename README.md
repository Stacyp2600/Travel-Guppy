# 🐟 Travel Guppy

**Little Fish. Big Adventures.**

> Save places from Instagram & Pinterest · Plan multi-country trips with AI · Find the right card to fund it all — free forever.

---

## What it is

Travel Guppy is a single-file travel planning app built for the traveler who saves amazing places from social media and then never does anything with them.

It bridges the gap between **travel inspiration** (Instagram, TikTok, Pinterest) and **actual trip planning** — with an AI itinerary builder, multi-country trip legs, credit card affiliate monetization, and a 🐟 fish rating system baked in.

No app store. No backend. No login required. Just open the HTML file and go.

---

## Features

### 🏠 Dashboard
- Unified view of all saved places across every board
- Priority flags: Must Do / Could Be Fun / Backup / Done
- 5-fish rating system (🐟🐟🐟🐟🐟) for post-visit reviews
- Pull any saved place directly into your active trip

### 📋 Boards
- Pinterest-style boards for saving places from Instagram, TikTok, Pinterest, Facebook
- Photo mosaic covers, category tags, source badges
- "Add to Trip →" flow from any board

### 🌍 Multi-leg Trip Planning
- Structure trips as legs: e.g. 🇵🇹 Lisbon → 🇲🇦 Marrakesh → 🇫🇷 Paris
- Each leg has its own city, country, dates, and color
- Pill tab navigation between legs — Places, Calendar, Budget, Country info all filter per leg
- Add/remove legs at any time

### ✨ AI Planner
- Generates day-by-day itineraries across all legs
- Style selectors: Relaxed / Packed / Mixed
- Focus areas: Food, Culture, Adventure, Hidden Gems, Nightlife
- One-tap "Add all to trip"

### 💰 Budget & Expenses
- Per-leg budget tracking with visual progress bars
- Real-time forecast vs actual
- Expense splitting across travelers
- Credit card rewards optimizer

### 💳 Credit Card Monetization
- 9 travel, hotel, and airline cards with affiliate links
- Signup bonus matching, rewards rate calculator, 0% APR financing tool
- Card nudges at every booking touchpoint

### 🗂 Full Trip Tabs
Calendar · Places · Flights & Transport · Budget · Cards · Country Info · Expenses · Documents · Packing · Journal · Collaborators

---

## Getting started

```bash
# Clone the repo
git clone https://github.com/YOURUSERNAME/travel-guppy.git

# Open directly in browser — no build step needed
open index.html
```

Or visit the live demo: **[yourusername.github.io/travel-guppy](https://yourusername.github.io/travel-guppy)**

---

## Tech stack

| Layer | Choice |
|---|---|
| Framework | React 18 (via CDN, no build step) |
| Styling | Custom CSS with CSS variables |
| AI | Anthropic Claude API (`/api/claude` proxy) |
| Persistence | localStorage (v4) |
| Deployment | Single HTML file — Vercel / GitHub Pages |

No npm. No webpack. No database. The entire app is one 240KB HTML file.

---

## Monetization model

Travel Guppy is free for users. Revenue comes from:

1. **Credit card affiliates** — $100–$400 per approved application via CJ Affiliate, Impact.com, Bankrate
2. **Hotel bookings** — Booking.com affiliate (25–40% commission)
3. **Activities** — Viator affiliate (8% commission)
4. **Travel insurance** — SafetyWing (10% commission)

---

## Roadmap

- [ ] Supabase backend for real persistence and user accounts
- [ ] Chrome extension — one-click save from Instagram/TikTok
- [ ] Instagram DM integration — DM a post to @travelguppy, it auto-saves to your board
- [ ] Google Places API integration for enriched place data
- [ ] Social recommendations — "travelers like you also visited…"
- [ ] Native iOS/Android app

---

## ICP

**The Intentional Explorer** — takes 3–5 trips per year, saves places from Instagram but never organizes them, interested in boutique hotels, food, culture, and adventure. Age 25–55. Has disposable income but hasn't optimized credit card rewards yet.

---

## Affiliate setup

Replace placeholder URLs in the `AFFILIATE_URLS` object at the top of `index.html`:

```js
const AFFILIATE_URLS = {
  "chase-sapphire-preferred": "https://creditcards.chase.com/...",
  "amex-gold": "https://americanexpress.com/...",
  // etc.
};
```

Register with:
- **Chase / Amex** → CJ Affiliate (cj.com)
- **Capital One** → Impact.com
- **Citi / Wells Fargo** → Bankrate or FlexOffers
- **Booking.com** → partners.booking.com
- **Viator** → partnerize.com
- **SafetyWing** → safetywing.com/affiliate

---

## Feedback

This is an early-stage product actively looking for user feedback. If you try it:

- What did you use first?
- What confused you?
- What's the one feature that would make you use it every trip?

Open an issue or reach out directly.

---

## License

MIT — use it, fork it, build on it.

---

*Built with ☕ and Claude.*
