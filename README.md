# 💻 Amanda | Full-Stack Developer (Backend-Focused)
Building production-ready web applications with Ruby on Rails

**Currently Available for Full-Stack & Backend Roles** | [Let's Connect!](mailto:grandtheftdisco@gmail.com)

---

## 🛠️ Technical Expertise

```ruby
backend_skills = {
  languages: ["Ruby", "JavaScript"],
  frameworks: ["Ruby on Rails"],
  databases: ["PostgreSQL"],
  apis: ["Stripe Payment Integration", "Cloudinary", "Algolia Search", "webhook routing"],
  architecture: ["service objects", "background jobs", "Redis caching"],
  testing: ["TDD/BDD", "MiniTest"],
  practices: ["code review", "git workflows", "Linux development"]
}
```

```ruby
frontend_skills = {
  styling: ["HTML5", "Tailwind CSS", "accessibility", "responsive/mobile-first design"],
  javascript: ["Vanilla JS", "async/await", "DOM manipulation"],
  frameworks: ["Hotwire"]
}
```
```ruby
currently_exploring = ["embedded dev", "procedural programming"]
```
---

## Featured Projects

### 🐊 [Cajun French API](https://cajunfrenchapi.zoasystems.dev)
A public REST API and community-curated lexicon for Cajun French (ISO 639-3: `frc`): an endangered Romance language spoken across south Louisiana, with no existing programmatic resource

- This is a passion project. I come from a Cajun family but the language was lost in my parents' generation, due to [governmental suppression and social persecution](https://www.mikegravel.org/why-is-cajun-french-in-danger-of-disappearing/).
- ⚜️<em>Es-tu cadien(ne)?</em> Ou es-tu un developer? [I'd love to hear from you.](mailto:cajunfrenchapi@gmail.com)

#### Tentative Features
- Linguistically Accurate Schema
  - Dual `slug`/`display_form` storage to handle non-standardized orthography
  - `spelling_variants` array to preserve all documented forms
  - `standard_french` nullable by design for loanwords with no Parisian equivalent (Choctaw, Spanish, African language borrowings)
- Controlled Regional Vocabulary
  - Parish-level region tagging backed by a constrained enum
  - Invalid regions rejected at the API layer, with slugs sourced from academic literature (Valdman 2010, Papen & Rottet 1997)
- Variant-Aware from Day One
  - Schema carries a `variant` field and `related_entry_ids` cross-references now, before any expansion is planned
  - Avoiding a painful migration when other variants of LA French, like Louisiana Creole, are eventually added
- Submissions Queue
  - Contributors write to a staging table; approved entries promote to the public dataset
  - This provides a full audit trail, meaning no bad data reaches consumers, with a grant-committee-friendly paper trail
- Academic Interoperability
  - Every entry links to Glottolog, Wikidata, ISO 639-3, the Endangered Languages Project, Linguasphere, and other extant online resources for integration with existing linguistic infrastructure

✨ STATUS: pre-launch; seed data and region list in progress

____________

### 🪻 Siempreviva - Greenfield E-Commerce Platform (Private Repo)
Full-stack Rails 8 application built for a botanical wellness business
- Dual-Path Payment Processing: Synchronous + webhook paths coordinated via pessimistic locking for idempotent payment handling
- Service Layer Architecture: Five modular service objects handling cart, payments, webhooks, admin fulfillment, and Stripe caching
- Webhook Security: Stripe HMAC and Cloudinary SHA1 signature verification with Redis-backed replay attack prevention
- Data Integrity Patterns: Reusable soft deletion concern with cascading deletes, DB-level constraints, and atomic transactions
- Background Job Pipeline: Solid Queue for async payment retry with backoff, abandoned cart cleanup, and search index sync

✨ _Stay tuned for the production site! I'll share the link here when we're live._

____________

  ### [🐔 Henventory - Egg Production Tracker](https://github.com/grandtheftdisco/henventory)
  **My first production Rails app, now in active feature expansion and rebrand (2026)**
  - Mid-rollout of the Coop redesign: warm storybook palette, mobile-first PWA, snap-scrolled dashboard with Quick-Log bottom sheet (Phase 0 shipped, Phase 1 in PR)
  - Shipped `collected_at` backdating for users who log eggs after the fact, using a phased rollout (nullable column → backfill → views) — final NOT NULL migration still ahead
  - Built an invite-token system on top of Rails 8's built-in authentication to gate signups

---

## When I'm Not Coding
- **Knitting** - Because debugging code and picking up dropped stitches require similar patience
- **Chicken Farming** - Battle-testing [Henventory](https://github.com/grandtheftdisco/henventory) day after day!

---

## 📬 Let's Build Something Together
**Status**: Available for full-stack or backend roles  
**Contact**: [grandtheftdisco@gmail.com](mailto:grandtheftdisco@gmail.com)
