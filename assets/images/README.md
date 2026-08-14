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

---

# Assets Under Review

## `HOME-REALITY-02`

- **File:** [`review/home/home-reality-02-triptych-concept.png`](review/home/home-reality-02-triptych-concept.png)
- **Status:** Concept approved; execution requires revision
- **Dimensions:** 1536 × 1024
- **Source:** AI-generated campaign concept
- **Purpose:** Three recognition moments showing customer messages, scattered notes, and work continuing after hours
- **Alt text:** Pending final production asset
- **What works:** Clear narrative sequence, recognizable administrative friction, consistent contractor character, and an effective transition from fieldwork to after-hours work.
- **Required revision:** Produce three clean underlying photographs without baked-in headings, captions, app UI, readable paperwork, or synthetic text. Build the headline, panel labels, descriptions, dividers, and any product UI as accessible HTML or approved interface composites. Bring the color and contrast closer to the softer `HOME-HERO-01` treatment, and keep the after-hours scene thoughtful rather than dramatically exhausted.

This concept must remain in `review/` until the three source images and responsive layout are approved.

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
