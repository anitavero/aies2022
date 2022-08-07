# AIES 2022

Statistics on what parts of the world were represented at the [Artificial Intelligence, Ethics, and Society 2022](https://www.aies-conference.com/2022/) conference.
See my [blog post](https://anilill.medium.com/ai-ethics-and-layers-of-biases-29756f39ea4e) on a summary of the conference and the discussions of these statistics.

---
## Data

Manually collected data of authors and organisations can be found in the csv files. The data is broken down to 
- keynote talks: `AIES-2022-keynote.csv`
- general talks: `AIES-2022-lightning-monday.csv`, `AIES-2022-lightning-tuesday.csv`
- student talks: `AIES-2022-student-lightning.csv`

`org_country.json` includes the countries of the universities and companies.

## Statistics

- [`aies_stats.ipynb`](https://github.com/anitavero/aies2022/blob/main/aies_stats.ipynb): Statistics on organisations and countries.
- [`bib_wordcloud.ipynb`](https://github.com/anitavero/aies2022/blob/main/bib_wordcloud.ipynb): Wordcloud of paper titles and abstracts in the conference proceedings.

---

## Useful Audit Tools
From Deborah Raji's [invited talk](https://dl.acm.org/doi/10.1145/3514094.3539566).

### Audit Accountability Tooling
- Legal Case Databases: PACER, Government and local databases, FOIAs
- Incident Reporting Systems: [Artificial Intelligence Incident Database (AID)](https://ojs.aaai.org/index.php/AAAI/article/view/17817) from Georgetown Law, Partnership on Al's Al Incidents Database, AI, Algorithmic and Automation Incident and Controversy Repository (AAAIRC)
- Algorithmic Transparency Tools: Algorithm Tips, MuckRock Algorithmic Control project
- Regulatory Monitoring Tools: Parity.ai, Compliance.ai

### Audit Evaluation Tooling
- Data Donation / Data Scraping Tools: NYU Ad Observatory, Mozilla Rally, The Markup's Citizen Browser, Algorithm Watch, Tracking Exposed
- Documentation templates: Data sheets, NLP statements, privacy labels, [Model cards](Model), etc.
- Benchmarks: Pilot Parliaments benchmark, COMPAS dataset, etc.
- Bias Analysis / Explainability tooling: Facebook's Fairness flow, IBM's AI Fairness 360. etc.
- Data visualisation: Google's Facets Dive, Language Interpretability Tool (LIT)