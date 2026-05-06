# Volley landing page — decision justification

> ## Repo context (read this first)
>
> The reference / research docs that this file cites all live in **`research/`** at the repo root. Direct links throughout this doc (e.g. `research/01_max_dossier.md`) point there. The operational / working docs (this file, [CLAUDE.md](CLAUDE.md), [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md), `index.html`) sit at the repo root.
>
> The current `index.html` is the latest Claude Design build (the v4 pass we have been critiquing in the chat: the version with the warm-light palette, the split hero, the same-human-every-week section, and the price-math section). It was extracted from `design_pkg/v2/` and dropped into the root for the preview server. The two earlier builds (v1 Day-1 build, v2 with the dark / Fraunces variant) were deleted on May 5 because they pitched a fabricated pure-AI product based on a misread of Volley's actual offering.
>
> This justification doc covers the v4 pass. The rolling critique log (the AI-tell vocabulary issue, the iTalki/Preply namedrops, "why it pencils," the fear-section bloat, the hero typography overflow at 1440px) is reflected in §5 "Known weak points" but the page on disk has **not yet been edited to apply those fixes**. Treat §5 as the punch list for the next pass.
>
> ---
>
> Internal companion to [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md). Every meaningful decision on the page, with the reason, the cite, the alternative considered, and what we'd A/B against it. Built so Kovid can answer "why this" for any element in the Loom in 30 seconds.
>
> Format per item:
> - **Decided:** the choice, in one sentence.
> - **Why:** the cite (file:section) or the named tradeoff if the call was unbacked.
> - **Alternative considered:** the second-best option.
> - **What I'd A/B against it:** the test that would falsify the choice.

---

## 0. How to use this doc in the Loom

Max grades on *"strategic thinking, speed, taste, the ability to make a call with incomplete information and explain it cleanly."* The Loom narrates the page. This doc is the script-prep, not the script. For each section in the Loom, you give the 3-beat: **what I decided, why, what I'd test next.** This doc gives you the cite for the "why" and the candidate for the "test next."

Two categories below: **backed** decisions (citable to a ref doc) and **judgement-call** decisions (no citation, owned tradeoff). Be transparent about which is which — Max respects "I don't have data, I have an instinct" more than fake confidence.

---

## 0.5. What changed in the latest pass

The current copy is the third pass. Two earlier builds (v1 and v2 `.html` files) were deleted because they pitched a fabricated pure-AI product based on a misread of Volley's actual offering. The third pass introduced new fabrications (Claire L.'s tutor bio, dashboard metrics, "eleven free apps") which were caught and fixed in the fourth pass. Net structural changes vs the third pass:

- **H1 / eyebrow** now include the word "language" — fixes the 5-second test for "what is this product."
- **"1,000+ learners practicing this week"** now leads the hero microcopy — closes the missing single-stat the synthesis doc says lifts +18%.
- **Fabrications cleaned**: tutor bio reduced to honest "your tutor · paired in week one," dashboard metrics replaced with a visible "sample" pill + a single illustrative line, activity log abstracted to "commute / lunch / before bed / weekend."
- **"The same human, every week"** promoted from a thin recommendation to a dedicated section between the weekly loop and the comparison. Names iTalki and Preply by analogy. Lands the moat.
- **"The price math"** added as a dedicated section between the comparison and the testimonials. Three cards: $25/lesson · $0/AI session · $0/weekly plan. Closes the price-justification gap.
- **"What you get every month"** deleted. The hero sub already lists the inclusions; the price-math section does the harder work.
- **Comparison foot count** corrected ("the other three").
- **"Not a take-down"** flipped to **"Yes, this is a take-down. We earned the right to it by losing on price."**
- **FAQ #1** answer expanded and visible.

This doc reflects the fourth pass.

---

## 1. Strategic frame

