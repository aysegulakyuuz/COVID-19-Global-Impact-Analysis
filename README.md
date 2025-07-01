# CORD-19 Metadata Analysis

## 📌 Project Overview

This project analyzes the **CORD-19 dataset**, a publicly available collection of COVID-19-related research papers, developed by the Allen Institute for AI and the White House. The goal is to support researchers by helping them explore and extract meaningful insights from the metadata of over 300,000 scientific publications.

📁 Dataset Source: [CORD-19 Research Challenge (Kaggle)](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)

---

## 🎯 Objective

- Understand the distribution of COVID-19-related publications across time.
- Identify the most active journals, sources, and license types.
- Analyze the frequency of key scientific terms like *vaccine*, *mutation*, *variant*, and *transmission*.
- Perform basic NLP tasks on abstract text to uncover content trends.

---

## 📂 Dataset Features

| Column        | Description                                  |
|---------------|----------------------------------------------|
| `title`       | Title of the article                         |
| `abstract`    | Summary of the research                      |
| `publish_time`| Publication date                             |
| `source_x`    | Source of the article (PMC, WHO, etc.)       |
| `journal`     | Journal name                                 |
| `license`     | License type (e.g. cc-by, no-cc)             |
| `doi`         | Digital Object Identifier                    |

---

## 🧪 Methods & Tools

- **Language:** Python (Jupyter Notebook)
- **Libraries:** pandas, matplotlib, seaborn, nltk, wordcloud
- **Techniques:** 
  - Data preprocessing & filtering
  - Keyword frequency analysis
  - WordCloud generation
  - Bar and pie chart visualizations
  - Temporal trend analysis

---

## 📊 Key Insights

- Publication counts peaked in 2020–2021, with major sources including *PMC*, *WHO*, and *Medline*.
- Most common keywords in abstracts relate to *virus*, *patients*, *infection*, *health*.
- The term **"vaccine"** saw a sharp rise in article frequency post-2020.
- A wide variety of journals are involved, with open-access licensing being prevalent.

---

## 📈 Visuals Included

- Bar charts for year-wise and source-wise distribution
- WordCloud of top abstract terms
- Line chart for "vaccine" mentions over time
- Histogram of abstract lengths
- Pie chart for license types

---

## 📁 Files in Repository

- `Cord19_Metadata_Analysis.ipynb` – full Jupyter Notebook
- `metadata.csv` – original dataset (external due to size)
- `sample_metadata.csv` – optional 10K row sample
- `README.md` – this file

---

## 👩‍💻 Author

**Ayşegül Akyüz**  


---
