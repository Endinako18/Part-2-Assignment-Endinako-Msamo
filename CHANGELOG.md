# Changelog

All notable changes to the ErrandEase platform will be documented in this file, detailing technical updates, target audience optimizations, service expansions, and user social proof implementation.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- **Upcoming Service:** Integration with smart-lock APIs to allow "contactless home entry" for verified runners handling home maintenance.

---

## [1.2.0] - 2026-06-12

### Added
- **Target Audience Feature (Runners):** Added live GPS tracking maps and instant push notifications to help Errand Runners navigate and claim tasks faster.
- **Target Audience Feature (Clients):** Implemented post-task tip adjustments, allowing busy clients up to 24 hours to modify tips.
- **Testimonial System Update:** Added a "Verified Badge" to the homepage testimonial carousel, pulling real-time 5-star ratings directly from completed platform transactions.

### Fixed
- Fixed a bug causing the Runner rating stars to display incorrectly on dark mode layouts within the testimonial blocks.

---

## [1.1.0] - 2026-03-05

### Added
- **Core Services Launch:** Formally rolled out four distinct, structured service categories with custom interactive checklists:
  * 📦 *Grocery & Custom Deliveries*
  * 🧹 *Home Improvement & Maintenance*
  * 🐾 *Pet Care Services*
  * 💻 *Tech Support & Admin Chores*
- **Testimonials Section:** Designed and deployed a responsive review component on the landing page showcasing early alpha-tester quotes (e.g., *Sarah M., Client: "ErrandEase saved my sanity..."*).
- **Target Audience Segmentation:** Refactored the registration pipeline to segment users into two distinct target audiences: **Clients** (simplified post-a-task wizard) and **Runners** (comprehensive background check and payment onboarding).

---

## [1.0.0] - 2026-01-10

### Added
- **Initial MVP Release:** Core platform launch for ErrandEase.
- **Target Audience Framework:** Set up database schemas separating "Clients" (Task Posters) and "Runners" (Task Doers).
- **Core Service Framework:** Created a generalized marketplace feed allowing users to post any generic errand or chore request.
- **Secure Payments:** Integrated Stripe escrow to safely hold funds until a client confirms their errand service is complete.
