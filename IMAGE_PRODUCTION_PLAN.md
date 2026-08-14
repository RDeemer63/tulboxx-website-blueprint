# TULBOXX Image Production Plan

**Version:** 1.0

**Status:** Canonical production inventory

**Applies to:** Photography generation, product capture, composites, real-customer proof, code-native visuals, responsive variants, and image approval for the TULBOXX marketing website.

---

# Purpose

The page blueprints define 66 section-level asset IDs. Those IDs do not represent 66 separate images.

This plan consolidates them into a smaller reusable production library and answers three practical questions:

1. Which photographs must be generated with the recurring homepage contractor?
2. Which real TULBOXX product screenshots must be captured?
3. Which visuals do not use either the recurring contractor or the application?

It also identifies visuals that should be built as responsive HTML, CSS, SVG, or motion rather than exported as raster images.

## At a Glance

- **66** section-level asset IDs are accounted for.
- **9** reusable contractor-photography source sets cover the recurring excavation story; **8** source sets now have approved desktop masters.
- **17** reusable product-capture sets cover the connected customer-to-payment story.
- **4** trade environments establish excavation, landscaping, painting, and HVAC relevance.
- **3** company-stage contexts support owner-operator, small-team, and future growing-company stories.
- **2** controlled work-detail sources support artifact and finished-work visuals.
- **2** authentic customer-proof sets remain blocked until real participants and permissions exist.
- Pricing requires **no generated photography**.

---

# Governing Documents

- `VISUAL_STORYBOARD.md` defines the visual story and sequence.
- `PHOTOGRAPHY_DIRECTION.md` defines how all photography should look and feel.
- Individual page blueprints define what each section asset must communicate.
- `assets/images/README.md` records actual files, approval status, alt text, and production notes.
- `docs/TULBOXX_BRAND_STYLE_GUIDE.pdf` governs brand colors, typography, and logo treatment.

If this inventory conflicts with a page's purpose, preserve the page purpose and update this inventory.

---

# Production Types

| Code | Production type | Source rule |
|---|---|---|
| `PHOTO` | Recurring contractor-story photography | Generate or commission using the approved contractor identity and `PHOTOGRAPHY_DIRECTION.md`. |
| `APP` | Product screenshot or screen recording | Capture from the real current TULBOXX product using approved fictional demonstration data. Never generate with an image model. |
| `HYBRID` | Photography plus approved product UI | Produce the photograph and application capture separately, then composite or pair them in layout. |
| `TRADE` | Photography outside the recurring contractor story | Generate or commission a trade-specific environment with its own accurate people, tools, and work. |
| `PROOF` | Real customer evidence | Use only real approved customer photography, quotes, data, and results. Never generate. |
| `CODE` | Responsive information design | Build in HTML, CSS, SVG, or motion from approved assets. Do not generate a flattened image. |

---

# Section A — Recurring Contractor Photography

These are the photographs that should follow the same excavation contractor, truck, wardrobe, residential drainage or grading project, weather family, camera language, and restrained post-processing.

The nine source sets below can support many page-level asset IDs. Generate a new photograph only when one of these sources cannot honestly perform the required communication job.

