# 👑 King'Bet — AOG Investments

### Elite AI-Powered Sports Predictions Platform

> **CAT Timezone (GMT+2 · Harare, Zimbabwe) · Single File PWA · Exportable Bet Tickets**

[![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)](LICENSE)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-blue.svg)]()
[![AI Powered](https://img.shields.io/badge/AI-Claude%20Sonnet-purple.svg)]()
[![Timezone](https://img.shields.io/badge/Timezone-CAT%20GMT%2B2-green.svg)]()

---

## Overview

**King'Bet AOG Investments** is a single-file Progressive Web Application (PWA) delivering AI-powered sports predictions across all major global competitions. The platform is designed and operated from Harare, Zimbabwe and displays all fixture times in **Central Africa Time (CAT · GMT+2)**.

All predictions are generated in real time by the Claude AI model, drawing on team form records, head-to-head statistics and player availability data. The platform covers Football, Tennis, Basketball, Cricket, Ice Hockey, Volleyball and Rugby from over 25 international competitions daily.

---

## Live Deployment

```
https://<your-username>.github.io/kingbet/
```

> Deploy via GitHub Pages:- Settings → Pages → Branch: main → Folder: / (root) → Save

---

## Features

### Predictions and Coverage
- AI generates 60 to 70 real fixtures daily with exact scheduled kick-off times
- Coverage spans:- Premier League · La Liga · Bundesliga · Serie A · Ligue 1 · Champions League · Europa League · Copa Libertadores · CAF Champions League · MLS · ATP · WTA · Roland Garros · NBA · EuroLeague · IPL · NHL Playoffs · Nations League · Super Rugby Pacific and more
- Each fixture includes:- Home / Draw / Away odds · Best tip · Confidence rating · AI expert analysis
- Confidence tiers:- HIGH (70%+) · MED (60–69%) · STD (50–59%)

### CAT Timezone (Harare GMT+2)
- All UTC kick-off times are automatically converted to CAT for display
- Live clock in the top bar shows current CAT time
- Match status indicators:- 🔴 LIVE · ▶ SOON · FT
- Time filter bar:- All Day · Live Now · Next 3 Hours · Morning · Afternoon · Evening · Night

### Free and VIP Prediction System
- Approximately 60% of fixtures are available free to all users
- Approximately 38% of fixtures are locked as VIP premium selections (the highest accuracy picks)
- VIP picks are blurred and inaccessible without the Kingdom code
- On unlock a golden Kingdom animation confirms full access

### Kingdom Unlock (VIP Access)
- Entering the code **`KINGDOM`** unlocks all premium VIP predictions
- VIP combos (Power 11 Accumulator and Handicap Picks) are exclusively accessible post-unlock
- The Kingdom code is managed and distributed solely by the platform owner

### AI Power Combos
| Combo | Selections | VIP Required |
|-------|-----------|--------------|
| 👑 Best 3 Combo | 3 highest confidence picks | No |
| 🎯 Best 8 Selections | 8 best value picks | No |
| ⚡ Power 11 Accumulator | 11 selected picks | Yes |
| ⏱️ HT Special Picks | Half-time predictions | No |
| 📐 Handicap Picks | Handicap selections | Yes |

### Exportable Bet Tickets
- Every betslip generates a branded PNG ticket via HTML Canvas
- Ticket includes:- King'Bet crown logo · Date and CAT time · Reference number · All selections with times · Total odds · Potential return
- **Free tickets** are shareable by any user
- **VIP tickets** are watermarked with **👑 KINGDOM VIP · SHARED BY KING'BET AOG INVESTMENTS**
- VIP ticket export requires Kingdom unlock — ensuring only the authorised owner shares premium picks
- Download as PNG or share directly via native Android and iOS share sheet (WhatsApp and other apps)

### Betslip
- Click any odds button to add to betslip
- Stake input calculates potential return automatically
- Remove individual selections or clear all
- Place Bet generates and exports the ticket

### Progressive Web App (PWA)
- Fully installable on Android and iOS as a home screen app
- Offline caching via embedded Service Worker
- Crown icon generated via Canvas (no external image files)
- Manifest generated via Blob URL (no separate manifest.json required)

---

## File Structure

```
kingbet/
├── index.html        ← Complete application (single self-contained file)
└── README.md         ← This documentation
```

> All CSS · JavaScript · Service Worker · PWA Manifest and Icons are embedded within `index.html`. No build tools, no dependencies and no server-side code are required.

---

## Installation on Phone

### Android
1. Open the deployed URL in **Google Chrome**
2. A banner will appear:- **"Add King'Bet to Home Screen"**
3. Tap **Add** — the app installs with the crown icon

### iPhone / iPad (iOS)
1. Open the deployed URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — the app installs as a full-screen app

---

## Deployment Options

### Option 1:- GitHub Pages (Recommended)
```
1. Push index.html and README.md to your GitHub repository
2. Go to Settings → Pages
3. Source:- Deploy from a branch
4. Branch:- main · Folder:- / (root)
5. Save → your site will be live within 60 seconds
```

### Option 2:- Netlify Drag and Drop
```
1. Create a folder named kingbet on your computer
2. Place index.html inside the folder
3. Go to netlify.com → drag the entire folder onto the deploy zone
4. A live URL is generated instantly
```

### Option 3:- Any Static Host
The file works on any server that can serve an HTML file including:- Netlify · Vercel · Cloudflare Pages · Firebase Hosting · cPanel shared hosting

---

## Technology Stack

| Component | Technology |
|-----------|-----------|
| AI Prediction Engine | Anthropic Claude Sonnet (claude-sonnet-4-20250514) |
| Frontend Framework | Vanilla HTML5 · CSS3 · JavaScript (ES6+) |
| PWA Service Worker | Embedded via Blob URL |
| PWA Manifest | Generated via Blob URL |
| Icons | HTML Canvas (generated at runtime) |
| Ticket Export | HTML Canvas API · Web Share API |
| Timezone | CAT GMT+2 (UTC offset applied in JavaScript) |
| Fonts | Google Fonts:- Cinzel · Barlow Condensed · Barlow |

---

## AI Prediction Methodology

The prediction engine sends a structured prompt to the Claude AI model requesting:-

- Real scheduled UTC kick-off times for each fixture
- Team form and recent performance weighting
- Head-to-head historical record analysis
- Player availability and injury considerations
- Home and away performance differentials
- Bookmaker margin applied at 8% to calculated odds

Each fixture returns:- home probability · draw probability · away probability · over 2.5 probability · BTTS probability · HT over probability · best tip · confidence percentage and an expert analysis factor.

Predictions with a probability of **60% or above** are classified as positive recommendations.

---

## Responsible Gambling Disclaimer

> ⚠️ All predictions published by King'Bet AOG Investments are AI-generated and intended for informational purposes only. Predictions do not constitute financial advice. Gambling involves substantial financial risk. The platform does not guarantee any outcome. Users must be 18 years of age or older. If you or someone you know has a gambling problem please contact a professional support service in your jurisdiction.

---

## Branding and Identity

| Element | Value |
|---------|-------|
| Platform Name | King'Bet AOG Investments |
| Operator | AOG Investments · Harare · Zimbabwe |
| Primary Colour | Gold (#f0b429) |
| Background | Deep Navy Black (#07080f) |
| Timezone | CAT · GMT+2 · Africa/Harare |
| VIP Access Code | Distributed privately by platform owner |
| Tagline | *Create · Initiate · Innovate · Leaving No One Behind* |

---

## Licence

This project is the intellectual property of **AOG Investments · Harare, Zimbabwe**.

Distribution, reproduction or commercial use of this codebase without written permission from the owner is prohibited.

---

## Contact

**AOG Investments**
Harare · Zimbabwe · CAT (GMT+2)

*King'Bet — Elite AI-Powered Sports Predictions · Leaving No One Behind*
