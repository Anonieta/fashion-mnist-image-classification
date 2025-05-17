# Fashion-MNIST Image Classification – Automation & Robotics Project

This project was completed as a team assignment for **EIN 4601C – Automation and Robotics** at the University of South Florida.

---

##  Project Overview

We applied **machine vision and supervised learning** techniques to automatically classify fashion items from grayscale images using the Fashion-MNIST dataset. Two classification models were implemented:

- **Setup 1:** K-Nearest Neighbors (KNN)
- **Setup 2:** Multilayer Perceptron (MLP)

---

##  Tools & Technologies

- Python (Jupyter Notebook / Google Colab)
- TensorFlow & Keras
- Scikit-learn
- NumPy
- Matplotlib & Seaborn

---

##  Methodology

- Data normalization and reshaping
- Hyperparameter tuning using `GridSearchCV`
- Cross-validation with `StratifiedKFold`
- Evaluation using:
  - Accuracy
  - Confusion matrices
  - Precision & Recall
  - Training time

---

##  Results

| Model | Accuracy | Precision | Recall | Training Time |
|-------|----------|-----------|--------|----------------|
| KNN   | 85%      | 86%       | 85%    | 443 sec        |
| MLP   | 88%      | 89%       | 88%    | 5211 sec       |

The **MLP classifier** outperformed KNN in all metrics, especially in recognizing visually similar classes like t-shirts vs. pullovers.

---

## Files Included

- `Team_12.ipynb` – Full Python notebook (Colab/Jupyter compatible)
- `AUTOMATION AND ROBOTICS FINAL PROJECT.pdf` – Final report with analysis and visualizations

---
## Team Members

Team 12:  
Antonieta Della Sala, Maria Villarreal, Laiba Aurangzeb, Cagla Unsalan

---

## Course Information

**Course:** EIN 4601C – Automation and Robotics  
**Instructor:** Dr. Susana Lai-Yuen  
**Semester:** Spring 2025

