Meta-Analysis Data & Reproducible Code

This repository contains the study-level datasets and a single unified analysis file (analysis.Rmd) used to reproduce all statistical results in our meta-analysis and network meta-analysis. All analyses (pairwise, NMA, sensitivity checks, and plots) are executed directly from the R Markdown file.

Contents

analysis.Rmd — full reproducible workflow

*.csv — cleaned study-level data used in the models

Flat structure only; no subfolders.

Usage

To reproduce:

rmarkdown::render("analysis.Rmd")

Rights

© 2025. All Rights Reserved.
Data and code may be viewed and cited for academic purposes only.
Redistribution or commercial use is not permitted without written permission.

Disclaimer

Research-only materials; no clinical or regulatory interpretations should be drawn from these files.
