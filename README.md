# 🚀 AI Bootcamp Labs

Welcome to my **AI Bootcamp Labs Repository**. This repository contains the hands-on lab work I completed during my AI Bootcamp. 
The labs cover Python programming, data analysis, machine learning fundamentals, deep learning, and data visualization using 
industry-standard tools and libraries.

---
# 📂 Repository Structure

```text
AI_Bootcamp/
│
├── Week_1/
│   ├── day-1/
│   ├── day-2
|   |-- day-3/
│   └── day-4/
│
├── Week_2/
│   ├── day-1/
│   ├── day-2/
│   └── day-4/
|
├── Week_3
|   |-- day-1/
│   ├── day-2/
|   |-- day-3/
│   └── day-4/
└── README.md
```

# 🎯 Purpose

This repository documents my hands-on learning journey throughout an AI Bootcamp. It contains laboratory exercises, coding practice, and practical implementations of concepts in Python, Data Analysis, Machine Learning, Deep Learning, and Data Visualization.

The primary goal of this repository is to:

- Practice AI and Data Science concepts through real-world lab exercises.
- Build a strong foundation in Python and machine learning.
- Document my progress and continuous learning.
- Showcase practical skills and projects to recruiters and the developer community.

## 📅 Week 1

### 📌 Day 1 – Development Environment Setup

#### Lab 1: Conda Environment
In this lab, I learned how to:
- Install Anaconda
- Create and manage Conda environments
- Install Python packages
- Activate and deactivate environments
- Manage project dependencies

#### Lab 2: Visual Studio Code Setup
Topics covered:
- Installing Visual Studio Code
- Configuring the Python interpreter
- Installing Python extensions
- Running Jupyter Notebooks
- Setting up a productive development environment

**Skills Learned**
- Conda
- VS Code
- Python Environment Management
- Jupyter Notebook

---

### 📌 Day 2 – Python Fundamentals

#### Dictionary Practice
Topics covered:
- Creating dictionaries
- Accessing values
- Updating dictionaries
- Removing items
- Dictionary methods
- Nested dictionaries
- Iterating through dictionaries

#### Python Practice Exercises
Worked on:
- Variables
- Data Types
- Lists
- Tuples
- Dictionaries
- Conditional Statements
- Loops
- Functions

**Skills Learned**
- Core Python
- Problem Solving
- Dictionary Operations
- Loops
- Functions

---

### 📌 Day 3 – Data Analysis with Pandas

#### Weather Dataset Analysis

Activities performed:
- Reading CSV files
- Exploring datasets
- Filtering data
- Selecting columns
- Descriptive statistics
- Data cleaning
- Data inspection

**Skills Learned**
- Pandas
- Data Analysis
- Data Cleaning
- CSV Processing

---


# 📅 Week 2

### 📌 Day 1 – Pandas Advanced Operations

#### DataFrame Basics

Topics covered:
- Creating DataFrames
- Reading datasets
- Data selection
- Indexing
- Statistical summaries
- Data inspection

#### Handling Missing Data

Worked on:
- Detecting missing values
- Filling missing values
- Replacing missing values
- Dropping null values

#### Merge Operations

Practiced:
- Inner Join
- Left Join
- Right Join
- Outer Join
- Merging multiple datasets

#### Concatenation

Topics covered:
- Combining DataFrames
- Appending rows
- Concatenating datasets

#### GroupBy Operations

Practiced:
- Data grouping
- Aggregate functions
- Summary statistics

#### Pivot Tables

Topics covered:
- Pivot Tables
- Data summarization
- Reshaping data

**Skills Learned**
- Pandas
- Data Cleaning
- Data Transformation
- Data Aggregation
- Exploratory Data Analysis (EDA)

---

### 📌 Day 2 – NumPy & Data Visualization

#### NumPy Practice

Topics covered:
- NumPy arrays
- Mathematical operations
- Broadcasting
- Matrix operations
- Statistical functions

#### Data Visualization

Created visualizations using:
- Line Charts
- Bar Charts
- Scatter Plots
- Histograms

#### Pandas Hands-on Exercises

Performed additional practice using real-world datasets.

**Skills Learned**
- NumPy
- Matplotlib
- Data Visualization
- Numerical Computing

---

---

### 📌 Day 4 – FastAPI REST API Development

#### To-Do List REST API

Built a RESTful API using **FastAPI** to manage a simple To-Do List application without using a database.

#### Activities Performed

- Created a FastAPI project
- Built RESTful API endpoints
- Created new tasks
- Retrieved all tasks
- Retrieved a task by ID
- Updated existing tasks
- Deleted tasks
- Stored data in an in-memory Python list
- Implemented request validation using Pydantic
- Tested APIs using Swagger UI
- Tested API endpoints using Postman

#### API Endpoints

- **POST** `/todos` – Create a new task
- **GET** `/todos` – Retrieve all tasks
- **GET** `/todos/{id}` – Retrieve a task by ID
- **PUT** `/todos/{id}` – Update an existing task
- **DELETE** `/todos/{id}` – Delete a task

**Skills Learned**

- FastAPI
- REST API Development
- CRUD Operations
- HTTP Methods (GET, POST, PUT, DELETE)
- Pydantic Models
- Request Validation
- API Testing with Swagger UI
- API Testing with Postman

---

# 📅 Week 3

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

# 📚 Learning Outcomes

Throughout these labs, I gained practical experience in:

- Python Programming
- Data Analysis
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering & Selection
- Data Augmentation (Image & Text)
- Outlier Detection & Robust Analysis
- Machine Learning Fundamentals
- Scikit-learn Pipelines & Hyperparameter Tuning
- Deep Learning Basics
- Time Series Forecasting
- REST API Development
- FastAPI Framework
- CRUD Operations
- API Testing with Swagger UI
- API Testing with Postman
- Working with Real-World Datasets


---

# 📌 Note

This repository contains my personal bootcamp lab work completed for educational purposes. Every notebook represents practical exercises performed during the AI Bootcamp to strengthen my understanding of Artificial Intelligence, Machine Learning, Data Science, and Python programming.

---

## 👨‍💻 Junior AI Engr

**Soojal Kumar**

Final Year Information Technology Student

Passionate about Artificial Intelligence, Machine Learning, and AgenticAI.

---
⭐ If you found this repository helpful, feel free to give it a star!