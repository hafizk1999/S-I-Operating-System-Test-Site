# S&I Urban Designers — Operations Dashboard

A self-contained, browser-based operations dashboard for **S&I Urban Designers Sdn Bhd**. No server, no database, no installation required — just open `index.html` in any browser.

## Live Site

Hosted via Vercel:  
**https://[your-github-username].github.io/S-I-Operating-System-Test-Site/**

---

## What It Does

| Tab | Purpose |
|-----|---------|
| 📊 Director Dashboard | 5 KPI cards, project health charts, pipeline value, overdue alerts |
| 📋 Tender Management | Full CRUD table — search, filter, sort, export CSV |
| 📈 Analytics | Win/loss trend, division breakdown, status charts |

### Key features
- Add, edit, and delete **projects** and **tenders** via slide-in forms
- **Auto-saves** everything to the browser — no account needed
- **Overdue alerts** — red banner if any tender deadline is missed
- **7-day warnings** — amber flag when a deadline is close
- **Export to CSV** — download your filtered tender list instantly
- Works fully **offline** after the first load

---

## How to Use

1. Open the link above in any web browser
2. Click **"+ Add Tender"** or **"+ Add Project"** to enter your data
3. Navigate between the three tabs to see different views
4. Your data saves automatically — close and reopen any time

---

## Divisions Covered

- Engineering & Construction  
- Interior Design  
- Signage & Wayfinding  
- Facility Management  
- Parking Management  
- M&E  

---

## Tech Stack

| What | Detail |
|------|--------|
| Language | Plain HTML + CSS + JavaScript (no framework) |
| Charts | Chart.js 4.4.0 (CDN) |
| Fonts | DM Sans + Sora (Google Fonts CDN) |
| Storage | Firebase Realtime Database |
| Hosting | Vercel |

---

*Built for S&I Urban Designers Sdn Bhd · Internal operations tool*
