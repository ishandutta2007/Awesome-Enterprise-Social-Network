# Awesome-Enterprise-Social-Network

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.

Here is the complete, ready-to-paste README.md for **Awesome-Enterprise-Resource-Planning-ERP-Legacy**.

---

# Awesome-Enterprise-Resource-Planning-ERP-Legacy

**Curated List of Legacy ERP Platforms & Open-Source Alternatives**
*Focused on On-Premises ERP Migration Paths, Sunset Timelines & Open-Source Replacements*
**Last updated: October 2026**

This repository tracks notable **legacy ERP platforms** and **open-source alternatives** for organizations running traditional on-premises ERP systems. These tools help teams maintain existing installations, plan migrations before sunset dates, or adopt modern open-source replacements.

**Examples** include Microsoft Dynamics AX, SAP R/3, Oracle E-Business Suite, JD Edwards EnterpriseOne, PeopleSoft, Baan ERP, Sage Line 500, Lawson ERP, SSA BPCS, and Infor SSA (the legacy category leaders).

**Open-source emphasis**: The open-source ERP ecosystem offers **mature, production-proven alternatives** to legacy systems. **Odoo Community** leads with **15M+ users** and **50,000+ modules** . **ERPNext** provides a **100% open-source** (AGPL) full-suite ERP with native production and multi-currency support . **Dolibarr** offers the simplest entry point for small organizations, installable in hours . This section documents these production-grade solutions.

## 📖 Table of Contents

