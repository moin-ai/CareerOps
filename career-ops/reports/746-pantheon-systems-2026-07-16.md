# Evaluación: Pantheon Systems — Software Engineer II, Data Platform

**Fecha:** 2026-07-16
**URL:** https://remotive.com/remote/jobs/software-development/software-engineer-ii-data-platform-5111125
**Arquetipo:** Data Engineering / AI Platform
**Score:** 2.5/5
**Legitimacy:** Proceed with Caution
**Verification:** unconfirmed (batch mode)
**PDF:** pendiente

---

## A) Resumen del Rol

| Campo | Detalle |
|---|---|
| **Arquetipo** | Data Engineering / AI Platform |
| **Domain** | Digital Experience Platform (WordPress hosting / WebOps) |
| **Function** | Build + Maintain |
| **Seniority** | Mid-level (Engineer II) |
| **Remote** | Full remote (USA — likely US-only) |
| **Team size** | Not mentioned |
| **Salary** | $116,640–$162,000 USD/year |

**TL;DR:** Pantheon needs a mid-level data engineer to build reliable pipelines, maintain SLOs for business-critical data systems, and partner with Sales Ops, Product, and Finance — core stack is Python/Go, dbt, Airflow, Snowflake/BigQuery, with Kubernetes and Terraform as infrastructure tools. Significant skill gaps vs. candidate's Azure-first profile; no visa sponsorship mentioned.

Pantheon is a Digital Experience Platform for WordPress and Drupal — not a data company, but hiring for internal data infrastructure. The company has gone through 3 rounds of layoffs in ~2.5 years (Glassdoor 2.9/5), which is a cultural risk signal, but it is currently actively hiring (24 open roles, July 2026).

---

## B) Match con CV

### Requirements vs. CV Mapping

| JD Requirement | CV Match | Strength |
|---|---|---|
| 3–5+ years building production data services | 6-month Mercedes-Benz internship + student working scheme + freelance Moinfinity | Partial (real but staggered) |
| Python proficiency | Python (Pandas, NumPy, PySpark) — cv.md Technical Skills | Strong |
| Go proficiency | Not in CV | Gap |
| SQL with relational DBs (MySQL, Postgres) + data warehouses (Snowflake, BigQuery) | MySQL, SQL Server in CV; no Snowflake or BigQuery listed | Partial |
| Containerization (Docker, OCI) | Not in CV | Gap |
| Terraform | Not in CV | Gap |
| Kubernetes (K8s) | Not in CV | Gap |
| dbt | Not in CV | Gap |
| Airflow | Not in CV | Gap |
| Looker | Not in CV (Power BI is listed instead) | Gap |
| Data pipelines at scale | ETL/ELT pipeline design, Databricks Architect cert (2026), Delta Lake | Partial (different stack) |
| Distributed systems understanding | Azure Databricks, Apache Spark, Delta Lake — cv.md Cloud & Big Data | Partial |
| Maintain SLOs | No SLO-specific experience in CV | Gap |
| Partner with Sales Ops, Finance, Product | Stakeholder management at Mercedes-Benz, Moinfinity client work | Strong |
| AI/ML pipeline experience (big plus) | PySpark, scikit-learn, local LLM exposure | Partial |

### Gaps

| Gap | Blocker? | Mitigation |
|---|---|---|
| Go programming | Hard gap | Python-only candidate; Go is listed as "and/or" — focus on Python strength |
| Terraform + Kubernetes | Hard gap | Databricks Architect cert shows infra awareness; highlight Azure experience |
| dbt | Notable gap | ELT/ELT pipeline design experience is adjacent; quick-to-learn framing possible |
| Airflow | Notable gap | DAG orchestration concepts familiar via Databricks; frame as learning fast |
| Snowflake / BigQuery | Soft gap | Azure Databricks + Delta Lake is equivalent pattern; different vendor |
| Looker | Soft gap | Power BI (PL-300) is comparable BI tool |
| 3–5 years production experience | Experience level gap | Staggered real-world delivery (Fortune 500, student scheme, freelance) — but thin for this yardstick |
| No visa sponsorship mentioned | -0.5 deduction | No mitigation; flag early |

---

## C) Nivel y Estrategia

**Nivel detectado:** Engineer II — mid-level with 3–5+ years expectation
**Nivel del candidato:** Entry–early-mid (strong output, real delivery, but < 2 years formal employment)

**Framing challenge:** The stack mismatch is significant. Moin's data experience is Azure Databricks / Delta Lake / Power BI. Pantheon's stack is dbt / Airflow / Snowflake or BigQuery / Go. These are different ecosystems with overlapping concepts but non-overlapping tooling. Hiring managers in this team would notice the gap immediately.

**Plan "vender senior sin mentir":**
- Lead with the Databricks Architect Certification (2026) — demonstrates understanding of distributed data systems at an architecture level, not just a user level
- Emphasize Python proficiency and pipeline design transferability
- Frame SQL expertise as foundation-level regardless of warehouse vendor
- Be upfront about Go: "I code primarily in Python; I've studied Go concepts and can ramp up quickly in a bilingual Python/Go codebase"

**Plan "si me downlevelan":** Not the right play here — the tool stack gaps are the issue, not seniority optics. A lower level doesn't fix the missing K8s, Terraform, dbt, Airflow experience.