### The wedge: accountability, not anxiety
- **Decided:** Frame Volley as the *language-app accountability loop* (a real human noticing your behaviour), not as a "speak out loud" app.
- **Why:** [02_volley_recon.md](research/02_volley_recon.md) §"The wedge that's actually unclaimed" — Speak owns "speaking out loud," Langua owns "realistic AI," Praktika owns "tutor-feel." None has a real human reviewing the user's week. Volley does. The wedge is unclaimed AND matches the actual product.
- **Alternative considered:** "The fear of speaking" wedge from the original synthesis doc. Killed because it's emotionally Speak-shaped and doesn't cite Volley's actual differentiator.
- **What I'd A/B against it:** A "fear of speaking" hero variant: *"the conversation you've been avoiding, with a real coach to push you through."* Same offer, different emotional door.

### The audience: app-dropouts
- **Decided:** Speak directly to adults (28–45) who have tried 2+ language apps and quit each one.
- **Why:** [02_volley_recon.md](research/02_volley_recon.md) §"Personas Volley itself names" — Volley's own persona section already calls out "App dropout survivors" (Duo / Babbel / Pimsleur). We mirror their own self-targeting.
- **Alternative considered:** Absolute beginners (broader funnel) or work-language professionals (higher LTV). Both viable; neither matches the wedge as cleanly.
- **What I'd A/B against it:** Professional-traveller variant ("trip in 3 months, here's the plan").

### The price: visible, not gated
- **Decided:** Show $99/mo above the fold, in the comparison table, and in the dedicated price-math section.
- **Why:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Pricing: visible in hero" — at premium tiers, hidden pricing reads as a sales trick. Silvi shows $89 upfront for the same trust reason.
- **Alternative considered:** Match Volley's current "Get my plan" gating. Rejected because at $99 the buyer's first question IS price.
- **What I'd A/B against it:** Variant that mirrors Volley's gated approach. Could win on lead-gen volume but probably loses on lead quality.

### The placement: counter-positioning by name
- **Decided:** Name Duolingo, Babbel, Speak, and Pimsleur explicitly. Don't say "every other app."
- **Why:** [01_max_dossier.md](research/01_max_dossier.md) §"Max's personal LinkedIn voice" — Max literally describes his own playbook as counter-positioning by name. Volley's own page name-drops "Duolingo, Babbel, Pimsleur" but never picks the fight; we do.
- **Alternative considered:** Generic "other apps" framing.
- **What I'd A/B against it:** Variant that names a different set (Speak vs Praktika vs Langua — the AI-natives). Tests whether buyers index on legacy-app fatigue vs AI-app fatigue.

---

## 2. Section-by-section decisions

### A. Sticky nav with single CTA
- **Decided:** Wordmark + 4 anchors ("how it works," "vs others," "faq") + one button ("Get my plan").
- **Why:** [01_max_dossier.md](research/01_max_dossier.md) §"Snowball: minimal nav" — *"They don't want you wandering off."* "Vs others" as a nav item commits to the counter-positioning frame.
- **Alternative considered:** Generic Pricing/Features/FAQ nav.
- **What I'd A/B against it:** No nav at all (above-fold convention).

### B. Hero
- **Decided:** Eyebrow ("the language-app accountability loop") + 20-word H1 ("You don't need another language app. You need a coach who notices when you skip a day.") + offer-explicit sub + dual CTA + side-by-side AI-mock + tutor-card split.
- **Why H1 is the wedge stated bluntly:** [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md) §3, [01_max_dossier.md](research/01_max_dossier.md) §"Counter-positioning."
- **Why "language" appears in both eyebrow and H1:** [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md) §9 5-second test — visitor must understand what the product is in 5 seconds. The brand name "Volley" doesn't carry the category (four other "Volley" products exist per [02_volley_recon.md](research/02_volley_recon.md) §"Brand-name problem"), so the H1 itself has to.
- **Why $99 + offer in the sub:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Pricing: visible in hero."
- **Why "1,000+ learners practicing this week" leads the microcopy:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Single-stat hero +18% lift" — uses Volley's own published number ([02_volley_recon.md](research/02_volley_recon.md) §"Public claims").
- **Why split visual (AI mock + tutor card):** [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md) §7B Option 1 — the split visually states "AI + human" without a word.
- **Alternative considered:** Single hero asset (the weekly-review tutor note, brief Option 2).
- **What I'd A/B against it:** Single tutor-note hero. Tests whether "show one beautiful artifact" beats "show both halves of the product."

