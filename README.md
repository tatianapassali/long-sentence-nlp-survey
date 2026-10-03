# From Lengthy to Lucid: A Systematic Literature Review on NLP Techniques for Taming Long Sentences

This repository contains the supplementary materials for the systematic literature review:

**From Lengthy to Lucid: A Systematic Literature Review on NLP Techniques for Taming Long Sentences**

The review investigates Natural Language Processing (NLP) techniques for transforming long and complex sentences into shorter and more readable forms.

The review focuses on two complementary tasks:

- **Sentence compression**
- **Sentence splitting**

The repository provides the structured dataset of publications included in the review, the taxonomy developed from the reviewed literature, and the figures used to analyse publication and methodological trends.

---

## Repository Structure

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

Both CSV files can be viewed directly as tables through the GitHub interface.

### `figures/`

Contains the figures produced for the systematic literature review.

These include visualizations of publication trends and methodological characteristics of the reviewed literature.

### `taxonomy/`

Contains the taxonomy developed to organize and characterize the approaches identified in the literature.

---

## Systematic Literature Review

### Background

Long and syntactically complex sentences can negatively affect readability and make information more difficult to process.

NLP techniques can address this problem by transforming complex sentences into shorter or simpler structures.

This review focuses on two complementary approaches:

### Sentence Compression

Sentence compression aims to shorten a sentence while preserving its essential meaning.

### Sentence Splitting

Sentence splitting aims to decompose a long or syntactically complex sentence into multiple shorter sentences while maintaining the meaning and coherence of the original text.

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

The included studies were categorized according to whether they addressed:

1. Sentence compression
2. Sentence splitting

The publication-level metadata is provided in the two datasets:

- [`sentence_compression_literature.csv`](papers/sentence_compression_literature.csv)
- [`sentence_splitting_literature.csv`](papers/sentence_splitting_literature.csv)
---


## Dataset

The datasets contain the publication-level metadata collected during the systematic literature review.

Each row corresponds to a publication included in the review.

### Sentence Compression

[`sentence_compression_literature.csv`](papers/sentence_compression_literature.csv)

This file contains publications addressing sentence compression.

### Sentence Splitting

[`sentence_splitting_literature.csv`](papers/sentence_splitting_literature.csv)

This file contains publications addressing sentence splitting.

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

---

## Taxonomy

A taxonomy was developed to organize the approaches identified across the reviewed literature.

The taxonomy captures important characteristics of approaches to sentence compression and sentence splitting, including methodological and task-related distinctions.

The taxonomy is available in:

[**View the taxonomy**](taxonomy/taxonomy.pdf)

---

## Figures

The `figures/` directory contains the figures associated with the systematic literature review.

These figures illustrate trends and characteristics of the reviewed literature, including:

- Publication trends over time
- Distribution of studies across sentence compression and sentence splitting
- Methodological approaches
- Training and supervision settings
- Other characteristics of the reviewed studies

The figures are provided as supplementary research materials and support the analysis presented in the associated systematic literature review.

---

## Research Analysis

The review provides a structured analysis of the literature according to several dimensions, including:

- Task category
- Methodological approach
- Task formulation
- Training and supervision setting
- Datasets
- Evaluation measures
- Language

This organization enables comparison of the approaches used for sentence compression and sentence splitting and provides an overview of how the research landscape has developed over time.

---

## Main Observations

The review identifies several characteristics of the existing literature.

Research on sentence compression and sentence splitting has developed across multiple methodological paradigms, with supervised approaches representing a substantial part of the literature.

Sentence compression has received considerably more research attention than sentence splitting.

The literature includes a variety of methodological approaches, training settings, task formulations, datasets, and evaluation measures.

The review also identifies opportunities for further investigation of weakly supervised and self-supervised approaches, as well as the application of large language models to sentence compression and sentence splitting.

These observations are discussed in detail in the associated publication.

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

## License

The supplementary materials provided in this repository are released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

The license applies to the materials contained in this repository.

The original publications referenced in the CSV datasets remain subject to their respective copyright and licensing terms.
