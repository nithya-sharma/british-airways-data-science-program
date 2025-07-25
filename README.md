# British Airways Data Science Virtual Experience

This project is part of the British Airways Data Science Virtual Experience Program on Forage. It focuses on gaining insights from customer reviews and predicting customer booking behavior using real-world data science techniques.

## 📌 Project Overview

The project is divided into two main parts:

1. **Web Scraping for Customer Sentiment Insights**  
   Scrapes and analyzes customer reviews of British Airways to identify common sentiment trends and themes.

2. **Predicting Customer Buying Behavior**  
   Builds machine learning models to predict whether a customer will complete a booking, based on user interaction data.

---

## Notebooks

### 1. Web Scraping for Company Insights

- **Notebook:** `british_airways_Web_scraping_to_gain_company_insights.ipynb`  
- **Description:**  
  Extracts and cleans customer reviews from AirlineQuality.com. Performs sentiment analysis using VADER and visualizes word clouds and sentiment distribution.

#### 🔧 Techniques Used:
- Web scraping using `requests` and `BeautifulSoup`
- Text preprocessing
- Sentiment analysis with VADER
- Word cloud & pie chart visualization

[👉 Open in Colab](https://colab.research.google.com/github/nithya-sharma/British-Airways-Data-Science-virtual-experience-programme/blob/main/british_airways_Web_scraping_to_gain_company_insights.ipynb)

---

### 2. Predicting Customer Buying Behavior

- **Notebook:** `british_airways_Predict_customer_buying_behaviour.ipynb`  
- **Description:**  
  Predicts the likelihood of a customer completing their booking using a machine learning pipeline involving data preprocessing, feature selection, and model training.

#### 🔧 Techniques Used:
- Data preprocessing and feature encoding
- Exploratory Data Analysis (EDA)
- Mutual Information for feature selection
- Model building with Random Forest and XGBoost
- Accuracy and confusion matrix evaluation

[👉 Open in Colab](https://colab.research.google.com/github/nithya-sharma/British-Airways-Data-Science-virtual-experience-programme/blob/main/british_airways_Predict_customer_buying_behaviour.ipynb)

---

## Installation

To run the notebooks locally, ensure the following packages are installed:

```bash
pip install requests beautifulsoup4 pandas nltk vaderSentiment seaborn matplotlib xgboost scikit-learn
