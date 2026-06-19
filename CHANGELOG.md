# Changelog

All notable changes to the ErrandEase platform will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Integration with smart-lock APIs to allow "contactless home entry" for verified runners.

---

## [1.2.0] - 2026-06-12

### Added
- **Errand Tracking Map:** Live GPS tracking view for clients to see their Runner's progress in real-time.
- **Tip Adjustments:** Clients can now add or modify a Runner's tip up to 24 hours after task completion.
- Push notification system for instant task assignment updates.

### Changed
- Upgraded the task matching algorithm to prioritize proximity.

### Fixed
- Resolved an issue where payment processing would timeout.
- Fixed a bug causing the Runner rating stars to display incorrectly on dark mode layouts.

---

## [1.1.0] - 2026-03-05

### Added
- **Errand Categories:** Added structured categories (Grocery Delivery, House Cleaning, Tech Support, Pet Care) with custom item checklists.
- Support for split-payments using Apple Pay and Google Pay.
- Automated email receipts generation upon task completion.

### Changed
- Profile verification process now requires a real-time selfie check alongside government ID upload to improve trust.

### Security
- Implemented data masking for client phone numbers and addresses; Runners now only see precise locations once a task is officially accepted.

---

## [1.0.0] - 2026-01-10

### Added
- **Initial MVP Release:** Core platform launch for ErrandEase.
- **User Roles:** Distinct onboarding pipelines, dashboards, and profiles for both "Clients" (posting tasks) and "Runners" (fulfilling tasks).
- **Task Marketplace:** Public feed for browsing, filtering, and bidding on local chores/errands.
- **Secure Payments:** Stripe escrow integration to hold funds safely until a client confirms task completion.
- Basic user review and rating system (1-5 stars).