| Source ID | Required scene | Reused by | Status | Required deliverables |
|---|---|---|---|---|
| `PHOTO-C01` | Contractor checking his phone beside the muddy work truck at an active residential grading site | `HOME-HERO-01`, `WHY-HERO-01` | Desktop master approved | Desktop master, dedicated mobile portrait, optimized exports |
| `PHOTO-C02` | Three moments of administrative friction: messages in the truck, scattered field notes, and paperwork after hours | `HOME-REALITY-02`, `WHY-SECOND-JOB-02` | Desktop master approved | Desktop triptych, three mobile-ready panels or source compositions, optimized exports |
| `PHOTO-C03` | Contractor discussing drainage or grading work with a homeowner at the property | `WHY-NATURAL-WORK-05`, `FEATURES-ESTIMATING-04` | Desktop master approved | Add real mobile UI to the blank screen, produce mobile crop, optimize exports |
| `PHOTO-C04` | Contractor photographing the site and recording a rough voice note before returning to the work | `HOME-AI-06`, `PLATFORM-CAPTURE-03`, `WORKFLOW-CAPTURE-03` | Desktop two-panel master approved | Separate mobile-ready panels, optimized exports, real UI captured separately |
| `PHOTO-C05` | Contractor using TULBOXX one-handed beside equipment or from a parked truck between tasks | `HOME-FIELD-07`, `WHY-FIELD-07`, `FEATURES-MOBILE-06` | Two desktop masters approved | Produce mobile portrait, close hand-and-device detail, optimized exports, and real UI composite |
| `PHOTO-C06` | Contractor handling a customer call from a parked truck with the active job visible outside | `WORKFLOW-CALL-02`, `FEATURES-CUSTOMERS-02` | Needed | Environmental truck scene, closer call moment, mobile crop |
| `PHOTO-C07` | Contractor reviewing the day's work with one or two crew members beside the demonstration project | `WHY-CAPACITY-08`, `WORKFLOW-JOB-06`, `FEATURES-JOBS-05` | Desktop master approved | Crew interaction master, safe mobile crop, real UI composite, optimized exports |
| `PHOTO-C08` | Contractor reviewing a received payment or business update from the parked truck after the fieldwork | `HOME-OUTCOMES-05`, `FEATURES-PAYMENTS-08` | Desktop master approved | Add real mobile UI to the blank screen, produce mobile crop, optimize exports |
| `PHOTO-C09` | Contractor closing the truck or looking over completed work as the day ends calmly | `HOME-OUTCOMES-05`, `HOME-CTA-10`, `WHY-CAPACITY-08`, `WHY-CLOSING-09` | Desktop master approved | Wide closing master, portrait variant, completed-work detail, optimized exports |

## Continuity Rules

- Use `HOME-HERO-01` as the identity reference for the contractor.
- Keep the charcoal hoodie or work shirt, tan work pants, brown boots, dark cap, and graphite truck consistent unless the time-of-day story requires an added practical layer.
- Keep the residential drainage and grading environment consistent with the Morgan Lee demonstration project.
- Show a believable progression through one workday rather than nine unrelated photo shoots.
- Never ask the image model to generate readable app UI, paperwork, logos, company names, phone numbers, or customer information.
- Product screens must be captured separately and composited only when the page requires them.
- Generated subjects are campaign characters, not real TULBOXX customers or employees.

## Current Approved Contractor Masters

| Asset ID | Approved file | Remaining work |
|---|---|---|
| `HOME-HERO-01` | `assets/images/approved/home/home-hero-01-desktop-master.png` | Dedicated mobile portrait and optimized production exports |
| `HOME-REALITY-02` | `assets/images/approved/home/home-reality-02-desktop-master.png` | Mobile-ready individual panels and optimized production exports |
| `PHOTO-C03` | `assets/images/approved/shared/photo-c03-customer-conversation-desktop-master.png` | Real mobile UI composite, dedicated mobile crop, and optimized production exports |
| `PHOTO-C04` | `assets/images/approved/shared/photo-c04-field-capture-desktop-master.png` | Mobile-ready individual panels, badge cleanup if required, and optimized production exports |
| `PHOTO-C05` | `assets/images/approved/shared/photo-c05-field-use-desktop-master.png`; `assets/images/approved/shared/photo-c05-field-use-truck-desktop-master.png` | Dedicated mobile portrait, close hand-and-device detail, real UI composites, and optimized production exports |
| `PHOTO-C07` | `assets/images/approved/shared/photo-c07-crew-coordination-desktop-master.png` | Safe mobile crop, real UI composite if the screen remains visible, and optimized production exports |
| `PHOTO-C08` | `assets/images/approved/shared/photo-c08-payment-review-desktop-master.png` | Real mobile UI composite, dedicated mobile crop, and optimized production exports |
| `PHOTO-C09` | `assets/images/approved/shared/photo-c09-closing-day-desktop-master.png` | Dedicated mobile portrait, completed-work detail, and optimized production exports |

