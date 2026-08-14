# TULBOXX Image Library

This directory stores marketing-image masters, review candidates, approval status, production notes, and final alt text.

`IMAGE_PRODUCTION_PLAN.md` defines the complete production inventory and reuse plan. `PHOTOGRAPHY_DIRECTION.md` governs how photography is generated, selected, edited, cropped, and approved. `VISUAL_STORYBOARD.md` and the page blueprints determine what each asset must communicate.

---

# Directory Structure

```text
assets/images/
├── approved/
│   └── {page}/
└── review/
    └── {page}/
```

- `approved/` contains source masters that have been explicitly approved for the campaign.
- `review/` contains promising concepts that must not be treated as production-ready.
- Page folders use lowercase route names such as `home`, `platform`, and `solutions`.

Production exports may be created from an approved master only after responsive cropping, optimization, accessibility, and final visual QA.

---

# Naming Standard

Use lowercase kebab-case derived from the canonical asset ID:

```text
{asset-id}-{variant}-{role}.{extension}
```

Examples:

```text
home-hero-01-desktop-master.png
home-hero-01-mobile-master.png
home-hero-01-desktop.webp
home-reality-02-desktop-master.png
photo-c04-field-capture-desktop-master.png
```

- `master` identifies the highest-quality approved source.
- `desktop` and `mobile` identify intentionally composed aspect ratios, not merely resized files.
- `concept` identifies a review asset that is not approved for production.
- Shared campaign sources use their `PHOTO-C##` source ID from `IMAGE_PRODUCTION_PLAN.md` when one master supports multiple page assets.
- Do not overwrite an approved master with an unapproved revision.

---

# Approved Assets

## `HOME-HERO-01`

- **File:** [`approved/home/home-hero-01-desktop-master.png`](approved/home/home-hero-01-desktop-master.png)
- **Status:** Approved desktop master
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; not a real customer, employee, or testimonial
- **Purpose:** Homepage hero recognition image
- **Alt text:** Excavation contractor checking his phone beside a muddy work truck at a residential grading jobsite.
- **Production notes:** Preserve the open space on the left for the hero copy. Create a dedicated mobile portrait composition rather than relying on a tight crop. Produce optimized WebP or AVIF derivatives during website implementation. Do not present the subject as a real TULBOXX customer.

## `HOME-REALITY-02`

- **File:** [`approved/home/home-reality-02-desktop-master.png`](approved/home/home-reality-02-desktop-master.png)
- **Status:** Approved desktop master
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; not a real customer, employee, or testimonial
- **Purpose:** Three recognition moments showing customer messages, scattered notes, and work continuing after hours
- **Alt text:** Three moments in an excavation contractor's day: checking customer messages in his truck, tracking job details in a notebook, and completing paperwork at home.
- **Production notes:** Keep the headline, panel labels, and descriptions in accessible HTML rather than compositing them into the image. On mobile, present the moments as three separate panels or intentionally cropped sources rather than shrinking the full triptych. Retouch or replace any phone or paperwork detail that becomes legible enough to resemble synthetic customer information. Keep the after-hours scene thoughtful rather than dramatically exhausted. Do not present the subject as a real TULBOXX customer.

## `PHOTO-C03`

- **File:** [`approved/shared/photo-c03-customer-conversation-desktop-master.png`](approved/shared/photo-c03-customer-conversation-desktop-master.png)
- **Status:** Approved desktop master with blank compositing screen
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; neither generated subject is a real customer, employee, or testimonial participant
- **Purpose:** Show the contractor discussing work with a homeowner and reviewing project or estimate information at the property.
- **Reused by:** `WHY-NATURAL-WORK-05` and `FEATURES-ESTIMATING-04`
- **Alt text:** Excavation contractor shows project details on his phone to a homeowner beside the customer's driveway.
- **Production notes:** Perspective-map only a real approved TULBOXX mobile capture onto the white phone screen, preserving realistic glare, brightness, and device edges. Do not use this generated homeowner as customer proof. Produce a mobile crop that preserves both people, the phone, the property, and the parked work truck.

## `PHOTO-C04`

- **File:** [`approved/shared/photo-c04-field-capture-desktop-master.png`](approved/shared/photo-c04-field-capture-desktop-master.png)
- **Status:** Approved desktop two-panel master
- **Dimensions:** 1537 × 1023
- **Source:** AI-generated campaign photography; not a real customer, employee, or testimonial
- **Purpose:** Show the contractor documenting a residential drainage site with a photograph and then recording a rough voice note.
- **Reused by:** `HOME-AI-06`, `PLATFORM-CAPTURE-03`, and `WORKFLOW-CAPTURE-03`
- **Alt text:** Excavation contractor photographs a residential drainage jobsite and records a voice note beside his work truck.
- **Production notes:** Treat the two moments as separate responsive panels on mobile rather than shrinking the complete horizontal composition. Keep all explanatory copy in HTML and composite only real approved TULBOXX UI. Remove or obscure any generated equipment badge that becomes legible at the final display size. Do not present the subject as a real TULBOXX customer.

