# CSE 200 – Technical Writing and Presentation
[![Stars](https://img.shields.io/github/stars/QuitttCat/CSE-200-Technical-Writing-and-Presentation?style=flat-square&logo=github)](https://github.com/QuitttCat/CSE-200-Technical-Writing-and-Presentation/stargazers)
[![Forks](https://img.shields.io/github/forks/QuitttCat/CSE-200-Technical-Writing-and-Presentation?style=flat-square&logo=github)](https://github.com/QuitttCat/CSE-200-Technical-Writing-and-Presentation/network/members)
![Repo Size](https://img.shields.io/github/repo-size/QuitttCat/CSE-200-Technical-Writing-and-Presentation?style=flat-square)
[![License](https://img.shields.io/github/license/QuitttCat/CSE-200-Technical-Writing-and-Presentation?style=flat-square)](LICENSE)
![Last Commit](https://img.shields.io/github/last-commit/QuitttCat/CSE-200-Technical-Writing-and-Presentation?style=flat-square&logo=git)
## 🚀 Tech Stack
### Languages
![LaTeX](https://img.shields.io/badge/LaTeX-TeX-blue?style=flat-square&logo=latex)
### Frameworks & Libraries
![TikZ](https://img.shields.io/badge/TikZ-PGF-lightgrey?style=flat-square)
![AMSmath](https://img.shields.io/badge/AMSmath-Math-purple?style=flat-square)
![Beamer](https://img.shields.io/badge/Beamer-Presentation-blue?style=flat-square)
### Developer Tools
![VS Code](https://img.shields.io/badge/VSCode-Editor-blue?style=flat-square&logo=visualstudiocode)
![Git](https://img.shields.io/badge/Git-VersionControl-orange?style=flat-square&logo=git)
![Overleaf](https://img.shields.io/badge/Overleaf-Online%20LaTeX%20Editor-green?style=flat-square&logo=overleaf)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=flat-square&logo=github)
---
## 📚 Table of Contents
- [Overview](#overview)
- [Offline 1 – Paper Copy With LaTeX](#offline-1--paper-copy-with-latex)
- [Presentation – Using LaTeX Beamer Slide](#presentation--using-latex-beamer-slide)
- [Quiz](#quiz)
- [Report](#report)
- [Installation & Running](#installation--running)
- [Folder Structure](#folder-structure)
- [Author](#author)
- [Star & Support](#star--support)
---
## 🧠 Overview
This repository contains full implementations and reports for
**CSE 200 – Technical Writing and Presentation (BUET, Level 2 Term 1)**.
These assignments cover:
- Reproducing research papers using LaTeX (e.g., "Shortest Paths Among Obstacles in the Plane Revisited" with diagrams like wavefronts and bisectors)
- Creating presentations with LaTeX Beamer on topics like Data Encryption Standard (DES), including history, algorithm, and security analysis
- LaTeX quiz practice with mathematical equations (e.g., normal distribution, Euler's formula, piecewise functions, Stirling numbers)
- Technical reports on encryption standards with TikZ diagrams (e.g., data encryption flows, Alice-Bob scenarios) and bibliographies
---
## Offline 1 – Paper Copy With LaTeX
- Reproduction of the paper "Shortest Paths Among Obstacles in the Plane Revisited" by Haitao Wang
- Includes abstract, introduction, algorithms, proofs, and diagrams (e.g., wavefront.png, bisectors.pdf, covertime.pdf)
- Uses LaTeX for typesetting theorems, lemmas, and bibliography
- Compiled PDF with sections on visibility graphs, continuous Dijkstra method, and optimal time/space complexity
---
## Presentation – Using LaTeX Beamer Slide
- Beamer presentation on "Data Encryption Standard: The Chamber of Secrets – Guarding Digital Realms"
- Covers introduction to DES, algorithm steps, security analysis, challenges, and future directions
- Features TikZ diagrams for encryption processes, Alice-Bob communication (e.g., encrypted vs. plain text scenarios)
- Includes sections on food for thought and suggested research areas
---
## Quiz
- LaTeX practice for lab quiz
- Demonstrates equations, alignments, brackets, piecewise functions, and complex math (e.g., Nambu-Goto action, Stirling numbers, Euler's equation)
- Compiled PDF with table of contents and solved examples
---
## Report
- Technical report on Data Encryption Standard (DES)
- Discusses algorithm details, vulnerabilities, comparisons (e.g., DEA vs. DES table), and conclusions
- Includes TikZ-generated images (DataEncryption.png, SendingEncryptedText.png, SendingPlainText.png) and references
- Compiled PDF with title page, sections, and bibliography
---
## ⚙ Installation & Running
### Clone Repository
```bash
git clone https://github.com/QuitttCat/CSE-200-Technical-Writing-and-Presentation.git
cd CSE-200-Technical-Writing-and-Presentation
```
### Install Dependencies
Install a LaTeX distribution like TeX Live or MiKTeX. Overleaf can also be used for online compilation. No additional pip requirements.

### Run Assignments
```bash
# Offline 1
cd "Offline 1 - Paper Copy With Latex"
pdflatex main.tex

# Presentation
cd "Presentation - Using Latex Beamer Slide"
pdflatex main.tex

# Quiz
cd Quiz
pdflatex "Quiz Practice.tex"

# Report
cd Report
pdflatex main.tex
```
---
## 📁 Folder Structure
```
CSE-200-Technical-Writing-and-Presentation/
│
├── Offline 1 - Paper Copy With Latex/
│   ├── bisectors.pdf
│   ├── covertime.pdf
│   ├── main.tex
│   ├── offline_1.pdf
│   ├── references.bib
│   └── wavefront.png
│
├── Presentation - Using Latex Beamer Slide/
│   └── main.tex
│
├── Quiz/
│   ├── Quiz Practice.tex
│   └── Quiz_Practice.pdf
│
├── Report/
│   ├── DataEncryption.png
│   ├── main.tex
│   ├── references.bib
│   ├── Report.pdf
│   ├── SendingEncryptesText.png
│   └── SendingPlainText.png
│
└── README.md
```
---
## 👤 Author
**Niloy Kumar Mondal**  
Student ID: **2105044**  
GitHub: https://github.com/QuitttCat  
---
## ⭐ Star & Support
If you found this repository helpful, please ⭐ star it on GitHub.  
Your support motivates future contributions! ❤️
