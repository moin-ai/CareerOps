# #631 — Aircall | Senior Data Engineer - Real time analytics

**Date:** 2026-07-06
**Score:** 1.7/5
**URL:** https://jobs.lever.co/aircall/d9fc4c01-a12b-402e-94ee-9c3984a1fe79
**PDF:** ❌
**Verification:** unconfirmed (batch mode)
**Legitimacy:** Tier 1 — Legitimate Company / Real Posting

---

## A — Match con CV | 1.5/5

Aircall is a French cloud-based VoIP/call center platform (unicorn, 22,000+ customers). This role is a key position on the analytics and event platform team, focused on designing and delivering near real-time data solutions at scale.

**Requirements extracted:**
- 3+ years experience with real-time, event-driven architecture
- 3+ years with a modern programming language (Scala, Python, Go, or TypeScript)
- Experience designing complex data processing pipelines
- Experience with data modeling (star schema, dimensional modeling)
- Bachelor's degree in CS or Mathematics
- Hands-on with full tech stack: AWS (Kinesis, Kafka, S3, DMS, Glue, EMR, EKS, Redshift, Spectrum), Apache Pinot, Apache Flink, Apache Airflow

**Relevant from CV:**
- Python (Pandas, NumPy, PySpark) — satisfies language requirement partially
- Apache Spark via PySpark/Databricks — conceptually adjacent to Flink but a different engine
- ETL/ELT pipeline design — general pipeline experience present
- SQL and data modeling — satisfies the dimensional modeling requirement partially
- Azure Databricks Architect (2026 cert) — big data processing experience, high-quality cert
- Data warehousing concepts — partial relevance to Redshift

**Critical gaps:**
- **Apache Flink — absent.** Flink is Aircall's primary stream processing engine. No streaming experience documented anywhere in Moin's CV.
- **Apache Pinot — absent.** Real-time OLAP engine for user-facing analytics; a specialized skill not present.
- **Kafka — absent.** The core event streaming backbone for real-time pipelines. Not mentioned in any form.
- **AWS ecosystem — absent.** Moin is Azure-certified and Azure-focused. Aircall runs entirely on AWS (Kinesis, Glue, EMR, EKS, Redshift). These are not interchangeable cloud skills at the engineering level.
- **Real-time/event-driven architecture — absent.** All of Moin's pipeline experience is batch-oriented (ETL, Databricks scheduled jobs, Power BI dataflows, SharePoint automation). There is no streaming or event-driven work documented.
- **Scala/Go — absent.** Python is present but Scala or Go are common for Flink development; not documented.

The match is structurally weak. Python and pipeline design experience partially satisfy secondary requirements, but the entire primary technical core of this role (Kafka/Flink/Pinot on AWS) is missing. Azure certifications do not transfer to an AWS-native stack.

---

## B — North Star Alignment | 2.0/5

- Role archetype: Data Engineer — this is Moin's secondary target (after Data Analyst, Business Analyst, Power Platform Developer). Directionally in range.
- Specialization: **Real-time streaming analytics** is a distinct niche within data engineering, significantly different from Moin's batch/BI/Power Platform experience vector. This is not a generic DE role.
- Seniority: "Senior" combined with real-time specialization typically implies 5+ years of dedicated streaming DE experience. Moin has ~3.5 years total across multiple roles, not all data-engineering-focused.
- Location: Paris, France. Not Germany. Aircall has offered Remote EMEA on similar roles, but primary headcount is Paris. This does not directly advance the EU Blue Card Germany goal.
- The role would be a strong match in 3–4 years if Moin builds a streaming engineering track (Kafka/Flink/AWS) and converts current Azure skills to the AWS ecosystem.

---

## C — Comp | 3.0/5

No salary range stated in the job posting.

Market estimates based on available data:
- Aircall Data Analyst in Paris: ~€50,675 (Glassdoor)
- Aircall Software Engineers in Paris: €38.7K–€53.8K median (Levels.fyi)
- Senior Data Engineer premium over median SWE in Paris: typically +30–50%
- Estimated Senior DE range at Aircall Paris: **€65K–€90K**

Against Moin's target of €50K–€110K (Germany): theoretical overlap exists. Paris compensation is generally 10–20% below equivalent German rates, so the absolute numbers may land toward the mid-range of Moin's target. The missing salary disclosure and the Paris vs. Germany differential add uncertainty; scored neutrally.