---

## D) Comp y Demanda

| Metric | Data |
|---|---|
| Salary range | $116,640–$162,000 USD (disclosed in JD) |
| Market comparison | Competitive for mid-level data engineering in US |
| Equity | Mentioned as part of total compensation package |
| Benefits | Medical/Dental/Vision, parental leave, 4 weeks PTO + 13 holidays, wellness allowance |
| Visa sponsorship | Not mentioned — deduct 0.5 from score |
| Company financial health | 3 layoff rounds in 2.5 years raises stability concerns |
| Demand for role | Modern data stack engineers (dbt/Airflow) are in steady demand |

Glassdoor employee rating: 2.9/5 — below average, driven by repeated layoffs and "month-by-month" uncertainty per reviews.

---

## E) Plan de Personalización

Not recommended at current skill match. If candidate wants to target this role type in the future:

| # | Sección | Estado actual | Cambio propuesto | Por qué |
|---|---------|---------------|------------------|---------|
| 1 | Skills | Azure Databricks focus | Add dbt, Airflow, Looker if learned | Stack alignment with modern data engineering market |
| 2 | Experience | Mercedes-Benz internship | Highlight pipeline automation + data modeling angle | Closest proof point to platform work |
| 3 | Summary | General data analyst/engineer | Reframe as "data platform builder" if stack gaps are closed | Language alignment |
| 4 | Certs | Databricks Architect | Add dbt Fundamentals cert (free, 4h) | Signals awareness of the dominant ELT paradigm |
| 5 | Projects | Internal tools | Build a public dbt + Airflow project on GitHub | Fills the tangible stack gap |

---

## F) Plan de Entrevistas

If candidate decides to apply despite gaps, these STAR stories are most relevant:

| # | JD Requirement | Historia | S | T | A | R | Reflection |
|---|---|---|---|---|---|---|---|
| 1 | Build reliable data systems | Mercedes-Benz Attendance System | Production plant needed reliable attendance tracking | Build end-to-end Power BI + SharePoint pipeline | Automated daily refresh, zero manual calculations | 100% elimination of manual attendance calculations | Would add SLO monitoring from day 1 |
| 2 | Partner with Sales Ops / Finance | Moinfinity client work | Clients needed web and data solutions for operations | Translate business needs into technical specs | Ran discovery workshops, built reporting automations | 2–6 hours daily saved for clients | Would formalize metrics definitions earlier |
| 3 | Scalable pipeline design | Mercedes-Benz Power Automate flow | Internal system data needed structured auto-collection | Build cloud flow to receive + structure data to SharePoint | Created scheduled flow with Excel auto-formatting | Eliminated manual data entry pipeline | Would have added error-handling logic |
| 4 | Distributed data systems | Databricks Architect cert (2026) | Needed to demonstrate architecture-level data knowledge | Study Spark, Delta Lake, ADLS at architect depth | Passed Databricks Platform Architect certification | Certified, can discuss partitioning, streaming, governance | Would now build a hands-on Databricks project |

**Case study recommendation:** The Mercedes-Benz Attendance + Power BI pipeline is the closest analog to a "data platform" story. Frame it as: requirements → data model → automated pipeline → stakeholder-facing BI layer → zero-maintenance operation.

**Red flag question:** "You don't have Go or K8s on your resume — how are you going to contribute on day one?"
**Response:** "My Python proficiency is production-grade, and I've built pipelines that run at scale on distributed systems. Go is learnable in weeks — I pick up new languages fast because I reason about the patterns, not just the syntax. K8s I've studied conceptually through my Databricks Architect work; I'd pair with your infra team early on to close the operational gap quickly."

---

## G) Posting Legitimacy

**Assessment: Proceed with Caution**

| Signal | Finding | Weight |
|---|---|---|
| Posting age | Two versions of this role visible (5096325 and 5111125) — suggests reposting | Concerning |
| Apply button | Not verified (batch mode) | Neutral |
| Description quality | Very specific: Python/Go, dbt, Airflow, Snowflake/BigQuery, K8s, Terraform, Looker — strong technical signal | Positive |
| Salary transparency | Fully disclosed ($116,640–$162,000) | Positive |
| Company layoff history | 3 rounds of layoffs in 2.5 years, ongoing monthly departures per Glassdoor | Concerning |
| Current hiring | 24 open roles listed on Pantheon careers in July 2026 | Positive |
| Reposting pattern | Same role appeared under two different Remotive IDs (5096325 + 5111125) | Concerning |

**Context Notes:** Multiple listings of the same role could indicate genuine difficulty filling the position (due to the niche stack or budget constraints) OR a pipeline role that gets refreshed periodically. The active company hiring and disclosed salary reduce overall suspicion. However, a company with repeated layoffs hiring aggressively is a yellow flag — new hires may be the next to go in the next restructure.

---

## Keywords extraídas

data platform, data pipeline, Python, Go, SQL, dbt, Airflow, Looker, Snowflake, BigQuery, MySQL, Postgres, Docker, Kubernetes, Terraform, SLO, data warehouse, distributed systems, analytics, BI, self-service tooling, data engineering, Software Engineer II, production services, data infrastructure, observability, pipeline reliability
