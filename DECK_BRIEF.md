# Claude Design — pitch deck brief for the Chief Achiever submission

> Read this top to bottom. Then read the codebase. Then build.
>
> This is **not a content spec**. The codebase is the content. Your job is to extract the strongest material from it, distill it into a scrollable editorial pitch deck, and host it on Vercel as a single self-contained HTML file. The deck's job is to make it impossible for Max to miss the *thinking* behind every deliverable.

---

## §1. What you're building

**A single-page scrolling pitch deck**, served as one self-contained HTML file (CSS + JS inline), Vercel-hostable, print-PDF-able as backup.

Audience: **Max Hertan**. He's the operator who wrote the [challenge brief](research/04_challenge_brief.md). He told us:

> *"I don't care if your slides are pretty. Strategic thinking. Speed. Taste. The ability to make a call with incomplete information and explain it cleanly."*

Translation: pretty doesn't hurt, but every section must visibly earn its space by demonstrating a decision and its receipts. **Show, don't tell. Receipts, not assertions.**

Format choice: **single-page editorial scroll**, not slide-by-slide PowerPoint. Why:
- Max's own brands (Snowball, Silvi, Megaphone) all use scrolling editorial pages. The format reads as house style, not generic deck.
- Faster to read on a phone, faster to share, faster to print.
- Feels like a confident executive briefing, not a sales deck.

Length target: **10–12 sections, ~8–12 minutes to read end-to-end.** Loom narration is the 5-minute companion; the deck is what Max keeps after.

---

## §2. Read the codebase before you start building