---

# Section B — Product Screenshot Library

Capture these states from the real current TULBOXX application. Use one fictional customer and one drainage and grading project throughout so the visitor recognizes the same work moving forward.

The canonical demonstration story is:

- **Customer:** Morgan Lee
- **Project:** Backyard Drainage and Grading
- **Business context:** Residential excavation and site work

Before capture, verify every field, status, action, channel, and transition against the current product. Remove real customer information, browser extensions, developer controls, notifications, and unrelated account data.

| Capture ID | Required product state | Primary surface | Reused by section assets |
|---|---|---|---|
| `APP-01` | Today's List or approved daily-priority view with one clear next action | Desktop and mobile | `HOME-OUTCOMES-05`, `PLATFORM-ATTENTION-05`, `WORKFLOW-NEXT-10`, `FEATURES-LEVERAGE-10` |
| `APP-02` | Customer overview with contact details, properties, project history, and communication context | Desktop | `HOME-WORKFLOW-04`, `PLATFORM-CENTER-02`, `FEATURES-CUSTOMERS-02` |
| `APP-03` | Calm project overview showing the customer, property, work context, photos, notes, and connected records | Desktop and mobile | `HOME-TRANSFORMATION-03`, `HOME-WORKFLOW-04`, `PLATFORM-HERO-01`, `PLATFORM-CENTER-02`, `PLATFORM-CTA-10`, `FEATURES-HERO-01`, `FEATURES-PROJECTS-03` |
| `APP-04` | Minimal new-customer or opportunity state containing only information known from the first call | Desktop or tablet | `WORKFLOW-CALL-02` |
| `APP-05` | Mobile field capture for property photos, notes, or supported voice input | Mobile | `PLATFORM-CAPTURE-03`, `WORKFLOW-CAPTURE-03`, `FEATURES-MOBILE-06` |
| `APP-06` | Rough input, AI-assisted draft, contractor edits, and explicit review or confirmation | Desktop and mobile as supported | `HOME-AI-06`, `PLATFORM-AI-07`, `WORKFLOW-CAPTURE-03`, `FEATURES-AI-09` |
| `APP-07` | Estimate editor with connected project details, contractor-entered pricing, and review state | Desktop | `HOME-WORKFLOW-04`, `HOME-OUTCOMES-05`, `WORKFLOW-ESTIMATE-04`, `FEATURES-ESTIMATING-04` |
| `APP-08` | Customer-facing estimate plus supported send, share, approval, or history state | Customer view and contractor view | `PLATFORM-CUSTOMER-06`, `WORKFLOW-ESTIMATE-04`, `WORKFLOW-SCHEDULE-05`, `FEATURES-ESTIMATING-04`, `FEATURES-COMMS-07` |
| `APP-09` | Approved work becoming a scheduled job while customer, scope, and project identity remain connected | Desktop and mobile as supported | `HOME-WORKFLOW-04`, `WORKFLOW-SCHEDULE-05`, `FEATURES-JOBS-05` |
| `APP-10` | Mobile job detail showing one useful field item such as approved scope, access note, site photo, or completion action | Mobile | `WORKFLOW-JOB-06`, `FEATURES-JOBS-05`, `FEATURES-MOBILE-06` |
| `APP-11` | Completion record with final photos, completed state, and contractor review | Desktop or mobile | `WORKFLOW-JOB-06`, `WORKFLOW-INVOICE-07` |
| `APP-12` | Invoice draft or editor carrying only confirmed project context into billing | Desktop | `HOME-WORKFLOW-04`, `HOME-OUTCOMES-05`, `WORKFLOW-INVOICE-07`, `FEATURES-PAYMENTS-08` |
| `APP-13` | Customer-facing invoice, reminder, due date, and supported delivery state | Customer view and contractor view | `PLATFORM-CUSTOMER-06`, `WORKFLOW-INVOICE-07`, `WORKFLOW-PAYMENT-08`, `FEATURES-COMMS-07`, `FEATURES-PAYMENTS-08` |
| `APP-14` | Contractor-recorded payment and updated invoice or project history | Desktop or mobile | `HOME-WORKFLOW-04`, `HOME-OUTCOMES-05`, `WORKFLOW-PAYMENT-08`, `FEATURES-PAYMENTS-08` |
| `APP-15` | Communication action and resulting history in the correct customer or project context | Desktop and customer-facing state | `PLATFORM-CUSTOMER-06`, `FEATURES-COMMS-07` |
| `APP-16` | Simple job path and larger project path beginning from the same starting state | Desktop sequence | `PLATFORM-FLEX-08`, `WORKFLOW-FLEX-09` |
| `APP-17` | Full connected project history from first call through completed work, invoice, and payment | Desktop | `PLATFORM-MOVEMENT-04`, `PLATFORM-OVERVIEW-09`, `PLATFORM-CTA-10`, `WORKFLOW-HERO-01`, `WORKFLOW-CTA-11`, `FEATURES-HERO-01` |

