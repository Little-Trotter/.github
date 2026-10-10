<!--
  Little Trotter Organization Profile
  Copyright (c) 2026 Eifel42 Stefan Zils
  Licensed under Apache License 2.0 and CC BY 4.0
-->

# Little Trotter

<p align="center">
  <img src="https://raw.githubusercontent.com/Little-Trotter/.github/main/profile/little-trotter-horse.png" alt="Little Trotter logo: stylised horse" width="280" />
</p>

**Sovereign E-Invoicing & Quotation Authoring for Small and Medium Businesses.**

Little Trotter is a modular open-source software suite designed for craft businesses, engineering consultancies, freelancers, and small to medium-sized enterprises (SMEs). It combines full regulatory compliance under European standards (EN 16931) with complete local data sovereignty (*Local-First*) — completely free of per-seat licenses, vendor lock-in, or third-party cloud fees.

---

## Business Capabilities at a Glance

- **Seamless Workflow (Quote to Invoice):** Full quotation lifecycle authoring (*Angebotswesen*), itemized scope tracking, and one-click conversion of accepted quotes directly into invoice drafts without media breaks.
- **Compliance by Architecture:** Native generation of validated **XRechnung 3.0.x** and **Factur-X / ZUGFeRD 2.x** files embedded in archival **DIN 5008 PDF/A-3** containers, pre-validated against official KoSIT Schematron rulebooks.
- **Engineered for Trade & B2B Realities:**
  - **Consumer Protections (Crafts Profile):** Automated statutory notices on B2C invoices (two-year retention requirement on property work, itemized separation of labor, machinery, and travel expenses).
  - **Enterprise Buyer References:** Flexible support for routing credentials (Buyer Reference / Leitweg-ID `BT-10`, Purchase Order `BT-13`, Project Reference `BT-11`).
  - **Cross-Border Tax Support:** Multi-jurisdiction VAT registrations (e.g., dual DE and LU tax IDs) and automated EU intra-community reverse charge processing.
- **Receipt Pool & Travel Expenses:** Centralized attachment repository with SHA-256 duplicate detection and automatic size-budget caps to prevent email server rejections.
- **Audit-Compliant Corrections:** Strict immutability; corrections produce formal cancellation documents (type 384) alongside the original. Zero in-place overwrites or record deletions.
- **Tax Advisor Handover:** One-click Excel workbooks per invoice or period with strongly typed cells, dynamic control formulas for internal reconciliations, and journal audit sheets.

---

## Digital Sovereignty & The Cooperative Principle

> *"Was dem Einzelnen nicht möglich ist, das vermögen viele."*  
> *(What is impossible for one alone, many can achieve.)*  
> — **Friedrich Wilhelm Raiffeisen**

Mandatory e-invoicing forces independent businesses into recurring subscription costs and proprietary cloud monopolies. Little Trotter applies the cooperative self-help principle to business infrastructure:

1. **Zero Recurring Costs:** Open source under the Apache 2.0 license. No seat licensing, no tier restrictions, no fees per sent invoice.
2. **Local-First Data Ownership:** All customer master data, quotations, invoices, and audit logs remain on your local hardware. No automated external data transmission.
3. **Low-Power Hardware:** Optimized along Green IT guidelines to run smoothly on silent, entry-level office mini PCs with automated overnight standby.

---

## The Little Trotter Ecosystem

| Repository | Purpose |
|---|---|
| [**`little-trotter/invoice`**](https://github.com/Little-Trotter/invoice) | **Core System:** E-Invoicing Engine, Quotation Module (`kotlin-quote`), B2B Email Dispatch (`kotlin-email`), Typst Document Renderer (`kotlin-xpdf`), Docker Compose quickstart, and comprehensive [arc42 architecture documentation](https://github.com/Little-Trotter/invoice/tree/main/arc42-docs). |
| [**`little-trotter/little-trotter-admin-tools`**](https://github.com/Little-Trotter/little-trotter-admin-tools) | **Operations & QA:** Playwright browser test suites, automated verification pipelines, and deployment tooling (scheduled for public release Q4/2027). |

---

## Release Lines (Focus & Business Value)

Named after traditional working and draft horse breeds (*Zugpferde*, inspired by ZUGFeRD):

- 🐴 **Haflinger (Core Invoicing Baseline):** Robust, sure-footed working foundation. Compliant EN 16931 invoicing, pre-dispatch validation, SHA-256 receipt deduplication, and database audit trail.
- 🐴 **Andalusian (B2B Document Dispatch):** Agile courier horse. Secure, tamper-evident invoice transmission (Ed25519 signatures, SMTP/TLS via NATS JetStream) to reduce Days Sales Outstanding (DSO) without transaction network tolls.
- 🐴 **Black Forest Fox (*Schwarzwälder Fuchs*, Quotation Engine):** Tenacious cold-blood breed for steep terrain; a personal tribute to ancestors in forestry and slate hauling. Drives sales efficiency through UBL Quotation XML synthesis and one-click invoice generation.
- 🐴 **Percheron (International Profiles & Scale):** Powerful heavy draft breed. Cross-border Factur-X profiles (France, Luxembourg, Belgium) and multi-tenancy for larger enterprises.

---

## License & Attribution

- **Software:** [Apache License 2.0](https://github.com/Little-Trotter/invoice/blob/main/LICENSE)
- **Concept & Documentation:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — credit *Little Trotter (https://github.com/little-trotter)*
- **Project Initiator:** Stefan Zils ([Eifel42](https://github.com/eifel42))
