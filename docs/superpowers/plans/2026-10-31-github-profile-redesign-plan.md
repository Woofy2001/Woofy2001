# GitHub Profile Redesign Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build and deploy a complete Dark Editorial & Technical Luxury GitHub Profile (`README.md`, 3 custom SVG cards, account metadata, and repository topics/descriptions) for Induwara Jayakody (`Woofy2001`).

**Architecture:** Self-contained SVG vector illustrations stored in `assets/` inside the `Woofy2001/Woofy2001` profile repository ensure zero external API downtime and crisp retina rendering on GitHub desktop and mobile. The `README.md` pairs these SVG cards with structured GFM tables, dark-calibrated `flat-square` badges, and verifiable engineering case studies.

**Tech Stack:** GitHub Flavored Markdown (GFM), Scalable Vector Graphics (SVG 1.1), Shields.io (`flat-square`), GitHub CLI (`gh api`).

**Spec:** `docs/superpowers/specs/2026-10-31-github-profile-redesign-design.md`

## Global Constraints
- Canvas palette: `#0A0E17` background, `#0F172A` surface, `#1E293B` border, `#14B8A6` primary teal accent, `#F59E0B` secondary amber accent, `#F8FAFC` primary text, `#94A3B8` muted slate.
- Every SVG file must be valid XML (`xmlns="http://www.w3.org/2000/svg"`, explicit `viewBox`, and web-safe system font stacks).
- No third-party rate-limited Vercel stat cards that can render broken images.
- Never expose private repository source code or proprietary credentials in public case study summaries.

## Review Focus
- Valid XML/SVG entity escaping (`&amp;` instead of raw `&` inside SVG text/attributes).
- Relative asset paths (`./assets/hero-banner.svg`) so GitHub renders images directly from the `main` branch.
- GitHub bio character limit (`<= 160` characters).
- Repository topic naming rules (lowercase alphanumeric and hyphens only, `<= 50` chars each).

---

### Task 1: Engineer Custom SVG Assets (`assets/`)

**Files:**
- Create: `assets/hero-banner.svg`
- Create: `assets/architecture-card.svg`
- Create: `assets/career-telemetry.svg`

- [ ] **Step 1: Create `assets/hero-banner.svg`, `assets/architecture-card.svg`, and `assets/career-telemetry.svg`**
- [ ] **Step 2: Validate XML well-formedness of all SVG files using PowerShell `[xml](Get-Content ...)`**

---

### Task 2: Author Profile `README.md`

**Files:**
- Create: `README.md`

- [ ] **Step 1: Write `README.md` incorporating all 6 sections, career blueprint, public flagship table, enterprise private systems showcase, and tech stack**
- [ ] **Step 2: Verify relative links and badge URLs in `README.md`**

---

### Task 3: Deploy to `Woofy2001/Woofy2001` & Synchronize GitHub Metadata

**Files:**
- Modify: Git repository & remote `https://github.com/Woofy2001/Woofy2001.git`

- [ ] **Step 1: Initialize git repo, commit `assets/*.svg` and `README.md`, and push to `Woofy2001/Woofy2001` (`main` branch)**
- [ ] **Step 2: Update GitHub user profile metadata (`bio`, `company`, `location`, `blog`) via `gh api -X PATCH user`**
- [ ] **Step 3: Update `SecureVault` description and set curated topics on `reqverify`, `ProjectBluePrint`, `boarding-buddy-connect`, and `SecureVault`**
- [ ] **Step 4: Verify live deployment via `gh api repos/Woofy2001/Woofy2001/readme` and `gh api user`**