- [🏛️ Legacy Platforms](#-legacy-platforms)
- [🔓 Open-Source Alternatives](#-open-source-alternatives)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## 🏛️ Legacy Platforms

> **📊 Market Context**: The legacy on-premises ERP market is **declining but persistent**. **SAP Business Suite 7** ends mainstream support on **December 31, 2027** (premium maintenance through end of 2030) . **Microsoft Dynamics GP** ends **September 30, 2029** (security patches only through April 2031) . **Oracle PeopleSoft** is committed to support at least through **2035** with a rolling 10-year guarantee . **Epicor** has set final on-premise release dates for Kinetic (2028.1), Prophet 21 (2028.1), and BisTrack (2028.1) . The pattern is clear: **every major vendor is sunsetting on-premises ERP** and forcing migrations to cloud platforms. Legacy ERP persists because late-majority enterprises resist migration costs and disruption, but the window is closing.

| Platform | Description | Current Status | Migration Path | Company Size |
|----------|-------------|----------------|----------------|--------------|
| **[SAP R/3 / SAP Business Suite 7](https://www.sap.com/)** | **The enterprise ERP standard for 30+ years.** ECC, CRM, SRM, SCM modules. Powers the majority of Fortune 500 companies. | **Mainstream support ends**: **December 31, 2027** . **Premium maintenance**: Through end of 2030 . **SAP ECC EHP 0-5**: Mainstream ended December 2025 . **SAP ECC EHP 6-8**: Mainstream ends December 2027 . | **SAP S/4HANA** (supported through ≥2040) . Migration is expensive and disruptive. | **~$35B revenue (SAP FY2025)** |
| **[Microsoft Dynamics AX](https://www.microsoft.com/en-us/dynamics-365)** | **Microsoft's legacy enterprise ERP.** Predecessor to Dynamics 365 Finance & Operations. | **Discontinued** — Dynamics AX 2012 mainstream support ended **October 2021**, extended support ended **January 2023**. | **Dynamics 365 Finance & Operations** (cloud) . | **~$281B revenue (Microsoft FY2025)** |
| **[Microsoft Dynamics GP](https://www.microsoft.com/en-us/dynamics-365)** | **Microsoft's mid-market ERP (formerly Great Plains).** Long-standing SMB and mid-market solution. | **End of support**: **September 30, 2029** . **Security patches only**: Through **April 30, 2031** . | **Dynamics 365 Business Central** (cloud) . | **~$281B revenue (Microsoft FY2025)** |
| **[Oracle E-Business Suite](https://www.oracle.com/)** | **Oracle's flagship ERP.** Financials, SCM, HRMS, CRM. Used by large enterprises globally. | **Premier Support**: Through **December 2030**. **Extended Support**: Additional fee, through **December 2033** . | **Oracle Fusion Cloud Applications** . | **~$53B revenue (Oracle FY2025)** |
| **[JD Edwards EnterpriseOne](https://www.oracle.com/)** | **Oracle's mid-market ERP (formerly PeopleSoft/JD Edwards).** Strong in manufacturing, distribution, and asset-intensive industries. | **Premier Support**: Through **December 2030**. **Extended Support**: Additional fee, through **December 2033** . JD Edwards World releases: Sustaining Support **indefinite** for older versions . | **Oracle Fusion Cloud ERP** or **JD Edwards on Oracle Cloud Infrastructure**. | **~$53B revenue (Oracle FY2025)** |
| **[Oracle PeopleSoft](https://www.oracle.com/)** | **Oracle's HCM and Campus Solutions platform.** Widely used in higher education and government. | **Support commitment**: At least through **2035** with **rolling 10-year guarantee** . **Annual extensions**, no fixed end date . | **Oracle Fusion Cloud Applications** . | **~$53B revenue (Oracle FY2025)** |
| **[Baan ERP](https://www.infor.com/)** | **Dutch ERP (now Infor LN).** Manufacturing and supply chain focus. Acquired by Infor. | **Legacy status** — Infor LN is the current supported version. Baan IV and Baan 5 are **obsolete**. | **Infor LN** (cloud or on-premises) . | **Part of Infor** |
| **[Sage Line 500](https://www.sage.com/)** | **Sage's legacy mid-market ERP.** UK-focused, widely used in distribution and manufacturing. | **Legacy status** — Sage has migrated customers to **Sage 200** and **Sage X3**. | **Sage 200** or **Sage X3** . | **~$2B revenue (Sage FY2025 est.)** |
| **[Lawson ERP](https://www.infor.com/)** | **Enterprise ERP for healthcare, retail, and public sector.** Acquired by Infor. | **Legacy status** — Infor has migrated Lawson customers to **Infor CloudSuite**. | **Infor CloudSuite** (industry-specific cloud ERP) . | **Part of Infor** |
| **[SSA BPCS](https://www.infor.com/)** | **Legacy ERP for manufacturing and distribution.** Acquired by Infor. | **Legacy status** — Infor has migrated BPCS customers to **Infor LX** and **Infor CloudSuite**. | **Infor LX** or **Infor CloudSuite Industrial** . | **Part of Infor** |

## 🔓 Open-Source Alternatives

Sorted by relevance and adoption for legacy ERP migration. Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|------|-------------|-------|
| **[Odoo](https://github.com/odoo/odoo)** — **The leading open-source ERP with the largest module ecosystem.** **15M+ users globally** . **50,000+ modules** available . **Community Edition is free** (LGPL-3.0); **Enterprise Edition** adds advanced features and support . Covers accounting, sales, CRM, purchasing, inventory, manufacturing, HR, e-commerce, and more . **Modern, intuitive interface** with Kanban, calendar, Gantt, and list views . **Scalable** from small business to multi-entity enterprise . **Dense global partner network** for implementation and support . **Real cost for Community**: €10,000–€50,000 for hosting and configuration . | [![Stars](https://img.shields.io/github/stars/odoo/odoo?style=social&color=white)](https://github.com/odoo/odoo/stargazers) | ~45,000 |
| **[ERPNext](https://github.com/frappe/erpnext)** — **100% open-source full-suite ERP (GPLv3).** **No commercial tier gates any feature** — the public repository is the product . Covers accounting, buying, selling, CRM, stock, point of sale, manufacturing, subcontracting, projects, assets, quality, support issues, website, and web shop . **Frappe framework** (Python) provides customization via custom fields and server scripts . **Self-host on Debian, Ubuntu, macOS, or containers**; or use **Frappe Cloud** managed hosting . **Best for smaller businesses with in-house technical skills** . **Real cost**: €5,000–€30,000 for hosting and configuration . **Limitations**: Less polished interface, smaller French community . | [![Stars](https://img.shields.io/github/stars/frappe/erpnext?style=social&color=white)](https://github.com/frappe/erpnext/stargazers) | ~30,000 |
| **[Dolibarr](https://github.com/Dolibarr/dolibarr)** — **The simplest open-source ERP for small organizations.** **GPL-3.0** licensed . Modular — activate only the features you need . Covers contacts, suppliers, invoices, orders, stocks, agenda, accounting, CRM, project management, manufacturing orders (MRP), and more . **Installation takes hours, not weeks** . **Best for TPEs under 15 employees**, simple tertiary sector, associations . **Real cost**: €1,000–€5,000 for initial configuration . **Limitations**: Limited functional depth as business complexity grows . | [![Stars](https://img.shields.io/github/stars/Dolibarr/dolibarr?style=social&color=white)](https://github.com/Dolibarr/dolibarr/stargazers) | ~5,000 |
| **[Apache OFBiz](https://github.com/apache/ofbiz-framework)** — **Best for developer-led enterprise customization.** **Apache-2.0** licensed Java framework . Modules include accounting, CRM, order management, e-commerce, warehousing, inventory, manufacturing (MRP), product/catalog/pricing, payments, and supply-chain processes . **Requires strong technical resources** — implementation is framework-led, not turnkey . **Best for enterprises with in-house Java skills** . | [![Stars](https://img.shields.io/github/stars/apache/ofbiz-framework?style=social&color=white)](https://github.com/apache/ofbiz-framework/stargazers) | ~1,000 |
| **[Tryton](https://github.com/tryton/tryton)** — **Best for modular operations and manufacturing.** Modular business platform with separate packages for accounting, sales, purchasing, stock, production, and projects . **Detailed production features**: routing steps, work centers, cycle tracking . **Smaller community than Odoo or ERPNext** . **Best for manufacturers and process-led companies** with technical or partner support . | [![Stars](https://img.shields.io/github/stars/tryton/tryton?style=social&color=white)](https://github.com/tryton/tryton/stargazers) | ~500 |
| **[iDempiere](https://github.com/idempiere/idempiere)** — **Enterprise-level open-source ERP/CRM/SCM.** Highly customizable, modular, and scalable . Based on ADempiere/Compiere lineage . Suitable for SMEs and large organizations . | [![Stars](https://img.shields.io/github/stars/idempiere/idempiere?style=social&color=white)](https://github.com/idempiere/idempiere/stargazers) | ~500 |
| **[metasfresh](https://github.com/metasfresh/metasfresh)** — **Best for distribution and supply-chain operations.** Open-source ERP focused on products, procurement, warehousing, logistics, manufacturing, and supply-chain execution . Documented modules include CRM, sales, purchasing, product data, BOM, manufacturing, warehouse, traceability, logistics, order picking, billing, payments, and EDI . **Best for distributors and wholesalers** . | [![Stars](https://img.shields.io/github/stars/metasfresh/metasfresh?style=social&color=white)](https://github.com/metasfresh/metasfresh/stargazers) | ~300 |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[LedgerSMB](https://github.com/ledgersmb/LedgerSMB)** — Integrated accounting and ERP for SMBs. Double-entry accounting, budgeting, invoicing, quotations, projects, orders, and inventory management . |
| **[ADempiere](https://github.com/adempiere/adempiere)** — Traditional open-source ERP known for robustness . |
| **[webERP](https://github.com/webERP/webERP)** — Lightweight open-source ERP with user-friendly layout and simplicity . |
| **[BlueSeer](https://github.com/BlueSeer/BlueSeer)** — Open-source ERP with comprehensive production control features . |
| **[Hubleto](https://github.com/hubleto/hubleto)** — Innovative ERP/CRM with large free-to-use app ecosystem . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's legacy or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Legacy ERP platforms handle sensitive financial and operational data; ensure proper security configuration, data migration planning, and compliance with data protection regulations.
- **Critical lifecycle notices**: **SAP Business Suite 7** ends mainstream support **December 31, 2027** . **Microsoft Dynamics GP** ends **September 30, 2029** . **SAP ECC EHP 0-5** mainstream support already ended **December 2025** . **Epicor Kinetic/Prophet 21** final on-prem release is **2028.1** . Organizations on unsupported versions should prioritize migration.
- **Open-source reality**: The open-source ecosystem for ERP is **mature and production-proven**. **Odoo Community** leads with **15M+ users** and the largest module ecosystem . **ERPNext** provides a **100% open-source** alternative with no feature gating . **Dolibarr** offers the simplest entry point for small organizations . However, **open-source ERP removes the license line but not the operational cost**. Real implementation costs range from €1,000–€5,000 (Dolibarr) to €10,000–€50,000 (Odoo Community) . **Compliance updates (e-invoicing, DSN) are not automatic** — they depend on community or integrator action . **Critical bug resolution depends on community or integrator availability** — no guaranteed SLA .
- **Key decision factor**: "Who runs the servers" outlives the license question by years . Open-source ERP is **genuinely viable** for organizations with strong IT capacity or a reliable implementation partner.

---

**Made for IT administrators managing legacy ERP migrations, SMBs seeking open-source alternatives, and enterprise architects evaluating ERP modernization.**
Let's make ERP modernization more open, transparent, and cost-effective.
