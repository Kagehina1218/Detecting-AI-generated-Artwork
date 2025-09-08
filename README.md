# 🔍 Detecting AI-generated Artwork

This repository contains sample code and a portion of the dataset used in our paper:

> **"Detecting AI-generated Artwork"**  
> *Meien Li/Grace Li*, *Mark Stamp*  
> ✅ Accepted at **Computer Science Conference for CSU Undergraduates, 2025**  
> 📄 [arXiv preprint](https://arxiv.org/abs/2504.07078)

---

## 📌 Overview

This project investigates the performance of various traditional machine learning models and compares them with deep learning models for the task of distinguishing **AI-generated art** from **human-created artwork**.

The dataset consists of:
- **Pre-extracted features** (Used for training LR, SVM, and MLP)

The pipeline includes:
- Data preprocessing
- Model training (ML & DL)
- Evaluation and comparison

> 🧪 All code is written and tested in **Google Colab**.

---

## 🗂️ Project Structure

```bash
project-root/
├── code/                       # Google Colab notebooks
│   ├── PreProcess_FeatureExtract.ipynb
│   ├── Training_CNN.ipynb
│   └── Training_LR_SVM_MLP.ipynb
│
├── dataset/                    # Dataset folder (sample only)
│   └── features/               # Extracted features (.csv or .npy)
│
├── README.md                   # Project documentation (this file)
