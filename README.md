# Hi, I'm MaharAdnanAkbar 👋

**Building Agri Mall — free and affordable software for Pakistani farmers and agro shops.**

I'm Mahar Adnan Akbar, from Akbar Sons Agro Traders, Layyah, Punjab, Pakistan.
I build the tools I needed in my own shop — then share them with other shops and farmers.

> 🌾 *Fasal ki bimari, hal aik photo mein.*

---

## What I'm building

| Project | What it is | Status |
|---|---|---|
| **Agri Mall POS** | Offline POS & billing for pesticide, seed & fertilizer shops — Windows + Android, licensed one-time | **Live — v1.3.0** · 1-Year Rs 7,000 · Lifetime Rs 25,000 |
| **Agri Mall Doctor** | Free all-in-one crop doctor PWA for farmers — weeds, diseases, pests, spray dose per acre / per tanki, tank-mix, weather, sowing-to-harvest lifecycle | **In development — Pakistan-wide, all crops · Layyah pilot** |
| **Zarai Ajnas Trading** | Agricultural commodity trading — buy from farmers, sell to traders, commission & mandi rates | **Live — v1.0.8** |
| **Akbar Sons Agro Traders** | Our family agro shop in Layyah — seeds, fertilizer, pesticides & ajnas | **Running since 10 Sep 2026** |

Private repositories — demo on request. Contact below.

---

## Agri Mall POS

- Offline-first — full billing, khata, stock and reports without internet
- Windows desktop (Tauri) + Android (Capacitor)
- Central sync, daily auto-backup, Admin / Staff roles
- Licensed one-time per shop — no monthly fee, no trial
- Built for pesticide / seed / fertilizer shops only

## Agri Mall Doctor

- Free for farmers — no server, no paid key, offline-first PWA
- Every crop's weeds, diseases, pests & nutrient deficiencies — identification, damage, severity, solution
- Spray dose per acre and per 20 L tanki, tank-mix compatibility, latest weather (Open-Meteo, free)
- Photo diagnosis — in development, on-device

**Honest status:** no trained model is shipped yet. Training is stopped until Layyah field photos are collected and verified. No accuracy percentage is claimed anywhere.

## Principles

- **Offline-first** — a farmer's tool must work without net
- **Free for farmers** — Doctor is free, always
- **Verified sources only** — no Punjab guidance copied to another province, no dose without a label check
- **No false accuracy** — if it isn't verified, it says NOT VERIFIED

---

## Tech

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?logo=tauri&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?logo=capacitor&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?logo=pwa&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Google_Apps_Script-4285F4?logo=google&logoColor=white)

Tauri v2 (Rust) · Capacitor 8 · PWA · TensorFlow Lite (planned) · Google Apps Script (free sync, no paid API)

---

## Open data — government sources

Agri Mall Doctor uses official Pakistani sources where they exist, and says so clearly where they don't. `DATA NOT AVAILABLE` is a valid answer.

| Data needed | Official source | Status |
|---|---|---|
| Crop area, production & yield, district-wise (121 crops) | Pakistan National Accounts — Agriculture Statistics | Source identified, not yet ingested |
| Crop condition, fortnightly reports, pest situation | Punjab Agriculture Dept — Crop Reporting Service, Crop Advisory, Pest Alerts | Advisory current (16–30 Nov 2026); individual documents not yet ingested |
| Disease / pest image datasets (Pakistan field photos) | PlantCity — 10,667 images, 12 crops, 52 classes, Charsadda & Chitral | Candidate only — licence UNVERIFIED; no wheat, cotton, rice or sugarcane in it |
| Federal crop statistics, production, imports & exports | Ministry of National Food Security & Research — Agricultural Statistics of Pakistan | Source identified, not yet ingested |

Advisory documents are **not** a replacement for labelled training photos. Both are requested separately, with written permission.

---

## Contact

**Akbar Sons Agro Traders** — Near Jazz Tower, Chak No. 173 TDA, Layyah, Punjab, Pakistan

- 📱 WhatsApp: 0344-7113080
- 📞 Call: 0344-7113080
- 🛒 Agri Mall POS sales & support: 0344-7113080

*Developed by Mahar Adnan Akbar.*
