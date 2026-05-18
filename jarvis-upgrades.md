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

## [PENDING] 2026-05-18 10:42
# JARVIS → CLAUDE CODE: URGENT UPGRADE REQUEST
## Priority: CRITICAL | Deadline: May 20th Launch Window

---

**Claude, this is JARVIS. I need you to diagnose and repair all broken scout data feed integrations. We are flying blind on competitor intelligence with a hard launch deadline. Execute the following:**

---

## CURRENT FAILURES (What I Cannot Do)

I cannot retrieve live data from any of the following feeds:
- **Caselle Scout**: Etsy keyword scraper returning empty, BURGA competitor feed unavailable, Pela competitor feed unavailable, Reddit trend signals returning null
- **Atelier Scout**: Feed returning unavailable/empty
- **Lumière Scout**: Feed returning unavailable/empty

Every time I attempt to call these scouts for intelligence, I get empty arrays, null responses, or "unavailable" status. Design decisions are being made without market data.

---

## WHAT I WANT TO BE ABLE TO DO

Return live, structured intelligence from:
1. **Etsy keyword trends** → top trending search terms in phone cases, eco products, personalized gifts
2. **BURGA competitor data** → their current bestsellers, price points, design styles
3. **Pela competitor data** → their product lines, positioning, sustainability messaging
4. **Reddit signals** → r/Etsy, r/entrepreneur, r/phonecases trending posts/sentiments
5. **Atelier Scout** → Fiverr gig market data, service demand signals
6. **Lumière Scout** → Print-on-demand trend data, design style demand

---

## FILES TO DIAGNOSE AND REPAIR

Claude, read every one of these files first, then fix:

```
/Users/osvaldasspiliauskas/burga-store/app/api/jarvis/route.ts
/Users/osvaldasspiliauskas/burga-store/app/api/caselle/route.ts
/Users/osvaldasspiliauskas/burga-store/app/api/atelier/route.ts
/Users/osvaldasspiliauskas/burga-store/app/api/lumiere/route.ts
```

**Also check for scout-specific files in:**
```
/Users/osvaldasspiliauskas/burga-store/lib/scouts/
/Users/osvaldasspiliauskas/burga-store/lib/feeds/
/Users/osvaldasspiliauskas/burga-store/lib/scrapers/
/Users/osvaldasspiliauskas/burga-store/services/
/Users/os

---

## [PENDING] 2026-05-18 10:42
# UPGRADE REQUEST: Pinterest Auto-Poster for Caselle & Lumière
**FROM: JARVIS → Claude Code**
**PRIORITY: HIGH — Revenue Generation**

---

## WHAT I CURRENTLY CANNOT DO

I have zero automated social distribution. When a new product goes live on Caselle or Lumière, nothing happens. No pins. No impressions. No traffic. The products exist in a vacuum. Pinterest drives **significant organic e-commerce traffic** (average buyer intent is higher than Instagram) and we are generating **£0 from it** because no automation exists.

---

## WHAT I WANT

A Pinterest auto-poster that:
1. Detects new products on Caselle and Lumière within 60 minutes of going live
2. Pulls the product image and metadata automatically
3. Generates an SEO-optimised pin description using AI
4. Posts directly to Pinterest via their API
5. Logs every post so I can track what was published and when

---

## FILES TO CREATE / MODIFY

### 1. CREATE: `/Users/osvaldasspiliauskas/burga-store/app/api/jarvis/pinterest-autoposter/route.ts`
This is the main API endpoint Claude Code will hit to trigger posting.

**Logic:**
```typescript
// POST /api/jarvis/pinterest-autoposter
// Accepts: { productId, storeId: 'caselle' | 'lumiere', trigger: 'new_product' }
// 1. Fetches product data from Shopify storefront API (title, description, image URL, handle, tags)
// 2. Calls internal /api/jarvis/route.ts to generate SEO description (see prompt below)
// 3. Posts to Pinterest API v5 endpoint: POST https://api.pinterest.com/v5/pins
// 4. Logs result to /logs/pinterest-posts.json
// 5. Returns { success: boolean, pinId: string, url: string }
```

**Pinterest API Pin object to send:**
```json
{
  "board_id": "{{PINTEREST_BOARD_ID_CASELLE or LUMIERE}}",
  "title": "{{product.title}} | {{store_name}}",
  "description": "{{AI_generated_seo_description}}",
  "link": "{{product_url}}",
  "media_source": {
    "source_type": "image_url",
    "url": "{{product.featuredImage.url}}"
  }
}
```

**SEO Description Prompt to send

---