## `PHOTO-C05`

- **File:** [`approved/shared/photo-c05-field-use-desktop-master.png`](approved/shared/photo-c05-field-use-desktop-master.png)
- **Prompt record:** [`approved/shared/photo-c05-field-use-desktop-master.prompt.md`](approved/shared/photo-c05-field-use-desktop-master.prompt.md)
- **Status:** Approved desktop master
- **Dimensions:** 1535 × 1024
- **Source:** Generated by Codex from the rejected trench concept and the approved `HOME-HERO-01` identity/style reference; not a real customer, employee, or testimonial
- **Purpose:** Show the recurring contractor checking TULBOXX safely between tasks while the active drainage work remains visible.
- **Reused by:** `HOME-FIELD-07`, `WHY-FIELD-07`, and `FEATURES-MOBILE-06`
- **Alt text:** Excavation contractor checks his phone from stable ground beside a muddy work truck while a drainage trench and excavator remain visible.
- **Production notes:** Safety, identity, hands, phone, lighting, equipment context, and visible branding passed review. Capture or generate a dedicated mobile portrait and a closer hand-and-device detail. Composite only real approved TULBOXX UI. Do not present the subject as a real TULBOXX customer.

### Parked-truck composition

- **File:** [`approved/shared/photo-c05-field-use-truck-desktop-master.png`](approved/shared/photo-c05-field-use-truck-desktop-master.png)
- **Status:** Approved alternate desktop master with blank compositing screen
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; not a real customer, employee, or testimonial
- **Purpose:** Provide a closer field-use composition of the contractor working safely from the open door of his parked truck between tasks.
- **Alt text:** Excavation contractor checks his phone while seated in the open doorway of his parked work truck with equipment visible behind him.
- **Production notes:** Perspective-map only a real approved TULBOXX mobile capture onto the white phone screen, preserving the phone angle, hand overlap, realistic glare, brightness, and device edges. This is an alternate `PHOTO-C05` composition, not the customer-call scene required for `PHOTO-C06`. The final treatment must remain unmistakably parked and must never imply phone use while driving.

### Device-detail composition

- **File:** [`approved/shared/photo-c05-field-use-device-detail-desktop-master.png`](approved/shared/photo-c05-field-use-device-detail-desktop-master.png)
- **Status:** Approved device-detail desktop master with blank compositing screen; background cleanup required
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; not a real customer, employee, or testimonial
- **Purpose:** Provide a prominent, unobstructed phone surface for pairing the recurring contractor story with a real TULBOXX mobile screen.
- **Alt text:** Excavation contractor holds his phone above the open tailgate of his work truck with tools and an active jobsite behind him.
- **Production notes:** Perspective-map only a real approved TULBOXX mobile capture onto the white phone screen, preserving the screen angle, hand overlap, realistic glare, brightness, and device edges. Remove or obscure all generated house-wrap lettering before production use. Keep the notebook writing illegible and do not present it as authentic project information.

## `PHOTO-C06`

- **File:** [`approved/shared/photo-c06-customer-call-desktop-master.png`](approved/shared/photo-c06-customer-call-desktop-master.png)
- **Status:** Approved desktop master; background cleanup required
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; neither generated worker is a real customer, employee, or testimonial participant
- **Purpose:** Show the contractor handling a customer call safely beside his parked truck while work continues at the jobsite.
- **Reused by:** `WORKFLOW-CALL-02` and `FEATURES-CUSTOMERS-02`
- **Alt text:** Excavation contractor speaks with a customer by phone beside his parked work truck while an operator works at the residential jobsite.
- **Production notes:** The contractor is visibly stationary and the active work provides useful context. Remove or obscure all generated house-wrap lettering and any legible equipment markings before production use. Produce a mobile crop that retains the phone-call gesture, contractor expression, and enough jobsite context to make the scene understandable.

## `PHOTO-C07`

- **File:** [`approved/shared/photo-c07-crew-coordination-desktop-master.png`](approved/shared/photo-c07-crew-coordination-desktop-master.png)
- **Status:** Approved desktop master
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; none of the generated subjects is a real customer, employee, or testimonial participant
- **Purpose:** Show a small excavation crew reviewing job information together beside the active project.
- **Reused by:** `WHY-CAPACITY-08`, `WORKFLOW-JOB-06`, `FEATURES-JOBS-05`, and potentially `SOLUTIONS-STAGE-04`
- **Alt text:** Three excavation crew members review job details on a phone beside their work truck and excavator.
- **Production notes:** Keep the interaction practical and collaborative rather than presenting the group as a posed team portrait. If the phone screen is visible at the final display size, replace it with a real approved TULBOXX mobile capture while preserving the hand overlap, viewing angle, glare, brightness, and device edges. Produce a mobile crop that retains all three crew members and enough truck or equipment context to establish the jobsite.

