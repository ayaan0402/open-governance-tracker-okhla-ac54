# open-governance-tracker-okhla-ac54
Open-source, non-partisan civic &amp; environmental governance dataset for Constituency AC-54 (Okhla, New Delhi) mapped strictly to statutory government records.
# Open Manifesto & Governance Tracker (Okhla AC-54 Pilot)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## 1. Project Overview & Empirical Methodology
The **Open Manifesto & Governance Tracker (Okhla AC-54 Pilot)** is a zero-cost, open-data civic accountability initiative designed for first-time and young voters in Assembly Constituency 54 (Okhla, South East Delhi). 

Developed using an empirical life-sciences and Environmental Studies (EVS) classification framework, this repository tracks quantifiable municipal, ecological, and statutory governance parameters—such as solid waste bio-mining (in Lakh Metric Tonnes), sewage treatment effluent quality (BOD and TSS in mg/L), and mandatory candidate disclosures—strictly against primary government records.

---

## 2. Jurisdictional Matrix (Preventing Agency Misattribution)
To prevent voter confusion across New Delhi's multi-tiered administrative structure, every record in `dataset_ac54` is segregated by statutory jurisdiction:

| Jurisdiction Tier | Responsible Statutory Agencies | Core AC-54 Domains Tracked |
| :--- | :--- | :--- |
| **Municipal Tier** | Municipal Corporation of Delhi (MCD) | Legacy waste bio-mining at Okhla Landfill, local sanitation orders |
| **State Tier (GNCTD)** | Delhi Jal Board (DJB), Delhi Pollution Control Committee (DPCC) | Okhla Mega STP (564 MLD) effluent quality, Yamuna Action Plan III metrics |
| **Central / Statutory Tier** | Election Commission of India (ECI), NGT, CPCB, DDA | Form 26 Candidate Affidavits (Rule 4A), NGT judicial remediation targets |

---

## 3. Strict Neutrality & Legal Disclaimer
1. **Zero Evaluative Framing:** This repository contains zero opinions, zero party ratings, and zero subjective labels ("good/bad", "pass/fail"). It presents only baseline statutory targets alongside the latest official quantitative measurements.
2. **Primary Source Standard:** Every data row is linked directly to official government gazettes, National Green Tribunal (NGT) orders, DPCC laboratory monitoring reports, or ECI Form 26 affidavits, backed by preserved archival PDFs.
3. **Statutory Safe Harbor:** Published strictly in the public interest for civic education and academic research, relying solely on verified extracts of public records (pursuant to public-record exceptions under Section 356 of the Bharatiya Nyaya Sanhita, 2023, and Section 4 of the Right to Information Act, 2005).

---

## 4. Data Schema (`dataset_ac54.csv`)
* `record_id`: Unique alphanumeric identifier linked to the archived primary PDF.
* `sector_category`: Standardized civic/environmental domain.
* `jurisdiction_tier`: Municipal, State (GNCTD), or Central/Statutory.
* `responsible_agency`: Executing statutory body on record.
* `statutory_mandate_or_target`: Official quantitative mandate or timeline.
* `mandate_source_url`: Direct URL to the primary statutory order/portal.
* `latest_official_metric`: Latest published quantitative figure in standard units (`MT`, `MLD`, `mg/L`, `INR Crore`).
* `status_source_url`: Direct URL to the verifying audit or lab report.
* `drive_evidence_backup_url`: Immutable link to the archived primary PDF document.
* `last_verified_date`: Date of last primary source verification (`YYYY-MM-DD`).

---

## 5. License & Academic Attribution
This work and dataset schema are licensed under a [Creative Commons Attribution 4.0 International License (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt this dataset for non-partisan civic and academic research, provided appropriate credit is given to the original author and repository.
