#  Zomato Restaurant Analytics & Cost Prediction

An end-to-end data science project that analyses Zomato restaurant data to uncover trends across ratings, cuisines, costs and locations, and uses regression models to predict a restaurant's **cost per plate**. The best model is deployed as an interactive **Streamlit** web app for real-time predictions.


##  Table of Contents

- [Overview](#-overview)
- [Objectives](#-objectives)
- [Tech Stack](#-tech-stack)
- [Dataset](#-dataset)
- [Project Workflow](#-project-workflow)
- [Model Performance](#-model-performance)
- [Key Insights](#-key-insights)
- [Project Structure](#-project-structure)
- [Installation & Usage](#-installation--usage)
- [Streamlit App](#-streamlit-app)
- [Future Improvements](#-future-improvements)
- [Author](#-author)


## Overview

Restaurant pricing depends on many factors: location, cuisine, ratings, service type and more. This project explores those relationships in Zomato's restaurant data and builds a machine learning model that estimates the cost per plate for a restaurant from its attributes.

## Objectives

- Clean and preprocess raw Zomato restaurant data
- Perform exploratory data analysis (EDA) to find patterns across ratings, cuisines, costs and locations
- Build and compare multiple regression models to predict cost per plate
- Deploy the best-performing model as a Streamlit application for real-time predictions
- Visualise key findings in an interactive Tableau dashboard

## Tech Stack

| Category | Tools |
| Language | Python |
| Data Analysis | Pandas, NumPy, SQL |
| Visualisation | Matplotlib, Seaborn, Tableau |
| Machine Learning | Scikit-learn |
| Deployment | Streamlit |

## Dataset

- **Source:** [add source, e.g. Kaggle dataset link]
- **Size:** [number of rows] restaurants × [number of columns] features
- **Key features:** [e.g. restaurant name, location, cuisines, rating, votes, online ordering, table booking, cost for two]
- **Target variable:** Cost per plate

## Project Workflow

### 1. Data Cleaning & Preprocessing
- Handled missing values and duplicate records
- Standardised column formats and data types
- Encoded categorical variables and scaled numerical features where required
- [Add any feature engineering you did]

### 2. Exploratory Data Analysis
- Analysed how ratings, cuisines and locations relate to cost
- Compared restaurant density and pricing across areas
- Identified the most popular cuisines and highest-rated categories
- Explored correlations between features and the target variable

### 3. Model Building & Evaluation
Built and compared multiple regression models:

- [Linear Regression]
- [Random Forest Regressor]
- [Decision Tree / Gradient Boosting / XGBoost, etc.]

Models were evaluated with [R², MAE, RMSE] on a held-out test set.

### 4. Deployment
The best model was saved with `[pickle / joblib]` and served through a Streamlit app that takes restaurant details as input and returns the predicted cost per plate.

## Model Performance

| Model | R² Score | MAE | RMSE |

| [Model 1] | [ ] | [ ] | [ ] |
| [Model 2] | [ ] | [ ] | [ ] |
| **[Best Model]** | **[ ]** | **[ ]** | **[ ]** |

## Key Insights

- [e.g. Restaurants in X locations have significantly higher average costs]
- [e.g. Cuisine type strongly influences price]
- [e.g. Online ordering and table booking are associated with higher-rated restaurants]
- [Add 3–5 findings from your own analysis]

## Project Structure

Zomato_ML_Project/
│
├── data/                  # Raw and cleaned datasets
├── notebooks/             # EDA and model-building notebooks
├── models/                # Saved trained model(s)
├── app.py                 # Streamlit application
├── requirements.txt       # Python dependencies
└── README.md
```

> Update this tree to match the actual repository layout.

##  Installation & Usage

**1. Clone the repository**
```bash
git clone https://github.com/VaradKongari03/Zomato_ML_Project.git
cd Zomato_ML_Project

**2. Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

**3. Install dependencies**
```bash
pip install -r requirements.txt

**4. Run the notebook**
```bash
jupyter notebook

**5. Launch the Streamlit app**
```bash
streamlit run app.py

## Streamlit App

The app lets users enter restaurant details such as [location, cuisine, rating, online ordering, table booking] and instantly get a predicted cost per plate.

<!-- Add a screenshot or GIF of the app: -->
<!-- ![App Screenshot](images/app_screenshot.png) -->

**Live demo:** [add link if deployed]

## Future Improvements

- Try advanced models such as XGBoost or LightGBM with hyperparameter tuning
- Add NLP-based features from customer reviews
- Extend the app with restaurant recommendations
- Deploy on Streamlit Community Cloud or Hugging Face Spaces

## Author

**[Vivek Jayant]**
- LinkedIn: [profile link]
- GitHub: [profile link]
- Email: [your email]


