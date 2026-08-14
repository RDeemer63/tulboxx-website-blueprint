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

---

# Assets Under Review

No assets are currently under review.

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
