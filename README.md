
# Machine Learning Projects

Welcome to my Machine Learning repository! This repository is a collection of my projects and experiments as I learn and explore various machine learning concepts and techniques. I will continuously update this repository with new projects, code, and insights as I progress in my machine learning journey. All the codes will primarily be in R.

---

## Introduction and Overview

This repository covers a wide range of machine learning methods, starting with classical linear and generalized linear models and progressing to modern non-linear statistical learning methods. Below is an overview of the topics that will be covered:

1. **Classical Linear and Generalized Linear Models:**
   - Linear Regression
   - Logistic Regression
   - Linear Discriminant Analysis

2. **Modern Resampling and Variable Selection Methods:**
   - Bootstrapping
   - Shrinkage Methods (e.g., Lasso, Ridge Regression)

3. **Traditional Multivariate Analysis Methods:**
   - Cluster Analysis
   - Principal Component Analysis (PCA)
   - Multivariate Regression Methods (e.g., Structural Equation Modeling)

4. **Modern Non-Linear Statistical Learning Methods:**
   - Generalized Additive Models (GAM)
   - Decision Trees
   - Random Forest
   - Boosting and Bagging
   - Support Vector Machines (SVM)
   - Neural Networks

---

## Repository Structure

The repository is organized into folders based on the type of machine learning task. Below is the directory structure:

```
└── sriramv1212-machine-learning/
    ├── README.md
    ├── Linear Regression/
    │   ├── Ames_Housing_Data.csv
    │   └── Linear Regression 1_ Housing price prediction.Rmd
    └── Logistic Regression/
        ├── Logistic Regression 2- Titanic.Rmd
        └── Titanic2.csv
```

---

## Projects

### 1. **Linear Regression: Housing Price Prediction**
- **Description:** This project focuses on predicting house prices using the Ames Housing dataset. Two variable selection methods—stepwise selection and best subset selection—are used to build and compare linear regression models.
- **Files:**
  - [`Ames_Housing_Data.csv`](Linear%20Regression/Ames_Housing_Data.csv): Dataset containing housing features and sale prices.
  - [`Linear Regression 1_ Housing price prediction.Rmd`](Linear%20Regression/Linear%20Regression%201_%20Housing%20price%20prediction.Rmd): R Markdown file with the analysis, model building, and evaluation.
- **Key Steps:**
  - Data splitting into training and testing sets.
  - Stepwise variable selection based on BIC.
  - Best subset selection based on SSE.
  - Model comparison using BIC, RMSE, and R².
- **Results:**
  - Stepwise model and best subset model coefficients.
  - RMSE and R² values for both models on the test data.
  - Comparison of model performance.

---

### 2. **Logistic Regression: Titanic Survival Prediction**
- **Description:** This project predicts passenger survival on the Titanic using logistic regression. The dataset is cleaned, and a logistic regression model is built to classify passengers as survivors or non-survivors.
- **Files:**
  - [`Titanic2.csv`](Logistic%20Regression/Titanic2.csv): Dataset containing passenger information and survival status.
  - [`Logistic Regression 2- Titanic.Rmd`](Logistic%20Regression/Logistic%20Regression%202-%20Titanic.Rmd): R Markdown file with the analysis, model building, and evaluation.
- **Key Steps:**
  - Data cleaning and preprocessing.
  - Splitting data into training and testing sets.
  - Fitting a logistic regression model with 7 predictors.
  - Evaluating the model using a confusion matrix, accuracy, sensitivity, and specificity.
  - Predicting survival for additional passengers.
- **Results:**
  - Confusion matrix and performance metrics (accuracy, sensitivity, specificity).
  - Predicted survival for additional passengers.

---

## Status of Machine Learning Methods

| **Method**                     | **Status**       | **Details**                                                                 |
|---------------------------------|------------------|-----------------------------------------------------------------------------|
| Linear Regression               | ✅ Completed     | [Link to Project](Linear%20Regression/Linear%20Regression%201_%20Housing%20price%20prediction.Rmd) |
| Logistic Regression             | ✅ Completed     | [Link to Project](Logistic%20Regression/Logistic%20Regression%202-%20Titanic.Rmd) |
| Linear Discriminant Analysis    | ⏳ Upcoming      | Planned for future updates.                                                |
| Bootstrapping                   | ⏳ Upcoming      | Planned for future updates.                                                |
| Shrinkage Methods               | ⏳ Upcoming      | Planned for future updates.                                                |
| Cluster Analysis                | ⏳ Upcoming      | Planned for future updates.                                                |
| Principal Component Analysis    | ⏳ Upcoming      | Planned for future updates.                                                |
| Decision Trees                  | ⏳ Upcoming      | Planned for future updates.                                                |
| Random Forest                   | ⏳ Upcoming      | Planned for future updates.                                                |
| Boosting and Bagging            | ⏳ Upcoming      | Planned for future updates.                                                |
| Support Vector Machines         | ⏳ Upcoming      | Planned for future updates.                                                |
| Neural Networks                 | ⏳ Upcoming      | Planned for future updates.                                                |

---

## Recommended Textbooks

1. **The Elements of Statistical Learning: Data Mining, Inference, and Prediction, Second Edition (2008)**  
   Trevor Hastie, Robert Tibshirani, Jerome Friedman. Springer.  
   [Download PDF](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)

2. **An Introduction to Statistical Learning with Applications in R (2017)**  
   Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani. Springer.  
   [Book Website](http://faculty.marshall.usc.edu/gareth-james/ISL/book.html)

3. **Applied Multivariate Statistics with R (Optional) (2015)**  
   Daniel Zelterman. Springer.  
   ISBN-13: 978-3319361635, ISBN-10: 3319361635.

---

## How to Use This Repository

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/sriramv1212/sriramv1212-machine-learning.git
   ```

2. **Navigate to the Project Folder:**
   - For Linear Regression:
     ```bash
     cd sriramv1212-machine-learning/Linear Regression
     ```
   - For Logistic Regression:
     ```bash
     cd sriramv1212-machine-learning/Logistic Regression
     ```

3. **Open the R Markdown File:**
   - Use RStudio or any compatible IDE to open and run the `.Rmd` files.

4. **Reproduce the Analysis:**
   - Ensure all required libraries are installed.
   - Run the code chunks in the R Markdown file to reproduce the analysis and results.

---

## Dependencies

- **R Libraries:**
  - `caret`
  - `MASS`
  - `leaps`
  - `dplyr`
  - `tidyverse`

Install the required libraries using:
```R
install.packages(c("caret", "MASS", "leaps", "dplyr", "tidyverse"))
```

---

## Author

- **Sriram Vivek**
- **GitHub:** [sriramv1212](https://github.com/sriramv1212)
- **Email:** sriram.vivek@stonybrook.edu

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- The Ames Housing dataset and Titanic dataset are publicly available and widely used for educational purposes.
- Special thanks to the R community for providing excellent resources and libraries for machine learning.

---

Happy Learning! 



