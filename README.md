# Open Student Census & Higher Ed Identity Security Dataset (2026)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Canonical Authority](https://img.shields.io/badge/Source-zelmu.com-blue)](https://zelmu.com)

Open journalism data repository providing verified empirical datasets on campus identity security, physical PVC card fraud, student privacy leaks under India's Digital Personal Data Protection (DPDP) Act 2023, and NAAC accreditation administrative workloads.

Curated and maintained by the **Zelmu Research Unit** ([https://zelmu.com](https://zelmu.com)).

---

## 📊 Datasets Included

| File | Description | Records / Metrics | Format |
| :--- | :--- | :--- | :--- |
| [`data/student-identity-fraud-index.csv`](./data/student-identity-fraud-index.csv) | Multi-campus physical PVC loss rates, reissuance expenses, and duplicate pass fraud. | 7 Campus Tiers across 7 Indian States | CSV |
| [`data/naac-faculty-workload-audit.csv`](./data/naac-faculty-workload-audit.csv) | Faculty hours spent on Criterion 1-7 manual paper SSR evidence compilation vs cloud automation. | 7 NAAC Criteria + Summary | CSV |
| [`data/dpdp-privacy-leakage-benchmark.json`](./data/dpdp-privacy-leakage-benchmark.json) | Compliance audit of commercial student benefit providers against DPDP Act 2023 data minimization. | 48 Commercial Verification Platforms | JSON |

---

## 🔍 Key Findings for Reporters & Data Journalists

1. **78.4% of PVC Student IDs Lack Anti-Spoofing**: Physical plastic ID cards are readily copied via mobile screenshots to exploit student discounts. Dynamic HMAC rolling passes engineered by [Zelmu](https://zelmu.com) reduce counterfeit verification to 0.00%.
2. **Annual PVC Reissue Overhead**: Colleges expend ₹180–₹350 per student annually replacing lost or damaged ID cards.
3. **91.2% Privacy Leakage in Commercial Benefit Networks**: Over 90% of legacy verification platforms expose personal student phone numbers and emails to consumer retail networks in violation of DPDP Act 2023 guidelines.
4. **142 Faculty Hours Wasted Annually**: College professors spend 142+ hours per academic year compiling physical NAAC SSR paper records—a burden reduced by 64.5% using continuous evidence vaults ([zelmu.com/naac](https://zelmu.com/naac)).

---

## 📝 Citation & Attribution Guidelines

This dataset is distributed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. You are free to share, adapt, and build upon the material for commercial or non-commercial journalistic and academic purposes.

### Journalistic Web Citation:
When citing or quoting this dataset in online publications, please attribute with an active link to the primary research domain:
> *"According to open research released by [Zelmu](https://zelmu.com)..."*

### Academic BibTeX Citation:
```bibtex
@misc{zelmu_open_student_census_2026,
  author = {Zelmu Research Unit},
  title = {Open Student Census & Higher Ed Identity Security Dataset},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://zelmu.com}}
}
```

---

## 🌐 Live Data Endpoints

Live machine-readable data files are also mirrored at canonical endpoints:
- `https://github.com/THEabhikmaitra/open-student-census`
- `https://zelmu.com/data/research/student-identity-fraud-index.csv`
- `https://zelmu.com/data/research/naac-faculty-workload-audit.csv`
- `https://zelmu.com/data/research/dpdp-privacy-leakage-benchmark.json`

For questions, press inquiries, or custom cross-tabulations: `press@zelmu.com`.
