<div align="center">

# 🤖 Machine Learning — Algorithms & Techniques

**From first principles to production-ready workflows — 100 Jupyter notebooks covering 18 ML algorithms (many coded from scratch), evaluation, regularization and the full feature-engineering toolkit.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-189AB4)
![NumPy](https://img.shields.io/badge/NumPy-From%20scratch-013243?logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Level](https://img.shields.io/badge/Level-Intermediate-0EA5A4)

</div>

---

## 🎯 What makes this course different

- 🧠 **Intuition first** — every algorithm starts with the geometric or mathematical idea behind it.
- 🛠️ **Built from scratch** — linear & logistic regression, gradient descent, KNN, K-means, AdaBoost and more are implemented in NumPy, then compared with scikit-learn.
- 🎛️ **Tuned like the real world** — hyperparameters, GridSearchCV / RandomizedSearchCV, cross-validation and the bias–variance trade-off.
- 🧹 **Data-ready** — a complete feature-engineering module: missing values, scaling, encoding, transformation, outliers, pipelines and feature selection.

---

## 📚 Module 1 — Introduction to Machine Learning

[MACHINE LEARNING (ML-Life cycle -theory part # 2)](1.%20Machine%20Learning%20Introduction/MACHINE%20LEARNING%20%28ML-Life%20cycle%20-theory%20part%20%23%202%29.ipynb) · [MACHINE LEARNING (theory part # 1)](1.%20Machine%20Learning%20Introduction/MACHINE%20LEARNING%20%28theory%20part%20%23%201%29.ipynb)

## 📚 Module 2 — ML basics & algorithms

### Foundations

| Topic | Notebooks |
|---|---|
| 🔢 Tensors (prerequisite) | [Tensors](2.%20ML%20Basics%20and%20Algorithms/1.%20Tensors/Tensors.ipynb) |
| 📊 Evaluation metrics | [Classification Metrics](2.%20ML%20Basics%20and%20Algorithms/3.%20ML%20Metrics/Classification%20Metrics.ipynb) · [Regression Metrics](2.%20ML%20Basics%20and%20Algorithms/3.%20ML%20Metrics/Regression%20Metrics.ipynb) |
| ⚖️ Bias–variance trade-off | [Bias Variance Trade-off _ Overfitting and Underfitting in Machine Learning](2.%20ML%20Basics%20and%20Algorithms/4.%20Bias-Variance%20Trade-off/Bias%20Variance%20Trade-off%20_%20Overfitting%20and%20Underfitting%20in%20Machine%20Learning.ipynb) |
| 🔄 Cross-validation | [Cross-validation in Machine Learning](2.%20ML%20Basics%20and%20Algorithms/5.%20Cross-Validation/Cross-validation%20in%20Machine%20Learning.ipynb) |

### Algorithms (supervised, unsupervised & ensembles)

| Algorithm | Notebooks |
|---|---|
| 📈 Linear regression | [Linear regression](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/1.%20LINEAR%20REGRESSION/Linear%20regression.ipynb) |
| ⛰️ Gradient descent | [BATCH GRADIENT DISCENT (on n-d data)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/2.%20GRADIENT%20DISCENT/BATCH%20GRADIENT%20DISCENT%20%28on%20n-d%20data%29.ipynb) · [Gradient Descent (INTRO+BATCH GD ON 2-D DATA)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/2.%20GRADIENT%20DISCENT/Gradient%20Descent%20%28INTRO%2BBATCH%20GD%20ON%202-D%20DATA%29.ipynb) · [Mini-Batch Gradient Descent](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/2.%20GRADIENT%20DISCENT/Mini-Batch%20Gradient%20Descent.ipynb) · [Stochastic Gradient Descent](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/2.%20GRADIENT%20DISCENT/Stochastic%20Gradient%20Descent.ipynb) |
| 🔀 Logistic regression | [1. Logistic Regression (Perceptron Trick code+sigmoid function)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/3.%20Logistic%20Regression/1.%20Logistic%20Regression%20%28Perceptron%20Trick%20code%2Bsigmoid%20function%29.ipynb) · [2. Logistic Regression _ Gradient Descent & Code From Scratch](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/3.%20Logistic%20Regression/2.%20Logistic%20Regression%20_%20Gradient%20Descent%20%26%20Code%20From%20Scratch.ipynb) · [3. Softmax Regression _ Multinomial Logistic Regression on iris data set](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/3.%20Logistic%20Regression/3.%20Softmax%20Regression%20_%20Multinomial%20Logistic%20Regression%20on%20iris%20data%20set.ipynb) · [4. Polynomial Features in Logistic Regression _ Non Linear Logistic Regression](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/3.%20Logistic%20Regression/4.%20Polynomial%20Features%20in%20Logistic%20Regression%20_%20Non%20Linear%20Logistic%20Regression.ipynb) · [5. Logistic Regression Hyperparameters](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/3.%20Logistic%20Regression/5.%20Logistic%20Regression%20Hyperparameters.ipynb) |
| 📐 Support vector machines | [Kernel Trick in SVM](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/4.%20Support%20Vector%20Machines/Kernel%20Trick%20in%20SVM.ipynb) · [Support Vector Machines](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/4.%20Support%20Vector%20Machines/Support%20Vector%20Machines.ipynb) |
| 🎲 Naive Bayes | [NAIVE BAYES  ALGORITHM (ON TENNIS TOY DATASET)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/5.%20NAIVE%20BAYES/NAIVE%20BAYES%20%20ALGORITHM%20%28ON%20TENNIS%20TOY%20DATASET%29.ipynb) |
| 📍 K-nearest neighbours | [Building a KNN Classifier from scratch](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/6.%20K%20Nearest%20Neighbors%20%28KNN%29/Building%20a%20KNN%20Classifier%20from%20scratch.ipynb) · [Introduction and Geometric Intuition](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/6.%20K%20Nearest%20Neighbors%20%28KNN%29/Introduction%20and%20Geometric%20Intuition.ipynb) · [KNN hyperparameters and weighted KNN](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/6.%20K%20Nearest%20Neighbors%20%28KNN%29/KNN%20hyperparameters%20and%20weighted%20KNN.ipynb) · [KNN- Working with a Real world dataset](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/6.%20K%20Nearest%20Neighbors%20%28KNN%29/KNN-%20Working%20with%20a%20Real%20world%20dataset.ipynb) |
| 🌳 Decision trees | [1. Decision Trees - Introduction and Geometric Intuition](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/1.%20Decision%20Trees%20-%20Introduction%20and%20Geometric%20Intuition.ipynb) · [2. Entropy in Decision Trees](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/2.%20Entropy%20in%20Decision%20Trees.ipynb) · [3. Information Gain IN Decision Trees](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/3.%20Information%20Gain%20IN%20Decision%20Trees.ipynb) · [4. Gini Impurity in depth Intuition](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/4.%20Gini%20Impurity%20in%20depth%20Intuition.ipynb) · [5. Handling Numerical values in Decision Trees](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/5.%20Handling%20Numerical%20values%20in%20Decision%20Trees.ipynb) · [6. Sklearn code(DecisionTreeClassifier)_Visualizing a Decision Tree](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/6.%20Sklearn%20code%28DecisionTreeClassifier%29_Visualizing%20a%20Decision%20Tree.ipynb) · [7. Underfitting_Overfitting in Decision Trees](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/7.%20Underfitting_Overfitting%20in%20Decision%20Trees.ipynb) · [8. Decision Tree Hyperparameters In-depth Intuition](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/8.%20Decision%20Tree%20Hyperparameters%20In-depth%20Intuition.ipynb) · [9. Hyper-parameter Tuning using GridSearchCV](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/9.%20Hyper-parameter%20Tuning%20using%20GridSearchCV.ipynb) · [10. Handwriting Classifier using Decision Trees](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/10.%20Handwriting%20Classifier%20using%20Decision%20Trees.ipynb) · [11. Awesome Decision Tree Visualization using dtreeviz library](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/11.%20Awesome%20Decision%20Tree%20Visualization%20using%20dtreeviz%20library.ipynb) · [12. Regression Tree Hyperparameter Tuning and Code Example](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/7.%20Decision%20Trees/12.%20Regression%20Tree%20Hyperparameter%20Tuning%20and%20Code%20Example.ipynb) |
| 🌲 Random forest | [1. Introduction to Ensemble Learning _ Ensemble Techniques in Machine Learning](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/1.%20Introduction%20to%20Ensemble%20Learning%20_%20Ensemble%20Techniques%20in%20Machine%20Learning.ipynb) · [2. Introduction to Random Forest_ Intuition behind the Algorithm](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/2.%20Introduction%20to%20Random%20Forest_%20Intuition%20behind%20the%20Algorithm.ipynb) · [3. How Random Forest Performs So Well_ Bias Variance Trade-Off in Random Forest](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/3.%20How%20Random%20Forest%20Performs%20So%20Well_%20Bias%20Variance%20Trade-Off%20in%20Random%20Forest.ipynb) · [4. Bagging Vs Random Forest](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/4.%20Bagging%20Vs%20Random%20Forest_.ipynb) · [5. Random Forest Hyper-parameters](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/5.%20Random%20Forest%20Hyper-parameters.ipynb) · [6.  GridSearchCV and RandomizedSearchCV With Code Example](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/6.%20%20GridSearchCV%20and%20RandomizedSearchCV%20With%20Code%20Example.ipynb) · [7. OOB Score _ Out of Bag Evaluation in Random Forest](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/7.%20OOB%20Score%20_%20Out%20of%20Bag%20Evaluation%20in%20Random%20Forest.ipynb) · [8. Feature Importance using Random Forest and Decision Trees _ How is Feature Importance calculated](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/8.%20RANDOM%20FOREST/8.%20Feature%20Importance%20using%20Random%20Forest%20and%20Decision%20Trees%20_%20How%20is%20Feature%20Importance%20calculated.ipynb) |
| 🎒 Bagging | [BAGGING CLASSIFIER](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/9.%20BAGGING/BAGGING%20CLASSIFIER.ipynb) · [Bagging Regressor](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/9.%20BAGGING/Bagging%20Regressor.ipynb) · [Bagging _ Introduction](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/9.%20BAGGING/Bagging%20_%20Introduction.ipynb) |
| 🚀 AdaBoost | [AdaBoost Algorithm  Code from Scratch](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/10.%20ADABOOST/AdaBoost%20Algorithm%20%20Code%20from%20Scratch.ipynb) · [AdaBoost Hyperparameters _ GridSearchCV in Adaboost](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/10.%20ADABOOST/AdaBoost%20Hyperparameters%20_%20GridSearchCV%20in%20Adaboost.ipynb) · [Bagging Vs Boosting](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/10.%20ADABOOST/Bagging%20Vs%20Boosting.ipynb) |
| 📉 Gradient boosting | [Gradient Boosting ( Classification case mathematics )](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/11.%20Gradient%20Boosting/Gradient%20Boosting%20%28%20Classification%20case%20mathematics%20%29.ipynb) · [Gradient Boosting (classification case)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/11.%20Gradient%20Boosting/Gradient%20Boosting%20%28classification%20case%29.ipynb) · [Gradient Boosting (regression case mathematics)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/11.%20Gradient%20Boosting/Gradient%20Boosting%20%28regression%20case%20mathematics%29.ipynb) · [Gradient Boosting intution (regression)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/11.%20Gradient%20Boosting/Gradient%20Boosting%20intution%20%28regression%29.ipynb) |
| ⚡ XGBoost | [XgBoost  (regression+classification)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/12.%20XGBOOST/XgBoost%20%20%28regression%2Bclassification%29.ipynb) |
| 🧭 PCA | [(PCA) Problem Formulation and Step by Step Solution](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/13.%20PCA/%28PCA%29%20Problem%20Formulation%20and%20Step%20by%20Step%20Solution.ipynb) |
| 🎯 K-means clustering | [K-Means Clustering Algorithm (Practical Example)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/14.%20K_means%20clusstering/K-Means%20Clustering%20Algorithm%20%28Practical%20Example%29.ipynb) · [K-Means Clustering Algorithm From Scratch](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/14.%20K_means%20clusstering/K-Means%20Clustering%20Algorithm%20From%20Scratch.ipynb) |
| 🌿 Hierarchical clustering | [Agglomerative Hierarchical Clustering](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/15.%20Agglomerative%20hierarchical%20clustering/Agglomerative%20Hierarchical%20Clustering.ipynb) |
| 🫧 DBSCAN | [16.DBSCAN](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/16.DBscan/16.DBSCAN.ipynb) |
| 🗺️ t-SNE | [t-distributed stochastic neighbor embedding (t-SNE)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/17.t-SNE/t-distributed%20stochastic%20neighbor%20embedding%20%28t-SNE%29.ipynb) |
| 🗳️ Voting ensemble | [Voting Ensemble(VOTING CLASSIFIER)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/18.Voting%20Ensemble/Voting%20Ensemble%28VOTING%20CLASSIFIER%29.ipynb) · [Voting Ensemble(VOTING REGRESSOR)](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/18.Voting%20Ensemble/Voting%20Ensemble%28VOTING%20REGRESSOR%29.ipynb) |
| 🛡️ Regularization |  |
| ↳ ElasticNet | [ElasticNet Regression](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/REGULARIZATION/ELASTICNET%20REGRESSION/ElasticNet%20Regression.ipynb) |
| ↳ Lasso (L1) | [LASSO REGRESSION IMPORTANT POINTS](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/REGULARIZATION/LASSO%20REGRESSION/LASSO%20REGRESSION%20IMPORTANT%20POINTS.ipynb) · [Lasso Regression Intuition and Code Sample](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/REGULARIZATION/LASSO%20REGRESSION/Lasso%20Regression%20Intuition%20and%20Code%20Sample.ipynb) |
| ↳ Ridge (L2) | [5 Key Points regarding Ridge Regression](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/REGULARIZATION/RIDGE%20REGRESSION/5%20Key%20Points%20regarding%20Ridge%20Regression.ipynb) · [Gradient Discent on Ridge Regression](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/REGULARIZATION/RIDGE%20REGRESSION/Gradient%20Discent%20on%20Ridge%20Regression.ipynb) · [Ridge Regression](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/REGULARIZATION/RIDGE%20REGRESSION/Ridge%20Regression.ipynb) · [gradient discent from scrach](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/REGULARIZATION/RIDGE%20REGRESSION/gradient%20discent%20from%20scrach.ipynb) |

📋 Cheat sheet: [ALL ALGORITHMS OF   [REGRESSION AND CLASSIFICATION]   PROBLEMS](2.%20ML%20Basics%20and%20Algorithms/2.%20ML%20Algorithms/ALL%20ALGORITHMS%20OF%20%20%20%5BREGRESSION%20AND%20CLASSIFICATION%5D%20%20%20PROBLEMS.ipynb)

## 📚 Module 3 — ML techniques (feature engineering)

Start here: [Feature engineering overview](3.%20ML%20Techniques%20%28Feature%20Engineering%29/1.%20Feature%20Engineering%20overview.ipynb)

| Technique | Notebooks |
|---|---|
| 🕳️ Missing values | [1.Complete Case Analysis](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/1.Complete%20Case%20Analysis.ipynb) · [2. Handling missing Numerical Data (mean and median imputation)](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/2.%20Handling%20missing%20Numerical%20Data%20%28mean%20and%20median%20imputation%29.ipynb) · [3.Arbitrary value_ End of distribution imputation](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/3.Arbitrary%20value_%20End%20of%20distribution%20imputation_.ipynb) · [4. Handling Missing Categorical Data](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/4.%20Handling%20Missing%20Categorical%20Data.ipynb) · [5. Random Sample Imputation](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/5.%20Random%20Sample%20Imputation_.ipynb) · [6. Missing Indicator](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/6.%20Missing%20Indicator.ipynb) · [7.Automatically select imputer parameters](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/7.Automatically%20select%20imputer%20parameters.ipynb) · [8. Multivariate Imputation (1. KNN Imputer)](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/8.%20Multivariate%20Imputation%20%281.%20KNN%20Imputer%29.ipynb) · [9. Multivariate Imputation (2. Iterative Imputer)](3.%20ML%20Techniques%20%28Feature%20Engineering%29/2.%20Working%20with%20missing%20values/9.%20Multivariate%20Imputation%20%282.%20Iterative%20Imputer%29.ipynb) |
| 📏 Feature scaling | [1. Standardization](3.%20ML%20Techniques%20%28Feature%20Engineering%29/3.%20FEATURE%20SCALING/1.%20Standardization_.ipynb) · [2. Normalization](3.%20ML%20Techniques%20%28Feature%20Engineering%29/3.%20FEATURE%20SCALING/2.%20Normalization_.ipynb) |
| 🔤 Feature encoding | [1. Ordinal Encoding and Label Encoding](3.%20ML%20Techniques%20%28Feature%20Engineering%29/4.%20Feature%20Encoding/1.%20Ordinal%20Encoding%20and%20Label%20Encoding.ipynb) · [2. One Hot Encoding](3.%20ML%20Techniques%20%28Feature%20Engineering%29/4.%20Feature%20Encoding/2.%20One%20Hot%20Encoding.ipynb) · [Encoding numerical feature](3.%20ML%20Techniques%20%28Feature%20Engineering%29/4.%20Feature%20Encoding/Encoding%20numerical%20feature.ipynb) |
| 🔁 Feature transformation | [Function Transformer](3.%20ML%20Techniques%20%28Feature%20Engineering%29/5.%20Feature%20Transformation/Function%20Transformer.ipynb) · [Power Transformer](3.%20ML%20Techniques%20%28Feature%20Engineering%29/5.%20Feature%20Transformation/Power%20Transformer.ipynb) |
| 🧱 Pipelines & ColumnTransformer | [Column Transformer in Machine Learning](3.%20ML%20Techniques%20%28Feature%20Engineering%29/6.%20Pipelines/Column%20Transformer%20in%20Machine%20Learning.ipynb) · [titanic-with-using-pipeline (prediction included)](3.%20ML%20Techniques%20%28Feature%20Engineering%29/6.%20Pipelines/titanic-with-using-pipeline%20%28prediction%20included%29.ipynb) · [titanic-without-using-pipeline (prediction included)](3.%20ML%20Techniques%20%28Feature%20Engineering%29/6.%20Pipelines/titanic-without-using-pipeline%20%28prediction%20included%29.ipynb) |
| 📅 Date & time features | [Handling Date and Time Variables](3.%20ML%20Techniques%20%28Feature%20Engineering%29/7.%20Handing%20Time%20and%20Date%20data/Handling%20Date%20and%20Time%20Variables.ipynb) |
| 🚨 Outliers | [Outlier Detection and Removal using Z-score Method](3.%20ML%20Techniques%20%28Feature%20Engineering%29/8.%20Working%20with%20Outlier/Outlier%20Detection%20and%20Removal%20using%20Z-score%20Method.ipynb) · [Outlier Detection and Removal using the IQR Method](3.%20ML%20Techniques%20%28Feature%20Engineering%29/8.%20Working%20with%20Outlier/Outlier%20Detection%20and%20Removal%20using%20the%20IQR%20Method_.ipynb) · [Outlier Detection using the Percentile Method _ Winsorization Technique](3.%20ML%20Techniques%20%28Feature%20Engineering%29/8.%20Working%20with%20Outlier/Outlier%20Detection%20using%20the%20Percentile%20Method%20_%20Winsorization%20Technique.ipynb) · [Working with Outlier](3.%20ML%20Techniques%20%28Feature%20Engineering%29/8.%20Working%20with%20Outlier/Working%20with%20Outlier.ipynb) |
| 🧩 Feature construction | [Feature Construction _ Feature Splitting](3.%20ML%20Techniques%20%28Feature%20Engineering%29/9.%20Feature%20Construction/Feature%20Construction%20_%20Feature%20Splitting.ipynb) |
| 🎛️ Feature selection | [Chi-Squared For Feature Selection using SelectKBest](3.%20ML%20Techniques%20%28Feature%20Engineering%29/10.%20Feature%20Selection/Chi-Squared%20For%20Feature%20Selection%20using%20SelectKBest.ipynb) · [Feature Selection using SelectKBest & Recursive Feature Elimination (SELF)](3.%20ML%20Techniques%20%28Feature%20Engineering%29/10.%20Feature%20Selection/Feature%20Selection%20using%20SelectKBest%20%26%20Recursive%20Feature%20Elimination%20%28SELF%29.ipynb) · [How does SelectKBest work in Feature Selection](3.%20ML%20Techniques%20%28Feature%20Engineering%29/10.%20Feature%20Selection/How%20does%20SelectKBest%20work%20in%20Feature%20Selection_.ipynb) |

---

## 🚀 Getting started

```bash
git clone https://github.com/ahmadhassan-aiops/machine-learning-algorithms-and-techniques.git
cd machine-learning-algorithms-and-techniques
pip install numpy pandas matplotlib seaborn scikit-learn xgboost mlxtend dtreeviz jupyter
jupyter notebook
```

Many notebooks use scikit-learn's built-in datasets (iris, diabetes, breast cancer, California housing) and run immediately. The others read a CSV from **the same folder as the notebook** — download it and place it next to the notebook.

---

## 🗂️ Datasets

| Dataset | Where to get it |
|---|---|
| Titanic (`train.csv`, `titanic_toy.csv`) | [Kaggle — Titanic](https://www.kaggle.com/c/titanic) |
| Digit Recognizer (`digit-recognizer.zip`) | [Kaggle — Digit Recognizer](https://www.kaggle.com/c/digit-recognizer) |
| `placement.csv`, `Social_Network_Ads.csv`, `cars.csv`, `wine_data.csv`, `concrete_data.csv`, `covid_toy.csv`, `customer.csv`, `data_science_job.csv`, `50_Startups.csv`, `student_clustering.csv`, `ushape.csv`, `weight-height.csv`, `heart.csv`, `orders.csv`, `messages.csv` and the other teaching CSVs | [Kaggle Datasets](https://www.kaggle.com/datasets) — search by file name |
| Built-in: iris, diabetes, breast cancer, California housing | Loaded automatically from `sklearn.datasets` |

---

## 📖 Further reading

- PCA on MNIST — [Kaggle notebook](https://www.kaggle.com/code/nitsin/pca-demo-1/notebook)
- Feature hashing for high-cardinality categories — [article](https://datasciencestunt.com/dealing-with-categorical-features-with-high-cardinality-feature-hashing/)
- Gradient boosting explained — [explained.ai](https://explained.ai/gradient-boosting/index.html)

---

## 🧭 Part of a complete Data Science path

**Python basics → NumPy → Pandas → Matplotlib → Seaborn → Statistics → Machine Learning**

- 🐍 [Python for Data Science](https://github.com/ahmadhassan-aiops/python-for-data-science)
- 🔢 [NumPy](https://github.com/ahmadhassan-aiops/Numpy)
- 🐼 [Pandas](https://github.com/ahmadhassan-aiops/Pandas)
- 📈 [Matplotlib](https://github.com/ahmadhassan-aiops/matplotlib)
- 🎨 [Seaborn](https://github.com/ahmadhassan-aiops/seaborn)
- 📊 [Statistics](https://github.com/ahmadhassan-aiops/statistics-for-data-science)
- 🤖 **Machine Learning** ← you are here

---

## 👨‍🏫 About the author

**Ahmad Hassan** — AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notebooks help you learn, please star the repo — it helps other students find it!
