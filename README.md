# 📊 LAB 6 | Handling Imbalanced Data and Feature Engineering

**Authors**:  
- Inshal Bint-i-Adil (F23607038)  
- Muhammad Imran (F23607042)

**Course**: PFAI (Programming Fundamentals for Artificial Intelligence)

**Date**: 2025-04-27

---

## 📄 Project Description

This lab focuses on advanced data preprocessing techniques using R, including:

- Handling imbalanced datasets with oversampling/undersampling techniques (ROSE).
- Feature engineering with the `recipes` package.
- Data visualization using PCA (Principal Component Analysis).
- Building and evaluating efficient machine learning models with `caret`.
- Comprehensive EDA and model performance analysis.

The project is structured in an R Markdown (`.Rmd`) format and can generate a full HTML report.

---

## 📦 Requirements

Make sure you have R installed along with the following packages:

- `data.table`
- `ROSE`
- `recipes`
- `caret`
- `FactoMineR`
- `factoextra`
- `ggplot2`

You can install missing packages by running:

```r
install.packages(c("data.table", "ROSE", "recipes", "caret", "FactoMineR", "factoextra", "ggplot2"))
```

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Open the `.Rmd` file**:
   - Use [RStudio](https://posit.co/download/rstudio-desktop/) or any R environment.

3. **Knit the file** to HTML:
   - Click the "Knit" button in RStudio to generate the full report.
   - Or run:
     ```r
     rmarkdown::render("task with efficient model.Rmd")
     ```

---

## 📋 Main Steps in the Project

- Environment Setup and Package Loading
- Data Import (100,000 sampled rows for Posit Cloud)
- Preprocessing using `recipes`:
  - Handling Missing Values
  - Scaling, Centering, Encoding
- Balancing the Dataset using `ROSE`
- Dimensionality Reduction using PCA
- Model Training and Evaluation using `caret`:
  - Logistic Regression
  - Decision Trees
  - Random Forests
- Visualization of Model Performance and PCA

---

## 📚 Learnings

- How to engineer features and handle data imbalance.
- Using pipelines (`recipes`) for clean preprocessing.
- Visualizing complex data transformations and model evaluations.
- Best practices for scalable machine learning workflows in R.

---

## 📜 License

This project is intended for academic use and learning purposes only.

---