## `PHOTO-C08`

- **File:** [`approved/shared/photo-c08-payment-review-desktop-master.png`](approved/shared/photo-c08-payment-review-desktop-master.png)
- **Status:** Approved desktop master with blank compositing screen
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; not a real customer, employee, or testimonial
- **Purpose:** Show the contractor reviewing a payment or business update safely from his parked work truck beside the jobsite.
- **Reused by:** `HOME-OUTCOMES-05` and `FEATURES-PAYMENTS-08`
- **Alt text:** Excavation contractor reviews a payment update on his phone while seated in his parked work truck beside the jobsite.
- **Production notes:** Perspective-map only a real approved TULBOXX mobile capture onto the white phone screen, preserving realistic glare, brightness, and device edges. The final composition must remain unmistakably parked and must never imply phone use while driving. Produce a mobile crop and optimized production exports.

## `PHOTO-C09`

- **File:** [`approved/shared/photo-c09-closing-day-desktop-master.png`](approved/shared/photo-c09-closing-day-desktop-master.png)
- **Status:** Approved desktop master
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign photography; not a real customer, employee, or testimonial
- **Purpose:** Close the recurring contractor story with a calm end-of-day moment after the work is complete.
- **Reused by:** `HOME-OUTCOMES-05`, `HOME-CTA-10`, `WHY-CAPACITY-08`, and `WHY-CLOSING-09`
- **Alt text:** Excavation contractor looks across a finished gravel driveway as a truck carries the excavator away at the end of the day.
- **Production notes:** Preserve the broad driveway and sky as flexible copy-safe space. The scene communicates completion and a calmer close to the day; it must not be presented as customer proof. Produce a dedicated mobile portrait and a closer completed-work detail rather than relying only on a tight crop of this wide master.

---

# Approved Product Captures

These screens were captured from the real TULBOXX V2 interface on August 14, 2026, from app commit `84fd0e4`. The isolated local fixture uses fictional information only: Evan Brooks at Ridgeline Excavation & Site Work, Morgan Lee, and the Backyard Drainage and Grading project. No production customer data appears in these files.

