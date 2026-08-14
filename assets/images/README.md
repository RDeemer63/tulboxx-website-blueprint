# TULBOXX Image Library

This directory stores marketing-image masters, review candidates, approval status, production notes, and final alt text.

`PHOTOGRAPHY_DIRECTION.md` governs how photography is generated, selected, edited, cropped, and approved. `VISUAL_STORYBOARD.md` and the page blueprints determine what each asset must communicate.

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
home-reality-02-triptych-concept.png
```

- `master` identifies the highest-quality approved source.
- `desktop` and `mobile` identify intentionally composed aspect ratios, not merely resized files.
- `concept` identifies a review asset that is not approved for production.
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
