<div align="center">

# Riccard Nef

**AI engineer in Swiss healthcare IT. Elevator mechanic first, data scientist second, systems builder now.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riccard-nef-62683511b/)
[![The Agora Method](https://img.shields.io/badge/Medium-The%20Agora%20Method-%2312100E.svg?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@stillwaiting/the-agora-method-b62263bde400)
[![Gmail](https://img.shields.io/badge/Gmail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:riccardnef99@gmail.com)

</div>

---

### Portfolio

| Repository | What it shows | Result | Status |
|---|---|---|---|
| [`agora-method`](https://github.com/riccardito/agora-method) | The method layer of my AI-development pipeline: sessions, skills, policies, and eight checks that keep them true. The real operating files from 402 recorded sessions, with a demo child that runs one session start to end, and a [requirements-engineering paper](https://github.com/riccardito/agora-method/blob/main/docs/requirements-engineering.md) on the catalogue that specifies the repository itself | Domain share 1.06 % → 0.0 % across 7 815 lines, enforced in CI · clone to green demo in 17 s against a 10-minute target | public, CI green |
| [`tardoc-validator`](https://github.com/riccardito/tardoc-validator) | Checks a Swiss outpatient service list against the TARDOC tariff rules and says in plain words what is wrong. The rules are YAML, the engine is one small function per rule kind, and a loader reads the official catalogue's rule column. A language model explains each finding in billing language behind a guard: the engine decides, the model only explains | 100 % recall and 0 % false alarms on 1 000 synthetic invoices with planted faults, against 8.4 % for a quantity-only baseline · all 1 388 official positions at 16 µs an invoice | public, CI green |
| [`fedlex-rag`](https://github.com/riccardito/fedlex-rag) | Answers everyday questions about Swiss federal law from the official text: 347 articles of the DSG, the OR's employment contract and the KVG, searched with a local embedding model, reranked by Claude, and answered with the article cited — or refused when the text does not say. Every Claude answer is recorded, so the evaluation runs without a key | Recall@5 90.2 % on 76 questions, against 34.4 % for keyword search and 63.9 % for dense search alone · the answer cites a right article for 90.2 % and refuses 15 of 15 questions the three acts do not cover | public, CI green |
| [`data-science-bookshelf`](https://github.com/riccardito/data-science-bookshelf) | Data science as a bookshelf: 12 shelves and 48 books, each a sequence of notebooks from foundation to advanced that closes on a challenge measured against a baseline. Four books written (Linear Algebra, Probability, Time Series, Images & Signals) on a tested toolbox; the rest catalogued | Zurich's electricity a day ahead at 7.29 MW MAE against 15.13 for last week · 83 % of payment fields from a blurred QR-bill photo where the code reads 0 % · a breach rate from one season within 2× of the truth only a third of the time | public, CI green |
| [`FHNW-Projects`](https://github.com/riccardito/FHNW-Projects) | My BSc Data Science coursework, one folder per course — deep learning, NLP, recommender systems, statistics, IoT. Algorithms written from the maths where the course asked for it | CIFAR-10 from a 55 % MLP to an 80 % CNN · Amazon-review sentiment at macro-F1 0.85 · a rockfall risk simulation at 1.2–2.9 × 10⁻⁴ deaths a year against a 10⁻⁴ limit | archive, every folder documented |

---

### About

I assembled elevators before I wrote code. A BSc in Data Science at FHNW — Switzerland's first — turned that into a profession, and three years in medical-registry IT and application management for clinics turned it into a domain. Today I work at CANCOM Switzerland and build clinical software end to end, from data model to deployment, with an AI pair and a method for keeping it honest. I wrote the method up as [*The Agora Method*](https://medium.com/@stillwaiting/the-agora-method-b62263bde400).

I'm not a computer science purist. I like building things that work.

---

### Stack

![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=flat-square&logo=flask&logoColor=white)
![htmx](https://img.shields.io/badge/htmx-%233366CC.svg?style=flat-square&logo=htmx&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248.svg?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-%23005571.svg?style=flat-square&logo=elasticsearch&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat-square&logo=scikit-learn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%232496ED.svg?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-%232088FF.svg?style=flat-square&logo=github-actions&logoColor=white)

---

<div align="center">
<sub>Mechanic 2009 — Data Scientist 2022 — Software Engineer 2025</sub>
</div>
