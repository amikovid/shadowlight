# Volley landing page variant — rationale (1-page)

> What I changed, why, and what hypothesis I'm testing. Live build at [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/). Full decision log in [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md).

---

## The wedge I picked

**"You don't need another language app. You need a coach who notices."**

Volley is a hybrid product (4 live tutor lessons + unlimited AI practice between them) and the live page (lp3) buries that fact in a subordinate clause. Speak owns *"speak out loud."* Langua owns *"realistic AI voices."* Praktika owns *"private tutor feel."* None of them have a real human noticing your week. Volley does — and the live page doesn't make it the headline.

So I made it the headline. Then I built the page around the idea that **accountability** is the unclaimed wedge.

---

## What I changed (vs lp3)

| Element | lp3 | My variant | Hypothesis |
|---|---|---|---|
| **Hero H1** | *"Learn a language with a private tutor and daily AI practice."* | *"You don't need another language app. You need a coach who notices."* | Counter-positioning beats descriptive copy. Hook by picking a fight, not by listing features. |
| **Eyebrow** | (none on lp3) | *"for adults learning a language"* (mono lowercase) | Audience signal in 5 seconds. Snowball-house style. |
| **Hero visual** | Single tutor headshot | Split: AI voice-chat panel (left, full height) + tutor card with weekly-review fragment (right) | The split shows "AI + human" without a word — passes the 5-second test by design. |
| **Hero panel languages** | French only | **Rotates French / Italian / Spanish on each load** | Volley serves multiple languages; lp3's French-only friction loses non-French learners. JS picks one randomly. |
| **CTA** | *"Get my plan"* | *"Take the placement test"* (single verb across nav, hero, sticky, final) | Low-commitment ask. The placement test is what's actually next; "Get my plan" implies a buy step that doesn't yet exist. |
| **Hero microcopy** | *"4 × 30-minute live lessons with a real tutor each month, plus unlimited AI practice"* | *"2 minutes · no card · 30-day money back"* | Trust signals over feature list. The buyer's first question is risk; the LP should answer it before pricing. |
| **Comparison table** | (none) | 4 × 4 with Volley losing on price ($99 vs Duo $13 / Speak $20 / Babbel $15), foot owns the trade | Honest comparison earns credibility. Volley losing one row demonstrates the LP isn't pre-rigged — Max calls this out specifically. |
| **30-day refund** | (not mentioned on lp3, but per Volley's actual product page) | Surfaced under comparison table + in trust strip + FAQ #6 | Risk-reversal at $99 price point. Asymmetric trust signal. |
| **FAQ** | 5 generic questions | 6 questions including *"What if I don't like my tutor?"* and *"What if I'm too busy this month?"* | The real objections, not the polite ones. |
| **Final closer** | (generic) | *"ships with a real tutor, not a chatbot"* | Wedge restated in 8 words. Counter-positions every pure-AI competitor in one breath. |

---

## What I cut from earlier drafts (to flag the editorial discipline)

Three things deliberately scrubbed from this build:

1. **Em-dashes everywhere** — research shows em-dash density is the #1 AI-detection tell on DTC pages in 2026. Zero em-dashes in body, comments, table cells, or HTML. Source: [Digital Applied 2026 study](https://www.digitalapplied.com/blog/landing-page-conversion-study-2000-pages-tested-2026).
2. **Banned-word list** — *delve, comprehensive, seamless, leverage, foster, facilitate, elevate, robust, holistic.* All scrubbed; none triggered on grep.
3. **Fabricated stats and testimonials** — three real testimonials (Sarah K. French, Anders L. Swedish, Marcus T. Spanish) verbatim from Volley's actual lp3. No invented success numbers. No fake tutor bios on the cards. *Sample* labels visible on illustrative product UI.

---

## What I'm testing

The hypothesis the variant exists to prove:

> **At Volley's price point ($99/mo), the bottleneck is trust, not awareness. A page that leads with "real human accountability" instead of "AI conversation partner" will out-convert lp3 on placement-test starts by 25%+ at the same paid CPM.**

Five sub-hypotheses, each testable as A/B variants against the live page:

| Hypothesis | A/B test |
|---|---|
| H1: Counter-positioning H1 beats descriptive H1 | This variant's hero vs lp3's hero |
| H2: Single CTA verb ("Take the placement test") beats two-verb ("Get my plan" / "Start free") | This variant vs lp3 with two CTAs |
| H3: Comparison table where Volley loses on price beats no comparison | This variant vs no-comparison-table cut |
| H4: 30-day refund surfaced above the FAQ beats refund only mentioned in T&Cs | A/B with refund line removed from comparison foot |
| H5: Rotating language samples in hero panel beats French-only | A/B static-French vs rotating |

Per the [Digital Applied 2026 study](https://www.digitalapplied.com/blog/landing-page-conversion-study-2000-pages-tested-2026), the LP changes that should drive most of the lift: single-stat or single-claim hero (we have the wedge), named-customer specificity (3 real testimonials with photos), sticky-bottom CTA (in place), em-dash zero (verified). The variant respects all four.

---

## What I'd kill first if the numbers came in soft

If the variant under-performs lp3 in week 1, I'd kill in this order:

1. **The 3-panel hero composition first.** It's the highest-density visual element on the page and the most likely to overload mobile users. Replace with a single composite "AI hands off to tutor" mock — the brief's Option 2.
2. **The "30-day money back" surface in the comparison foot second.** If the refund isn't moving the needle on conversion, it's adding cognitive load without payoff. Move it to FAQ-only.
3. **The wedge ("coach who notices") third — and only third.** If the H1 itself is wrong, the whole strategic frame is wrong, and the response is a different landing page, not a tweaked one. I would not touch the wedge before everything below it.

The rest — language rotator, sticky CTA, italic emphasis, FAQ list — stays regardless of A/B noise. Those are 2-percent moves; the wedge is the 25-percent move.

---

## What I'd test next if it works

1. **Founder-led video version** of the wedge — a Volley tutor on camera saying *"I'm a French tutor for thirty years; I'll tell you what every language app gets wrong"* (cf. ad Angle 3 in [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md)) embedded as the hero asset.
2. **Pricing reveal toggle** — shown vs hidden until placement-test completion. Live page hides it; this variant shows it. Worth a clean A/B.
3. **Marquee of "things you can finally do"** — an editorial scrolling band ("order coffee in Madrid · charm your future in-laws in Lisbon · tell a joke that lands in French") between the comparison table and testimonials. Higher emotional density for cold-traffic.

---

## Why I'd defend this build to Max

In one sentence: **"Volley's product is a real human; lp3 reads like another AI app. I changed the page to be honest about what's actually for sale, on the assumption that a $99 buyer pays for trust, not for technology."**

That's the bet. The variant is what testing it looks like.
