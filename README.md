<p align="center">
  <img src="https://massimoaria.github.io/biblioshiny-book/book_cover.png" alt="Science Mapping Analysis - Book Cover" width="280">
</p>

<h1 align="center">Science Mapping Analysis</h1>
<h3 align="center">A Primer with Biblioshiny</h3>

<p align="center">
  <strong>Massimo Aria</strong> &middot; <strong>Corrado Cuccurullo</strong><br>
  <sub>University of Naples Federico II &bull; University of Campania Luigi Vanvitelli</sub>
</p>

<p align="center">
  <a href="https://www.mheducation.it"><img src="https://img.shields.io/badge/Publisher-McGraw--Hill-red?style=flat-square" alt="McGraw-Hill"></a>
  <a href="https://www.bibliometrix.org"><img src="https://img.shields.io/badge/Software-bibliometrix-1a3a5c?style=flat-square" alt="bibliometrix"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License"></a>
  <a href="https://github.com/massimoaria/biblioshiny-book"><img src="https://img.shields.io/github/stars/massimoaria/biblioshiny-book?style=flat-square&color=yellow" alt="Stars"></a>
</p>

<p align="center">
  <code>ISBN 978-88-386-2297-7</code> &middot; <code>McGraw-Hill Education, 2026</code>
</p>

---

## The Book

Every year, millions of scientific articles are published across thousands of journals. How can researchers navigate this ocean of knowledge, identify the most influential works, and uncover the hidden structures that shape a scientific field?

**Science Mapping Analysis: A Primer with Biblioshiny** provides a comprehensive, hands-on guide to the quantitative study of scientific literature through citation patterns, keyword co-occurrences, and collaboration networks. Written by the creators of **bibliometrix** — the most widely adopted open-source bibliometric tool, used by researchers in over 180 countries — this book bridges the gap between methodological rigor and practical accessibility.

Organized around the **SAAS workflow** (Search-Appraisal-Analysis-Synthesis), the eleven chapters take the reader from foundational concepts to advanced techniques. Every method is explained with its theoretical underpinnings and demonstrated step by step through **Biblioshiny**, a point-and-click web interface that requires no programming expertise.

A common example runs through all chapters, showing how different techniques illuminate different facets of the same field. Mathematical formulations are included where they clarify the logic; worked examples make every analysis immediately reproducible.

> *"In a world deluged by irrelevant information, clarity is power."*
> — Yuval Noah Harari

---

## Contents

| Part | Chapters | Topics |
|------|----------|--------|
| **A — Foundations & Tools** | 1. Introduction to Science Mapping | Sociology of science, key techniques, matrix algebra, software ecosystem |
| | 2. Introducing Biblioshiny | Installation, SAAS workflow, interface navigation, Biblio AI assistant |
| | 3. Bibliographic Databases | Web of Science, Scopus, Dimensions, PubMed, OpenAlex, Lens.org |
| **B — Focus on Domain** | 4. Overview | Production trends, citation analysis, life cycle, three-field plot |
| | 5. Sources | Impact indicators, Bradford's Law, growth trajectories, source clustering |
| | 6. Authors | Lotka's Law, productivity, affiliation and country analysis, collaboration |
| | 7. Documents | Most cited works, RPYS, trend topics, word clouds, TreeMaps |
| **C — Knowledge Structures** | 8. Conceptual Structure | Co-word networks, thematic maps, thematic evolution, MCA |
| | 9. Intellectual Structure | Co-citation, bibliographic coupling, historiographic mapping |
| | 10. Social Structure | Co-authorship networks, institutional and country collaboration |
| **D — Content Analysis** | 11. Content Analysis of Key Publications | Structural analysis, in-context citation analysis, readability, keyword extraction |

---

## Who This Book Is For

- **Researchers across all disciplines** — conduct systematic, evidence-based literature reviews beyond narrative approaches
- **PhD students and early-career researchers** — navigate a scientific field and identify influential works, themes, and communities
- **Research managers and policymakers** — assess research area structure and dynamics for strategic planning and evaluation
- **Librarians and information professionals** — a comprehensive reference to bibliometric methods and tools
- **Instructors and course designers** — a textbook combining theoretical rigour with practical application

No prior programming experience is required.

---

## About This Repository

This is the **official companion repository** for the book. It contains all datasets, supplementary files, and resources needed to reproduce every analysis presented in the chapters.

### Repository Structure

```
biblioshiny-book/
├── datasets/              Bibliographic data used throughout the book
│   ├── management_collection.rdata      Pre-processed Management Collection
│   ├── management_raw_files.zip         Raw WoS/Scopus export files
│   └── collection_description_biblioAI.txt
├── content_analysis/      Source texts for Chapter 11
│   ├── ..._10.1002_smj.397.txt          Ramos-Rodríguez & Ruíz-Navarro (2004)
│   └── ..._20260307_152627.txt          Zupic & Čater (2015)
├── other_files/           Ancillary resources for text pre-processing
│   ├── field_tag_list.pdf               Complete field tag reference
│   ├── stopword_list.txt                Custom stopword list
│   └── synonym_list.txt                 Synonym dictionary
├── LICENSE
└── README.md
```

### The Management Collection

All applied examples in the book use a common dataset — the **Management Collection** — a set of bibliometric and scientometric research articles retrieved from the Web of Science. This shared dataset allows readers to follow the analytical thread across chapters and observe how different techniques reveal different facets of the same scientific field.

---

## Getting Started

**1. Clone this repository**

```bash
git clone https://github.com/massimoaria/biblioshiny-book.git
```

**2. Install bibliometrix**

```r
install.packages("bibliometrix")
```

**3. Launch Biblioshiny**

```r
library(bibliometrix)
biblioshiny()
```

**4. Load the data**

Open the `datasets/` folder in Biblioshiny and import the Management Collection to follow along with the book's examples.

---

## Requirements

- **R** >= 4.1.0
- **bibliometrix** >= 5.3.0
- A modern web browser (for the Biblioshiny interface)

---

## Links

| | |
|---|---|
| **Book website** | [massimoaria.github.io/biblioshiny-book](https://massimoaria.github.io/biblioshiny-book) |
| **bibliometrix** | [www.bibliometrix.org](https://www.bibliometrix.org) |
| **CRAN** | [cran.r-project.org/package=bibliometrix](https://cran.r-project.org/package=bibliometrix) |
| **Issues** | [github.com/massimoaria/biblioshiny-book/issues](https://github.com/massimoaria/biblioshiny-book/issues) |

---

## License

This repository is released under the [MIT License](https://opensource.org/licenses/MIT).

© 2026 Massimo Aria & Corrado Cuccurullo
