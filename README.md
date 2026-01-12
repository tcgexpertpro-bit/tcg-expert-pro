TCG EXPERT PRO 

Professional Pokémon Card Verification & Market Research Toolkit

TCG Expert Pro is a premium offline-capable web app designed for Pokémon collectors, flippers, and investors. It provides instant access to certification checks, live & sold price comparisons, cross-check tools, and curated flip-finding utilities — all from one interface.

This project is built as a Progressive Web App (PWA), meaning it can be installed on mobile devices and works offline after the first load.


---

🚀 Live Access

Launcher (Main Entry Point)

/launcher.html

Main Toolkit

/index.html

Bonus Flip Finder

/bonus.html


---

✨ Features

🔍 Certification Verification

Direct PSA certification lookups

Fast access to official cert pages

Offline fallback after first load


📊 Price & Comp Tools

eBay UK (Live + Sold)

eBay Worldwide (Sold)

Vinted UK (Live + Sold)

130Point

PriceCharting

TCGPlayer

Collectr

PokeData

PokeScope

PokéCardValues


⚡ One-Tap Comp Builder

Type a card name once and instantly open all relevant comp sources.

🧠 Watchlist

Save searches locally

Add notes (e.g., target grade, price caps)

One-tap reopen


🧰 Bonus Flip Finder (Exclusive)

Curated high-value targets:

Grails

Vintage Liquid

Shining Pokémon

Gold Stars

Crystals & Special Holos


Each entry includes:

Exact search phrases

Identification notes

Mistake traps to avoid

One-tap search launchers



---

📦 Offline Support

Once loaded, TCG Expert Pro continues to work without internet access.

✔ Cached locally
✔ Loads instantly
✔ Watchlist stored on device
✔ No external dependencies


---

📲 Installable App (PWA)

You can install TCG Expert Pro like a real app.

Android (Chrome)

1. Open the launcher page


2. Tap ⋮ Menu


3. Tap Add to Home Screen or Install App


4. Launch from your home screen



Desktop (Chrome / Edge)

1. Open the launcher page


2. Click the Install icon in the address bar


3. Confirm install




---

⚠ Worker / Offline Indicator Note

You may occasionally see the status indicator show something like:

“Worker: Offline” or “Worker: Checking…”

This does NOT mean the toolkit is broken.

The worker indicator reflects: • Browser restrictions
• Refresh timing
• Cache state
• Network handshake status

Even if the indicator says “offline,” the toolkit will still function normally as long as it has been loaded once.

If in doubt: ✔ Refresh the page
✔ Reopen from home screen
✔ Clear browser cache and reload


---

🗂 File Structure

/tcg-expert-pro
│
├── launcher.html          → App launcher
├── index.html             → Main toolkit
├── bonus.html             → Bonus Flip Finder
├── manifest.json          → PWA configuration
├── sw.js                  → Service worker (offline support)
├── logo-192.png           → App icon
├── logo-512.png           → App icon
├── logo-512-maskable.png  → Maskable icon
├── toolkit.png            → Visual branding
└── README.md              → This file


---

🔒 Privacy

TCG Expert Pro:

Stores everything locally

Does not collect personal data

Does not track users

Does not use analytics

Does not use cookies



---

⚠ Disclaimer

TCG Expert Pro is an educational and research tool only.

It does not provide: ❌ Financial advice
❌ Investment advice
❌ Guaranteed authenticity
❌ Buy/sell recommendations

Always perform your own due diligence before making purchases.


---

🧪 Developer Notes

When updating any files, bump the cache version inside sw.js:

const CACHE_NAME = "tcg-expert-pro-v3";

Then reload the app to refresh the cache.


---

🧠 Built For Collectors, By Collectors

This toolkit eliminates:

❌ Guesswork
❌ Fake listings
❌ Price confusion
❌ Manual searching
❌ Wasted time

And replaces them with:

✅ Speed
✅ Accuracy
✅ Confidence
✅ Research power
✅ Profit clarity
