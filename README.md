# Volley Landing Page Variant

Built for the Max Hertan / Snowball Chief Achiever challenge.
Single-page, self-contained. No build step. Deploys in 60 seconds.

## What's here

- `index.html` — the entire landing page (all CSS + JS inline)
- `vercel.json` — Vercel config (clean URLs)

## Deploy to Vercel (recommended)

**Option A: Vercel CLI (fastest)**

```bash
npm i -g vercel        # if you don't have it
cd path/to/volley
vercel                 # answer the prompts, link to your account
vercel --prod          # ships to production
```

You get a URL like `volley-variant-kovid.vercel.app` in under a minute.

**Option B: Drag-and-drop**

1. Go to vercel.com/new
2. Drag the `volley/` folder onto the page
3. Click deploy

**Option C: GitHub**

Push the folder to a public repo, import it in Vercel. Auto-deploys on every push.

## Custom domain (optional, free)

Add `volley.kovidbhaduri.com` (or similar) in Vercel project settings → Domains. Point CNAME at `cname.vercel-dns.com`.

## What the page is doing

- **Hero:** Picks a fight with Duolingo. Strikethrough animation triggers on load.
- **Proof block:** Animated chat demo of an actual week-1 Spanish conversation. Messages stagger in when scrolled into view.
- **Why cards:** Three reasons Volley wins. Hover-lift + warm gradient on hover.
- **Comparison table:** Volley vs Duolingo vs Speak vs Human Tutor. The honest one nobody else puts on their own site.
- **Guarantee:** 30-day refund promise as a category-defining trust signal.
- **Testimonial:** Single quote (placeholder — swap in real one).
- **Final CTA:** Maximalist closing. Price clarity below the fold.

## What I did NOT include (and why)

- No "as seen in" logos — Volley doesn't have them, fakes tank trust
- No feature grid — kills conversion in consumer apps
- No 3-step "how it works" — overexplaining a product whose pitch is "open the app and talk"
- No video testimonials — premature for current stage

## Hypotheses being tested

The page is built to test five concrete hypotheses against the current `lp3`:

1. A specific, opinionated headline outperforms a generic feature description (vs current "AI Language Tutor")
2. An animated product demo above the fold lifts time-on-page and CTA clicks
3. Direct competitive comparison reduces decision paralysis for visitors who arrive from a roundup-article search
4. A no-friction money-back guarantee meaningfully lifts conversion at the $99 price point
5. Voice and personality (cheeky, opinionated) outperform neutral, professional copy in this category

Tracking and kill criteria for each are in the testing-plan deliverable.
