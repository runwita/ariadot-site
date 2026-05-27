# Ariadot SEO plan (drafted 2026-05-26)

Internal reference, not a published page. Covers keyword targeting and
per-page content recommendations. Technical on-page SEO (canonical,
JSON-LD, OG/Twitter, sitemap, robots) is already done as of this date.

## Honest framing first

SEO for a brand-new domain takes months, not days. ariadot.app has near-zero
domain authority right now, so even perfect on-page work won't rank for
competitive terms ("AI email assistant") for a long while. The realistic
near-term wins are:
1. **Branded search** ("ariadot") — own this immediately, it's uncontested.
2. **Long-tail, low-competition phrases** that match the exact problem, where
   a small site can rank because few others target them precisely.
3. **The safety/privacy angle** — a genuinely differentiated, content-rich
   page that few competitors match in depth. This is the SEO moat.

Distribution (Discord, Reddit, Indie Hackers, word of mouth, the beta) will
drive more early traffic than organic search. SEO is the long game running
underneath that.

## Primary keyword themes

The product is hard to keyword because it's a new category (Quadrant-4: low-
frequency, high-stakes, ad-hoc). Don't chase "to-do app" or "email client" —
wrong intent. Target the *problem*, not the category.

**Tier 1 — own these (low competition, high intent):**
- "app that reminds you of things in your email"
- "AI that reads my email and tells me what matters"
- "never forget a deadline buried in email"
- "email that turns into reminders" / "turn emails into reminders automatically"
- "what slips through the cracks email calendar"
- "morning brief from my inbox"

**Tier 2 — aspirational (more competitive, target later via content):**
- "AI email assistant privacy"
- "AI inbox assistant that doesn't train on your data"
- "household admin app" / "mental load app"
- "personal assistant AI for email and calendar"

**Tier 3 — branded (own from day one):**
- "ariadot", "ariadot app", "ariadot ai"

## Per-page recommendations

### Homepage (/)
- Current title "ariadot, a calm hand on your day" is brand-voice but SEO-weak
  (no keywords). Consider an H1 or supporting copy that includes "reads your
  email" and "morning brief" naturally. The title tag could become
  "Ariadot — your inbox, read back to you each morning" or similar that
  carries a keyword while staying on-voice. (Decision for Bharat: brand voice
  vs keyword density. Lean brand for the hero, keywords in body + meta.)
- Ensure the page body uses the Tier-1 phrases in real sentences.

### /safety — the SEO moat
- This is the strongest page. It's deep, specific, and answers privacy fears
  competitors gloss over. Target "AI email assistant privacy",
  "does [AI email app] read my email", "AI that doesn't train on your data".
- Already has FAQ-style structure on /faq; consider cross-linking heavily.

### /faq — now has FAQPage schema
- Eligible for rich results (expandable Q&As in Google). The 14 Q&As target
  exactly the privacy/security long-tail. Keep questions phrased the way
  people actually search ("Can anyone at Ariadot read my email?").
- This is the highest-leverage organic page for the privacy angle.

### /features/{brief,loops,handbook}
- Each should target the feature's job-to-be-done phrase:
  - brief → "daily summary of my inbox", "morning email brief"
  - loops → "track open items from email", "follow-ups I forget"
  - handbook → "household info in one place", "shared family details"

## Content ideas (future, when there's capacity)

A blog/notes section would let you target Tier-1/2 phrases with dedicated
pages. Candidate posts (each targets a search intent):
- "Why your to-do app doesn't catch the form due in three weeks" (Q4 framing)
- "How we let an AI read your email without it ever seeing your name" (the
  masking story — unique, shareable, ranks for the privacy angle)
- "The mental load is a search problem" (category-defining essay)
- A /vs page or comparison content once competitors are clear.

NOTE: no blog exists yet and building one is real work. Flagged, not committed.

## Off-page (cannot be done in code)
- Get listed: Indie Hackers, Product Hunt (at launch), relevant directories.
- Backlinks from the founder essays / any press.
- The Discord + Reddit presence already in motion helps brand search.

## Measurement
- GSC is now set up (sitemap submitted). Watch: branded impressions first,
  then long-tail. Don't expect Tier-1/2 movement for 2-3 months minimum.
- Track which /faq questions earn impressions — that tells you which privacy
  fears people actually search, and where to write more.
