# The Vibe Coder Portfolio: 7 Multi-Platform Digital Products
**Author:** Shailender Pushkar (Founder, Product Operator & AI Builder)  
**Incubation:** AIC-BHU (Atal Incubation Centre, Banaras Hindu University)  
**Location:** Pune, Maharashtra, India (Available On-Site Immediately)  
**Contact:** shailenderofficial01@gmail.com | +91 7376159577 | [LinkedIn](https://www.linkedin.com/in/shailender-pushkar-4b7586231/) | [GitHub](https://github.com/shailender14)  
**Interactive Web Portfolio:** [Open portfolio.html](file:///c:/Users/pc/Downloads/Resume/portfolio.html)

---

## ⚡ Executive Overview: The Power of Vibe Coding
In early-stage ventures, speed of execution is the ultimate moat. Traditional software development cycles—involving weeks of ticket grooming, bloated engineering teams, and slow feature velocity—burn critical capital before achieving product-market fit.

**Vibe Coding** is the modern paradigm of software engineering: combining domain expertise, product architecture, and user journey mapping with high-speed AI orchestration (Antigravity IDE, Google GenAI SDK, Cursor, Stitch API). 

Without relying on external dev agencies or hiring a multi-person dev team, I single-handedly architected, coded, tested, and deployed **7 production-grade digital products** spanning Mobile Apps, Real-time CRMs, Foodtech Monorepos, OSINT Scrapers, and Luxury E-Commerce.

---

## 🌐 Live Product Access & Verification Directory

| Project Name | Category | Primary Live Link | Supporting Assets / Drive |
| :--- | :--- | :--- | :--- |
| **1. WooFie (PawSpace)** | Petcare Super-App & Digital ID | 🔗 [pawspace-india.netlify.app](https://pawspace-india.netlify.app/) | 📂 [Stitch UI Designs (Drive)](https://drive.google.com/drive/folders/1-Qrj7Wn3pCKDB1nHQnwVQ2bROhFW2_lZ) |
| **2. FOMINS B2B CRM** | Enterprise Sales Pipeline | 🔗 [crm.fomins.co.in](https://crm.fomins.co.in/) | 📂 [GitHub Repo / Codebase](https://github.com/shailender14) |
| **3. FOMINS Foodtech Platform** | Corporate Dining Storefront | 🔗 [www.fomins.co.in](https://www.fomins.co.in/) | 📋 [Design Specification (Stitch)](file:///c:/Users/pc/Downloads/FOMINS_Website/DESIGN.md) |
| **4. House of Mandana** | Luxury D2C E-Commerce | 🔗 [houseofmandana.in](https://houseofmandana.in/) | 📑 [Vaaree Audit Blueprint](file:///C:/Users/pc/.gemini/antigravity/brain/753cce39-991a-4b45-9b96-1b9d3545312d/VIBE_CODING_PORTFOLIO_SHOWCASE.md) |
| **5. FOMINS Mobile App (Stitch UI)** | Mobile Foodtech UI Prototypes | 📂 [Stitch Mobile UI (Drive)](https://drive.google.com/drive/folders/1YORJlyWmSWfnUP_vBNEgL_JQ3EpbQwgD) | 📱 Google Stitch Mobile Flow |
| **6. B2B OSINT Lead Scraper** | Python Data & SMTP Engine | 💻 [Engine Architecture Page](file:///c:/Users/pc/Downloads/Resume/b2b_lead_scraper.html) | 🔍 Port 25 SMTP Socket Handshake |
| **7. FOMINS Monorepo** | Customer + Rider + KDS Admin | 💻 [Monorepo Architecture](file:///C:/Users/pc/Downloads/fomis-foodtech/README.md) | 📦 React Native + Next.js KDS |

---

## 🍕 Project 1: FOMINS Foodtech Ecosystem (Monorepo)
*Full-Stack Multi-App Architecture for Urban Workplace Dining & Quick Food Delivery*
* **Primary Reference:** [fomis-foodtech Monorepo](file:///C:/Users/pc/Downloads/fomis-foodtech/README.md)

```
fomis-foodtech/
├── apps/
│   ├── customer-app/          # Native React Native (Expo) - Swiggy/EatSure/Swish Tier UI
│   ├── rider-app/             # Native React Native (Expo) - Fleet Partner App (Play Store Ready)
│   └── web-kds-admin/         # Next.js App Router - Tablet Kitchen Display System & Super Admin
└── packages/
    ├── shared-firebase/       # Centralized Firebase SDK, Firestore rules, schemas & shared hooks
    └── ui-tokens/             # Design tokens, color palettes (#E53E3E, #2D3748), typography
```

### 1. Problem & Vision
Urban professionals and corporate employees face a sharp tradeoff between speed (quick commerce snacks) and meal quality (freshly prepared culinary dining). FOMINS bridge this gap by integrating a multi-brand cloud kitchen with a unified digital ecosystem.

### 2. Architecture & Technical Implementation
* **Monorepo Design:** Built using a synchronized monorepo pattern where customer ordering, kitchen dispatch, and fleet delivery share identical TypeScript interfaces, Firestore schemas, and brand tokens.
* **Customer App (`apps/customer-app`):** High-framerate React Native mobile app featuring animated food category rails, instant dish customization, localized cart state, and real-time order tracking.
* **Fleet Rider App (`apps/rider-app`):** Streamlined courier UI for quick order acceptance, step-by-step route directions, and OTP delivery handshakes.
* **Kitchen Display System (KDS) & Admin (`apps/web-kds-admin`):** High-contrast tablet interface for kitchen chefs to view incoming ticket orders (KOT), mark preparation milestones (Queued ➔ Cooking ➔ Ready ➔ Dispatched), and track kitchen prep times.

---

## 📊 Project 2: FOMINS B2B Outreach CRM
*Enterprise Sales Pipeline & Foodtech Corporate Deals Platform*
* **Live System:** 🔗 [https://crm.fomins.co.in/](https://crm.fomins.co.in/)

```
fomins-b2b-crm/
├── app/                       # Next.js 14 App Router (leads, pipeline, analytics)
├── components/                # Modular enterprise UI
│   ├── KanbanBoard.tsx        # Multi-stage drag-and-drop deal board
│   ├── TableView.tsx          # High-density searchable enterprise data grid
│   ├── TastingModal.tsx       # Corporate food tasting session scheduler
│   ├── ScheduleMeetingModal.tsx # Google Calendar scheduling integration
│   ├── AddLeadModal.tsx       # Context-aware lead entry modal
│   ├── LeadDetailModal.tsx    # Complete corporate intelligence overview
│   ├── ExcelUploader.tsx      # Bulk lead parsing and validation engine
│   └── AnalyticsBar.tsx       # Live deal volume & pipeline conversion velocity
└── server_engine/             # Backend automation and lead validation routines
```

### 1. Problem & Vision
Selling corporate catering, daily cafeteria meal passes, and bulk lunch subscriptions requires a specialized sales pipeline that standard CRMs (like HubSpot or Salesforce) cannot handle without expensive custom plugins—specifically handling corporate tasting sessions, menu preference negotiations, and headcount-based meal quotas.

### 2. Architecture & Technical Implementation
* **Real-time Pipeline Management:** Built on **Next.js 14 App Router**, **Tailwind CSS**, and **Cloud Firestore** for zero-latency multi-user sync.
* **Interactive Kanban Board:** Drag-and-drop deal transitions across 6 custom stages: *New Lead ➔ Contacted ➔ Tasting Scheduled ➔ Proposal Sent ➔ Won / Active ➔ Closed Lost*.
* **B2B Foodtech Specialized Modals:**
  * `TastingModal.tsx`: Coordinates culinary sampling sessions at tech parks (menu selection, attendee count, feedback capture).
  * `ScheduleMeetingModal.tsx`: Direct integration with Google Calendar API (`googleapis`).
  * `ExcelUploader.tsx`: Ingests raw `.xlsx`/`.csv` directories and maps company metadata, employee tiers, and POC contacts seamlessly.

---

## 📱 Project 3: FOMINS Mobile Food App (Stitch UI Prototypes)
*Mobile Foodtech UI Architecture & Stitch Prototypes*
* **Google Drive Repository:** 📂 [stitch_fomins_mobile_food_app (Google Drive)](https://drive.google.com/drive/folders/1YORJlyWmSWfnUP_vBNEgL_JQ3EpbQwgD)

```
stitch_fomins_mobile_food_app/
├── lib/
│   ├── core/                  # Design system, themes, API services, routing
│   ├── data/                  # Firestore data providers, repository pattern
│   ├── features/              # Cart, cafeteria browsing, live tracking, subscriptions
│   ├── main.dart              # Customer Mobile Application entrypoint
│   └── main_rider.dart        # Fleet Courier Partner Application entrypoint
├── android/                   # Native Gradle, ProGuard, Keystore configurations
└── Stitch UI Screens/         # Interactive mobile foodtech screens & UI specs
```

### 1. Problem & Vision
Designing and spec'ing an intuitive mobile food ordering experience for corporate employees that eliminates ordering friction during peak lunch hours.

### 2. Architecture & Technical Implementation
* **Stitch Standard UI:** Designed according to Google Stitch UI principles with responsive category rails, calorie/nutrition indicators, and instant meal-pass checkouts.
* **Fleet Partner Flows:** Wireframed courier routing screens with turn-by-turn navigation and OTP handshakes.
* **Google Drive Repository:** Fully organized and accessible on Google Drive showcasing raw Stitch screen assets and design prototypes.

---

## 🕵️ Project 4: Leads — Python B2B Lead Scraper & Deliverability Engine
*Autonomous OSINT Lead Extraction, Data Sanitation & SMTP Socket Verification*
* **Architecture & Interactive Showcase:** 💻 [b2b_lead_scraper.html](file:///c:/Users/pc/Downloads/Resume/b2b_lead_scraper.html)

```
leads/
├── b2b_lead_engine.py         # Multi-zone OSINT company & people extraction engine
├── reverify_existing_leads.py # Port 25 SMTP handshake & Gemini AI entity verifier
├── fill_missing_company_leads.py # Automated missing contact data enricher
├── lead_history.db            # Local SQLite database for deduplication and logging
└── lead_output/               # Structured 5-tier verified corporate database
```

### 1. Problem & Vision
B2B database subscriptions (Apollo, ZoomInfo, Lusha) cost thousands of dollars annually and frequently carry stale, bounced, or irrelevant contacts for regional Indian IT corridors. We needed a proprietary, zero-cost lead pipeline targeting decision-makers (HR Heads, Facility Managers, Admin Leads) in Pune IT Parks.

### 2. Architecture & Technical Implementation
* **Anti-Bot OSINT Scraper (`b2b_lead_engine.py`):** Targeted IT corridors (Hinjewadi Phase 1-3, Magarpatta Cybercity, Kharadi EON Free Zone). Generated strict directory outputs categorizing companies, employee brackets, and human profiles.
* **Multi-Pattern Email Synthesis:** Dynamically constructed permutations (`{first}.{last}`, `{first}{last}`, `{first}.{l}`) based on company MX domain patterns.
* **Live Port 25 SMTP Handshake (`reverify_existing_leads.py`):** Established direct socket connections to recipient mail servers (Google Workspace, Microsoft 365, proofpoint) executing `HELO ➔ MAIL FROM ➔ RCPT TO` sequences to verify mailbox existence **without triggering spam filters or sending actual emails**.
* **AI Intelligence Layer:** Utilized the **Google GenAI SDK (Gemini API)** for entity disambiguation, phone number extraction, and job title standardization (filtering out non-decision makers).

---

## 🌐 Project 5: FOMINS Workplace Food Solutions Website
*Enterprise Digital Storefront & Automated Quote Engine*
* **Live Website:** 🔗 [https://www.fomins.co.in/](https://www.fomins.co.in/)

```
FOMINS_Website/
├── src/
│   ├── components/            # Hero slider, cafeteria explorer, quote calculator
│   ├── pages/                 # Corporate catering, meal pass subscriptions, compliance
│   ├── services/              # Firebase integration & Google Maps API loader
│   └── data/                  # Catalog dump, pricing matrices, menu tiers
├── DESIGN.md                  # Comprehensive Google Stitch Standard UI/UX Specification
└── catalog_audit_report.txt   # Nutritional, allergen, and price audit report
```

### 1. Problem & Vision
Corporate decision-makers require a credible, legally compliant, and polished web interface before signing long-term catering or meal-pass agreements.

### 2. Architecture & Technical Implementation
* **Design Excellence:** Built strictly following the **Google Stitch Design Standard**—high-contrast typography, zero-jank responsive grids, and micro-interactions powered by **Framer Motion**.
* **Google Maps Integration:** Embedded `@googlemaps/js-api-loader` to provide dynamic radius calculations from the Hinjewadi hub to client corporate campuses.
* **Instant B2B PDF Proposals:** Integrated `html2canvas` and `jspdf` to allow HR and Procurement managers to configure custom meal plans and instantly download customized, branded B2B commercial proposals.
* **Regulatory Compliance:** Showcases complete compliance verification (CIN, DPIIT Startup India #DIPP209957, FSSAI License, GSTIN).

---

## 🐾 Project 6: Milli - PawSpace (Petcare Super-App)
*Comprehensive Architecture & MVP for Modern Pet Parenting*
* **Live Web App:** 🔗 [https://pawspace-india.netlify.app/](https://pawspace-india.netlify.app/)
* **Google Drive Designs:** 📂 [stitch_pawspace_pet_care_platform_homepage](https://drive.google.com/drive/folders/1-Qrj7Wn3pCKDB1nHQnwVQ2bROhFW2_lZ)

```
Milli/
├── src/app/
│   ├── digital-pet-id/        # Smart QR collar & public/private pet profile engine
│   ├── pawport/               # Pet air & rail travel compliance verification
│   ├── services/              # Cage-free boarding, daycare & dog walking tracking
│   ├── delivery-safety/       # B2B pet delivery safety standard API
│   ├── wellness/              # Doorstep wellness checkup scheduling
│   └── portal/                # Customer and host management portal
├── firestore.rules            # Hardened security rules with role-based access
├── GEMINI.md                  # Locked 5-tone design system (#2A338D, #95D9EE, #F47645)
└── playwright.config.ts       # End-to-end automated UI test suite
```

### 1. Problem & Vision
The pet care sector in India is deeply fragmented: boarding kennels rely on cages, dog-walking lacks accountability, and pet travel (rail/air) faces bureaucratic hurdles. Inspired by my published book *Millu – She Rescued Us*, I architected **PawSpace** as an all-in-one ethical pet ecosystem.

### 2. Architecture & Technical Implementation
* **Digital Pet ID & QR Collar:** Dual-view profile architecture. When a pet collar QR is scanned by a stranger, it reveals a clean Lost & Found contact modal; when accessed by authorized boarding hosts or vets, it displays full medical records, dietary restrictions, and allergy history.
* **Pawport Travel Engine:** Comprehensive compliance engine generating standardized travel documents for Indian Railways and domestic airlines, complete with a **4-digit secure veterinarian verification PIN**.
* **Cage-Free Boarding & Daycare:** Includes a 10-point environmental inspection checklist, mandatory Meet & Greet scheduling, and live photo check-in milestones.
* **Live GPS Dog Walking Tracker:** Real-time path tracing with geo-tagged pee/poo pins and mandatory water hydration photo proofs.
* **Enterprise Hardening:** Hardened Firestore security rules, comprehensive storage policies, and automated Playwright E2E tests.

---

## 👑 Project 7: House of Mandana (Luxury D2C E-Commerce)
*Custom Shopify Storefront Architecture, Vaaree Benchmark & Agentic SEO*
* **Live Store:** 🔗 [https://houseofmandana.in/](https://houseofmandana.in/)

```
HOUSE OF MANDANA/
├── custom-liquid-sections/    # 13 bespoke homepage modules in modular Liquid/HTML
├── design-system/             # Luxury editorial typography & high-AOV color palettes
├── catalog/                   # 15-product launch photography, weights & dimensions
├── ACTION-PLAN.md             # High-intent SEO & Collection restructuring playbook
├── audit-results.json         # Competitive benchmark audit against Vaaree
└── analyze_weight_mapping.py  # Automated inventory & courier volumetric weight engine
```

### 1. Problem & Vision
Competing in the luxury home decor and artisan lifestyle space requires elevated editorial aesthetics, fast page load speeds, and strict SEO indexing to capture high-ticket organic buyers without massive ad spend.

### 2. Architecture & Technical Implementation
* **Competitive Audit vs Vaaree:** Executed a comprehensive gap audit analyzing *Vaaree*’s collection filters, mobile ergonomics, and cart upsell mechanics, translating the findings into a superior custom theme blueprint.
* **Modular Storefront Engine:** Engineered 13 bespoke homepage sections (Luxury Hero, Curated Vignettes, Artisan Highlights, Sliding Carousels, Sticky Cart Drawer) in clean, modular HTML5/CSS3/Vanilla JS.
* **Collections SEO Master Architecture:** Restructured collection handles and 301 redirect trees to capture high-intent queries (e.g., "Buddha Zen Decor", "Luxury Ceramic Vases"), resolving duplicate collection indexing issues.
* **Product Catalog & Fulfillment Mapping:** Scripted Python automation (`analyze_weight_mapping.py`) to map SKU weights and courier volumetric rates for 15+ flagship launch items.

---

## 🎯 Summary: Why This Portfolio Matters for Employers

| Capability | Demonstrated Proof in Portfolio |
| :--- | :--- |
| **0-to-1 Product Ownership** | Conceived, architected, and shipped 7 distinct digital systems from scratch. |
| **Modern AI Orchestration** | Harnessed LLMs, Stitch API, and generative coding tools to produce agency-level code in record time. |
| **Full-Stack Versatility** | Hands-on across Flutter, React Native, Next.js, Firebase, Python, and Shopify Liquid. |
| **Ground-Level Business Acumen** | Grounded in real-world startup execution—commercial kitchen P&L, AIC-BHU incubation, and B2B enterprise sales. |

---
*Curated by Shailender Pushkar. Ready for deployment across GitHub, portfolio websites, and recruiter presentations.*
