# Volley landing page — design brief for Claude Design

> Self-contained brief. Written so a designer with no prior context can build a defensible, on-strategy variant in one pass. Read top to bottom before opening a file.

---

## 1. What you're building (and what it's for)

A single-page landing page for **Volley** — an AI + human language coaching app at $99/month — as the primary deliverable in a 48-hour challenge for a Chief of Staff role with Max Hertan (Snowball, Megaphone, Silvi).

The brief from Max literally says: *"Pretend I just handed you the account. What would you change, and how would you prove it works?"* Volley's current page lives at **getvolley.ai/lp3**. We are not redesigning it for sport — we are pitching a paid-ads-ready A/B variant we'd ship Monday.

What Max grades on (his words): *"Strategic thinking. Speed. Taste. The ability to make a call with incomplete information and explain it cleanly."*

Output: one self-contained HTML/CSS/JS file. No build step. Should look beautiful at 1440 × 900 desktop and degrade cleanly to 375px mobile.

---

## 2. The product (do not invent features)

Volley is **a hybrid: a real human tutor + an AI practice app.** Not pure AI. Not pure tutoring. The loop:

1. You take a 2-minute placement test, get matched with a human tutor.
2. You get **4 × 30-min live tutor lessons per month**.
3. Between lessons, you do **unlimited AI practice** in the app: voice chat, audio lessons, smart flashcards (mistakes from conversations become flashcards).
4. The AI logs every word you said, every mistake, every flashcard reviewed.
5. Once a week, your tutor opens that data, finds your weak spots, and adjusts next week's plan.

That weekly review loop is the actual moat. Most "AI language apps" have no human; most "tutoring apps" have no AI feedback loop. Volley does both.

**Languages confirmed** (from real testimonials on lp3): French, Spanish, Swedish. Likely more — don't claim a count we don't have.

**Platforms**: iOS + Android (per their FAQ). Web likely.

**Public proof points we can repeat verbatim**: "1,000+ learners," 5-star rating, three named testimonials (see §6).

**Read [02_volley_recon.md](research/02_volley_recon.md) before writing copy** — it has the full product map, the full quote bank, and what Volley's page currently does well/badly.

---

## 3. The wedge (this is the whole strategic bet)

Speak owns "speak out loud." Langua owns "realistic AI voices." Praktika owns "feels like a private tutor." Duolingo owns "habit." None of them have a real human in the loop.

**Volley's unclaimed wedge: accountability.**

> *You don't need another app. You need a coach who notices when you skip a day.*