## Screenshot Capture Standards

- Capture at a consistent browser size and zoom level.
- Use high-density source captures so crops remain sharp.
- Capture mobile states at a real supported viewport rather than placing desktop UI inside a phone frame.
- Keep the same customer name, address pattern, project title, photos, estimate, dates, and statuses consistent across the story.
- Use realistic fictional values and customer information.
- Do not expose production customer data, API keys, internal URLs, debug panels, browser extensions, or personal notifications.
- Do not redesign or simplify the product inside a marketing mockup without product approval.
- Record the product version or commit, capture date, route, viewport, data fixture, and approval status.
- Re-capture a state when the production interface changes materially.

---

# Section C — Images Outside the Recurring Contractor Story

These images do not use the homepage excavation contractor and do not depend on a TULBOXX product screen.

## Trade Photography

| Source ID | Required environment | Used by | Status | Notes |
|---|---|---|---|---|
| `TRADE-01` | Residential excavation or site work | `HOME-SOLUTIONS-09`, `FEATURES-CTA-12`, `SOLUTIONS-HERO-01`, `SOLUTIONS-TRADES-03` | Campaign imagery may be reused | Use the excavation campaign when the scene performs the same job; do not generate an unnecessary duplicate. |
| `TRADE-02` | Landscaping or hardscape work | `HOME-SOLUTIONS-09`, `FEATURES-CTA-12`, `SOLUTIONS-HERO-01`, `SOLUTIONS-TRADES-03` | Needed | Show recognizable work, tools, materials, and environment before adding a label. |
| `TRADE-03` | Residential or light-commercial painting | `HOME-SOLUTIONS-09`, `FEATURES-CTA-12`, `SOLUTIONS-HERO-01`, `SOLUTIONS-TRADES-03` | Needed | Show preparation or active work, not a generic person holding a paint roller. |
| `TRADE-04` | HVAC or another service-call trade | `HOME-SOLUTIONS-09`, `FEATURES-CTA-12`, `SOLUTIONS-HERO-01`, `SOLUTIONS-TRADES-03` | Needed | Show a credible diagnostic or service environment with safe, trade-accurate behavior. |

Do not reuse one generated person, property, or vehicle as though they operate four different trades. Each trade must have its own accurate visual world while sharing the TULBOXX photography treatment.

## Company-Stage Photography

| Source ID | Required context | Used by | Status | Notes |
|---|---|---|---|---|
| `STAGE-01` | Owner-operator handling fieldwork and business responsibility | `SOLUTIONS-STAGE-04` | Reuse contractor campaign where appropriate | Do not imply that remaining an owner-operator is a lesser outcome. |
| `STAGE-02` | Small crew coordinating practical work | `SOLUTIONS-STAGE-04` | May reuse `PHOTO-C07` or an approved trade scene | Show useful coordination rather than a posed team portrait. |
| `STAGE-03` | Growing service company with added people or parallel work | `SOLUTIONS-STAGE-04` | Needed after team capabilities are confirmed | Do not imply unsupported roles, permissions, dispatching, or crew-management features. |

