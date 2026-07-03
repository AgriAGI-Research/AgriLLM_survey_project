# 🌾 AgriLLM Survey Project

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?logo=github)](https://agriagi-research.github.io/AgriLLM_survey_project/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--03-informational)](https://github.com/AgriAGI-Research/AgriLLM_survey_project/commits/main)

&gt; **Survey data and interactive analysis for Agricultural Large Language Models (AgriLLMs) review paper.**

---

## 📊 Live Demo

**🔗 Interactive HTML Report:** [https://agriagi-research.github.io/AgriLLM_survey_project/](https://agriagi-research.github.io/AgriLLM_survey_project/)

---

## 🏛️ Credit

**AgriAGI Research**  

Zhejiang University, China

---

## 📁 Repository Structure

AgriLLM_survey_project/
├── AgriLLM_survey_dat/           # Raw survey data
│   └── AgriLLM_survey 20260420.xlsx
├── index.Rmd                     # R Markdown source
├── index.html                    # Generated HTML report
├── README.md                     # This file
└── .gitignore


---

## 🛠️ How to Reproduce

### Prerequisites

- [R](https://www.r-project.org/) (≥ 4.0)
- [RStudio](https://posit.co/download/rstudio-desktop/)

### Required R Packages

```r
install.packages(c("readxl", "kableExtra", "dplyr", "ggplot2", "rmarkdown"))
```

**Steps**

1. Clone this repository: git clone https://github.com/AgriAGI-Research/AgriLLM_survey_project.git

2. Open report.Rmd in RStudio

3. Click Knit → Knit to HTML

4. The output index.html will be generated in the project root


## 📝 Citation

If you use this dataset in your research, please cite:

@misc{agriagi2026agrillm,
  author = {AgriAGI Research, Zhejiang University},
  title = {AgriLLM Survey: A Comprehensive Dataset of Agricultural Large Language Models},
  year = {2026},
  howpublished = {\url{https://agriagi-research.github.io/AgriLLM_survey_project/}}
}

## 🐛 Issues & Feedback

Found a mistake or have suggestions? Please open an issue.

##📜 License

This project is licensed under the MIT License.



