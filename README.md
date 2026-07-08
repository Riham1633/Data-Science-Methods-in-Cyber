# Paper-Reproduction---Data-Science-Methods-in-Cyber

# Tree-based Intelligent Intrusion Detection System in Internet of Vehicles

### Paper Reproduction and Critical Evaluation

## Project Description

The project also includes a critical evaluation of the original paper, discussing its strengths, limitations, reproducibility, and methodological assumptions.

The objective is to reproduce the proposed intrusion detection framework, analyze its methodology, and compare the reproduced results with those reported in the original paper. The implementation includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, performance evaluation, and error analysis using the CICIDS2017 dataset.

The reproduced models include:

* Decision Tree
* Random Forest
* Extra Trees
* XGBoost
* Stacking Ensemble

The project also provides a critical evaluation of the paper, discussing its strengths, limitations, reproducibility, and potential improvements.

---

## Original Paper

**Title**

Tree-based Intelligent Intrusion Detection System in Internet of Vehicles

[**Link**](https://arxiv.org/pdf/1910.08635)

---

[**Original GitHub Repository**](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-Machine-Learning/tree/main)

---

## Dataset

This project uses the **CICIDS2017** intrusion detection dataset.



[**Dataset source**](https://github.com/Western-OC2-Lab/Intrusion-Detection-System-Using-Machine-Learning/blob/main/data/CICIDS2017_sample.csv)

The reproduction was performed using the sampled dataset provided with the authors' implementation.

---

## Repository Contents

* `Tree_based_IDS_Report_2.pdf` – Final project report.
  (This version is an updated version of the original report (Tree_based_IDS_Report.pdf), updated based on the given feedback).
* `Tree_based_IDS_Reproduction_2.ipynb` – Complete code implementation.
  (This version is an updated version of the original notebook (Tree_based_IDS_Reproduction.ipynb), updated based on the given feedback).
* `CICIDS2017_sample.csv` – Sampled CICIDS2017 dataset used for the reproduction.
* `requirements.txt` – Python dependencies required to run the notebook.
* `README.md` – Project description and execution instructions.

---

## Execution Instructions

1. Open the notebook Tree_based_IDS_Reproduction_2.ipynb.
2. Install the required Python packages: pip install -r requirements.txt
3. Download the sampled CICIDS2017 dataset from the link above and upload CICIDS2017_sample.csv when prompted by the notebook.
4. Execute the rest of the notebook.

The notebook performs:

* Data loading
* Data preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Model Training
* Performance Evaluation
* Error Analysis
* Comparison with the original paper
* Duplicate Removal Validation and Comparison with the Original Paper


## Notes on Reproducibility

The reproduction uses the sampled CICIDS2017 dataset released with the authors' implementation. Therefore, the reported performance should be interpreted as a sample-based reproduction of the proposed methodology rather than a direct numerical replication of the full-dataset results reported in the original paper.
---

## Author

Riham Badarna

University of Haifa

Data Science