## Work and Environment Details

| Source ID | Required image | Used by | Status | Notes |
|---|---|---|---|---|
| `DETAIL-01` | Completed or visibly improved drainage and grading work | `HOME-CTA-10`, `WHY-CLOSING-09` | Can be captured with `PHOTO-C09` | The finished work should communicate capability without becoming a dramatic reveal. |
| `DETAIL-02` | Realistic field artifacts: site photo, rough note, measurement sketch, and paper estimate | `HOME-TRANSFORMATION-03`, `WHY-BACKWARDS-04` | Needed as controlled source material | Use fictional, non-sensitive information. Keep readable content authored and approved rather than generated. |

## Authentic Customer Proof

| Proof ID | Required material | Used by | Status |
|---|---|---|---|
| `PROOF-01` | Real customer portrait or work photography with written permission | `HOME-PROOF-08` | Blocked until an approved customer story exists |
| `PROOF-02` | Trade-specific customer evidence, quote, workflow, and verified result | `SOLUTIONS-PROOF-07` | Blocked until an approved customer story exists |

Generated imagery may support the surrounding layout but must never stand in for these proof assets.

---

# Section D — Visuals That Should Not Be Generated as Images

These section assets are primarily layout, information design, diagrams, calculators, accordions, or code-driven composites. Build them responsively from approved photography and app captures.

| Page | Asset IDs | Correct production method |
|---|---|---|
| Home | `HOME-TRANSFORMATION-03`, `HOME-WORKFLOW-04`, `HOME-OUTCOMES-05`, `HOME-AI-06` | HTML/CSS/SVG or restrained motion using approved artifacts, photography, and captures |
| Why TULBOXX | `WHY-FALSE-CHOICE-03`, `WHY-BACKWARDS-04`, `WHY-NATURAL-WORK-05`, `WHY-BELIEFS-06` | Split layout, relationship diagram, workflow sequence, and editorial panels using approved sources |
| Platform | `PLATFORM-HERO-01`, `PLATFORM-CENTER-02`, `PLATFORM-CAPTURE-03`, `PLATFORM-MOVEMENT-04`, `PLATFORM-ATTENTION-05`, `PLATFORM-CUSTOMER-06`, `PLATFORM-AI-07`, `PLATFORM-FLEX-08`, `PLATFORM-OVERVIEW-09`, `PLATFORM-CTA-10` | Product-led compositions and relationship maps built from real captures |
| How It Works | `WORKFLOW-HERO-01`, `WORKFLOW-CALL-02`, `WORKFLOW-CAPTURE-03`, `WORKFLOW-ESTIMATE-04`, `WORKFLOW-SCHEDULE-05`, `WORKFLOW-JOB-06`, `WORKFLOW-INVOICE-07`, `WORKFLOW-PAYMENT-08`, `WORKFLOW-FLEX-09`, `WORKFLOW-NEXT-10`, `WORKFLOW-CTA-11` | Timeline and step layouts using photography and app captures as inputs |
| Features | `FEATURES-HERO-01`, `FEATURES-CUSTOMERS-02`, `FEATURES-PROJECTS-03`, `FEATURES-ESTIMATING-04`, `FEATURES-JOBS-05`, `FEATURES-MOBILE-06`, `FEATURES-COMMS-07`, `FEATURES-PAYMENTS-08`, `FEATURES-AI-09`, `FEATURES-LEVERAGE-10`, `FEATURES-FINDER-11` | Product modules, paired proof, or text-forward responsive components |
| Solutions | `SOLUTIONS-FINDER-02`, `SOLUTIONS-OUTCOMES-05`, `SOLUTIONS-PATHS-06`, `SOLUTIONS-CTA-08` | Editorial routing, verified workflows, and pricing transition using approved sources |
| Pricing | `PRICING-HERO-01`, `PRICING-PLANS-02`, `PRICING-INCLUDED-03`, `PRICING-ROI-04`, `PRICING-FAQ-05`, `PRICING-CTA-06` | Typography, offer card, grouped inclusions, calculator, accordion, and quiet CTA; no generated photography required |

