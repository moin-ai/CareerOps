# Evaluación: RoomPriceGenie — Remote Senior Data Engineer (m/f/d)

**Fecha:** 2026-05-15
**URL:** https://euremotejobs.com/job/remote-senior-data-engineer-m-f-d/
**Arquetipo:** Data Engineering — Modern Analytics Stack (product-minded)
**Score:** 4.0/5
**Legitimacy:** High Confidence
**PDF:** ❌
**Verification:** unconfirmed (batch mode)

---

## A: Role Summary

| Field | Detail |
|---|---|
| Company | RoomPriceGenie (hotel revenue management SaaS; Best Place to Work in Hotel Tech 2026; offices in Mannheim, Berlin, Sydney) |
| Role | Remote Senior Data Engineer (m/f/d) |
| Function | Data engineering — ETL/ELT pipelines, data modeling, dbt + Snowflake + Dagster, analytics reliability |
| Seniority | Senior |
| Location | Fully remote (Europe preferred; co-working spaces in Mannheim, Berlin, Sydney) |
| Remote Policy | Fully remote with office option |
| Visa Sponsorship | Not mentioned — deduct 0.5 |
| TL;DR | Product-minded senior DE to design scalable pipelines using Snowflake + dbt + Dagster, own full lifecycle from design to monitoring, work closely with Product/Analytics/Engineering to enable data-driven decisions |

**Score adjustments:** −0.5 (no sponsorship) + dbt gap (core requirement) −0.3 + product-minded culture strongly aligns with Moin's background +0.3 → **4.0/5**

---

## A (cont.): Why 4.0 despite dbt gap

RoomPriceGenie explicitly seeks "product-minded" engineers who care about the "why" — this is Moin's strongest trait, evidenced by VP-level stakeholder work, Harvard leadership recognition, and consulting delivery mindset. The culture alignment partially compensates for the technical gap. The modern stack (Snowflake + dbt + Dagster) can be self-taught with a structured 2-week prep sprint.

---

## B: CV Match Table

| JD Requirement | CV Evidence | Gap? |
|---|---|---|
| ETL/ELT pipelines on cloud data warehouses (Snowflake/Databricks/BigQuery) | Azure Databricks cert; ETL pipelines at UMPSA + Moinfinity | Good on Databricks; Snowflake gap |
| Strong data modeling (fact/dim, analytics-ready schema) | Power BI star-schema data models; dimensional modeling concepts | Good foundation |
| dbt (transformation layer) | Not listed | **Hard gap — critical** |
| Dagster / Airflow orchestration | Not listed | Hard gap |
| Data testing and documentation | UMPSA: validation rules + docs; Mercedes-Benz: user guide + tooltips | Moderate — production testing gap |
| Python (custom transforms, automation) | Python/Pandas; PySpark; ETL automation | Solid |
| Working with Product/Analytics/Engineering | Mercedes-Benz cross-functional: Ops + IT + Management | Strong |
| Translating business questions → technical design | Core of all three main roles | Strong |
| Data reliability / observability / monitoring | Mercedes-Benz: anomaly alerts + status dashboard | Moderate |
| "Product-minded" — understand who relies on data and why | Harvard leadership program; VP-trusted analyst within 5 months; interview trusted | **Exceptional match** |
| 5+ years experience | Staggered 2.5–3 real years | Gap |

**Culture fit is genuinely high** — RoomPriceGenie's "product-minded" description matches Moin's demonstrated behavior (Harvard leadership, Mercedes-Benz trust, client-first consulting) better than most roles in this batch.

---

## C: Seniority Strategy

**Sell senior without lying:** Lean into "product-minded" language from the JD. Frame entire career narrative around the "why": "I've never just built dashboards — I've built operating systems that VP-level leaders depend on daily. My work at Mercedes-Benz eliminated 100% of manual processing because I understood the business problem deeply before writing a line of code."

**On the technical gaps (dbt, Dagster):** "I come from a Power BI/Databricks stack and I'm actively learning the Snowflake/dbt ecosystem. I can have a working dbt project portfolio ready within 2 weeks. The patterns are the same — the tools are learnable; the mindset is what matters."

**Honest positioning:** "I'm a senior-level thinker in a mid-level career phase — I bring the judgment, communication, and delivery ownership of a senior engineer with 2.5–3 years of genuinely complex production experience."

---

## D: Comp & Market Data

| Metric | Value |
|---|---|
| RoomPriceGenie Senior DE market estimate | €60,000–€85,000 (European remote) |
| Hotel tech SaaS DE range | €55,000–€80,000 (mid-market SaaS) |
| Candidate target (Germany) | €50,000–€80,000 |
| Alignment | Good — within target band |
| EU Blue Card path | Mannheim/Berlin offices — EU relocation possible if sponsorship offered |
| Sydney office | Australia secondary market — potential AU track if EU fails |

