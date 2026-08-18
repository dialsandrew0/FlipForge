# FlipForge

> Field & resale intelligence — photo-to-verdict triage, authenticity tells, value ranges, and instant listing generation. Where generic lens tools stop.

**FlipForge** is the camera-first power tool for estate sales, thrift, garage, and field finds. Snap → structured read (Observed vs Inferred) → Buy / Skip / Maybe verdict with confidence → authenticity tells → copy-paste listing ready for eBay, Facebook Marketplace, or other channels.

Built on the honesty principle from ArtPeriod Field Triage and the decision speed of ClickFlip / RelicMined concepts.

---

## Core Promise

- **30–60 second field decision** instead of 10–20 minutes of research
- Explicit separation of what the camera **observed** vs what the model **inferred**
- Confidence scores and evidence, never false certainty
- Instant listing drafts tuned to channel
- Category-aware authenticity checklists

---

## Product Flow

1. **Capture** — 1–N photos (camera or upload)
2. **Triage Card**
   - Observed facts (materials, marks, condition, dimensions if readable)
   - Inferred (period, maker, style, value range) with confidence + evidence
   - Buy / Watch / Skip recommendation
   - Key physical checks still to perform before paying
3. **Deep Mode** (optional) — niche comps, authenticity tells, risk flags
4. **Listing Forge** — title, bullets, condition notes, SEO keywords, ready to paste

---

## Honesty Protocol (non-negotiable)

Every valuation surface must show:

- **Observed** — what is directly visible or measurable
- **Inferred** — model or data-driven claims
- **Confidence** — 0–1 or low/medium/high with reason
- **Evidence / Sources** — when available
- Clear “insufficient data” states instead of invented precision

This is the trust moat. Generic AI tools project confidence; FlipForge earns it.

---

## Customer Personas

1. **Field hunter / estate & thrift flipper**  
   Pain: slow research, decision fatigue, weak listing copy, authenticity risk.  
   Need: camera-first, fast verdict, listing draft, tells checklist.

2. **Serious reseller building inventory**  
   Pain: inconsistent margins, time sink.  
   Need: history of past triage decisions, outcome tracking, multi-channel listing variants.

UX: mobile-first, high-contrast for outdoor use, one primary action, dense but calm.

---

## Architecture (target)

```
FlipForge/
├── apps/
│   ├── web/                # Next.js or Vite field + desk UI
│   └── mobile/             # (future) native or PWA camera experience
├── packages/
│   ├── triage/             # Observed/Inferred schemas + scoring
│   ├── authenticity/       # Category-specific tell checklists
│   ├── listing/            # Channel-tuned generators
│   └── shared/
├── functions/              # Vision + LLM endpoints with spend controls
└── docs/
    ├── HONESTY.md
    ├── PERSONAS.md
    ├── CATEGORIES.md
    └── ROADMAP.md
```

Tech direction: TypeScript, strong typing on Observed/Inferred, vision model + LLM with hard spend limits, local-first where possible for field use.

---

## Market Position

Competitors in the space include FlipSnap, generic Google Lens + manual research, and seller catalog tools. Most either:
- Give a single number with no confidence, or
- Are built for the seller/cataloger rather than the person deciding in the moment.

FlipForge owns the **field decision + listing artifact** loop with radical honesty.

---

## Reality Check & Next Moves

**Carried forward**  
- Observed vs Inferred principle  
- Photo → structured triage  
- Instant listing generation concept  
- Category-aware thinking

**Gaps**  
- Production vision pipeline with cost controls  
- Real authenticity tell libraries per category  
- Outcome capture (did the user buy? what was actual resale?)  
- Offline / poor-connectivity field mode

**Immediate roadmap**  
1. Lock Observed / Inferred / Confidence TypeScript schemas  
2. Build the triage card UI (mobile-first)  
3. Implement one strong category end-to-end (e.g. jewelry or tools)  
4. Add listing generator for eBay + FB Marketplace  
5. Private field tests with real hunters

---

## Brand Note

FlipForge is the consolidated, renamed evolution of ClickFlip / FlipFindr, RelicMined object intelligence, and the Field Triage honesty system. All new field/resale work lives here.

Snap. Decide. List. With evidence.
