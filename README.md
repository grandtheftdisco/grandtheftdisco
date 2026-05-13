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