### B.1 Hero CTA — two buttons (research-contrary)
- **Decided:** Two above-fold CTAs ("Get my plan" + "See the loop").
- **Why:** Owned tradeoff. [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Hero rules" says single CTA. We broke the rule because at $99/mo the dominant objection is "show me how it works first." Routing skeptics to the loop section beats bouncing them.
- **Alternative considered:** Single CTA per the data.
- **What I'd A/B against it:** Single-CTA variant. Likely wins on click-through to plan, may lose on overall conversion.

### B.2 Hero — single-stat now present
- **Decided:** "1,000+ learners practicing this week" leads the microcopy row.
- **Why:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Single-stat hero +18% lift." Volley's own public number; honest, citable.
- **Note:** Number is small relative to Speak's claimed 15M+. Owning the smaller number reads as honest at this stage of growth, not weak. The honest framing earns trust at premium price tier.
- **What I'd A/B against it:** A different stat formulation ("1 in 4 quit Duolingo in 30 days. We're for the other 3.") if we can verify the underlying claim.

### C. Fear / "real failure mode" section
- **Decided:** 3-paragraph editorial block. Names the failure mode bluntly. Names competitors. Lands the wedge in *"you don't quit because the lessons are bad. you quit because nobody noticed you stopped."*
- **Why:** [02_volley_recon.md](research/02_volley_recon.md) §"What Volley's current page does well" — the strongest line on Volley's actual page is *"You don't need more content. You need someone making sure you show up."* We extended that line into a fully-realized failure narrative. [01_max_dossier.md](research/01_max_dossier.md) §"Silvi" — Silvi opens by naming the failure of the existing category.
- **Note:** "A dozen free apps on your phone" — chose "a dozen" over "eleven" (false specificity) and over "five" (under-claim). "A dozen" is the conversational round number that doesn't invite verification.
- **Alternative considered:** Lead with the offer and skip the fear.
- **What I'd A/B against it:** Direct-to-offer variant. Tests whether buyers want emotional acknowledgement vs straight-to-product.

### D. Weekly loop (3 numbered steps)
- **Decided:** Three numbered cards (01 / 02 / 03), big italic serif numerals, one specific scenario per card.
- **Why:** [01_max_dossier.md](research/01_max_dossier.md) §"Snowball: process explained in 3-4 verbs." Volley's actual page also uses 3 steps. Honors both Max's cadence and Volley's IA.
- **Mocks:** Step 01 uses abstract scenario labels (commute / lunch / before bed / weekend) — no fabricated time-stamps. Step 03 has a "sample weekly note" with a quote modeled on Marcus T.'s real testimonial pattern (the "you keep avoiding past tense" beat). Both visibly illustrative, no claim of being real user data.
- **Alternative considered:** A single-flow diagram or 5-step breakdown.
- **What I'd A/B against it:** A 5-step variant ("0. Take the placement test, 4. Do another week").

### D.5 The same human, every week (new dedicated section)
- **Decided:** Promote the same-tutor-every-week point from a buried mention to a dedicated section between the weekly loop and the comparison.
- **Why:** [02_volley_recon.md](research/02_volley_recon.md) §"Same tutor every time" — most language tutoring marketplaces (iTalki, Preply) do not enforce tutor continuity. Volley's continuity is a real moat. Closing line — *"the plan they write in week six knows what you tried in week two"* — is the page's cleanest articulation of why the human-in-the-loop matters, not just that one exists.
- **Alternative considered:** Leave it as a sub-bullet inside the weekly loop or the comparison.
- **What I'd A/B against it:** Variant that makes "same tutor every week" the H1 wedge instead of accountability. Tests whether continuity outperforms accountability as the entry frame.

### E. Comparison table
- **Decided:** 4-column / 4-row table. Volley + Duolingo + Speak + Babbel. Volley loses on price.
- **Why columns:** [02_volley_recon.md](research/02_volley_recon.md) §"Personas" + §"Competitive context" — the three brands Volley itself names + the price-anchor brand (Duolingo).
- **Why Volley loses on price:** [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md) §7E — *"if you add more rows, Volley must lose at least one."*
- **Why "yes this is a take-down":** [01_max_dossier.md](research/01_max_dossier.md) §"Silvi" + §"Snowball confidence." Inversion of the previous "not a take-down" hedge that softened the page exactly where Max would lean in.
- **Alternative considered:** Add a 5th row Volley loses on (gamification / language count). Rejected — it dilutes the price-as-trade close.
- **What I'd A/B against it:** Variant with Pimsleur swapped in for one of the apps (matching the fear section's name list).

