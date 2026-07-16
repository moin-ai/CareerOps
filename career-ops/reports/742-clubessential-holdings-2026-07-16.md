# Evaluación: Clubessential Holdings — Senior Data Engineer

**Fecha:** 2026-07-16
**URL:** https://remotive.com/remote/jobs/data/senior-data-engineer-5147986
**Arquetipo:** Data Engineer (Senior, B2B SaaS)
**Score:** 2.0/5
**Legitimacy:** Proceed with Caution
**Verification:** unconfirmed (batch mode)
**PDF:** pendiente

> ⚠️ US-ONLY: "Remote USA" role. Moin requires visa sponsorship; no sponsorship mentioned. Score capped at 2.5 (US-only) then -0.5 (no sponsorship) = 2.0/5.
> ⚠️ SENIORITY GAP: 5+ years required; Moin has ~3 years staggered (internship + student scheme + freelance). Note in Block C.
> ⚠️ STACK MISMATCH: Role requires deep T-SQL, SQL Server, and SSRS experience. Moin's stack is Azure Databricks, PySpark, Delta Lake, and Power BI. Significant overlap in concepts but not in specific tooling.

---

## A) Resumen del Rol

| Field | Detail |
|---|---|
| **Arquetipo** | Data Engineer (Senior) — B2B SaaS / Club Management Software |
| **Domain** | SaaS (hospitality/private club management) — customer-facing data product |
| **Function** | Build and maintain data mart, ETL migration, SQL optimization, customer support |
| **Seniority** | Senior (5+ years required) |
| **Remote** | Remote USA |
| **Team size** | Central data team (size unspecified); cross-functional with account managers, finance teams |
| **Salary** | Not specified |
| **TL;DR** | A senior SQL-heavy data engineering role at a PE-backed club management SaaS company — wrong stack and geography for Moin, with a meaningful seniority gap. |

**Company context:** Clubessential Holdings, 500–1,000 employees, $80.7M revenue, Battery Ventures-backed. Operates ClubReady alongside other club management platforms. Established business in hospitality/private club sector.

**Key Responsibilities (from JD):**
- Design, optimize, and maintain stored procedures and SSRS reports across the ClubReady reporting environment
- Own the customer-facing Postgres data mart product serving enterprise clients
- Co-own migration from legacy Go ETL to new Fivetran → Snowflake → dbt → Postgres pipeline (with central data team)
- Serve as technical domain expert for data mart customers; triage and resolve customer-reported data discrepancies
- Author Azure DevOps work items, review PRs, operate inside two-week sprints
- Maintain internal data dictionary and external data documentation
- Tune queries and indexes against very large tables (multi-billion-row scale)

**Requirements:**
- 5+ years data engineering or BI development with deep T-SQL and SQL Server (transactional, customer-facing)
- Production experience with Snowflake/BigQuery/Redshift and modern ELT (dbt, Fivetran, Airbyte)
- Strong SQL query performance: indexing, execution plans, statistics, partitioning
- Python proficiency
- SSRS or enterprise reporting platform experience
- Senior IC ownership; customer communication (finance teams, account managers, customer-side analysts)
- Experience mentoring junior engineers
- Multi-tenant data product experience (per-customer schemas, row-level security, tenant onboarding)

---

## B) Match con CV

| JD Requirement | Moin's CV Match | Quality |
|---|---|---|
| Data engineering / BI development (5+ years) | Mercedes-Benz (6mo intern), UMPSA (13mo student scheme), Moinfinity Digital (2.5yr freelance) — total ~3–3.5 years staggered — cv.md | Weak (gap: 5yr vs ~3yr) |
| T-SQL / SQL Server deep experience | SQL listed in Technical Skills; relational DB design at UMPSA; MySQL and SQL Server listed — cv.md | Moderate (no deep T-SQL/SSRS production history) |
| Snowflake/BigQuery/Redshift + dbt/Fivetran | Azure Databricks (certified), Delta Lake, Azure ADLS — cv.md | Moderate (Azure Databricks ≈ Snowflake conceptually; no dbt/Fivetran production) |
| Python proficiency | Python (Pandas, NumPy, scikit-learn), PySpark — cv.md Technical Skills | Strong |
| SSRS or enterprise reporting | Power BI (PL-300 certified), DAX measures, production refresh pipelines — cv.md | Moderate (Power BI ≠ SSRS; different toolchain) |
| SQL query performance / indexing / execution plans | Relational database design, RDBMS architecture at UMPSA; no explicit query tuning at multi-billion-row scale — cv.md | Weak |
| Customer-facing data product experience | Moinfinity Digital: client discovery, stakeholder management, solution delivery across 7+ engagements — cv.md | Moderate |
| Multi-tenant data product | No direct multi-tenant SaaS data product experience | Weak |
| Mentoring junior engineers | Moinfinity: managed project teams, delegated tasks, educated team members on scope — cv.md | Moderate |
| Azure DevOps / sprint-based delivery | Agile/Scrum listed; GitHub/GitLab listed; no specific Azure DevOps mention — cv.md | Moderate |

