<div align="center">

# From Lengthy to Lucid

### A Systematic Literature Review on NLP Techniques for Taming Long Sentences

[![Systematic Literature Review](https://img.shields.io/badge/Review-Systematic%20Literature%20Review-blue)]()
[![PRISMA](https://img.shields.io/badge/Framework-PRISMA-green)]()
[![170 Studies](https://img.shields.io/badge/Studies-170-orange)]()
[![2000–2026](https://img.shields.io/badge/Period-2000--2026-purple)]()

</div>

---

## At a Glance

| 170 Studies | 2 Tasks | 2000–2026 | PRISMA |
|:---:|:---:|:---:|:---:|
| Reviewed publications | Compression & Splitting | Review period | Review framework |

This repository contains the supplementary materials for the systematic literature review:

> **From Lengthy to Lucid: A Systematic Literature Review on NLP Techniques for Taming Long Sentences**

The review investigates Natural Language Processing (NLP) techniques for transforming long and complex sentences into shorter and more readable forms.

The review focuses on two complementary tasks:

- **Sentence compression**
- **Sentence splitting**

The repository provides the structured literature datasets, the taxonomy developed from the reviewed studies, and the figures used to analyse publication and methodological trends.

---

## Explore the Review

| Resource | Description |
|:---|:---|
| 📚 [**Sentence compression literature**](papers/sentence_compression_literature.csv) | Publications addressing sentence compression |
| 📚 [**Sentence splitting literature**](papers/sentence_splitting_literature.csv) | Publications addressing sentence splitting |
| 🧭 [**Taxonomy**](taxonomy/taxonomy.pdf) | Taxonomy developed from the reviewed literature |
| 📊 [**Figures**](figures/) | Figures associated with the systematic literature review |

## Repository Structure

```text
long-sentence-nlp-survey/
│
├── README.md
│
├── papers/
│   ├── sentence_compression_literature.csv
│   └── sentence_splitting_literature.csv
│
├── figures/
│   ├── cumulative_number_of_publications.pdf
│   ├── cumulative_compression.pdf
│   └── cumulative_splitting.pdf
│
└── taxonomy/
    └── taxonomy.pdf
```

### `papers/`

Contains two structured datasets corresponding to the two tasks covered by the systematic literature review:

- [`sentence_compression_literature.csv`](papers/sentence_compression_literature.csv) — publications addressing **sentence compression**
- [`sentence_splitting_literature.csv`](papers/sentence_splitting_literature.csv) — publications addressing **sentence splitting**

GitHub renders CSV files as tables, allowing the publication metadata to be browsed directly in the repository.

### `figures/`

Contains the figures associated with the systematic literature review, including visualizations of publication trends and other characteristics of the reviewed literature.

- [`cumulative_number_of_publications.pdf`](figures/cumulative_number_of_publications.pdf)
- [`cumulative_compression.pdf`](figures/cumulative_compression.pdf)
- [`cumulative_splitting.pdf`](figures/cumulative_splitting.pdf)

### `taxonomy/`

Contains the taxonomy developed to organize and characterize the approaches identified in the literature.

- [`taxonomy.pdf`](taxonomy/taxonomy.pdf)

---

## Review Scope

The review considers research addressing either **sentence compression** or **sentence splitting**.

The eligibility criteria cover studies published between **2000 and 2026**.

The review considers eligible scholarly publications written in English and available in full text, including journal and conference publications. Dissertations and theses are excluded.

The systematic review follows the **PRISMA** framework.

---

## Literature Search

The literature search was conducted using the following sources:

- Google Scholar
- Scopus
- ACM Digital Library
- Springer Digital Library
- IEEE Xplore
- arXiv

The search strategy included terminology related to both sentence compression and sentence splitting, including:

- sentence compression
- sentence summarization
- sentence shortening
- sentence condensation
- sentence reduction
- sentence splitting
- split and rephrase
- split-and-rephrase
- sentence decomposition

---

## Study Selection

Following the search and screening process, **170 studies** were included in the final review.

### Sentence Compression

[**sentence_compression_literature.csv**](papers/sentence_compression_literature.csv)

Contains publications addressing **sentence compression**.

### Sentence Splitting

[**sentence_splitting_literature.csv**](papers/sentence_splitting_literature.csv)

Contains publications addressing **sentence splitting**.

The datasets contain the following fields:

| Field | Description |
|---|---|
| `Title` | Title of the publication |
| `Authors` | Authors of the publication |
| `Category` | Sentence compression or sentence splitting |
| `Link` | Link to the publication or publication source |
| `Year` | Year of publication |
| `Method` | Methodological approach described for the study |
| `Type` | Task formulation |
| `Training` | Training or supervision setting |
| `Language` | Language addressed by the study |

The CSV files are provided as structured research datasets and can be opened directly in spreadsheet software or viewed as tables through GitHub.

The original publications referenced in the datasets are not redistributed by this repository. The links in the datasets point to the corresponding publication or source.

---

## Associated Publication

**Tatiana Passali, Efstathios Chatzikyriakidis, Stelios Andreadis, Thanos G. Stavropoulos, Anastasia Matonaki, Anestis Fachantidis, and Grigorios Tsoumakas**

**From Lengthy to Lucid: A Systematic Literature Review on NLP Techniques for Taming Long Sentences**

[**arXiv:2312.05172**](https://arxiv.org/abs/2312.05172)

---

## Citation

If you use the datasets, taxonomy, figures, or other materials from this repository, please cite the associated publication.

```bibtex
@article{passali2023lengthy,
  title   = {From Lengthy to Lucid: A Systematic Literature Review on NLP Techniques for Taming Long Sentences},
  author  = {Passali, Tatiana and
             Chatzikyriakidis, Efstathios and
             Andreadis, Stelios and
             Stavropoulos, Thanos G. and
             Matonaki, Anastasia and
             Fachantidis, Anestis and
             Tsoumakas, Grigorios},
  journal = {arXiv preprint arXiv:2312.05172},
  year    = {2023}
}
```

---

## License

<div align="left">

[![CC BY 4.0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

</div>

The supplementary materials provided in this repository are licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

The license applies to the materials contained in this repository.

The original publications referenced in the CSV datasets remain subject to their respective copyright and licensing terms.

---
