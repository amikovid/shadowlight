# Volley + Snowball — Chief Achiever submission

48-hour submission for Max Hertan's Chief of Staff / "Chief Achiever" challenge. Two real problems on Max's plate: a marketing build for **Volley** (AI + human language coaching app at $99/mo), and a hiring search for **Snowball Agency**.

## Live build

**Volley landing page variant:** [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/) — single-file, deployed via Vercel from this repo.

## The deliverables

Per the [challenge brief](research/04_challenge_brief.md):

### Challenge 1 — Volley

Each deliverable comes in a **short 1-page exec summary** AND a **long source doc** with full receipts. The short docs link out to the long ones for specific quotes / framework details / kill-order nuance.

| | What | Short (exec) | Long (source) |
|---|---|---|---|
| **Landing page variant** | Live HTML build, warm-light palette, real photos, rotating language samples (FR / IT / ES), 30-day refund surfaced, all em-dashes scrubbed | [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/) · source: [`index.html`](index.html) | — |
| **LP rationale** | Wedge derivation, 5-move change list vs lp3, voice discipline rules, hypothesis, kill order, what-I'd-test-next | [LP_RATIONALE.md](LP_RATIONALE.md) | [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md) (every sub-decision with citation, alternative, A/B that would falsify) |
| **3 Meta ad angles** | Quick Math (CEO + plant), She's a 10 (POV romcom), Tutor Manifesto (Masterclass) — see testing plan for the funnel logic | (lives in long) | [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md) (full scripts, casting, camera, sound, A/B variants, inspirations) |
| **Testing plan** | Philosophy + 7-day spend table + lead metrics per angle + kill order + decision tree | [TESTING_PLAN.md](TESTING_PLAN.md) | embedded in [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md) §"How the three angles fit together" |

### Challenge 2 — Snowball Head of Sales

| | What | Where |
|---|---|---|
| **3 candidates (1-page exec)** | Christian Liquigan (Receipts), Jack Frimston (Mindshare), Nate Nkangwen (Native) — framework + 1 paragraph each | [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md) |
| **Outreach DMs** | The actual messages I'd send each candidate (LinkedIn for Christian + Jack, X DM for Nate) | [OUTREACH.md](OUTREACH.md) |
| **Hunting methodology** | Three-lens search frame, paste-ready Sales Nav recipes, niche behavioral signals, fit rubric | [research/07_recruitment_gameplan.md](research/07_recruitment_gameplan.md) |
| **Full dossiers (long)** | Detailed per-candidate breakdown, career arcs, rubric scores, risks with mitigation, the cut decision (why Justin Adelman didn't make the shortlist), Loom narration script | [research/08_candidate_dossiers.md](research/08_candidate_dossiers.md) |

### Challenge 3 — Loom

5-minute walkthrough. Linked separately in the email reply.

## How decisions got made

If you want to read deeper into the *why* behind anything in the deliverables:

- [JUSTIFICATION_DOC.md](JUSTIFICATION_DOC.md) — every meaningful LP decision with the citation, the alternative considered, and the A/B test that would falsify it
- [CLAUDE_DESIGN_BRIEF.md](CLAUDE_DESIGN_BRIEF.md) — the brief that produced the LP build (strategic frame, voice rules, structural decisions)
- [ADS_BRAINDUMP.md](ADS_BRAINDUMP.md) — the original 10-angle brainstorm before narrowing to 3

## How I researched

The [`research/`](research/) folder has the full reference set, in the order it was built:

| File | What it is |
|---|---|
| [`00_index.md`](research/00_index.md) | Folder TOC |
| [`01_max_dossier.md`](research/01_max_dossier.md) | Max's voice, house style across Snowball/Megaphone/Silvi, counter-positioning instinct |
| [`02_volley_recon.md`](research/02_volley_recon.md) | Volley product reality, competitive map, real testimonials, what we can/cannot claim |
| [`03_landing_page_synthesis.md`](research/03_landing_page_synthesis.md) | 2026 LP conversion data + Max house style + category conventions |
| [`04_challenge_brief.md`](research/04_challenge_brief.md) | Max's verbatim challenge brief |
| [`05_job_description.md`](research/05_job_description.md) | The JD with Loom-relevant analysis |
| [`06_meta_ads_research.md`](research/06_meta_ads_research.md) | Competitor ad teardowns (Duolingo, Praktika, Babbel, Jumpspeak, Speak) + Max's brands (Megaphone, Snowball, Silvi) + 2026 Meta best-practice data |
| [`07_recruitment_gameplan.md`](research/07_recruitment_gameplan.md) | Snowball Head of Sales hunting framework |
| [`08_candidate_dossiers.md`](research/08_candidate_dossiers.md) | Full per-candidate breakdown |

## Repo notes

- Public. Anyone with the URL can read everything.
- Vercel auto-deploys the LP from `main`.
- Internal Claude Code settings (`.claude/`) and raw design handoff bundles (`design_pkg/`) are gitignored.

— Kovid Bhaduri
