# 🚀 AI Bootcamp Labs – Week 3

Welcome to **Week 3** of my AI Bootcamp Labs. This section covers data preprocessing pipelines, feature engineering, data augmentation, exploratory data analysis, and outlier detection.

---

# 📂 Structure

```text
Week_3/
├── day-1/
├── day-2/
├── day-3/
└── day-4/
```

# 🎯 Purpose

This week focused on the core techniques needed to prepare and understand data before modeling:

- Building end-to-end preprocessing and modeling pipelines
- Engineering new features and augmenting image/text data
- Performing exploratory data analysis (EDA)
- Detecting and handling outliers robustly

---

### 📌 Day 1 – Data Preprocessing & Modeling Pipelines

#### Titanic Data Preprocessing & Modeling

Worked with the Titanic dataset to practice a full preprocessing-to-modeling workflow.

Activities performed:
- Exploring missing values and visualizing their distribution
- Imputation strategies: deletion, group-median imputation (Age by Pclass), mode imputation (Embarked), missing indicators
- Feature scaling with StandardScaler (z-score) and MinMaxScaler
- Encoding categorical variables using Label Encoding and One-Hot Encoding
- Building preprocessing pipelines with `ColumnTransformer`
- Combining preprocessing and modeling into a single `Pipeline`
- Hyperparameter tuning with `GridSearchCV`
- Evaluating models and inspecting feature importance

**Skills Learned**
- Missing Value Imputation
- Feature Scaling (Standardization & Normalization)
- Categorical Encoding
- Scikit-learn Pipelines & ColumnTransformer
- Hyperparameter Tuning (GridSearchCV)
- Model Evaluation

---

### 📌 Day 2 – Feature Engineering & Data Augmentation

#### Feature Engineering for Tabular Data

Practiced engineering new features from the Titanic dataset, including:
- Extracting titles from names
- Creating family size, is-alone, and fare-per-person features
- Binning Age and Fare into categories
- Deriving deck information from Cabin
- Building interaction features and additional categorical encodings
- Feature selection using `SelectKBest`
- Training and evaluating a model on the engineered feature set

#### Advanced Feature Engineering

- Generating polynomial features
- Dimensionality reduction with PCA and explained variance analysis

#### Data Augmentation for Images & Text

- Basic image augmentation with Keras
- Augmentation using `tf.image`, OpenCV, and Albumentations
- Text data augmentation techniques
- Using augmentation to balance imbalanced classes (MNIST)
- Comparing model performance on imbalanced vs. augmented/balanced data

**Skills Learned**
- Feature Engineering
- Feature Selection
- Polynomial Features & PCA
- Image Augmentation (Keras, tf.image, OpenCV, Albumentations)
- Text Data Augmentation
- Class Imbalance Handling

---

### 📌 Day 3 – Exploratory Data Analysis (EDA)

#### Titanic EDA

Performed an in-depth exploratory analysis of the Titanic dataset.

Activities performed:
- Dataset inspection and summary statistics
- Univariate analysis with histograms, KDE plots, and boxplots
- Categorical value counts and distribution visualizations (class, gender, embarkation, survival)
- Bivariate analysis: survival rate by class, sex, and embarkation port
- Correlation matrix and pairplot analysis
- Outlier detection using Z-score and IQR methods
- Feature engineering for age groups, fare categories, and family size
- EDA challenge analyzing survival patterns by extracted title

**Skills Learned**
- Exploratory Data Analysis (EDA)
- Univariate & Bivariate Analysis
- Data Visualization (Seaborn/Matplotlib)
- Correlation Analysis
- Outlier Detection (Z-score, IQR)

---

### 📌 Day 4 – Outlier Detection & Robust Analysis

#### Advanced Outlier Detection

Worked with a synthetic dataset containing outliers to practice detection and handling techniques.

Activities performed:
- Visualizing distributions, boxplots, and scatter plots to spot outliers
- Implementing Z-score and IQR-based outlier detection
- Comparing statistical measures with and without outliers
- Handling outliers via removal and log transformation
- Correlation analysis before and after outlier removal, including robust (Spearman) correlation
- Multivariate outlier detection and visualization (pair plots, 3D scatter plots)
- Feature profiling to flag potential data issues
- Comparing standard scaling vs. RobustScaler
- Demonstrating the impact of outliers on linear regression
- Interactive exercises covering Isolation Forest and building a custom outlier detection workflow

**Skills Learned**
- Outlier Detection (Z-score, IQR, Isolation Forest)
- Robust Statistics (Spearman Correlation, RobustScaler)
- Multivariate Outlier Analysis
- Feature Profiling
- Impact Analysis on Regression Models

---

# 📚 Week 3 Learning Outcomes

- Scikit-learn Preprocessing & Modeling Pipelines
- Feature Engineering & Selection
- Data Augmentation (Image & Text)
- Exploratory Data Analysis (EDA)
- Outlier Detection & Robust Statistics

---

# 📌 Note

This folder contains my personal bootcamp lab work completed for educational purposes, part of the larger [AI Bootcamp Labs](../README.md) repository.

---

## 👨‍💻 Junior AI Engr

**Soojal Kumar**

Final Year Information Technology Student

Passionate about Artificial Intelligence, Machine Learning, and AgenticAI.