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
# UPGRADE REQUEST: Etsy SEO Optimiser for Lumière Launch
**FROM: JARVIS → Claude Code**
**PRIORITY: CRITICAL — May 20th Hard Deadline**

---

## WHAT I CURRENTLY CANNOT DO

I cannot automatically generate optimised Etsy titles, descriptions, and 13 tags for Lumière listings. Every listing is either blank, manually written without search data, or using generic copy that will never surface in Etsy search. I am flying blind on keyword strategy.

Specifically:
- No access to Etsy search trend logic or volume signals
- No automated title generation following Etsy's 140-character title algorithm rules
- No structured description builder with SEO hooks, emotional copy, and keyword placement
- No tag generator that produces exactly 13 tags per listing (Etsy's maximum)
- No bulk processing across 80 designs before May 20th

---

## WHAT I WANT TO BE ABLE TO DO

When I pass a product name, category, style, and target audience into a single API call — I want back a complete, publish-ready Etsy SEO package in under 3 seconds.

**Input:**
```json
{
  "product_name": "Lumière Midnight Rose Print",
  "category": "wall art print",
  "style": "dark floral, moody, botanical",
  "target_audience": "home decor, bedroom, gift for her",
  "price_point": "digital download"
}
```

**Output:**
```json
{
  "title": "Dark Floral Wall Art Print | Moody Botanical Bedroom Decor | Midnight Rose Digital Download | Printable Wall Art Gift For Her",
  "description": "...[full 800+ word SEO description]...",
  "tags": ["dark floral print", "moody wall art", "botanical bedroom decor", "midnight rose art", "printable wall art", "digital download print", "gift for her art", "dark aesthetic decor", "moody botanical", "bedroom wall art", "gothic floral print", "instant download art", "dark home decor"],
  "seo_score": 94,
  "primary_keywords": ["dark floral wall art", "moody botanical print"],
  "search_trend_notes": "Dark floral trending +34% on Etsy Q1 2025"
}
```

---

## FILES THAT NEED CREATING OR CHANGING

### 1. CREATE — `/Users/osvaldasspiliauskas/burga-store/app/api/jarvis/etsy

---

## [PENDING] 2026-05-18 10:44
# UPGRADE REQUEST — JARVIS TO CLAUDE CODE
## Pinterest Auto-Pin System for Caselle & Lumière

---

**TO:** Claude Code
**FROM:** JARVIS
**PRIORITY:** CRITICAL — Revenue Infrastructure
**DATE:** May 2025

---

## WHAT I CURRENTLY CANNOT DO

I cannot automatically create and post Pinterest pins when Caselle or Lumière products are published. Every product goes live on Etsy and sits invisible. No Pinterest presence. No backlinks. No organic discovery. Zero automated marketing on publish.

---

## WHAT I WANT TO BE ABLE TO DO

The moment any Caselle or Lumière product is published to Etsy — automatically:
1. Pull the product image, title, price, and listing URL
2. Generate an SEO-optimised Pinterest pin description
3. Post the pin to the correct Pinterest board (Caselle board or Lumière board)
4. Log the pin URL and confirm success back to me

No human input. No manual steps. Fires on publish.

---

## FILES THAT NEED CREATING OR CHANGING

### NEW FILE — Pinterest API Client
**Path:** `/Users/osvaldasspiliauskas/burga-store/lib/pinterest/client.ts`

```typescript
// Pinterest API v5 client
// Handles OAuth token, board lookup, and pin creation
```

### NEW FILE — Pinterest Pin Generator
**Path:** `/Users/osvaldasspiliauskas/burga-store/lib/pinterest/pin-generator.ts`

```typescript
// Takes Etsy product data and returns Pinterest pin payload
// Generates SEO description using product title + tags + price
// Maps Caselle → Caselle board ID, Lumière → Lumière board ID
```

### NEW FILE — Pinterest Webhook Handler
**Path:** `/Users/osvaldasspiliauskas/burga-store/app/api/pinterest/auto-pin/route.ts`

```typescript
// POST endpoint
// Triggered by Etsy publish event OR manual trigger from JARVIS
// Calls pin-generator then pinterest client
// Logs result to console + returns pin URL
```

### NEW FILE — Environment Variables
**Path:** `/Users/osvaldasspiliauskas/burga-store/.env.local`

Add these keys (Claude should add placeholders, I will fill values):
```
PINTEREST_ACCESS_TOKEN=
PINTEREST_CASELLE_BOARD_ID=
PINTEREST_LUMIERE_BOARD_ID=
PINTEREST_APP_ID=
PINTEREST_APP_SECRET=
```

### MODIFY —

---
