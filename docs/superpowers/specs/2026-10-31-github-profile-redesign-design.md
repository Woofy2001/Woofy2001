# Induwara Jayakody (`Woofy2001`) GitHub Profile Redesign Specification

**Date:** 2026-10-31  
**Author:** Induwara Yasas Jayakody (`Woofy2001`)  
**Target Repository:** `https://github.com/Woofy2001/Woofy2001`  
**Design Paradigm:** Dark Editorial & Technical Luxury (`design-taste-frontend` + `impeccable`)

---

## 1. Executive Summary & Purpose
Transform the `Woofy2001` GitHub profile from an unpopulated overview into a high-signal, dark-editorial developer homepage and career identity for **Induwara Yasas Jayakody**, positioning him as an **AI / Agentic Systems & Full-Stack Product Engineer**, **Founder & Lead Engineer at Obsid Labs**, and **BEng (Hons) Software Engineering / Computer Science Final Year Researcher (IIT / University of Westminster)**.

---

## 2. Visual Design System & Color Tokens
- **Canvas Background:** `#0A0E17` (Deep Obsidian Slate)
- **Elevated Card Surface:** `#0F172A` with `#1E293B` 1px crisp structural border
- **Primary Accent:** `#14B8A6` (Electric Teal — Agentic Verification & System Architecture)
- **Secondary Accent:** `#F59E0B` (Warm Amber — Empirical Calibration, Research & Product Highlights)
- **Primary Text:** `#F8FAFC` (Crisp Alabaster)
- **Secondary Text:** `#94A3B8` (Muted Technical Slate)
- **Typography inside SVGs:** System UI / Inter / Segoe UI for display headers; JetBrains Mono / SFMono-Regular / Consolas for architecture specs, telemetry, and tags.

---

## 3. Custom Self-Contained SVG Assets (`assets/`)
To guarantee 100% uptime and bypass third-party Vercel rate limits or broken image icons on GitHub's Camo proxy, all visual cards are engineered as self-contained, responsive vector graphics inside the `Woofy2001/Woofy2001` repository:

1. **`assets/hero-banner.svg` (`1200x340`)**:
   - Asymmetric 60/40 dark editorial layout with subtle architectural blueprint grid (`#1E293B` at 35% opacity) and glowing radial mesh accents (`#14B8A6` & `#F59E0B`).
   - Top status pill: `AVAILABLE FOR AI / AGENTIC & FULL-STACK ROLES • COLOMBO, LK (UTC+5:30)`.
   - Main Display Headline: `Induwara Yasas Jayakody`.
   - Sub-headline: `AI / Agentic Systems & Full-Stack Product Engineer`.
   - Right-hand telemetry terminal card displaying active stack, institutional affiliation (`IIT / Univ. of Westminster`), and venture role (`Founder @ Obsid Labs`).
2. **`assets/architecture-card.svg` (`1200x260`)**:
   - Visualizes Induwara's 3-pillar engineering workflow:
     1. **Agentic AI & Verification** (`Claude Sonnet 5.5` • `LangGraph` • `Pydantic v2` • `Playwright` • `ECE/Brier Calibration`)
     2. **Full-Stack Product & Mobile** (`Next.js / TypeScript` • `FastAPI` • `Flutter` • `Node.js / Express` • `Multi-Tenant SaaS`)
     3. **AppSec & Production Reliability** (`Black-Box Auditing` • `AES-256 / Fernet` • `RBAC / JWT` • `Docker & CI/CD`)
3. **`assets/career-telemetry.svg` (`1200x230`)**:
   - High-precision dark bento card displaying:
     - **Domain Allocation Bar**: 45% Full-Stack TypeScript/Next.js, 35% Agentic AI & Python/FastAPI, 20% Mobile (Flutter) & AppSec.
     - **Engineering Highlights**: `23+` Repositories across Public Research & Commercial SaaS, `406+` Annual Contributions, `4-Agent` Explainable Verification Pipeline, `Multi-Tenant` SaaS POS Architecture.
     - **Career Trajectory Milestones**: Academic Research (`2023–2027`) → Venture Leadership (`Obsid Labs`) → Target Senior/Product Engineering Impact.

