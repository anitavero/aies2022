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
- Legal Case Databases: [PACER](https://pacer.uscourts.gov/), Government and local databases, [FOIA](https://www.foia.gov/)s
- Incident Reporting Systems: [Artificial Intelligence Incident Database (AID)](https://ojs.aaai.org/index.php/AAAI/article/view/17817) from Georgetown Law, Partnership on AI's [AI Incidents Database](https://partnershiponai.org/workstream/ai-incidents-database/), [AI, Algorithmic and Automation Incident and Controversy Repository (AAAIRC)](https://www.aiaaic.org/)
- Algorithmic Transparency Tools: [Algorithm Tips](http://algorithmtips.org/), [MuckRock Algorithmic Control project](https://www.muckrock.com/assignment/predictive-algorithms-big-data-analytics-and-smart-technologies-deployed-by-governments-in-the-us-241/?flag=null&search=#assignment-responses)
- Regulatory Monitoring Tools: Parity.ai, [Compliance.ai](https://www.compliance.ai/)

### Audit Evaluation Tooling
- Data Donation / Data Scraping Tools: [NYU Ad Observatory](https://adobservatory.org/), [Mozilla Rally](https://rally.mozilla.org/), [The Markup's Citizen Browser](https://themarkup.org/citizen-browser), [Algorithm Watch](https://algorithmwatch.org/), [Tracking Exposed](https://tracking.exposed/)
- Documentation templates: Data sheets, NLP statements, privacy labels, [Model cards](https://arxiv.org/pdf/1810.03993.pdf), etc.
- Benchmarks: [Pilot Parliaments benchmark](http://gendershades.org/overview.html), [COMPAS dataset](https://www.kaggle.com/datasets/danofer/compass), etc.
- Bias Analysis / Explainability tooling: [Facebook's Fairness flow](https://ai.facebook.com/blog/how-were-using-fairness-flow-to-help-build-ai-that-works-better-for-everyone/), [IBM's AI Fairness 360](https://arxiv.org/pdf/1810.01943.pdf). etc.
- Data visualisation: [Google's Facets Dive](https://pair-code.github.io/facets/), [Language Interpretability Tool (LIT)](https://pair-code.github.io/lit/)