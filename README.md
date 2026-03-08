# Science Mapping Analysis — A Primer with Biblioshiny

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Bibliometrix](https://img.shields.io/badge/R-Bibliometrix-blue.svg)](https://www.bibliometrix.org)
[![GitHub stars](https://img.shields.io/github/stars/massimoaria/biblioshiny-book?style=social)](https://github.com/massimoaria/biblioshiny-book)

> Official companion repository for the book **"Science Mapping Analysis — A Primer with Biblioshiny"**

---

## 📖 About This Book

This repository bridges theory and practice for bibliometric research. It provides all the datasets, scripts, and supplementary materials needed to replicate every analysis presented in the book, using the `bibliometrix` R package and its web interface, **Biblioshiny**.

The book covers both the **methodological foundations** of science mapping and **hands-on applications**, with each chapter structured around a real-world case study.

---

## 📁 Repository Structure

```
biblioshiny-book/
├── datasets/               # Raw bibliographic data (WoS & Scopus exports)
├── content_analysis/       # Plain-text files for Chapter 11 (Content Analysis)
├── supplementary-materials/ # High-resolution figures and extended notes
├── scripts/                # R scripts for advanced custom workflows
└── exercises/              # Practical tasks and self-assessment files
```

### Folder Details

| Folder | Description |
|--------|-------------|
| `/datasets` | Raw bibliographic data in Plain Text and BibTeX formats, exported from Web of Science (WoS) and Scopus. Used in the step-by-step tutorials. |
| `/content_analysis` | Plain-text files produced by the Biblioshiny Content Analysis extraction step, used to reproduce all results in **Chapter 11**. |
| `/supplementary-materials` | High-resolution scientific citation network models, figures, and extended methodological notes. |
| `/scripts` | R scripts for advanced users who want to customize bibliometric workflows beyond the GUI. |
| `/exercises` | Practical tasks and self-assessment files to test your science mapping skills. |

#### Content Analysis Source Papers

The `/content_analysis` folder includes pre-processed text files based on the following reference works:

- Ramos-Rodríguez, A. R., & Ruíz-Navarro, J. (2004). Changes in the intellectual structure of strategic management research: A bibliometric study of the *Strategic Management Journal*, 1980–2000. *Strategic Management Journal*, 25(10), 981–1004.

- Zupic, I., & Čater, T. (2015). Bibliometric methods in management and organization. *Organizational Research Methods*, 18(3), 429–472.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/massimoaria/biblioshiny-book.git
cd biblioshiny-book
```

### 2. Install `bibliometrix`

```r
install.packages("bibliometrix")
```

### 3. Launch Biblioshiny

```r
library(bibliometrix)
biblioshiny()
```

### 4. Load the Datasets

Access the `datasets/` folder for the ZIP archives referenced in **Chapter 3**. Files are named according to the corresponding chapters and case studies in the book.

---

## 📦 Requirements

- **R** ≥ 4.1.0
- **bibliometrix** ≥ 4.0.0
- A modern web browser (for the Biblioshiny interface)

---

## 📬 Contact & Support

- 🌐 Website: [www.bibliometrix.org](https://www.bibliometrix.org)
- 🐛 Issues: [GitHub Issues](https://github.com/massimoaria/biblioshiny-book/issues)
- 📧 Author: Massimo Aria

---

## 📄 License

This repository is released under the [MIT License](https://opensource.org/licenses/MIT).  
© Massimo Aria