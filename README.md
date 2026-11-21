<p align="center">
  <img src="assets/readmission-hero.png" alt="Hospital readmission prediction — machine learning research" width="420" />
</p>

<h1 align="center">Predicting Hospital Readmissions</h1>

<h3 align="center">Machine Learning · Clinical NLP · Statistical Research</h3>

<p align="center">
  <strong>Can we identify patterns associated with a patient's return to the hospital?</strong>
</p>

<p align="center">
  An academic research project exploring hospital readmission prediction through<br>
  data analysis, classification experiments, and BERT-based clinical text processing.
</p>

<p align="center">
  <img alt="Python 3.8+" src="https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Jupyter Notebooks" src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white" />
  <img alt="Machine Learning" src="https://img.shields.io/badge/Machine-Learning-176B8A?style=flat-square" />
  <img alt="Clinical NLP — BERT" src="https://img.shields.io/badge/Clinical_NLP-BERT-7147A5?style=flat-square" />
  <img alt="Academic Research" src="https://img.shields.io/badge/Project-Academic_Research-2F855A?style=flat-square" />
</p>

<p align="center">
  <a href="notebooks/">Explore the notebooks</a> ·
  <a href="models/">Model experiments</a> ·
  <a href="Scientific_Article_and_Poster/">Scientific paper &amp; poster</a>
</p>

---

## The challenge

Hospital readmissions are a meaningful research problem at the intersection of **healthcare, data science, and predictive modeling**. Understanding which patterns may be associated with a patient's return to the hospital can support research into risk assessment and patient outcomes.

This project investigates that challenge using machine learning experiments, statistical analysis, and natural language processing of medical text.

> **Research scope:** This is an academic demonstration, **not** a clinically validated decision-support system. No individual prediction should be used to make medical decisions.

## What you'll find here

<table>
<tr>
<td width="33%" valign="top">
<h3>🧠 Clinical NLP</h3>
<p>Experiments with <strong>BERT</strong> for analyzing admission and discharge text from clinical records.</p>
</td>
<td width="33%" valign="top">
<h3>📊 Statistical analysis</h3>
<p>Notebooks, statistical tests, and visualizations for studying research results.</p>
</td>
<td width="33%" valign="top">
<h3>🔬 ML experimentation</h3>
<p>Model training artifacts, evaluation outputs, logs, and classification reports.</p>
</td>
</tr>
</table>

### Research workflow at a glance

```mermaid
flowchart LR
    A[Clinical research data] --> B[Exploration & analysis]
    B --> C[Statistical tests]
    B --> D[Machine learning experiments]
    E[Clinical admission & discharge text] --> F[BERT-based NLP]
    C --> G[Research findings]
    D --> G
    F --> G
    G --> H[Paper, poster & presentation]
```

*This diagram summarizes the repository's research areas; it does not imply that every notebook runs as a single automated pipeline.*

## Repository guide

| Location | Contents |
| :-- | :-- |
| [`models/`](models/) | Training and evaluation notebooks, classification reports, and experiment logs (including JSON, TSV, and TensorBoard artifacts). |
| [`notebooks/`](notebooks/) | Exploratory analysis and statistical notebooks organized by research topic. |
| [`NLP/`](NLP/) | BERT-related notebooks analyzing clinical admission and discharge text. |
| [`Statistical tests_Updates/`](Statistical%20tests_Updates/) | Visualizations and outputs from statistical tests, with links to related analyses. |
| [`Presentation_and_Summary/`](Presentation_and_Summary/) | Project presentation and research summary. |
| [`Scientific_Article_and_Poster/`](Scientific_Article_and_Poster/) | Scientific article and accompanying academic poster. |
| `requirements.txt` | Python package dependencies. |

## Getting started

### Requirements

- Python **3.8 or newer** (subject to the actual dependencies in `requirements.txt`)
- Jupyter Notebook
- Packages listed in `requirements.txt`

### Setup

```bash
# Clone this repository
git clone https://github.com/RanAlmagor/DataFinalProjectDegree-Demo-main.git
cd DataFinalProjectDegree-Demo-main

# Optional: create an isolated environment
python -m venv .venv

# Activate it (macOS / Linux)
source .venv/bin/activate
# On Windows: .venv\Scripts\activate

# Install Python dependencies
pip install -r requirements.txt

# Open the notebook environment
jupyter notebook
```

Browse the notebooks in `notebooks/`, `NLP/`, or `models/` to explore the relevant analyses and experiments.

**Important:** The public version does not distribute confidential patient-level data. Some notebooks or training steps may require separately authorized data access or supporting files and might not run end-to-end from the public repository alone.

## Research outputs

The repository contains supporting material for the academic study:

- **Analysis notebooks** — exploration, modeling, and statistical investigation.
- **Training and evaluation artifacts** — experiment outputs and classification reports.
- **Research presentation** — summary of the project and its findings.
- **Scientific article and poster** — written and visual communication of the research.

To assess actual model performance, consult the **classification reports and research artifacts** in the repository. Performance numbers are intentionally not quoted here until their final versions have been verified.

## Data privacy and responsible use

Patient confidentiality is essential. **Sensitive medical records and identifiable patient data are excluded** from the public demonstration.

- Do not commit patient records, credentials, or protected clinical files.
- Obtain permission before accessing restricted datasets.
- Treat findings as academic research, not clinical recommendations.

## About this portfolio

**Ran Almagor** · B.Sc. in Computer Science  
[GitHub profile](https://github.com/RanAlmagor)

This portfolio repository highlights my work within a collaborative academic research project. Contributions are preserved in the repository history and associated research materials.

---

<p align="center">
  <sub>Exploring how machine learning and clinical text analysis can advance research into hospital readmission risk.</sub>
</p>