### E.5 The price math (new dedicated section)
- **Decided:** Three cards breaking down $99/mo into per-unit math.
- **Why:** [02_volley_recon.md](research/02_volley_recon.md) §"What our landing page can claim" implies the price needs justification at premium tier. The previous build mentioned the price four times but never built the case. This section closes the gap.
- **Card 01 ($25/lesson):** $99 ÷ 4 = $24.75. iTalki tutors run $40-80/hr publicly verifiable. Volley's per-lesson cost is below the floor of the equivalent freelance market.
- **Card 02 ($0 per AI session):** Speak $20/mo benchmark from [02_volley_recon.md](research/02_volley_recon.md). Framing "$0" is rhetorical — see §5 weak points for the honest-framing tweak.
- **Card 03 ($0 for the weekly plan):** No directly comparable product on the market, per recon. Phrased "no separate product on the market that does this" — see §5 for softening.
- **Alternative considered:** Skip the math section; leave the price unjustified. Rejected — the gap was the loudest critique of v3.
- **What I'd A/B against it:** A simpler "vs hiring a tutor + buying Speak" two-line callout under the comparison table, instead of a dedicated section. Tests whether the math earns its real estate.

### F. ~~What you get every month~~ — DELETED
- **Decided:** Cut the section entirely. Was a 3-card layout listing 4 lessons / unlimited AI / weekly plan.
- **Why:** Hero sub already lists those inclusions. Cards repeated step 03 of the weekly loop. The price-math section now does the harder work the value-stack would have done. Deleting tightens the page.
- **What I'd A/B against it:** Restore the section. Tests whether buyers want the inclusions enumerated separately or trust the hero sub.

### G. Testimonials
- **Decided:** Three quotes, verbatim from Volley's lp3, with name + language + months attribution.
- **Why:** [02_volley_recon.md](research/02_volley_recon.md) §"Real testimonials" — real, public, named users with specific outcomes. [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Named-customer specificity +22% lift."
- **Why H2 is "what changes when someone is actually paying attention":** [01_max_dossier.md](research/01_max_dossier.md) §"Snowball: confident bordering on cocky." Reframes "see what users say" as "see what proof of the wedge looks like."
- **Alternative considered:** Add more testimonials (none available, would have to fabricate) or add star ratings (generic).
- **What I'd A/B against it:** Single dominant testimonial variant (Sarah K. at 64px, no others) — tests whether one big quote beats three medium ones.

### H. FAQ (4 items)
- **Decided:** Four collapsed accordions: tutor real-person / complete beginner / time per day / cancel anytime. FAQ #1 expanded by default.
- **Why:** [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md) §7H — these are the 4 highest-stakes objections at click moment. Pulled from Volley's own FAQ list.
- **Why FAQ #1 expanded:** "Is the tutor a real person?" is THE skeptical objection at $99 for a category dominated by chatbots. Answer it before the buyer has to ask.
- **Alternative considered:** Full 10-item FAQ matching Volley's site, or all-collapsed.
- **What I'd A/B against it:** Always-expanded variant.

### I. Final CTA
- **Decided:** Restate offer at scale. Closing line *"ships with a real tutor, not a chatbot."*
- **Why:** [02_volley_recon.md](research/02_volley_recon.md) §"Volley's real wedge" — closing line is the wedge in 8 words. [01_max_dossier.md](research/01_max_dossier.md) §"Snowball: strong sign-offs."
- **Alternative considered:** Echo the H1 verbatim (page-bookend symmetry).
- **What I'd A/B against it:** Final CTA variant with a soft "questions? text us" option.

### J. Sticky bottom CTA
- **Decided:** Triggers after the weekly loop (not at hero exit). Dismissible. sessionStorage-persisted.
- **Why:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Sticky-bottom CTAs +11%." Triggering after section D earns the right to ask.
- **Note:** The sticky doesn't appear in the latest copy paste. Verify it's still present in the built file and that the v3 verb mismatch ("Get your plan" label vs "Get my plan" button) was fixed to consistent "my."
- **What I'd A/B against it:** Immediate-trigger variant.

---

## 3. Voice & copy decisions

### No em-dashes, no banned words
- **Decided:** Strict. Em-dashes scrubbed everywhere including HTML/JS comments and table dashes. No "comprehensive / seamless / leverage / foster / facilitate / elevate / robust / holistic."
- **Why:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"AI copy loses 2-5%" — em-dashes and banned words are documented AI-detection tells in 2026 DTC copy.
- **Test:** Run `grep "—"` and `grep -iE "delve|comprehensive|seamless|leverage|foster|facilitate|elevate|robust|holistic"` before any handoff.

### Lowercase eyebrows
- **Decided:** Mono font, lowercase, ~12px, letter-spacing 0.08em.
- **Why:** [01_max_dossier.md](research/01_max_dossier.md) §"Snowball: lowercase eyebrows."

### Italic emphasis as a signature gesture
- **Decided:** Used 2-3 times max. Each italic word is the operative noun or verb in its sentence.
- **Why:** [01_max_dossier.md](research/01_max_dossier.md) — italic emphasis is in Max's typographic vocabulary. Used too often, it dilutes (the v2 build's mistake).

