# Volley + Snowball — Chief Achiever submission

48-hour submission for Max Hertan's Chief of Staff / "Chief Achiever" challenge. Two real problems on Max's plate: a marketing build for **Volley** (AI + human language coaching app at $99/mo), and a hiring search for **Snowball Agency**.

## Live build

**Volley landing page variant:** [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/) — single-file, deployed via Vercel from this repo.

## The deliverables

Per the [challenge brief](research/04_challenge_brief.md):

### Challenge 1 — Volley

| | What | Where |
|---|---|---|
| **Landing page variant** | Live HTML build, warm-light palette, real photos, rotating language samples (FR / IT / ES), 30-day refund surfaced, all em-dashes scrubbed | [shadowlight-xi.vercel.app](https://shadowlight-xi.vercel.app/) · source: [`index.html`](index.html) |
| **Rationale (1-page)** | What I changed vs lp3, why, the testable hypothesis, the kill order if it fails | [LP_RATIONALE.md](LP_RATIONALE.md) |
| **3 Meta ad angles** | Quick Math (CEO + plant), She's a 10 (POV romcom), Tutor Manifesto (Masterclass-format) — full scripts, camera direction, sound, casting | [ADS_CREATIVE_BRIEFS.md](ADS_CREATIVE_BRIEFS.md) |
| **Testing plan (1-page)** | 14-day, $1,200 budget, format-specific kill criteria, decision tree | [TESTING_PLAN.md](TESTING_PLAN.md) |

### Challenge 2 — Snowball Head of Sales

| | What | Where |
|---|---|---|
| **3 candidates** | Christian Liquigan (Receipts), Jack Frimston (Mindshare), Nate Nkangwen (Native) — LinkedIn, role, why, outreach DM each | [CANDIDATE_SHORTLIST.md](CANDIDATE_SHORTLIST.md) |
| **Hunting methodology** | Three-lens search frame, paste-ready Sales Nav recipes, niche behavioral signals, fit rubric | [research/07_recruitment_gameplan.md](research/07_recruitment_gameplan.md) |
| **Full dossiers** | Detailed per-candidate breakdown, the cut decision (why Justin Adelman didn't make the shortlist), Loom narration script | [research/08_candidate_dossiers.md](research/08_candidate_dossiers.md) |

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