---

## D — Cultural Signals | 3.0/5

- Aircall is a legitimate, well-funded French unicorn. International culture: offices in Paris, Madrid, London, Berlin, New York, San Francisco, Sydney, Mexico City.
- JD is written in English despite Paris HQ — confirms English-first engineering culture.
- Similar roles at Aircall are posted as "Remote EMEA," indicating genuine remote-flexibility exists. Whether this specific role carries remote eligibility is unclear from the posting.
- VoIP/cloud communications is a modern, fast-growing SaaS category. Engineering at scale (22,000+ customers) is technically stimulating.
- No German language requirement; no indication of cultural rigidity or red-flag management signals.
- Scored at 3.0 rather than higher due to location uncertainty (Paris vs. Remote EMEA) and the absence of explicit visa/sponsorship language.

---

## E — Red Flags

1. **Streaming tech gap — Critical blocker.** Kafka, Apache Flink, and Apache Pinot are the core of this role. None appear anywhere in Moin's CV. This is a fundamental skills mismatch, not a stretch gap.
2. **Cloud platform mismatch — significant.** Aircall is fully AWS. Moin is Azure-certified (Databricks on Azure, ADLS, Azure Synapse patterns). AWS Kinesis, Glue, EMR, EKS, and Redshift require distinct hands-on familiarity — not transferable on paper.
3. **Seniority gap.** "Senior" + real-time specialization typically implies 5+ years focused DE experience. Moin has ~3.5 years across multiple part-time/internship/freelance roles.
4. **Visa sponsorship not mentioned.** France requires a work permit for non-EU citizens. -0.5 adjustment applied. No signals that Aircall sponsors visas for this role.
5. **Location:** Paris is the hiring base. This does not advance Germany/EU Blue Card targeting. If the role turns out to be Remote EMEA, the location issue is mitigated — but this cannot be confirmed from the posting.
6. **No salary disclosed.** Cannot confirm compensation alignment.

---

## F — Global Score | 1.7/5

| Block | Score | Weight | Contribution |
|-------|-------|--------|-------------|
| A — Match con CV | 1.5 | 35% | 0.53 |
| B — North Star Alignment | 2.0 | 25% | 0.50 |
| C — Comp | 3.0 | 20% | 0.60 |
| D — Cultural Signals | 3.0 | 20% | 0.60 |
| **Weighted subtotal** | | | **2.23** |
| Visa not mentioned | −0.5 | | |
| **Final score** | | | **1.7/5** |

**Recommendation: SKIP.**

The structural blocker is unambiguous: the entire technical core of this role (Kafka, Apache Flink, Apache Pinot, AWS streaming infrastructure) is absent from Moin's profile. Real-time streaming engineering is a specialist discipline, and this is a senior-level position inside a unicorn's production data platform. Applying with batch ETL + Azure Databricks + Power BI experience would not survive screening for this role.

Secondary blockers — cloud platform mismatch (Azure vs. AWS), seniority gap, France visa uncertainty, and Paris location vs. Germany target — compound the technical gap further.

**What to track instead:** Aircall does post Senior Data Engineer (Analytics) and Senior/Staff Data Engineer Remote EMEA roles that may be better fits (batch analytics, BI-adjacent, Redshift/dbt patterns). If Moin develops hands-on Kafka/Flink/AWS experience over the next 12–18 months, revisit Aircall's real-time team at that point.

---

## G — Posting Legitimacy | Tier 1 — Legitimate Company / Real Posting

**Signals:**
- Aircall is a verified French SaaS unicorn (raised $120M+ Series D, 22,000+ enterprise customers, listed on multiple reputable company databases).
- Lever.co is a reputable enterprise-grade ATS used by hundreds of tech companies — not a scam vector.
- The job description is technically precise, internally consistent, and uses credible domain vocabulary (Apache Pinot, Flink, Kinesis, EKS, DMS, Redshift Spectrum — terms that would not appear in a fake posting).
- Multiple concurrent data engineering roles open at Aircall confirms active, genuine hiring activity.
- No suspicious redirect chains, pay-to-apply signals, or mismatched domain indicators.
- Company presence is independently verifiable across LinkedIn, Glassdoor, Crunchbase, and news sources.

The posting is legitimate. The caution is purely about fit, not authenticity.
