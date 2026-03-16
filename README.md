<h1 align="center">Hi, I'm Bambang Abhinawa (Abhin)</h1>
<h3 align="center">Data Science & Machine Learning | Dual Degree · UGM & University of Birmingham</h3>

<p align="center">
  <a href="https://linkedin.com/in/bambang-abhinawa-pinakasakti" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://kaggle.com/abhinawap" target="_blank">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white" />
  </a>
  <a href="mailto:bxp561@student.bham.ac.uk">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" />
  </a>
</p>

---

I build end-to-end ML pipelines from messy real-world data to reproducible, tested models. My work spans computer vision, fraud detection, and NLP, with a particular interest in making models that hold up under realistic evaluation conditions (temporal splits, class imbalance, proper validation).

Currently seeking an **industrial placement in data science**.

---

## Projects

### Brain Tumor Segmentation & Classification
> *PyTorch · U-Net · MLflow · GitHub Actions · pytest*

End-to-end pipeline for brain MRI segmentation and classification. Trained on 2,500+ scans with custom BCEDiceLoss, experiment tracking via MLflow, and a full pytest suite with CI/CD.

| Metric | Score |
|--------|-------|
| Validation Dice | 87.95% |
| Validation IoU | 79.93% |
| Validation Accuracy | 99.60% |

[View repository →](https://github.com/Abhinawap/brain-tumor-detection-ml)

---

### Elliptic Bitcoin Fraud Detection
> *XGBoost · Random Forest · SHAP · scikit-learn · MLflow*

Fraud detection on the Elliptic++ graph dataset (203,769 transactions, 9.25:1 class imbalance). Key design choices: temporal train-test split to prevent data leakage, threshold optimisation on the precision-recall curve, and triple feature validation (Gini, permutation importance, SHAP).

| Model | Fraud F1 | ROC-AUC |
|-------|----------|---------|
| XGBoost-186 (best) | 0.665 | 0.942 |
| Random Forest-186 | 0.655 | 0.919 |
| XGBoost-30 features | 0.658 | 0.955 |

[View repository →](https://github.com/Abhinawap/elliptic-fraud-detection)

---

### Fire Detection
> *Computer Vision · Deep Learning*

Object detection model for fire and smoke identification in real-time video streams.

[View repository →](https://github.com/Abhinawap/Fire-Detection)

---

### Indonesian Sentiment Analysis — UKT Tuition Fee Cancellation
> *SVM · TF-IDF · NLTK · Sastrawi · scikit-learn*

Sentiment classification (positive / neutral / negative) of Indonesian Twitter data around the 2024 UKT tuition fee policy. Built while working as Data Analyst at BEM KM UGM. Full NLP pipeline: Indonesian stemming with Sastrawi, stopword removal, TF-IDF vectorisation, and SVM with RBF kernel.

[View repository →](https://github.com/Abhinawap/sentiment-analysis-indonesian-tuition-fee-cancellation)

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-017CEE?style=flat&logo=data:image/png;base64,&logoColor=white)

**Data & Experiment Tracking**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)

**Engineering**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

## Currently

- **Working on:** Bitcoin fraud detection, extending XGBoost pipeline with Graph Neural Networks (GraphSAGE/GAT)
- **Learning:** Cloud computing, advanced feature selection, functional programming
- **Open to:** Industrial placement / internship opportunities in data science / machine learning

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Abhinawap&show_icons=true&theme=default&hide_border=true&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhinawap&layout=compact&hide_border=true&hide=jupyter%20notebook" height="150" />
</p>