Do not flatten these components into images. Text must remain accessible, responsive, searchable, and easy to update.

---

# Section E — Complete 66-Asset Crosswalk

This table assigns every section-level asset ID a primary production type and reusable source.

## Home

| Asset ID | Type | Primary source or action |
|---|---|---|
| `HOME-HERO-01` | `PHOTO` | `PHOTO-C01`; approved desktop master |
| `HOME-REALITY-02` | `PHOTO` | `PHOTO-C02`; approved desktop master |
| `HOME-TRANSFORMATION-03` | `CODE` + `APP` | `DETAIL-02` + `APP-03` |
| `HOME-WORKFLOW-04` | `CODE` + `APP` | `APP-02`, `APP-03`, `APP-07`, `APP-09`, `APP-12`, `APP-14` |
| `HOME-OUTCOMES-05` | `HYBRID` | `APP-01`, `APP-07`, `APP-12`, `APP-14`, `PHOTO-C08`, `PHOTO-C09` |
| `HOME-AI-06` | `HYBRID` | `PHOTO-C04` + `APP-06` |
| `HOME-FIELD-07` | `HYBRID` | `PHOTO-C05` + `APP-10` or the confirmed mobile next-action screen |
| `HOME-PROOF-08` | `PROOF` | `PROOF-01` |
| `HOME-SOLUTIONS-09` | `TRADE` | `TRADE-01` through `TRADE-04` |
| `HOME-CTA-10` | `PHOTO` | `PHOTO-C09` + `DETAIL-01` |

## Why TULBOXX

| Asset ID | Type | Primary source or action |
|---|---|---|
| `WHY-HERO-01` | `PHOTO` | Reuse or art-direct a crop from `PHOTO-C01` |
| `WHY-SECOND-JOB-02` | `PHOTO` | Reuse selected moments from `PHOTO-C02` |
| `WHY-FALSE-CHOICE-03` | `CODE` + `PHOTO` | Split narrative using `PHOTO-C03`, `PHOTO-C07`, and controlled admin artifacts |
| `WHY-BACKWARDS-04` | `CODE` | Relationship diagram using `DETAIL-02`; no standalone generated image |
| `WHY-NATURAL-WORK-05` | `HYBRID` | `PHOTO-C03`, `PHOTO-C04`, `APP-03` |
| `WHY-BELIEFS-06` | `CODE` + `APP` | Editorial panels using details from `APP-06`, `APP-07`, `APP-10`, and `APP-16` |
| `WHY-FIELD-07` | `HYBRID` | `PHOTO-C05` + confirmed mobile app capture |
| `WHY-CAPACITY-08` | `PHOTO` | `PHOTO-C07`, `PHOTO-C08`, `PHOTO-C09` |
| `WHY-CLOSING-09` | `PHOTO` | `PHOTO-C09` or `DETAIL-01` |

## Platform

| Asset ID | Type | Primary source or action |
|---|---|---|
| `PLATFORM-HERO-01` | `CODE` + `APP` | Connected composition using `APP-03` and supporting records |
| `PLATFORM-CENTER-02` | `CODE` + `APP` | Relationship map using `APP-02`, `APP-03`, and linked records |
| `PLATFORM-CAPTURE-03` | `HYBRID` | `PHOTO-C04`, `APP-05`, `APP-03` |
| `PLATFORM-MOVEMENT-04` | `CODE` + `APP` | Scroll sequence using `APP-17` and its source states |
| `PLATFORM-ATTENTION-05` | `APP` | `APP-01` + `APP-03` |
| `PLATFORM-CUSTOMER-06` | `APP` | `APP-08`, `APP-13`, `APP-15` as supported |
| `PLATFORM-AI-07` | `APP` | `APP-06` |
| `PLATFORM-FLEX-08` | `APP` | `APP-16` |
| `PLATFORM-OVERVIEW-09` | `CODE` + `APP` | Connected map using `APP-17` |
| `PLATFORM-CTA-10` | `APP` | Final connected state from `APP-17` |

