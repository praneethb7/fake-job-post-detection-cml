# Fake Job Post Detection 🕵️‍♀️

This repository contains the code and resources for a machine learning project aimed at detecting fraudulent job postings. The primary goal is to build a classification model that can accurately distinguish between real and fake job advertisements.

The entire analysis, from data preprocessing to model training and evaluation, is documented in the Jupyter Notebook. A comprehensive summary of the project, including methodology and findings, is available in the project report.

---

## 📋 Table of Contents

- [Dataset](#-dataset)
- [Repository Structure](#-repository-structure)
- [Usage](#-usage)
- [Project Report](#-project-report)
- [Model & Results](#-model--results)

---

## 📊 Dataset

This project utilizes the **"Real or Fake Job Postings Prediction"** dataset available on Kaggle. It contains 18,000 job descriptions, with both real and fraudulent entries.

**Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)

### How to Fetch the Dataset

To download the dataset, you'll need the Kaggle API. Follow these steps to get Kaggle API credentials:

1. Go to your Kaggle account settings (`https://www.kaggle.com/[Your-Kaggle-Username]/account`).
2. Click on **"Create New API Token"**. This will download a `kaggle.json` file.
3. Provide this file in Notebook when requested by the code.

---

## 📁 Repository Structure

The repository is organized as follows:

```
.
├── fake_job_post_detection.ipynb \# Colab Notebook with all the code
├── Project_Report.pdf \# Detailed project report
└── README.md \# This file

```

---

## 🚀 Usage

Google Colab Notebook is reccomended to use for this project to run the Jupyter Notebook

---

## 📄 Project Report

For a detailed walkthrough of the project, including exploratory data analysis (EDA), feature engineering techniques, model architecture, and a discussion of the results, please refer to the **`Project_Report.pdf`** file included in this repository.

---

## 🤖 Model & Results

After training muultiple models on same dataset, the best model in this project was found out to be **Support Vector Machine (SVM)**. After training and evaluation on the test set, the model achieved the following performance:

- **Accuracy:** `0.9869`
- **Precision:** `0.9701`
- **Recall:** `0.7514`
- **F1-Score:** `0.8469`

These results indicate a high level of effectiveness in identifying fraudulent job postings.

---
