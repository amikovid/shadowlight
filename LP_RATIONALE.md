# Volley landing page — what I built and why

> **Live build:** [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/) · **Full decision log:** [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md) · **Source content for the LP design pass:** [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md)

---

## In one sentence

**Volley's product is a real human; the live page reads like another AI app. The variant is what fixing that looks like.**

That sentence is the entire bet. Everything below is the work behind it.

---

## What I learned about Volley before touching a pixel

Three findings that reshaped the whole thing, in the order I learned them:

1. **The live page (lp3) is JS-rendered.** Static fetchers see only the meta description: *"Speak any language with your AI conversation partner."* My first recon doc treated this as the product description. **It wasn't.** It's a marketing line that hides the actual offer.
2. **The actual product is a hybrid.** Real human tutor (4 × 30-min live lessons/month) PLUS unlimited AI practice between them PLUS weekly tutor reviews of your data. I only learned this when I stopped relying on fetchers and opened lp3 in a real browser. Findings documented in [`research/02_volley_recon.md`](research/02_volley_recon.md).
3. **The wedge is unclaimed.** Speak owns *"speak out loud."* Langua owns *"realistic AI voices."* Praktika owns *"private tutor feel."* Duolingo owns *"habit / streak."* **Nobody owns "a real human noticing your week."** Volley does, and the live page buries it.

The first two findings forced me to rebuild from scratch. Two earlier LP versions were deleted because they pitched a fabricated pure-AI product.

---

## The wedge

> **"You don't need another language app. You need a coach who notices."**

Counter-positioning by category, not by competitor. Frames every other app — including AI-only ones — as missing the load-bearing piece.

The wedge is the hero H1. Everything else on the page either earns it or restates it.

---

## What I changed (vs lp3, in 5 moves)

| Move | lp3 | Variant | Why |
|---|---|---|---|
| **1. Lead with the wedge, not the feature** | *"Learn a language with a private tutor and daily AI practice."* | *"You don't need another language app. You need a coach who notices."* | Counter-positioning beats descriptive copy. Pick a fight, don't list features. Source: [`research/01_max_dossier.md`](research/01_max_dossier.md) §"Counter-positioning as a strategy" — Max's own brands do this consistently. |
| **2. Show the hybrid in the hero, not in copy** | Single tutor headshot | Split: AI voice-chat panel (left, full height) + tutor card with weekly-review fragment (right) | Passes the 5-second test by structure. Viewer sees "AI + human" without reading. |
| **3. Rotate the language sample** | French only, hardcoded | JS rotates French / Italian / Spanish on each load | Volley serves multiple languages. French-only friction loses non-French learners on cold traffic. |
| **4. Single CTA verb** | *"Get my plan"* | *"Take the placement test"* (consistent across nav, hero, sticky, final) | Lower-commitment ask. Standard playbook for premium products with a price barrier (Noom, Future). |
| **5. Surface the 30-day refund** | Not on lp3 (verified separately on Volley's actual product page) | In comparison foot + sticky bar + FAQ #6 | At $99 the buyer's biggest objection is risk. The page should answer it before pricing. |

---

## The voice discipline

Three rules, all defensible against a published source:

| Rule | Source / mechanism |
|---|---|
| **Zero em-dashes anywhere** (body, table cells, comments) | Per the [Digital Applied 2026 study](https://www.digitalapplied.com/blog/landing-page-conversion-study-2000-pages-tested-2026): *"Pages with more than 2 em-dashes per 100 words lose 5% on average."* Zero is conservative; the visual signature of any em-dash is itself the AI-tell regardless of density. |
| **Banned-word list scrubbed** *(delve, comprehensive, seamless, leverage, foster, facilitate, elevate, robust, holistic)* | Same study: *"Pages using `delve`, `leverage`, `synergize`, or `optimize your experience` lose 8%."* My list extends the cultural pattern. |
| **No fabricated facts** | Three real testimonials from lp3 verbatim with name + language + months in. Real photos. *Sample* labels visible on illustrative product UI. Tutor card has no invented bio. |

The full audit of every claim on the page (sourced vs inferred vs fabricated) is in [`research/02_volley_recon.md`](research/02_volley_recon.md) §"What our landing page can claim, scientifically."

---

## The hypothesis I'm actually testing

One bet:

> **At Volley's price point ($99/mo), the bottleneck is trust, not awareness. A page that leads with "real human accountability" instead of "AI conversation partner" out-converts lp3 on placement-test starts by 25%+ at the same paid CPM.**

Five sub-hypotheses, each falsifiable:

| H | Test |
|---|---|
| Counter-positioning H1 beats descriptive H1 | This variant's hero vs lp3's hero |
| Single CTA verb beats multi-verb | Variant vs lp3 with two CTAs |
| Honest comparison table (Volley losing on price) beats no comparison | Variant vs no-comparison cut |
| 30-day refund surfaced above the FAQ beats refund only mentioned in T&Cs | A/B with the refund line removed from comparison foot |
| Rotating language samples beats French-only | Static-French vs rotating |

The conversion-data findings backing each move (single-stat hero +18%, named-customer specificity +22%, sticky CTAs +11%) all come from the same 2,000-page 2026 study cited above.

---

## Kill order if the variant under-performs lp3

Three cuts I'd make in order, smallest move first:

1. **3-panel hero composition.** Highest visual density on the page, most likely to overload mobile. Replace with a single composite "AI hands off to tutor" mock.
2. **30-day money-back surface in the comparison foot.** If the refund isn't lifting conversion, it's adding cognitive load. Move to FAQ-only.
3. **The wedge itself.** Only if H1 testing proves the strategic frame is wrong. That's a different page, not a tweak.

The rest — language rotator, sticky CTA, italic emphasis, FAQ list — stays regardless of A/B noise. Those are 2-percent moves; the wedge is the 25-percent move.

---

## What I'd test next if it works

| Idea | Why |
|---|---|
| **Founder-led video version** of the hero (a real Volley tutor on camera, *"I've been a French tutor for thirty years; I'll tell you what every language app gets wrong"*) | Same wedge, video format. Single-stat hero data says video underperforms image; tutor talking-head data says authority-coded video over-performs in masterclass categories. Worth A/B. |
| **Pricing reveal toggle** (shown vs hidden until after placement test) | lp3 hides; this variant shows. Clean A/B on whether transparency lifts at $99 tier. |
| **Marquee of "things you can finally do"** between comparison and testimonials | Higher emotional density for cold traffic. *"Order coffee in Madrid · charm your future in-laws in Lisbon · tell a joke that lands in French."* |

---

## What I'd defend in the Loom

Three beats, ~90 seconds total:

1. *"Volley's product is a real human; the live page reads like another AI app. I changed the page to be honest about what's actually for sale."*
2. *"Five concrete moves: counter-positioning H1, hybrid-in-the-hero visual, language rotator, single CTA verb, refund surfaced. Each one has a published study or a Max-house-style precedent backing it."*
3. *"If it under-performs in week 1, here's my kill order. The wedge stays. Everything below it is testable."*

---

## Repo navigation

| Want to read more? | Go here |
|---|---|
| The full decision log (every sub-decision, alternative considered, A/B test that would falsify it) | [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md) |
| The brief that produced the LP build | [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md) |
| Volley product/competitive recon | [research/02_volley_recon.md](research/02_volley_recon.md) |
| The 2026 LP conversion data + Max house style synthesis | [research/03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) |
| Max's voice profile | [research/01_max_dossier.md](research/01_max_dossier.md) |
