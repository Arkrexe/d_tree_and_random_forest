# Decision Trees and Random Forests

This project is part of my AI & ML Internship. I worked on classifying heart disease using Decision Trees and Random Forests.

---

## 📂 Dataset Used

- **Name:** Heart Disease Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Target Column:** `target` (0 = No disease, 1 = Disease)

---

## ✅ What I Did

1. Loaded the data and explored it.
2. Trained a **Decision Tree Classifier**.
3. Visualized the decision tree.
4. Reduced overfitting by limiting tree depth.
5. Trained a **Random Forest Classifier** and compared the accuracy.
6. Checked **feature importances**.
7. Evaluated both models using **cross-validation**.

---

## 📊 Results

| Model           | Accuracy |
|----------------|----------|
| Decision Tree  | ~77%     |
| Random Forest  | ~85%     |

---

## 🔍 Key Points

- Random Forest gave better accuracy than a single tree.
- Important features: `cp`, `thalach`, `ca`, `oldpeak`.
- Used `sklearn`, `pandas`, `matplotlib`, and `seaborn`.

---
