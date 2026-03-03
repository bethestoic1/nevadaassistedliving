# Nevada Assisted Living — SEO & Affiliate Audit (March 2026)

## Traffic reality check (GSC)

| Metric | Last 7 days (Feb 23–Mar 1, 2026) |
|--------|-----------------------------------|
| **Clicks** | 0 |
| **Impressions** | 49 |
| **Avg. position** | 63.3 |
| **CTR** | 0% |

**Takeaway:** You’re getting **impressions** (listings in results), not traffic yet. Position ~63 means you’re usually off the first few pages, so clicks are unlikely. The upside: search demand is clear and almost entirely **Henderson-focused**. That’s the lever.

---

## Top queries (where you show up)

| Query | Impressions |
|-------|-------------|
| assisted living henderson | 13 |
| assisted living henderson nv | 5 |
| henderson assisted living | 4 |
| retirement homes henderson nv | 4 |
| senior assisted living henderson nv | 4 |
| senior living in henderson nevada | 3 |
| assisted living in henderson nevada | 2 |
| merrill gardens at green valley ranch | 1 |
| assisted living henderson nevada | 1 |

**Content/SEO implication:** Double down on Henderson. Add content that matches “retirement homes,” “senior living,” and “senior assisted living” in Henderson/NV. Consider a small section or mention for “Merrill Gardens at Green Valley Ranch” to capture that brand query.

---

## SEO audit summary

### Done well
- Clear titles and meta descriptions on index and Henderson page.
- Henderson page has JSON-LD (LocalBusiness), good for local intent.
- `sitemap.txt` and `robots.txt` in place; `llms.txt` for AI discoverability.
- Sensible internal links from cost-checklist and LTC to other guides.
- Homepage alert links to Henderson guide.

### Gaps fixed in repo
- **Canonicals:** Added `rel="canonical"` on all main pages to avoid duplicate/session URL issues.
- **Henderson in main nav:** Henderson is now in the main navigation on every page (it was only in the homepage alert). Better discovery + internal link weight.
- **OG/Twitter meta:** Added to financial-aid, memory-care, locations, cost-checklist, and long-term-care-insurance so shares look correct and signals stay consistent.

### Implemented (March 2026)
1. **Henderson page expanded** — Add sections that explicitly target:
   - “Retirement homes Henderson NV”
   - “Senior living in Henderson Nevada” / “Senior assisted living Henderson NV”
   - Optional: “Facilities to consider” with a line on Merrill Gardens at Green Valley Ranch (and 1–2 others) for brand/long-tail.
2. **More internal links to Henderson** — From `locations.html` (Vegas vs. Reno) and `memory-care.html` (e.g. “Memory care in Henderson”) so Henderson becomes a clear hub.
3. **New location pages** — “Assisted Living Las Vegas 2026” and “Assisted Living Reno 2026” (or Reno/Sparks) to capture city-level searches; link from `locations.html`.
4. **Deeper pillar content** — Financial-aid, memory-care, and locations are short. Adding 300–600 words each (examples, FAQs, 2026 specifics) will help E-E-A-T and rankings.

---

## Affiliate / monetization audit

### Current setup
- **Lead gen:** Tally form on homepage; referral to partners.
- **Partner links:** A Place for Mom and Caring.com on Henderson, Las Vegas, Reno, and cost-checklist (see `AFFILIATE_LINKS.md`).
- **Disclosure:** Present and linked in footer and near CTAs.

### Pain points → affiliate fit (from skill)
- Facility selection, funding, family decisions → senior care referral (A Place for Mom, Caring.com), insurance/financing content.
- Recurring: senior referral is often one-time or rev-share; document what’s recurring with your partners.

### Recommendations
1. **Tracked partner URLs** — When you have affiliate/tracked links, replace the current partner URLs in `AFFILIATE_LINKS.md` (and in the HTML) so attribution is correct.
2. **CTAs on more pages** — Add a soft CTA on financial-aid, memory-care, and locations: e.g. “Compare options with a local advisor” → homepage form or a partner link. Keeps monetization aligned with intent without being heavy.
3. **Optional extra partner** — e.g. SeniorLiving.org or one more referral partner, as noted in `AFFILIATE_LINKS.md`, to test which converts.

### Passive income angle
- Each lead that converts = one-time or rev-share fee. Volume comes from moving from position ~63 into top 20 for “assisted living henderson” and related terms. Priority: **Henderson content + internal linking + canonicals/nav** (done in repo), then **Las Vegas + Reno pages** and deeper pillars.

---

## Next steps (prioritized)

**Update (March 2026):** All items in the table below have been implemented: Las Vegas and Reno pages added, pillars deepened, soft CTAs and form deep-link in place, nav/sitemap/llms updated.

| Priority | Action | Impact |
|----------|--------|--------|
| 1 | **Expand Henderson page** with “Retirement homes,” “Senior living,” and optional facility mention (e.g. Merrill Gardens). | Directly targets 90%+ of current impressions; better relevance and CTR potential. |
| 2 | **Add “Assisted Living Las Vegas 2026” page** and link from locations. | Captures “assisted living las vegas” and related; builds topical cluster. |
| 3 | **Internal links:** locations → Henderson (and future Vegas/Reno); memory-care → Henderson (memory care in Henderson). | Passes relevance and authority to the page that’s already getting impressions. |
| 4 | **Add “Assisted Living Reno 2026” (or Reno/Sparks) page.** | Completes Nevada geography and long-tail. |
| 5 | **Deepen financial-aid, memory-care, locations** with 2026 details, examples, 1–2 FAQs each. | Stronger E-E-A-T and ranking potential. |
| 6 | **Add soft CTAs** on financial-aid, memory-care, locations (form or partner link). | Monetizes existing traffic as it grows. |

---

## Content outline: “Assisted Living Las Vegas 2026” (when you add it)

- **Target keywords:** assisted living las vegas, assisted living las vegas nv, senior living las vegas.
- **H1:** Assisted Living Las Vegas 2026 | Cost & Area Guide  
- **H2s (example):** 2026 Las Vegas assisted living cost overview; Best areas for senior living (Summerlin, Henderson, etc.); How Las Vegas compares to Henderson and Reno; How to compare facilities; Next steps (form/partner CTA).
- **Internal links:** To Henderson guide, locations (Vegas vs. Reno), financial-aid, cost-checklist.
- **Monetization:** Same CTA pattern as Henderson (form + A Place for Mom / Caring.com for Las Vegas or Nevada).

---

*Audit and in-repo fixes completed March 2026. Re-run GSC in 28 days to compare impressions and (hopefully) first clicks.*