| ID | File | Dimensions | Alt text | Production notes |
|---|---|---:|---|---|
| `APP-01` | [`approved/app/app-01-todays-list-desktop.png`](approved/app/app-01-todays-list-desktop.png) | 1418 × 985 | TULBOXX Today view prioritizing an active pool-pad job and a driveway-estimate follow-up. | Approved desktop capture. |
| `APP-01` | [`approved/app/app-01-todays-list-mobile.png`](approved/app/app-01-todays-list-mobile.png) | 375 × 812 | Mobile TULBOXX Today view with an in-progress job first and a customer follow-up below it. | Approved mobile capture. |
| `APP-02` | [`approved/app/app-02-customer-overview-desktop.png`](approved/app/app-02-customer-overview-desktop.png) | 1418 × 985 | Morgan Lee's customer record with contact details, total billed, notes, reminders, and connected work history. | Approved desktop capture. |
| `APP-03` | [`approved/app/app-03-project-overview-desktop.png`](approved/app/app-03-project-overview-desktop.png) | 1418 × 985 | Backyard Drainage and Grading project showing its approved estimate, completed job, paid invoice, and recent activity. | Approved desktop capture. The current mobile layout remains under review because a workspace heading overflows horizontally. |
| `APP-04` | [`approved/app/app-04-new-opportunity-desktop.png`](approved/app/app-04-new-opportunity-desktop.png) | 1440 × 1000 | New estimate form containing Morgan Lee's project, the drainage problem, proposed approach, desired result, and price. | Approved representation of the supported first-call-to-estimate starting state. |
| `APP-05` | [`approved/app/app-05-field-capture-mobile.png`](approved/app/app-05-field-capture-mobile.png) | 390 × 844 | Mobile Quick capture form recording Morgan Lee's post-storm drainage check while the contractor is in the field. | Approved mobile capture; nothing was saved or sent. |
| `APP-06` | [`approved/app/app-06-ai-estimate-input-desktop.png`](approved/app/app-06-ai-estimate-input-desktop.png) | 1440 × 1000 | TULBOXX estimate input with plain-language project details and a button to build an AI-assisted field quote. | Approved input state only. Capture the generated draft from a fresh project; the seeded project already has an approved first estimate and rejected another version. |
| `APP-07` | [`approved/app/app-07-estimate-review-desktop.png`](approved/app/app-07-estimate-review-desktop.png) | 1418 × 985 | Contractor estimate review for Backyard Drainage and Grading with customer details, project overview, and scope of work. | Approved contractor review state. |
| `APP-08` | [`approved/app/app-08-customer-estimate-desktop.png`](approved/app/app-08-customer-estimate-desktop.png) | 1425 × 990 | Customer-facing Ridgeline estimate for Morgan Lee with project overview, detailed scope, inclusions, and validity date. | Approved customer view; approval and send actions are documented separately in the interface. |
| `APP-09` | [`approved/app/app-09-estimate-to-job-desktop.png`](approved/app/app-09-estimate-to-job-desktop.png) | 1418 × 985 | Completed drainage job with its booked estimate and paid invoice still visibly connected. | Approved connected-job state. Capture a distinct scheduled state later if the marketing composition needs it. |
| `APP-10` | [`approved/app/app-10-job-detail-mobile.png`](approved/app/app-10-job-detail-mobile.png) | 375 × 812 | Mobile completed-job detail showing Morgan Lee, the booked estimate, paid invoice, and completion note. | Approved mobile capture. |
| `APP-11` | [`approved/app/app-11-completed-job-desktop.png`](approved/app/app-11-completed-job-desktop.png) | 1418 × 985 | Completed Backyard Drainage and Grading job with customer, dates, scope, access notes, estimate, and invoice. | Approved desktop completion record. |
| `APP-12` | [`approved/app/app-12-invoice-editor-desktop.png`](approved/app/app-12-invoice-editor-desktop.png) | 1418 × 985 | Invoice editor carrying Morgan Lee's contact details and four confirmed drainage-project line items into billing. | Approved desktop editor state; no second invoice was saved. |
| `APP-13` | [`approved/app/app-13-customer-invoice-desktop.png`](approved/app/app-13-customer-invoice-desktop.png) | 1440 × 1000 | Customer-facing paid invoice from Ridgeline to Morgan Lee with service line items, total, message, and warranty note. | Approved customer view. A separate reminder-state capture remains optional. |
| `APP-14` | [`approved/app/app-14-paid-invoice-history-desktop.png`](approved/app/app-14-paid-invoice-history-desktop.png) | 1418 × 985 | Paid invoice showing a $12,850 collected balance, zero outstanding, and the recorded bank-transfer payment. | Approved contractor payment-history state. |
| `APP-15` | [`approved/app/app-15-customer-communication-history-desktop.png`](approved/app/app-15-customer-communication-history-desktop.png) | 1418 × 985 | Morgan Lee's customer record with call context, job updates, reminders, and note actions kept together. | Approved supported communication-history state. |
| `APP-16` | [`approved/app/app-16-field-quote-vs-full-proposal-desktop.png`](approved/app/app-16-field-quote-vs-full-proposal-desktop.png) | 1440 × 1000 | New Estimate screen offering a quick Field Quote path and a more detailed Full Proposal path from the same project. | Approved branching-path capture. |
| `APP-17` | [`approved/app/app-17-connected-project-history-desktop.png`](approved/app/app-17-connected-project-history-desktop.png) | 1418 × 985 | Connected project workspace reconciling Morgan Lee's approved estimate, completed job, paid invoice, amounts, and activity. | Approved overview capture; use focused crops for individual marketing sections. |

---

# Assets Under Review

## `APP-03` mobile

- **File:** [`review/app/app-03-project-overview-mobile-overflow.png`](review/app/app-03-project-overview-mobile-overflow.png)
- **Status:** Hold for product fix or recapture
- **Dimensions:** 415 × 899
- **Issue:** The work-progress heading creates horizontal overflow at a supported mobile viewport. Do not use this capture in marketing until the responsive layout is corrected and recaptured.

---

# Approval Workflow

For every candidate:

1. Match it to a canonical asset ID in a page blueprint.
2. Review it against `PHOTOGRAPHY_DIRECTION.md`.
3. Confirm whether it is generated campaign imagery, authentic customer proof, product capture, or a composite.
4. Give it a stable descriptive filename.
5. Record dimensions, source, purpose, alt text, and production notes here.
6. Keep it in `review/` until explicitly approved.
7. Move the approved master into `approved/{page}/`.
8. Create responsive and optimized production exports without replacing the master.

Alt text should describe the information the image contributes in its final page context. If adjacent HTML already communicates the same information and the image is purely decorative, use an empty alt attribute in implementation rather than repeating the visible copy.

---

# Guardrails

- Generated people must never be represented as real customers, employees, or testimonial subjects.
- Customer-proof assets require real material and documented approval.
- Generated text, paperwork, logos, vehicle lettering, customer information, and application UI are not production assets.
- Keep visible copy in HTML whenever possible so it remains responsive, searchable, selectable, and accessible.
- Preserve original prompts, reference assets, and reproducibility details when available.
- Do not publish an image merely because it exists in this repository; its recorded status controls.