This frame:
- Matches the actual product (the human tutor IS the differentiator)
- Counter-positions cleanly against pure-AI competitors AND gamified legacy apps
- Justifies the $99/mo price (humans cost money; AI alone doesn't)
- Lands the strongest line on Volley's own page ("you don't need more content; you need someone making sure you show up")
- Is unclaimed in May 2026 per the recon

The page should make this wedge unmissable in the first viewport.

---

## 4. Who you're writing for

**Primary persona: the app-dropout adult.** 28–45. Has tried Duolingo, Babbel, Pimsleur, maybe Speak. Quit each one within 60 days. Can read a menu in their target language. Cannot order from one out loud. Has a real reason to learn — partner's family, work travel, immigration, a trip booked. Has $99/month of disposable income and is past the point of pretending another free app will fix this.

What they want to hear: *"You're not bad at this. You just stopped showing up. Here's the thing that fixes that."*

What they don't want to hear: another "fluency in 30 days" promise. They've heard it. They're cynical. Earn the click with specificity, not hype.

---

## 5. Voice rules (binding — Max grades on this)

Max's voice is documented in [01_max_dossier.md](research/01_max_dossier.md). The non-negotiables:

- **No em-dashes. Anywhere.** Use commas, periods, parentheses, line breaks. Em-dashes are the #1 AI-detection tell on DTC pages in 2026 (per [03_landing_page_synthesis.md](research/03_landing_page_synthesis.md)). Yes, even if it "feels right." No.
- **No banned words**: delve, comprehensive, seamless, leverage (as a verb), navigate (as a verb for non-physical things), foster, facilitate, elevate, robust, holistic, "in today's fast-paced world." If you reach for one, find a different word.
- **Lowercase eyebrows.** Mono font, lowercase, letter-spaced. Mirrors Snowball's house style.
- **Italic emphasis is a signature gesture, not decoration.** Use it 2–3 times across the page max. Each italic word should be the operative word in its sentence (verb or pivot noun). Repeating the device on every H2 dilutes it.
- **Counter-position by name.** Mention Duolingo, Babbel, Speak by name in at least one section. Saying *"every other app"* is too polite. Max writes pages that pick fights.
- **Specificity over abstraction.** Real numbers ("4 × 30-min lessons"), real names (Sarah K.), real scenarios (ordered dinner in French), real verbs. Never "personalized experience" — say what's personalized and how.
- **Confidence without hedging.** "Will," not "may." "Does," not "can." Pick a side every time.

What success looks like: a copywriter reading the page couldn't tell if it was AI- or human-written, and the strategy team would say "this sounds like a Snowball page."

---

## 6. Real testimonials (use verbatim, do not invent more)

These are public on Volley's lp3. They are real people. Use exactly as written.

> *"After 3 months I ordered dinner in French and understood the waiter's follow-up question. The weekly lessons are what got me there. I actually showed up every day."*
> **Sarah K. · Learning French · 3 months in**

> *"I quit Duolingo twice and Babbel once. The difference here is my tutor messaged me when I skipped Tuesday and gave me a shorter session to get back on track. I haven't missed a week since."*
> **Anders L. · Learning Swedish · 4 months in**

> *"The AI practice alone is worth it, but my tutor noticed I kept avoiding past tense and made that my focus for two weeks. That one adjustment unlocked a ton of new conversations."*
> **Marcus T. · Learning Spanish · 2 months in**

(I cleaned the em-dash out of Sarah's quote. Otherwise verbatim.)

Do not invent additional testimonials. Do not invent download counts, language counts, or App Store ratings.

---

## 7. Page structure (sections, in order)

This is the recommended flow. You can refine the section count or sequence if you can defend the change in one sentence.

### A. Sticky nav
Wordmark left ("volley" or stylized variant). Single CTA right ("Get my plan" — match Volley's actual CTA, do not invent a new one). Nav blurs/darkens on scroll.

### B. Hero
- **Eyebrow**: lowercase, mono, ~12 chars (e.g. "the accountability loop").
- **H1**: the wedge, sharply. The hero should make the human + AI structure unmissable. Examples to riff on (don't copy verbatim, write your own):
  - *"You don't need another app. You need a coach who notices when you skip a day."*
  - *"A real tutor. A real plan. The reason you'll actually finish this time."*
- **Sub** (1–2 sentences): the offer in plain English. *"$99/month. Four 30-minute live lessons with a real language tutor, plus unlimited AI practice between them. Your tutor reviews your week and adjusts your plan."*
- **Primary CTA**: "Get my plan" → links to a placeholder app URL (e.g. https://app.getvolley.ai/start). Below CTA: micro-row with "$99/mo · 2-min placement test · cancel anytime."
- **Hero visual**: this is the design call. Two strong options:
  1. **The split**: a left-side product mock (AI chat or flashcard) and a right-side tutor card (photo + "your tutor" label + a fragment of a weekly review note). The split visually states "AI + human" without a word.
  2. **The weekly review screenshot**: a single, larger mock of the tutor's note to the user ("You did 4 sessions this week. Restaurant vocab jumped to 87%. I'm assigning two follow-up conversations next week."). One artifact, but it's the artifact no competitor has.
  Pick one. Defend the choice in a comment in the file.

### C. The fear / the stuck (one paragraph block)
Name the real failure mode. "You've tried Duolingo. Twice. You can read the language. You can't speak it. You don't need another vocabulary app. You need someone to make sure you show up." Three short paragraphs. Last paragraph pivots to the offer. Use Volley's own line as a base — *"You don't need more content. You need someone making sure you show up 5 days a week and practice the right things."*

### D. The weekly loop (3 numbered steps)
Volley's actual differentiator. Three cards, numbered (01, 02, 03):
1. **Practice in the app.** *"15-min audio lesson on your commute. AI voice chat at lunch. Flashcards before bed. Whatever fits your day."*
2. **AI tracks everything.** *"Every word you say, every mistake, every card reviewed. Logged automatically. No journaling required."*
3. **Your tutor reviews it weekly.** *"Once a week, a real human opens your data, finds your blindspots, and adjusts next week's plan."*
Each card gets one specific scenario or visual. The tutor card should have a real photo (use a stock placeholder credit-tagged "tutor photo placeholder" if no real headshot is available).

### E. Counter-positioning (the comparison Volley currently avoids)
A small comparison block. **Three rows max, four columns**: Volley · Duolingo · Speak · Babbel.

Rows that actually differentiate (no filler):
1. **A real human reviews your week** — Volley ✓, others ✗
2. **Open-ended voice practice** — Volley ✓, Speak ✓, Duolingo ✗, Babbel ✗
3. **Adapts to your specific blindspots, not a fixed curriculum** — Volley ✓, others ✗

If you add more rows, **Volley must lose at least one** (e.g. price — Volley $99 vs Duolingo $13). A comparison where Volley wins everything is dishonest and Max will catch it. The strongest version of this section says "yes, we cost more. Here's why."

### F. What you get every month
Three cards listing the actual monthly inclusions. Match Volley's own structure but make the copy sharper:
1. **4 live tutor lessons** — *"30 minutes each. Scheduled around your week. Same tutor each time."*
2. **Unlimited AI practice** — *"Voice chat, audio lessons, smart flashcards. Use it for 5 minutes or 5 hours."*
3. **A weekly plan, made for you** — *"Your tutor reads your practice data and tells you what to work on next."*

### G. Real testimonials
Three quotes from §6. Each with name, language, and "X months in" attribution. Treat as the social proof anchor — make the typography do the work, no logos, no star ratings, no fake counts. Format suggestion: stacked, generous whitespace, names in mono, quotes in serif italic.

### H. Brief FAQ (3–4 items, accordion or static)
Pull from Volley's actual FAQ — the questions are listed in [02_volley_recon.md](research/02_volley_recon.md) §"FAQ topics on lp3." Pick the four that matter most for the buyer at the click moment:
1. *Is the tutor a real person?*
2. *What if I'm a complete beginner?*
3. *How much time does it take each day?*
4. *Can I cancel anytime?*
Answer each in 2–3 sentences. Specific. No corporate hedging.

### I. Final CTA
Restate the offer. Bigger. The closing line should escalate the hero, not echo it. End with the trust strip: "$99/mo · cancel anytime · ships with a real tutor, not a chatbot."

### J. Sticky bottom CTA (mobile + scroll past hero)
Triggers after section D (the weekly loop), not the moment hero exits. Dismissible, sessionStorage-persisted. "Get my plan" + "$99/mo, 2-min placement test."

### K. Footer
Minimal. © 2026 Volley · privacy · terms · support.

---

## 8. Design system

The current Volley page uses a warm cream/beige palette with dark sections, real photos, and friendly illustrations. **We are not copying it.** Our variant should feel like Volley grew up — same warmth, more typographic confidence, more editorial discipline. Think Snowball-meets-Volley, not "darker version of Volley."

### Palette
Pick one of two directions and commit:

**Option 1: Warm light (closer to current Volley, more refined)**
- Background: warm cream `#F5F0E5` or similar
- Ink: deep brown-black `#1A140F`
- Secondary ink: warm gray `#6B5E4D`
- Accent (CTA, highlights): Volley's existing orange-red `#E04E2C` or `#FF5B2A`
- Tutor accent (used sparingly, for the human-loop cards): a warm green `#3F7A5C` (echoes the current page's tutor card)
- Surfaces: white `#FFFFFF` for cards, very pale beige for nested cards

**Option 2: Editorial dark (Snowball-adjacent, sharper differentiation from current Volley)**
- Background: warm near-black `#0E0E0C`
- Ink: warm cream `#F4EFE3`
- Secondary ink: muted warm gray `#A89F8A` (must hit WCAG AA — this is a real failure mode, test it)
- Accent: same orange-red `#FF5B2A`
- Italic emphasis: amber `#F2C76B`

Pick whichever you can defend. Add a one-line comment in the HTML stating which and why.

### Typography
- **Display**: a serif with strong italics. Fraunces (variable) is the default — confident, has italic personality, works at 110px. Acceptable alternates: Source Serif 4, Tiempos.
- **Body**: a clean grotesque. Manrope or Inter. Body size 16–17px, line-height ~1.6.
- **Mono** (eyebrows, microcopy, prices): JetBrains Mono or IBM Plex Mono. 11–12px, lowercase, letter-spacing 0.06–0.1em.

### Components
- **Buttons**: pill-shaped, full color for primary, outlined for secondary. Hover: slight lift + arrow translates right. Focus: 2px outline in accent-2 with 3px offset.
- **Cards**: subtle border (1px hairline), generous padding (32px+), gentle hover lift. No drop shadows on light bg. Inner radial accent on hover is fine but optional.
- **Numbered step cards** (weekly loop): big italic serif numerals (01, 02, 03) in accent color. Number is the visual anchor.
- **Comparison table**: clean, no zebra striping, Volley column subtly tinted (don't overdo it — current build's heavy orange tint reads as biased).

### Motion (use sparingly; everything respects `prefers-reduced-motion`)
- Reveal-on-scroll for major sections (IntersectionObserver, opacity + translateY).
- Hero word-strike or italic fade-in is allowed, ONCE, ~1s after load. No more than one signature animation in the hero.
- The tutor card or weekly-review mock can have a subtle pulse / "live" indicator. Don't overdo dot pulses — one place, max.

### Imagery
- **Real photos** for the tutor card. Use a single high-quality placeholder; mark as placeholder in a comment.
- **Real product UI mocks** for the AI features (voice chat bubble, flashcard, audio lesson player). They can be in any of Volley's confirmed languages (French/Spanish/Swedish) — Swedish is the most visually distinctive and matches the live page.
- **No illustrations of generic happy-person-on-laptop.** If you can't get a real photo, use typography.

### Density / rhythm
- Section padding: clamp(60px, 10vw, 120px) vertical.
- Max content width: 1200px.
- Generous gutters: clamp(20px, 4vw, 48px).
- Hero is the only section that should feel cinematic; everything else should feel like reading a well-set magazine.

---

## 9. Hard rules (these are not stylistic — they are submission-killers if violated)

1. **No fabricated facts about Volley.** Real product, real testimonials, real claims only. The full list of what we can/cannot claim is in [02_volley_recon.md](research/02_volley_recon.md) §"What our landing page can claim."
2. **No em-dashes anywhere.** Search for `—` before declaring done. Including in HTML comments, page title, JS comments, table dashes — all out. Use commas, periods, parentheses, line breaks, en-dashes, or middots.
3. **No banned words.** Listed in §5.
4. **No invented testimonials.** The three real ones in §6 are the only quotes allowed. Mark any photo, illustration, or non-quote text that's a placeholder with a visible "placeholder" indicator.
5. **No invented pricing or guarantee terms.** Volley charges $99/mo (per Max). No public guarantee/refund policy exists. If you want to suggest one as a "what I'd add" recommendation, put it in the deck/Loom narration, not on the page itself.
6. **Single CTA destination.** All CTAs link to one URL (use `https://app.getvolley.ai/start` as a placeholder, or any consistent URL). One CTA verb across the whole page ("Get my plan" — match Volley's actual button).
7. **Color contrast must pass WCAG AA for body text.** This is a real test, not a checkbox. If using dark mode, lift the secondary-ink token until small body copy at #6B-ish on near-black hits 4.5:1.
8. **The 5-second test.** A first-time visitor must understand within 5 seconds: *what Volley is* (human tutor + AI app), *who it's for* (adult app-dropouts), *why it's different* (the weekly tutor review). If the hero doesn't land all three, the hero isn't done.

---

## 10. References (read in this order)

1. **[02_volley_recon.md](research/02_volley_recon.md)** — what the product actually is, the real testimonials, what we can/can't claim. Read this twice.
2. **[03_landing_page_synthesis.md](research/03_landing_page_synthesis.md)** — what works on landing pages in 2026 (single-stat heroes, named testimonials, sticky CTAs, AI-detection patterns to avoid). The structural patterns from "What 2026 Landing Page Data Actually Shows" are evidence-backed; treat them as defaults.
3. **[01_max_dossier.md](research/01_max_dossier.md)** — Max's voice, his counter-positioning instinct, the Snowball/Megaphone/Silvi house style. Read for tone calibration.
4. **The actual current Volley landing page (getvolley.ai/lp3)** — open it in a browser. Note the warm palette, the real testimonials, the weekly-loop concept, the persona section, the FAQ topics. This is the baseline our variant has to beat in an A/B test, not just a reference to admire.
5. **[04_challenge_brief.md](research/04_challenge_brief.md)** — Max's verbatim challenge text. Confirms what he's grading on.

---

## 11. Deliverable + handoff

- One self-contained HTML file. All CSS and JS inline. No build step.
- File should live at `/index.html` in the repo root.
- Deploy-ready as static (Vercel/Netlify zero-config — `vercel.json` already exists).
- At the top of the `<head>`, include a brief HTML comment with: (a) which palette direction you chose and why, (b) which hero visual you chose and why, (c) any invented placeholders you couldn't avoid (e.g. tutor photo source).
- Test the page at 1440px, 1024px, 768px, 375px before declaring done. Do not ship a page where the hero is text-only on mobile.
- Run a `grep "—"` on the file before handoff. If any em-dash survives, fix it.

When you're done, send back a one-paragraph note covering: which palette/hero you picked, what tradeoffs you made on the comparison table (which row Volley loses), and one thing you'd want to A/B test against your own build.

---

## 12. The Loom test (your real grading rubric)

Every section you build must survive Max's 30-second narration test:

1. **What I decided** — the choice, in one sentence.
2. **Why I decided it** — citing a ref doc or a piece of evidence.
3. **What I'd test next** — the alternative hypothesis I'd run an A/B against this.

If a section's design can't be defended in those three beats, the design isn't strong enough. Either find the citation or change the design.

This is the actual bar. Build for that.