## How It Works

| Asset ID | Type | Primary source or action |
|---|---|---|
| `WORKFLOW-HERO-01` | `CODE` + `APP` | Timeline using `APP-17` and a project photo |
| `WORKFLOW-CALL-02` | `HYBRID` | `PHOTO-C06` + `APP-04` |
| `WORKFLOW-CAPTURE-03` | `HYBRID` | `PHOTO-C04`, `APP-05`, `APP-06` |
| `WORKFLOW-ESTIMATE-04` | `APP` | `APP-07` + `APP-08` |
| `WORKFLOW-SCHEDULE-05` | `APP` | `APP-08` + `APP-09` |
| `WORKFLOW-JOB-06` | `HYBRID` | `PHOTO-C07` + `APP-10` + `APP-11` |
| `WORKFLOW-INVOICE-07` | `APP` | `APP-11`, `APP-12`, `APP-13` |
| `WORKFLOW-PAYMENT-08` | `APP` | `APP-13` + `APP-14` |
| `WORKFLOW-FLEX-09` | `CODE` + `APP` | Branching path using `APP-16` |
| `WORKFLOW-NEXT-10` | `APP` | `APP-01` |
| `WORKFLOW-CTA-11` | `CODE` + `APP` | Completed-project handoff using `APP-17` |

## Features

| Asset ID | Type | Primary source or action |
|---|---|---|
| `FEATURES-HERO-01` | `CODE` + `APP` | Outcome transitions using `APP-17` and focused supporting states |
| `FEATURES-CUSTOMERS-02` | `HYBRID` | `PHOTO-C06` + `APP-02` |
| `FEATURES-PROJECTS-03` | `APP` | `APP-03` |
| `FEATURES-ESTIMATING-04` | `HYBRID` | `PHOTO-C03` or truck review + `APP-07` + `APP-08` |
| `FEATURES-JOBS-05` | `HYBRID` | `PHOTO-C07` + `APP-09` + `APP-10` |
| `FEATURES-MOBILE-06` | `HYBRID` | `PHOTO-C05` + mobile captures including `APP-05` and `APP-10` |
| `FEATURES-COMMS-07` | `APP` | `APP-15` plus supported customer-facing state |
| `FEATURES-PAYMENTS-08` | `HYBRID` | `PHOTO-C08` + `APP-12`, `APP-13`, `APP-14` |
| `FEATURES-AI-09` | `APP` | `APP-06` |
| `FEATURES-LEVERAGE-10` | `APP` | `APP-01`, `APP-13`, and confirmed reporting state |
| `FEATURES-FINDER-11` | `CODE` | Text-forward component; no image generation |
| `FEATURES-CTA-12` | `TRADE` | `TRADE-01` through `TRADE-04` |

## Solutions

| Asset ID | Type | Primary source or action |
|---|---|---|
| `SOLUTIONS-HERO-01` | `TRADE` | `TRADE-01` through `TRADE-04` |
| `SOLUTIONS-FINDER-02` | `CODE` + `TRADE` | Editorial routing using approved trade and stage sources |
| `SOLUTIONS-TRADES-03` | `TRADE` | Large story blocks from `TRADE-01` through `TRADE-04` |
| `SOLUTIONS-STAGE-04` | `TRADE` | `STAGE-01` through `STAGE-03` |
| `SOLUTIONS-OUTCOMES-05` | `CODE` + `APP` | Connected before-and-after states from the app library |
| `SOLUTIONS-PATHS-06` | `CODE` + `APP` | Three verified workflows using trade-relevant fictional data |
| `SOLUTIONS-PROOF-07` | `PROOF` | `PROOF-02` |
| `SOLUTIONS-CTA-08` | `CODE` | Quiet work-to-pricing transition; reuse approved imagery if needed |

## Pricing

