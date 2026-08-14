# TULBOXX Website Blueprint

This repository is the planning and source-of-truth workspace for the TULBOXX marketing website.

The goal is to define the positioning, story, sitemap, page copy, visual direction, and implementation guidance before those decisions are moved into the production `tulboxx-web` repository.

## Core idea

TULBOXX should not feel like another contractor CRM or software feature catalog. The website should tell a story about helping contractors take back control of their business.

Primary positioning:

> Run Your Entire Service Business From One Place.

Brand promise:

> Help contractors spend less time managing paperwork and more time growing their business.

## Working principles

- Sell the transformation, not the software.
- The contractor is the hero. TULBOXX is the guide.
- Emotion first, product second.
- Every page should answer the next logical question in the buyer's mind.
- Show real workflows, real contractors, and real outcomes.
- Avoid feature dumping and generic SaaS language.
- Design should feel premium, industrial, modern, and simple.

## Repository structure

### Strategy and direction

- `AGENTS.md` - operating instructions for Codex and all contributors.
- `WEBSITE_NORTH_STAR.md` - strategic direction and non-negotiables.
- `WHY.md` - company purpose and product philosophy.
- `BRAND_STRATEGY.md` - positioning, messaging, audience, and voice.
- `DESIGN_PRINCIPLES.md` - visual and interaction principles.
- `CUSTOMER_JOURNEY.md` - the visitor's psychological journey.
- `WEBSITE_SITEMAP.md` - information architecture and page roles.

### Page blueprints

- `HOME.md`
- `WHY_TULBOXX.md`
- `PLATFORM.md`
- `HOW_IT_WORKS.md`
- `FEATURES.md`
- `SOLUTIONS.md`
- `PRICING.md`

Each page blueprint defines the page's purpose, narrative sequence, public-copy candidate, visual direction, responsive behavior, accessibility requirements, and implementation checks. Strategy and page structure are locked; public copy still requires final approval, and product-dependent claims require verification before launch.

### Visual and component system

- `VISUAL_STORYBOARD.md` - coordinated image, product UI, and motion direction.
- `PHOTOGRAPHY_DIRECTION.md` - canonical photographic art direction, generation rules, campaign continuity, and post-processing standard.
- `assets/images/README.md` - image library, naming rules, approval status, alt text, and production notes.
- `COMPONENT_LIBRARY.md` - reusable marketing component patterns.
- `docs/TULBOXX_BRAND_STYLE_GUIDE.pdf` - source reference for visual styling, typography, and color.

## Blueprint status

The core launch journey from Home through Pricing is documented. Resources, Customer Stories, and About remain intentional later-phase pages; they should be developed when approved content, evidence, and business requirements are available.

The Start Free offer is established: no credit card is required; the first five AI-assisted estimates can be created, sent, shared, and downloaded free; and TULBOXX creates estimate six before protecting its send, share, and download actions with the upgrade wall. The current paid offer is Pro at the confirmed $39-per-month Ground Floor Rate, with every feature included and the monthly rate protected for the life of the active subscription. Ground Floor names the offer and member cohort; Pro remains the product plan name. The final signup route, account-creation steps, and remaining estimate-count edge cases still require implementation decisions; `PRICING.md` is the source of truth.

## Handoff to production

Once the strategy, page copy, and visual assets are approved, Codex can use this repository as the source of truth while implementing the site in the production `tulboxx-web` repository.

Do not treat this repository as the production app unless explicitly directed.