---

## 4. Profile `README.md` Architecture
1. **Adaptive Hero Banner (`<picture>`)** + **Quick-Action Pill Bar** (LinkedIn `www.linkedin.com/in/induwara-jayakody-21a478303`, Email `zed.induwara@gmail.com`, Obsid Labs, Flagship Research `ReqVerify`).
2. **Executive Positioning & "Current Focus (`Now`)"**:
   - Concise 5-second positioning statement + structured table of current research, commercial engineering, and career trajectory.
3. **System Architecture Visual (`assets/architecture-card.svg`)**.
4. **Flagship Open-Source & Research Systems (2x2 Matrix)**:
   - `ReqVerify`: Multi-Agent Explainable Requirements-Verification Framework (`Python`, `LangGraph`, `Claude Sonnet 5.5`, `Playwright`, `Pydantic v2`).
   - `ProjectBluePrint`: AI-Powered 2D Floor Plan Generator & Marketplace (`Flutter`, `FastAPI`, `Firebase`, `Voice-to-Plan`).
   - `boarding-buddy-connect`: Student Accommodation Platform & Modular REST API (`TypeScript`, `Node.js`, `Express`, `MongoDB`, `Cloudinary`, `JWT`).
   - `SecureVault`: Endpoint File Encryption & Threat Detection Suite (`Python`, `AES-256 / Fernet`, `Watchdog`, `USB Telemetry`).
5. **Commercial & Enterprise Production Systems (Selected Private Architecture)**:
   - **Multi-Tenant SaaS POS Platform (`Pos_System_WC`)**: Offline-first sync, CRM, inventory analytics, super-admin control plane for retail, hospitality, and pharmacies.
   - **Enterprise AppSec & Security Audits (`nikko-motors-security-audit`)**: Vulnerability assessment, access control hardening, and commerce platform engineering.
   - **Obsid Labs Client Engineering**: High-craft web platforms (`v_jewellery`, `wj-construction`, `Niru_Bathik`, `Td_Investment`).
6. **Curated Tech Stack & Career Readiness Checklist**:
   - Clean, categorized shields.io `flat-square` dark-calibrated badge matrix.
   - Comprehensive Career Path & Proof-of-Work summary + Footer contact CTA.

---

## 5. GitHub Account & Repository Metadata Synchronization
- **User Profile (`PATCH /user`)**:
  - `name`: `Induwara Jayakody`
  - `bio`: `AI / Agentic Systems & Full-Stack Engineer | Building multi-agent LLM frameworks (LangGraph) & scalable web/mobile products | Founder @ Obsid Labs`
  - `company`: `Obsid Labs`
  - `location`: `Colombo, Sri Lanka`
  - `blog`: `https://www.linkedin.com/in/induwara-jayakody-21a478303`
- **Public Repository Metadata & Topics**:
  - `reqverify`: Add topics `llm-agents`, `langgraph`, `playwright`, `requirements-verification`, `claude-sonnet`, `python`, `software-testing`, `calibration`.
  - `ProjectBluePrint`: Add topics `flutter`, `fastapi`, `generative-ai`, `floor-plan-generator`, `firebase`, `mobile-app`, `python`.
  - `boarding-buddy-connect`: Add topics `typescript`, `nodejs`, `express`, `mongodb`, `jwt-authentication`, `rest-api`, `sri-lanka`.
  - `SecureVault`: Set description to `"Modular Python cybersecurity toolkit featuring AES-256 (Fernet) file encryption, directory tampering watchdog, and USB device telemetry."` and add topics `cybersecurity`, `python`, `aes-encryption`, `fernet`, `threat-detection`, `file-monitoring`.