RoomPriceGenie has both German and Australian offices — dual-path opportunity for Moin's two primary target markets.

---

## E: CV Personalization Plan

1. **Build a dbt project in the next 2 weeks** — use DuckDB or Databricks Community + dbt Core; create 3–5 models with tests, documentation, and a README; link in CV under projects
2. **Reframe all project descriptions with "product-minded" language** — "I designed this system because the Ops team was losing 5 hours/day to manual reconciliation — the engineering was in service of that human problem"
3. **Add Snowflake mention** — even "Snowflake (familiar, applying to Databricks knowledge)" — shows awareness of the stack
4. **Highlight full lifecycle ownership** — "designed, built, tested, documented, monitored, and maintained in production" for each project; RoomPriceGenie cares about end-to-end ownership
5. **Lead cover letter with "product-minded" value prop** — open with: "I build data systems that teams trust to make decisions from — not just systems that run. Here's how I think about the problem before writing any code..."

---

## F: Interview Prep (STAR+R Stories)

**1. "Tell me about a time you worked at the intersection of engineering and business impact"**
> Mercedes-Benz: geo-fenced attendance system. Started not from a technical spec but from a conversation with the Ops VP about what decisions he couldn't make without better data. Designed the system around those decisions — real-time plant-level visibility, shift-pattern analysis, absence trend alerts. The result: the VP used my dashboard in his weekly leadership review.

**2. "How do you ensure the data you build can be trusted?"**
> Mercedes-Benz: built anomaly detection that flagged when attendance data looked wrong (e.g., employee checked in at two locations simultaneously — impossible). Created a data health status panel inside the dashboard so users could see data freshness and quality score. Trust = transparency.

**3. "Describe a data modeling decision you made for analytics readiness"**
> Power BI at Mercedes-Benz: chose to separate attendance events (fact) from employee/shift/location dimensions rather than using a flat table. This allowed slicing by any dimension without expensive cross-joins and enabled new reporting dimensions (e.g., department, team lead) to be added without rebuilding the model.

**4. "How do you work with Product, Analytics, and Engineering simultaneously?"**
> UMPSA: hostel management system required alignment between IT (who owned the database), admin staff (who entered data), and the rector's office (who needed reports). Ran weekly sync sessions, maintained a shared requirements doc, and built the system in public demos so each stakeholder could see their needs addressed.

**5. "Tell me about a pipeline you owned from idea to production to monitoring"**
> UMPSA hostel pipeline: scoped requirements → designed schema → built Python ETL → validated with stakeholders → deployed → added monitoring alerts → operated for 13+ months. Every phase owned personally, including production troubleshooting (e.g., when Excel format changed upstream, I detected it via validation alert and fixed within 2 hours).

**6. "Why hotel tech / why RoomPriceGenie?"**
> Hotel revenue management is a precision analytics problem — every night unsold is revenue gone forever. Building the data infrastructure that helps hotel operators optimize pricing decisions requires both technical rigor and deep empathy for the business model. That combination is exactly what I want to work on. Also: Best Place to Work in Hotel Tech 2026 suggests a team that takes culture seriously.

**7. "What's your approach to data documentation?"**
> Mercedes-Benz: wrote a 2-page user guide for every dashboard, including field definitions, calculation logic, and data refresh schedule. Built in-dashboard tooltips for every metric. Goal: any manager should be able to answer "where does this number come from?" without asking me. UMPSA: maintained a data dictionary in Notion linked from the admin panel.

---

## G: Posting Legitimacy

| Signal | Assessment |
|---|---|
| Posted on | EU Remote Jobs (aggregator) — RoomPriceGenie has own careers page |
| Job description quality | Highly specific, product-minded language, named tech stack (Snowflake + dbt + Dagster) |
| Company status | RoomPriceGenie is a real company — hotel SaaS, won Best Place to Work in Hotel Tech 2026, offices in Mannheim, Berlin, Sydney |
| Posting freshness | 2026 date confirmed via web search |
| Hiring signals | Specific, detailed JD suggests genuine open position |
| Red flags | None — verify on RPG official careers page |

**Verdict: High Confidence** — legitimate role at a genuine, mission-driven SaaS company.

---

## Keywords (ATS — 15–20)

Senior Data Engineer, ETL/ELT, dbt, Snowflake, Dagster, Data Modeling, Dimensional Modeling, Fact Tables, Dimension Tables, Data Pipeline, Python, SQL, Data Quality, Data Observability, Analytics Engineering, Cloud Data Warehouse, Data Documentation, Stakeholder Analytics, Remote Data Engineer, SaaS Analytics