| Asset ID | Type | Primary source or action |
|---|---|---|
| `PRICING-HERO-01` | `CODE` | Typography and branded field; no photograph required |
| `PRICING-PLANS-02` | `CODE` | One accessible offer card |
| `PRICING-INCLUDED-03` | `CODE` | Grouped inclusions and restrained checkmarks |
| `PRICING-ROI-04` | `CODE` | Transparent interactive calculator or plain value explanation |
| `PRICING-FAQ-05` | `CODE` | Accessible accordion or open text sections |
| `PRICING-CTA-06` | `CODE` | Quiet branded CTA; no new photograph required |

---

# Section F — Production Sequence

## Phase 1 — Complete the Homepage Photography Story

1. Produce mobile compositions for `PHOTO-C01` and `PHOTO-C02`.
2. Produce the dedicated mobile portrait and completed-work detail for approved `PHOTO-C09`.
3. Capture the minimum homepage app set: `APP-01`, `APP-03`, `APP-06`, `APP-07`, `APP-12`, and `APP-14`.
4. Produce `TRADE-02`, `TRADE-03`, and `TRADE-04` only when the Solutions preview is ready.
5. Keep `HOME-PROOF-08` in an honest pre-proof state until `PROOF-01` exists.

## Phase 2 — Build the Connected Product Story

1. Create the complete Morgan Lee demonstration-data fixture.
2. Capture `APP-02` through `APP-17` in workflow order.
3. Build the Platform and How It Works sequences from the shared capture library.
4. Generate `PHOTO-C06`; use approved `PHOTO-C07` to connect job coordination to real work.

## Phase 3 — Expand Relevance

1. Complete the Features page from the existing photography and app libraries.
2. Produce and approve the four trade environments.
3. Research each trade before producing trade-specific workflow composites.
4. Delay `STAGE-03` claims and imagery until team capabilities are confirmed.

## Phase 4 — Add Authentic Proof

1. Select participating customers.
2. Obtain written permission for photography, names, quotes, work, and results.
3. Verify all claims and measurements.
4. Replace temporary proof states with `PROOF-01` and `PROOF-02`.

---

# Approval and Alt-Text Workflow

When an asset is approved:

1. Save the master under `assets/images/approved/{page}/` using the naming rules in `assets/images/README.md`.
2. Record its canonical asset ID, filename, dimensions, source, purpose, approval status, and production notes.
3. Write alt text for the image in its intended page context.
4. If adjacent HTML communicates the same information and the image is decorative, record that implementation should use an empty alt attribute.
5. Preserve the generation prompt, reference image identifiers, and reproducibility information when available.
6. Produce dedicated desktop and mobile compositions when cropping cannot preserve the essential story.
7. Commit and push the completed approval batch.

---

# Final Production Rules

- Do not generate product screenshots.
- Do not use generated people as customer proof.
- Do not bake headlines, captions, buttons, prices, app UI, or meaningful copy into photography.
- Do not create a new photograph when an approved source already performs the same communication job.
- Do not flatten diagrams, calculators, accordions, workflows, or offer cards into images.
- Do not publish a product capture until its behavior and terminology are verified.
- Do not let page-level asset IDs become a reason to create 66 unrelated files.
- The website should feel like one contractor campaign, one connected product story, and a small number of accurate supporting trade worlds.

---

## Related Documents

- `PHOTOGRAPHY_DIRECTION.md`
- `VISUAL_STORYBOARD.md`
- `assets/images/README.md`
- `HOME.md`
- `WHY_TULBOXX.md`
- `PLATFORM.md`
- `HOW_IT_WORKS.md`
- `FEATURES.md`
- `SOLUTIONS.md`
- `PRICING.md`

## Document Authority

This document is the canonical production inventory for visual assets. It controls classification, reuse, source requirements, production sequencing, and status tracking across the seven launch page blueprints.

Page documents continue to own section purpose and specific communication requirements. `PHOTOGRAPHY_DIRECTION.md` continues to own photographic style. `assets/images/README.md` continues to own actual filenames, approval status, alt text, and file-level production notes.