The repo is at [github.com/amikovid/shadowlight](https://github.com/amikovid/shadowlight) — public. Two-tier source structure: **short docs** (1-page exec summaries for navigation and quick context) and **long docs** (full source material with receipts, frameworks, and specific quotes). **Actively choose** which to pull from depending on what you're building.

### Reading order

| Order | File | Why first |
|---|---|---|
| 1 | [README.md](README.md) | Max-facing nav. Map of everything. |
| 2 | [research/04_challenge_brief.md](research/04_challenge_brief.md) | What's being graded. |
| 3 | [research/01_max_dossier.md](research/01_max_dossier.md) | Voice calibration. Max-coded language patterns. |
| 4 | All other short docs (LP_RATIONALE, TESTING_PLAN, CANDIDATE_SHORTLIST) | Exec summaries; navigation through the deliverables. |
| 5 | Long docs (JUSTIFICATION_DOC, ADS_CREATIVE_BRIEFS, research/07, research/08) | Pull-as-needed for receipts and specific quotes. |

### Mapping table — deck section → source

| Building this section | Pull primarily from (short, exec) | Pull deeper from (long, receipts) |
|---|---|---|
| **Greeting / meta summary** | Write fresh, but mirror voice from [research/01_max_dossier.md](research/01_max_dossier.md) | — |
| **The setup (two problems)** | [research/04_challenge_brief.md](research/04_challenge_brief.md) | — |
| **Volley wedge** | [LP_RATIONALE.md](LP_RATIONALE.md) §"In one sentence" + §"The wedge" | [research/02_volley_recon.md](research/02_volley_recon.md) §"The wedge that's actually unclaimed" |
| **Volley LP variant** | [LP_RATIONALE.md](LP_RATIONALE.md) §"What I changed" table | [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md) §2 (per-section decisions) for sharper quotes |
| **Volley ads (3 angles)** | [TESTING_PLAN.md](TESTING_PLAN.md) §"The philosophy" + the three-angle table | [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md) for full scripts, casting, sound, **inspirations** |
| **Volley testing plan** | [TESTING_PLAN.md](TESTING_PLAN.md) | — |
| **Snowball framework** | [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md) §"The framework" | [research/08_candidate_dossiers.md §2](research/08_candidate_dossiers.md) for the four-bets reasoning |
| **Snowball candidates** | [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md) §"The three picks" | [research/08_candidate_dossiers.md §3-5](research/08_candidate_dossiers.md) for receipts, specific reasons, risks |
| **Snowball outreach** | **Summarize only.** Link to [OUTREACH.md](OUTREACH.md) — do not waste real estate quoting full DMs. | [OUTREACH.md](OUTREACH.md) |
| **The cut (Justin)** | Reference [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md) §"A fourth bet was considered and cut" | [research/08_candidate_dossiers.md §6](research/08_candidate_dossiers.md) for the full defense |
| **How I hunted (methodology)** | [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md) §"How I hunted" | [research/07_recruitment_gameplan.md](research/07_recruitment_gameplan.md) for the lens framework + niche signals |
| **Loom hook** | Write fresh, frame it as the companion piece | — |
| **Closer / decision philosophy** | Pull from across the codebase — the consistent voice across LP_RATIONALE, candidate dossiers, justification doc | — |

---

## §3. Structural shape (10–12 sections)

Section list in order. Each section is **one screen worth of scroll** unless noted. Each section ends with a **"further reading"** footer link to the relevant source doc.

### 1. Greeting / meta summary

Open the deck with a direct address to Max. Acknowledge the 48 hours. Set the structure. Something in the spirit of:

> *"For Max, with respect. 48 hours of work on the two problems you put in front of me — Volley and Snowball. Below is the executive narrative: how I thought about each, what I built, and the decisions I made along the way. Every section is short by design; every claim links back to the underlying research. If you only have 5 minutes, the Loom is at [link]. The deck is the receipts."*

Distill this in your own voice — don't copy verbatim. **Personal, confident, not sycophantic.**

Below the greeting: a quick navigator (anchor links to each subsequent section), so Max can skim or jump.

### 2. The setup

A one-screen orientation. Frame the two problems Max put in front:

- **Volley:** AI + human language coaching app at $99/mo. *"Pretend I just handed you the account."*
- **Snowball:** Find a Head of Sales. *"Don't send me obvious org-chart picks."*

Plus the meta-deliverable: the 5-minute Loom that Max said is "where this is won or lost." Make clear the deck is the *receipts*; the Loom is the *thinking*.

### 3. Volley — the wedge

**One screen, dominant typography, one big claim.**

Pull the strategic call from [LP_RATIONALE.md](LP_RATIONALE.md):

> *"You don't need another language app. You need a coach who notices."*

Show the wedge derivation in 3–4 lines: Speak owns "speak out loud," Langua owns "realistic AI voices," Praktika owns "private-tutor feel," Duolingo owns "habit." Volley's unclaimed wedge: **accountability**. The variant is the page that finally claims it.

Footer: *"Read more in [LP_RATIONALE.md](LP_RATIONALE.md) and [research/02_volley_recon.md](research/02_volley_recon.md)."*

### 4. Volley — the page

Live build embedded as iframe (or hero screenshot if iframe fails on mobile) at [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/).

Below the embed: the **5-move change list** from [LP_RATIONALE.md](LP_RATIONALE.md) §"What I changed." Compress to a tight visual table. Each row: lp3 → variant → why.

Footer: *"Full decision log: [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md)."*

### 5. Volley — the funnel (3 ad angles)

This is the biggest section. **Show the three angles as a coherent funnel, not three random picks.**

Pull from [TESTING_PLAN.md](TESTING_PLAN.md) §"The philosophy":

> *"Three angles, three funnel stages, three creative grammars. Find the one winner fast, pour gas. Don't try to maximize coverage — try to compound the win."*

Then the three-angle table: format, length, funnel stage, **inspiration links**. Pull the inspirations from [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md) — they're listed per angle. Hyperlink to actual reference videos / styles where possible:

| Angle | Inspiration to link |
|---|---|
| **Quick Math** | Cliff Weitzman / Speechify TikToks |
| **She's a 10** | Roy Lee / Cluely viral POV format, *La La Land* / *Past Lives* trailer pacing |
| **Tutor Manifesto** | Aaron Sorkin Masterclass trailer, NYT Modern Love video pieces |

For each angle, give a tight 4–6 line story: hook + format + length + key creative move + why it works for that funnel stage. Don't reproduce the full script. Link to [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md) for those.

Footer: *"Full creative briefs: [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md). The 10-angle brainstorm that produced these three: [ADS_BRAINDUMP.md](ADS_BRAINDUMP.md). Competitor teardowns: [research/06_meta_ads_research.md](research/06_meta_ads_research.md)."*

### 6. Volley — testing plan

Pull from [TESTING_PLAN.md](TESTING_PLAN.md). Show the visual sequence (7-day spend table) + the kill order. Don't reproduce the whole doc — the spend table + the three lead metrics + the kill order is enough for the deck.

Specifically include: **the "what I'd kill from THIS plan if forced" closer.** That's a Max-coded "make a call" moment.

Footer: *"Full plan: [TESTING_PLAN.md](TESTING_PLAN.md)."*

### 7. Snowball — how I hunted

Methodology before candidates. Pull from [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md) §"The framework":

> *"Three candidates representing three strategic bets on what the role actually needs. Not three picks from one search — three hypotheses about where the operator should come from, each represented by the strongest exemplar."*

Show the four-bet table (Receipts / Mindshare / Native / Rolodex), with Rolodex marked as cut.

Then a 3–4 line summary of HOW each candidate surfaced — the search lenses + niche signals. Pull from [research/07_recruitment_gameplan.md](research/07_recruitment_gameplan.md) §"The niche behavioral angles" for the off-org-chart signals (verbal tics, online shoutouts, podcast guest sweeps, layoff trigger windows).

Footer: *"Full hunting framework + Sales Nav recipes + niche signals: [research/07_recruitment_gameplan.md](research/07_recruitment_gameplan.md)."*

### 8. Snowball — the three

One section, three stacked candidate cards. **Typographic, not portrait-photo.** Editorial restraint > stock-photo collage.

Per candidate, show:
- Name + bet name (e.g. *"Christian Liquigan — The Receipts Bet"*)
- LinkedIn URL (clickable)
- Current role + company + location
- **The receipt** — one specific number or fact from their work that locks the pick. From [research/08_candidate_dossiers.md](research/08_candidate_dossiers.md):
  - Christian: *"<$50K → multi-million Auto book at TikTok in 18 months. 23% of Auto revenue in 2021."*
  - Jack: *"Author of Sales Is Therapy. Co-Director of UK's 2nd Best Sales Agency. Bio ends with 'remember you will die.'"*
  - Nate: *"$32k direct revenue from one client video this month. Faze Rug as a client. 150M+ aggregate views in 28 months."*
- **The specific reason** — 2-3 sentences on why him for THIS bet
- **Outreach hook** — one-line summary of what the DM leads with (e.g. *"DM leads with the TikTok Auto stat in the subject line"*). Link to [OUTREACH.md](OUTREACH.md) for the full message — **do not reproduce the DMs in the deck.**

Footer: *"Full per-candidate dossiers: [research/08_candidate_dossiers.md](research/08_candidate_dossiers.md). Outreach DMs: [OUTREACH.md](OUTREACH.md)."*

### 9. Snowball — the cut (Justin)

One screen explaining what got cut and why. Pull from [research/08_candidate_dossiers.md §6](research/08_candidate_dossiers.md):

> *"The Rolodex Bet got cut. Snowball's brand already pulls Fortune 500 CMOs through inbound. The salesperson's job is to close what comes in and expand into adjacent verticals — not to bring relationships in their phone."*

Three-reason defense, in tight form:
1. Rolodex is the most-replaceable bet for Snowball specifically
2. Justin's relationships partially redundant with Christian's
3. Justin is the most "obvious-on-paper" of the four — least off-org-chart, against Max's explicit ask

This section is critical for the "how you hunt" grading axis. **Showing what we cut is showing how we think.**

Footer: *"Full cut rationale: [research/08_candidate_dossiers.md §6](research/08_candidate_dossiers.md)."*

### 10. The Loom

A small section at the end of the substantive content. Embedded link to the Loom video (placeholder URL — Kovid will fill).

> *"Decks tell you what I did. The Loom tells you how I think. Five minutes."*

Plus a short outline of what's in the Loom (~3 beats, one line each — Volley thinking, Snowball hunting, decision philosophy).

### 11. What I'd do on Day 1

Closing section. The decision philosophy that runs through both deliverables. Compressed Kovid-voice summary — what working with this person would look like. Anchored in:

- **Volley:** *"At $99 the bottleneck is trust, not awareness. I'd ship this variant against lp3 Monday."*
- **Snowball:** *"Reach out to Christian first, even at low yes-probability. The conversation is worth it whether or not the hire lands."*
- **Decision philosophy:** *"Make the call. Cite the receipt. Ship the test."*

This section is **essential** — Max grades on "the ability to make a call with incomplete information and explain it cleanly." The closer is where you prove that capacity in Kovid's voice.

### 12. Appendix — further reading

A clean link tree to the entire research folder + working docs. Group by topic:

- **The thinking behind the LP:** [LP_RATIONALE.md](LP_RATIONALE.md), [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md), [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md)
- **The thinking behind the ads:** [TESTING_PLAN.md](TESTING_PLAN.md), [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md), [ADS_BRAINDUMP.md](ADS_BRAINDUMP.md), [research/06_meta_ads_research.md](research/06_meta_ads_research.md)
- **The thinking behind the candidates:** [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md), [OUTREACH.md](OUTREACH.md), [research/07_recruitment_gameplan.md](research/07_recruitment_gameplan.md), [research/08_candidate_dossiers.md](research/08_candidate_dossiers.md)
- **The voice and product context:** [research/01_max_dossier.md](research/01_max_dossier.md), [research/02_volley_recon.md](research/02_volley_recon.md), [research/03_landing_page_synthesis.md](research/03_landing_page_synthesis.md)
- **The challenge brief itself:** [research/04_challenge_brief.md](research/04_challenge_brief.md)

---

## §4. Voice rules (binding)

Mirror the voice from the LP build. Specifically:

- **No em-dashes anywhere.** Body, captions, footers, even HTML/CSS comments. Use commas, periods, parentheses, line breaks, en-dashes, or middots. Run `grep "—"` before declaring done.
- **No banned words.** *delve · comprehensive · seamless · leverage · foster · facilitate · elevate · robust · holistic · "in today's fast-paced world."*
- **Lowercase eyebrows.** Mono font, lowercase, letter-spaced. Section labels read as eyebrows above the H2.
- **Italic emphasis is signature, not decoration.** Use 2–3 times across the entire deck — not per section. Each italic word/phrase must be the operative pivot.
- **Counter-position by name.** Don't say "every other app." Say "Speak. Langua. Praktika." Don't say "obvious-on-paper picks." Say "Head of Sales at Whalar."
- **Specificity over abstraction.** Real numbers, real names, real receipts, real scenarios. Always. Per [research/01_max_dossier.md](research/01_max_dossier.md): *"Real numbers, real names, real scenarios. Always."*
- **Confidence without hedging.** "Will," not "may." "Does," not "can." Pick a side every time.
- **First person, restrained.** "I built…" "I cut…" "I'd ship…" Not "we" unless referring to Snowball/Volley as the subject.

What success looks like: a copywriter reading the deck couldn't tell if it was AI- or human-written, and a strategist would say *"this sounds like a Snowball page."*

Source: full voice rules in [research/01_max_dossier.md](research/01_max_dossier.md). 2026 conversion data backing the no-em-dash and banned-word rules in [research/03_landing_page_synthesis.md](research/03_landing_page_synthesis.md) §3.

---

## §5. Design system (match the LP)

Mirror the LP at [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/) for brand consistency. Specifically:

### Palette (warm light)

```
--bg: #F5F0E5      (warm cream background)
--bg-2: #EFE8D8    (slightly darker cream for nested cards)
--surface: #FFFFFF (white card surfaces)
--ink: #1A140F     (deep brown-black for body text)
--ink-2: #6B5E4D   (warm gray for secondary text)
--hairline: rgba(26, 20, 15, 0.12)
--accent: #E04E2C  (orange-red for CTAs, italics, key punctuation)
--tutor: #3F7A5C   (warm green for human-tutor accents — used sparingly)
```

For occasional dark sections (the wedge slide can go full-bleed dark), invert: warm cream type on `#1A140F` background with `#F5F0E5` ink.

### Typography

- **Display:** Fraunces, weight 500–600. Variable-font opsz 144 for headlines >40px. Italic accent on `<em>` in display copy.
- **Body:** Inter, weight 400–600. 16–17px on body, line-height 1.55–1.7.
- **Mono (eyebrows, microcopy, link labels):** JetBrains Mono, weight 400–500, lowercase, letter-spacing 0.06–0.10em, 11–13px.

### Components

- **Eyebrows above H2s:** mono lowercase + a short hairline (the LP does this — 18px tail before the text).
- **Italic accent on H1/H2 pivot words:** Fraunces italic in `--accent` color. 2–3 across the entire deck. Don't sprinkle.
- **Cards:** subtle border (1px hairline), generous padding (32px+), gentle hover lift on link cards. No drop shadows on the warm-light bg.
- **Tables:** clean, no zebra striping. Volley column or "winner" column subtly tinted with `--accent` at 5% alpha.
- **Footer links per section:** mono small, prefix with a small arrow or hairline, e.g. *"→ further reading: [doc.md](doc.md)."*

### Motion (sparingly)

- Reveal-on-scroll for major sections (IntersectionObserver, opacity + translateY).
- One signature animation — propose a strikethrough on a competitor name in the wedge slide, OR a subtle accent-color reveal on the *"coach who notices"* italic in the wedge H1. Not both.
- Respect `prefers-reduced-motion`.

### Embeds

- **Live LP iframe** in §4 (Volley — the page). If iframe is awkward at scale, use a high-resolution screenshot with a clickable overlay linking to the live URL.
- **Loom embed** in §10. Use Loom's standard responsive embed code.
- **Inspiration video links** in §5 (Volley — the funnel) — text-link with a small play-icon prefix is enough; don't try to embed third-party TikTok/YouTube unless trivially possible.

### Imagery

- **No stock candidate photos.** Editorial restraint. Typographic candidate cards.
- **No "happy person on laptop" stock.** If a section needs imagery beyond typography, use real product UI mockups (already in the LP), real LinkedIn URL previews, or skip imagery entirely.

---

## §6. Hard rules (these are submission-killers if violated)

1. **No fabricated facts.** Every claim about Volley is sourced. Every candidate detail is real (per dossier in [research/08_candidate_dossiers.md](research/08_candidate_dossiers.md)). If you encounter ambiguity, leave a clearly marked PLACEHOLDER and document what to fill (see §8).
2. **Outreach DMs do NOT appear in full in the deck.** Summarize each in one line ("DM leads with X"), link to [OUTREACH.md](OUTREACH.md) for the actual messages. Real estate matters.
3. **Every section ends with a "further reading" footer link** to the relevant source doc. This is part of the deck's grading argument — *"the methodology is provable, not asserted."*
4. **Em-dash sweep before declaring done.** Run `grep "—"` on the final HTML. Zero matches expected.
5. **Banned-word sweep.** Run `grep -iE "delve|comprehensive|seamless|leverage|foster|facilitate|elevate|robust|holistic"`. Zero matches.
6. **Real LinkedIn URLs for candidates** — clickable. No mock URLs.
7. **Live LP URL** ([shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/)) embedded or linked, not just described.
8. **Loom URL** is a placeholder until Kovid records it. Use a clearly marked `[LOOM_URL_TBD]` token; do not invent.

---

## §7. Inspirations to reference (deck aesthetic + ad creative)

### Deck aesthetic

- **Snowball Agency** ([snowball.agency](https://snowball.agency)) — Max's own house style. The scrolling-page-as-pitch-deck convention. **Most important reference.**
- **Silvi** ([silvi.com](https://silvi.com)) — Max's DTC brand. Editorial type-driven product page.
- **Atlantic Re:think** — long-form editorial brand-content pages. The pacing reference.
- **NYT "Modern Love" video pieces** — for embedded-video editorial pacing.

### Ad creative inspirations (for §5 — Volley funnel)

Already in [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md). Re-emphasize in the deck section so Max sees we've done the homework on creative reference:

- **Quick Math:** Cliff Weitzman / Speechify direct-to-camera TikToks (kitchen aesthetic, fast zoom, casual conviction)
- **She's a 10:** Roy Lee / Cluely viral POV format (competence-as-seduction); *Past Lives* / *La La Land* trailer pacing for the romantic-jazz crescendo
- **Tutor Manifesto:** Aaron Sorkin Masterclass trailer (credentialing-then-philosophy-then-anecdote rhythm); NYT Modern Love video pieces (contemplative pacing); Apple "Crazy Ones" spot (make-the-viewer-fall-in-love-with-the-person-before-mentioning-product)

For each, link to a Google search or an actual reference video where possible. The point: showing Max we know the reference set, not just the trend.

---

## §8. Placeholder protocol

**Default behavior: fill out as much as possible from the codebase.**

When you legitimately can't:

1. Use a clearly marked placeholder token: `[LOOM_URL_TBD]`, `[CANDIDATE_PHOTO_TBD]`, etc. NOT a generic "placeholder" — a typed token Kovid can find-and-replace.
2. At the bottom of the deck (or as a hidden HTML comment Kovid can find), maintain a **placeholder list**: every TBD with a one-line description of what to fill.
3. **Ask before you guess.** If a section needs a piece of content you can't find in the codebase and can't reasonably extrapolate (e.g. specific Volley pricing tiers beyond $99/mo, candidate phone numbers, etc.), leave a PLACEHOLDER and flag it in your handback note.

For data we KNOW won't be there yet:
- **Loom URL** — `[LOOM_URL_TBD]` everywhere it appears
- **Specific A/B test results** — none exist; the testing plan is forward-looking, not retrospective
- **Candidate phone numbers / direct emails** — not collected, will be obtained through their reply to outreach

---

## §9. Deliverable

- One self-contained HTML file: `/index.html` in a new repo or branch (suggest: `deck/` subdirectory of the existing `shadowlight` repo, OR a new `shadowlight-deck` repo — Kovid's call).
- All CSS + JS inline (same pattern as the LP build).
- Vercel-deploy-ready (`vercel.json` simple static-build config in the same directory).
- Print-PDF-able from a browser. Test before declaring done.

After the build, send back a one-paragraph handback note covering:
1. Which short vs long docs you pulled from per section, in case Kovid wants to swap a quote
2. Any tradeoffs you made that contradict the brief (and why)
3. The full list of placeholder tokens that need Kovid to fill in
4. Specific lines you'd want Kovid to voice-check before publishing (anything the codebase doesn't have a clear precedent for)

---

## §10. The Loom test (your real grading rubric)

Every section in the deck must survive Max's 30-second narration test:

1. **What I decided** — the choice, in one sentence.
2. **Why I decided it** — citing a source doc or a real piece of evidence.
3. **What I'd test next** — the alternative hypothesis I'd run an A/B against this.

If a section's content can't be defended in those three beats, the section isn't strong enough. Either find the citation (somewhere in the codebase — it's there) or rewrite the section.

This is the actual bar. Build for that.

---

## §11. Closing — what makes this deck land vs not

The deck wins if:

- **Max can read it in 8 minutes** and feel he's seen the thinking behind every deliverable
- **Every claim has a receipt** (a quote, a number, a named source)
- **The cuts are visible** (Justin, the meme set, the v6 conviction-takedown that got burned) — showing what we passed on is showing how we judged
- **The voice is unmistakably Max-coded** (no em-dashes, lowercase eyebrows, italic signature, counter-positioning by name)
- **The Loom is positioned as the companion** (not a redundant version of the deck — a different artifact entirely)

The deck loses if:

- It reads as generic agency-pitch (template energy)
- It buries the cut decisions (only shows the picks, not the rejected ones)
- It tries to fit too much (every section bloats; nothing lands)
- The voice drifts (em-dashes creep in; "leverage" appears once)
- The Loom URL is missing or the deck doesn't reference it explicitly

Build for the wins. Avoid the losses. Ship.

---

> **One more note:** if anything in this brief contradicts something in the codebase, **the codebase wins.** This brief was written before the build; the docs may have iterated since. Trust the code, trust the research, and reach out if you hit ambiguity.

— Kovid (via the codebase)