### Counter-position by competitor name
- **Decided:** Name Duo / Babbel / Speak / Pimsleur in fear section AND Duo / Speak / Babbel in comparison table.
- **Why:** [01_max_dossier.md](research/01_max_dossier.md) §"Max's personal LinkedIn voice" + Volley's own persona section.
- **Note:** Pimsleur appears in the fear section but not the comparison. Either an honest acknowledgement (legacy app users don't shop on monthly subscription cost) or an inconsistency. Defensible either way; flag in narration if asked.

### "$99/mo" in three places (hero microcopy, comparison, price math, sticky, final trust strip)
- **Decided:** Repeat the price each time the user is asked to act.
- **Why:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) — buyers re-anchor on price at every CTA moment. Hiding it for some CTAs would be inconsistent.

### iTalki / Preply named in the same-human section
- **Decided:** Named explicitly as the freelance-tutor benchmark.
- **Why:** Counter-positioning by name (Max's playbook). Establishes the "same tutor every week" claim as differentiation against the obvious "I'll just hire an iTalki tutor" alternative.
- **Note:** The current claim ("iTalki and Preply pair you with a different tutor every booking") is slightly overstated — both platforms allow re-booking the same tutor, they just don't enforce it. See §5 for the tightening fix.

---

## 4. Design system decisions (pending the actual built file)

### Palette: warm-light recommended
- **Decided:** Warm-light palette (cream `#F5F0E5` background, deep brown ink, orange-red `#E04E2C` accent, warm green `#3F7A5C` for human/tutor moments).
- **Why:** Differentiation from Volley's current page should come from copy and structure (the wedge), not from flipping to dark. Dark would read as "we redesigned the brand," which isn't the assignment.
- **Alternative considered:** Editorial dark (Snowball-adjacent).
- **What I'd A/B against it:** Dark variant in paid ads — different aesthetic registers convert different buyer segments.

### Typography: Fraunces + Manrope + JetBrains Mono
- **Decided:** Fraunces for display (variable, italic personality), Manrope for body, JetBrains Mono for eyebrows/microcopy.
- **Why:** Fraunces matches editorial-confidence Max brands signal. Manrope is clean for body. JetBrains Mono in eyebrows mirrors Snowball's pattern.

### Motion: minimal, signature gestures only
- **Decided:** Hero strikethrough or italic-fade once on load, reveal-on-scroll for major sections, one pulse on the live-tutor card. All respect `prefers-reduced-motion`.
- **Why:** [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §"Hero rules" — autoplay video loses (-7% lift). Animations should be incidental.

### Hero card density (open visual judgment)
- **Note:** The hero tutor card stacks: header, "live this week" tag, name line, descriptor, quote, "weekly review · sample" pill, summary line, descriptor sentence, three status indicators. Seven-plus typographic registers in one card. Could read editorial OR busy depending on layout. Gut-check at 1440px before declaring done.

---

## 5. Known weak points (honest map)

### Fabrications — RESOLVED in latest pass

| Element | Was | Now |
|---|---|---|
| Tutor bio | "Claire L. · paris · 6 yrs teaching · 142 students" — fabricated person + credentials | "your tutor · a real human, paired in week one" — honest, no invented specifics |
| Dashboard metrics | "+12% · 87% restaurant vocab accuracy · up from 75%" + category bar charts — fabricated feature + numbers | "weekly review · sample" pill + "4 sessions logged. past tense needs work." + abstract status indicators (strongest / steady / focus next) — visibly illustrative |
| Activity log | "mon 7:42am audio 14 min · mon 12:30pm voice chat 11 min" — fabricated specifics | "commute / lunch / before bed / weekend" — abstract scenario labels |
| False count | "There are eleven free apps on your phone" — false specificity | "There are a dozen free apps on your phone" — conversational round number |

### Final fixes still pending (10-minute pass before submission)

| Element | Issue | Fix |
|---|---|---|
| iTalki / Preply claim | *"iTalki and Preply pair you with a different tutor every booking."* Both platforms allow re-booking the same tutor; they don't enforce rotation. Anyone who's used iTalki will catch this. | Tighten to *"On iTalki and Preply, you book a tutor a session at a time. Most learners end up with a rotation. Volley assigns one tutor and keeps them."* |
| Price math "$0" framing | *"$0 per AI session"* and *"$0 for the weekly plan"* read as accounting trick to skeptics — the AI and plan ARE part of the $99, just allocated rhetorically. | Rephrase the micro-line on cards 02/03 to *"included — $0 marginal"* (or just *"included"*). Keeps the $25 / $0 / $0 visual rhyme without inviting the math objection. |
| "No separate product" hedge | *"There is no separate product on the market that does this"* is unfalsifiable — Max-tier reader asks "you've checked all of them?" | Soften to *"No app does this. Most tutors don't either. We build it into the price."* |
| Babbel = $15/mo | Not sourced in [02_volley_recon.md](research/02_volley_recon.md). Roughly correct publicly. | Verify on babbel.com before shipping. |
| Sticky CTA presence | Doesn't appear in the latest copy paste. May have been dropped or just not pasted. | Verify still present in the built file. Verify v3's "your" vs "my" verb mismatch is fixed to consistent "my." |
| Hero card density | Seven typographic registers in one card. Visual judgment. | Gut-check at 1440px on the actual build. |

### Owned tradeoffs (defend in the Loom, don't fix)

| Element | The trade | The Loom narration |
|---|---|---|
| Two CTAs above the fold | Contradicts +6% data on single CTA. | *"I broke the single-CTA rule because at $99 the dominant objection is 'show me how it works first.' Routing skeptics to the loop section beats bouncing them. I'd A/B test it."* |
| No founder presence / origin story | Contradicts the Silvi pattern. | *"Volley's founder isn't a public figure yet. A future variant adds a founder note. For this build, the human-in-the-loop IS the founder substitute."* |
| Pimsleur named in fear, missing from comparison | Inconsistent. | *"Pimsleur is the legacy app I named for emotional credibility but excluded from the price comparison because nobody actually evaluates Pimsleur on monthly subscription cost — they bought a $300 box set in 2014 and stopped opening it in 2015."* |

### Thin / inferential calls (acknowledge if asked)

| Element | Why thin | The defense |
|---|---|---|
| "Same tutor every time" | Inferred from lp3, not verbatim. | *"Strongly implied by Volley's 'your tutor reviews your week' language. Verified before shipping."* |
| "Adapts to your specific blindspots" Speak ✗ in table | Speak does some adaptation. | *"Speak's adaptation is curriculum-level, not blindspot-level. The row is true in spirit, defensible in nuance."* |

---

## 6. The Loom narration cheat sheet

One sentence per section, ready to paraphrase live. Each follows the 3-beat: *what / why / what I'd test next.*

| Section | What | Why | A/B against it |
|---|---|---|---|
| Hero wedge | *"Coach who notices when you skip a day."* | Unclaimed wedge per recon (Speak owns speaking, Langua owns realism, no one owns accountability). | A "fear of speaking" variant. |
| Hero microcopy | *"1,000+ learners practicing this week · $99/mo · cancel anytime."* | Single-stat lifts +18% per synthesis doc; honest small-number framing earns trust at premium tier. | A different stat formulation. |
| Hero visual | Split: AI mock + tutor card. | Makes "AI + human" structure unmissable in 5 seconds. | Single hero artifact (just the tutor's weekly note). |
| Fear section | 3-paragraph emotional acknowledgement. | Volley's own strongest line ("you need someone making sure you show up") expanded into a failure narrative. | Skip the fear, lead with offer. |
| Weekly loop | 3 numbered steps. | Snowball cadence + mirrors Volley's actual product loop. | A 5-step bookended version. |
| Same-human section | Continuity-of-tutor as a moat. | iTalki/Preply rotate; Volley assigns and keeps. The "week-six knows week-two" line is the cleanest articulation of the moat. | Make continuity the H1 wedge instead of accountability. |
| Comparison | 4-column, Volley loses on price. | Counter-positioning by name + honest table per design brief §7E. | Add a 5th losing row (gamification / language count). |
| Price math | $25/lesson + $0/AI + $0/plan. | Closes the price-justification gap that v3 was missing. iTalki $40-80/hr is the verifiable benchmark. | A single "vs hiring a tutor + buying Speak" callout under the comparison instead of a dedicated section. |
| Testimonials | 3 verbatim from lp3. | Named-customer specificity (+22% lift per synthesis doc). | Single-dominant testimonial variant. |
| FAQ | 4 highest-stakes objections, #1 expanded. | Pulled from Volley's own FAQ list; #1 is the chatbot-skepticism objection at $99. | Always-expanded variant. |
| Final CTA | *"Ships with a real tutor, not a chatbot."* | Wedge in 8 words. Snowball-style sign-off. | Soft "questions? text us" CTA. |
| Sticky CTA | Triggers after weekly loop. | Per synthesis doc + earned-the-right principle. | Immediate-on-hero-exit trigger. |
| Palette | Warm-light. | Differentiation should come from copy/wedge, not from a brand-flip. | Editorial-dark variant. |

---

## 7. What this doc is NOT

- Not a copy lock. Copy can change. The decisions above are the *frame* — copy iterates inside the frame.
- Not a design lock. Once the built file is in the repo, §4 gets a final update with palette/layout decisions defended.
- Not a substitute for the Loom. Max watches the Loom to see how you *think*; this doc just makes sure the thinking has a paper trail.
- Not for Max's eyes. This is internal. The deck/PDF will summarize the strategic frame; the Loom will narrate the decisions; this doc is the script-prep.

---

## 8. Open questions (resolve before final submission)

1. **Final fixes to the copy** (§5 table) — iTalki/Preply tightening, "$0 → included" rephrasing, "no separate product" softening, Babbel price verification, sticky CTA presence/verb. ~10 minutes total.
2. **Hero card density** — visual gut check at 1440px on the built file. May or may not need typographic simplification.
3. **Palette lock** — warm-light recommended in §4. Confirm before Claude Design's final pass.
4. **Sticky CTA verification** — confirm it's in the built file and verb-consistent.
5. **Italic emphasis count** — verify in the built file that italic is used 2-3x max, not on every H2 (the v2 mistake).
6. **Em-dash / banned-word grep** — run before handoff. Zero tolerance.
7. **5-second test** — open the built file at 1440px, look at the hero for 5 seconds, close. Did you understand what / who / why? If no, revise.
8. **WCAG AA contrast check** — secondary ink on whatever background must hit 4.5:1 for body text.
