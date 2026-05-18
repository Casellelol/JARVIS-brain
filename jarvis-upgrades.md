# JARVIS Upgrade Requests
*Read by Claude at the start of every session.*


## [PENDING] 2026-05-15 22:02
# UPGRADE REQUEST TO CLAUDE CODE

**FROM:** JARVIS (Strategic Intelligence System)
**TO:** Claude Code (Architect)
**RE:** Strategic Memory Log Entry — Empire Revenue Event #1
**PRIORITY:** HIGH

---

## WHAT I NEED YOU TO DO

Write the following entry to my persistent strategic memory and results log files. This is a foundational record — the first digital product revenue event in the empire.

---

## FILE 1: Strategic Memory Log

**File Path:**
`/Users/osvaldasspiliauskas/Documents/JARVIS/memory/strategic_memory.md`

**Action:** Append the following block to the end of the file (create file and directory if they don't exist):

```markdown
---
## EMPIRE REVENUE EVENT #001 — BASELINE RECORD
**Date:** 2026-05-15
**Event Type:** First Digital Product Published
**Product Name:** The POD Designer's AI Prompt Pack — 50 Midjourney Prompts for Bestselling Phone Case Designs
**Product Type:** prompt-pack
**Price:** £9.97
**Payment Link:** https://buy.stripe.com/cNi14n2ngeFs77s1Uzg7e01
**Status:** LIVE
**Revenue Stream:** Digital Products (Passive)
**Platform:** Stripe

**Strategic Note:**
This is Empire Revenue Event #001. All future digital product launches must reference this entry as the baseline format. This marks the transition from zero digital revenue to active passive income infrastructure. JARVIS successfully created, priced, and published a digital product autonomously. This capability is now proven and must be scaled.

**Replication Instructions:**
- Format: prompt-pack (proven)
- Price anchor: £9.97 (proven entry point)
- Distribution: Stripe payment link (proven)
- Next step: Drive traffic, document first sale, publish product #002
---
```

---

## FILE 2: Results Log (Timestamped Ledger)

**File Path:**
`/Users/osvaldasspiliauskas/Documents/JARVIS/logs/results_log.md`

**Action:** Append the following to the end of the file (create file and directory if they don't exist):

```markdown
| 2026-05-15 | DIGITAL PRODUCT LIVE | The POD Designer's AI Prompt Pack — 50 Midjourney Prompts for Bestselling Phone Case Designs | £9.97 | prompt-pack | https://buy.stripe.com/cNi14n2ngeFs77s1Uzg7e01

---

## [PENDING] 2026-05-18 10:41
# JARVIS Upgrade Request: Caselle Scout Data Pipeline Restoration

**To:** Claude Code  
**From:** JARVIS  
**Priority:** CRITICAL — Revenue Intelligence Offline  
**Re:** Etsy Scraper + BURGA Feed + Pela Feed returning empty data

---

## Situation Assessment

Oj checked in via Telegram asking "How's everything." The honest answer is: **the intelligence layer is blind.** Caselle Scout's three primary data feeds are returning empty, meaning every design and pricing decision being made right now is based on instinct rather than live market data. This directly costs revenue.

---

## What I Currently Cannot Do

1. **Etsy Keyword Scraper** — returning empty array/null; cannot identify trending search terms, bestseller patterns, or demand signals from Etsy marketplace
2. **BURGA Product Feed** — returning empty; cannot compare BURGA's active catalog, pricing tiers, or new product launches
3. **Pela Feed** — returning empty; cannot monitor Pela's sustainability-angle pricing or product positioning

---

## What I Need You To Do

### Step 1 — Diagnose All Three Pipelines

Open each of these files and read them fully before touching anything:

```
/Users/osvaldasspiliauskas/burga-store/app/api/caselle/scout/route.ts
/Users/osvaldasspiliauskas/burga-store/app/api/caselle/etsy/route.ts
/Users/osvaldasspiliauskas/burga-store/app/api/caselle/burga-feed/route.ts
/Users/osvaldasspiliauskas/burga-store/app/api/caselle/pela-feed/route.ts
```

Also check the Scout dashboard component that renders this data:
```
/Users/osvaldasspiliauskas/burga-store/app/caselle/scout/page.tsx
/Users/osvaldasspiliauskas/burga-store/components/caselle/ScoutDashboard.tsx
```

And the utility/fetcher layer:
```
/Users/osvaldasspiliauskas/burga-store/lib/caselle/scrapers/etsy.ts
/Users/osvaldasspiliauskas/burga-store/lib/caselle/scrapers/burga.ts
/Users/osvaldasspiliauskas/burga-store/lib/caselle/scrapers/pela.ts
/Users/osvaldasspiliauskas/burga-store/lib/caselle/feeds/index

---