**Gaps:**
| Gap | Hard Blocker? | Mitigation |
|---|---|---|
| US-only remote (no sponsorship) | **HARD BLOCKER** — Moin has no US work authorization | No mitigation |
| 5+ years requirement (Moin has ~3 staggered) | Significant gap | Frame Moinfinity as real enterprise consulting experience |
| T-SQL + SQL Server mastery | Moderate blocker | Emphasize relational DB design; SQL knowledge transfers |
| SSRS experience | Moderate gap | Power BI equivalent framing + DAX expertise |
| dbt + Fivetran production experience | Moderate gap | Azure Databricks + Delta Lake as parallel stack |
| Multi-billion-row query tuning | Significant gap | No large-scale SQL performance history |
| Multi-tenant SaaS data product | Significant gap | No direct equivalent |

---

## C) Nivel y Estrategia

**Nivel detectado:** Senior IC (5+ years, end-to-end ownership, customer-facing, mentoring required)

**Moin's natural level for this archetype:** Entry–Mid Data Engineer. His Databricks cert is strong, but practical DE experience is ~3 years staggered, none at multi-billion-row scale.

**Gap summary:** The role asks for a seasoned SQL Server + SSRS specialist transitioning to Snowflake/dbt. Moin's stack is Azure-first (Databricks, Delta Lake, Power BI) — not incompatible conceptually, but the specific tooling mismatch would be apparent in a technical screen.

**Plan "vender senior sin mentir":**
- Lead with Databricks Architect certification (2026) as the highest signal for data platform credibility
- Frame Mercedes-Benz ETL/reporting work as customer-facing (internal stakeholders = internal customers)
- Moinfinity Digital's 7+ engagements = end-to-end project ownership without supervision
- Position the Databricks/PySpark/Delta Lake stack as the Azure-native equivalent of the Snowflake/dbt stack

**If downleveled:** This role should not be pursued at any level given the US-only restriction.

---

## D) Comp y Demanda

**Advertised:** Not specified

| Market source | Range | Notes |
|---|---|---|
| Glassdoor / Levels.fyi (2026, US, Senior DE with Snowflake/dbt) | $135,000–$185,000 base | Mid-to-senior tier US market |
| Coastal metros premium | $160,000–$195,000 | NYC/SF/Seattle ranges |
| Clubessential context (PE-backed, 500–1K employees, $80.7M rev) | Estimated $110,000–$150,000 | Mid-market SaaS; Battery Ventures portfolio |

**Demand:** Senior data engineers with Snowflake + dbt expertise remain in high demand in 2026. The Fivetran→Snowflake→dbt stack is the dominant modern ELT pattern in mid-market SaaS.

**For Moin's targets:** Germany (€50K–€110K) or Australia (AUD 90K–155K). This US role does not serve those markets.

---

## E) Plan de Personalización

**Not recommended to apply.** US-only with no sponsorship history; significant stack and seniority gap.

| # | Section | Current State | Proposed Change | Why |
|---|---|---|---|---|
| 1 | N/A | N/A | Do not customize | US-only, no sponsorship, stack mismatch |

---

## F) Plan de Entrevistas

**Not applicable.** Role is inaccessible due to location/sponsorship constraint.

---

## G) Posting Legitimacy

**Assessment: Proceed with Caution**

| Signal | Finding | Weight |
|---|---|---|
| Posting age | Added to scan-history today (2026-07-16); Remotive ID 5147986 is in high range — likely a recent posting. Listed as active in scan-history as "added" | Positive |
| Apply button | Unverified (batch mode) | Neutral |
| JD specificity | High quality — names specific stack (Fivetran, Snowflake, dbt, Postgres, SSRS), describes team dynamics, customer context, sprint cadence, and mentoring expectations | Positive |
| Salary transparency | Not disclosed | Neutral (common for PE-backed SaaS) |
| Company hiring signals | No layoffs found; ZipRecruiter shows Clubessential actively hiring at $30K–$90K range; Battery Ventures-backed company appears stable | Positive |
| Reposting detection | First appearance in scan-history; no previous Clubessential entries | Neutral |
| Role-company fit | Clubessential builds club management SaaS; a Senior Data Engineer owning a customer-facing Postgres data mart is a natural fit for their scale | Positive |

**Context notes:**
- The role describes an active migration project (Go ETL → Fivetran → Snowflake → dbt → Postgres), which suggests real engineering work in progress, not a ghost posting.
- Battery Ventures is an active private equity backer in software; Clubessential appears to be growing.
- The missing salary is the only notable gap in transparency, which is common in PE-backed companies.

---

## Keywords extraídas

senior data engineer, T-SQL, SQL Server, SSRS, Postgres, data mart, Snowflake, dbt, Fivetran, ETL migration, multi-tenant, stored procedures, query optimization, indexing, execution plans, Azure DevOps, Python, ELT pipeline, enterprise reporting, customer-facing data, row-level security, data dictionary, sprint, two-week sprints, BI development, remote USA
