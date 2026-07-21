# 🚀 AI Bootcamp Labs – Week 1

Welcome to **Week 1** of my AI Bootcamp Labs. This section covers the setup of my development environment, Python fundamentals, my first steps into data analysis with Pandas, and an introduction to time-series forecasting with LSTMs.

---

# 📂 Structure

```text
Week_1/
├── day-1/
├── day-2/
├── day-3/
└── day-4/
```

# 🎯 Purpose

This week focused on building the foundations needed for the rest of the bootcamp:

- Setting up a productive Python development environment
- Practicing core Python programming concepts
- Getting hands-on with real-world data using Pandas
- Building a first deep learning model for time-series forecasting

---

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

### 📌 Day 4 – Time Series Forecasting with LSTM

#### PM2.5 Air Quality Forecasting

Built an LSTM-based deep learning model to forecast PM2.5 air quality levels using the Beijing PRSA weather dataset.

Activities performed:
- Loading and cleaning the PRSA dataset (dropping rows with missing `pm2.5`, `TEMP`, or CO values)
- Selecting relevant features (CO, temperature, PM2.5)
- Normalizing features using `MinMaxScaler` and saving the scaler with `joblib`
- Creating time-series sequences (24-hour windows) for supervised learning
- Splitting data into training and test sets
- Building a Sequential LSTM model with a `Dense` output layer
- Training the model with `EarlyStopping` to prevent overfitting
- Saving the trained model in Keras format
- Loading the saved model and generating predictions on the test set

**Skills Learned**
- Time Series Forecasting
- LSTM (Long Short-Term Memory) Networks
- TensorFlow / Keras
- Sequence Generation for Time Series
- Feature Scaling (MinMaxScaler)
- Model Persistence (saving/loading models & scalers)
- EarlyStopping & Overfitting Prevention

---

# 📚 Week 1 Learning Outcomes

- Python Environment Setup (Conda, VS Code, Jupyter)
- Core Python Programming
- Dictionary Operations, Loops & Functions
- Data Analysis Fundamentals with Pandas
- CSV Processing & Data Cleaning
- Time Series Forecasting with LSTM
- Deep Learning with TensorFlow/Keras

---

# 📌 Note

This folder contains my personal bootcamp lab work completed for educational purposes, part of the larger [AI Bootcamp Labs](../README.md) repository.

---

## 👨‍💻 Junior AI Engr

**Soojal Kumar**

Final Year Information Technology Student

Passionate about Artificial Intelligence, Machine Learning, and AgenticAI.