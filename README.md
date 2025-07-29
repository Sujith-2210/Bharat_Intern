# SmartML_Projects

This repository contains two beginner-friendly yet impactful machine learning projects developed in Jupyter Notebooks. Each project is self-contained and includes all necessary datasets for training and testing. The main objective is to demonstrate real-world applications of supervised and recommendation-based learning models.

---

## 📁 Projects Included

### 1. 🏠 House Price Prediction System

**Notebook:** `House-Price-Prediction-System.ipynb`  
**Dataset:** `house_price_data_1000.csv`

#### 📌 Objective:
To predict the sale price of a house based on various features like number of bedrooms, square footage, location, etc.

#### 🔧 Techniques Used:
- Data preprocessing (handling missing values, feature encoding)
- Exploratory Data Analysis (EDA)
- Feature selection
- Model training using:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Model evaluation using RMSE and R² Score

#### 📊 Output:
The notebook outputs the best-performing model and its metrics along with price predictions for sample inputs.

---

### 2. 🎬 Movie Recommendation System

**Notebook:** `Movie-Recommendation-System.ipynb`  
**Datasets:** `movies.csv`, `ratings.csv`

#### 📌 Objective:
To build a system that recommends movies to users based on their preferences and past ratings.

#### 🔧 Techniques Used:
- User-item interaction matrix
- Cosine similarity for collaborative filtering
- Content-based filtering using genres
- Hybrid recommendation (optional)

#### 📊 Output:
A list of top recommended movies for a given user or based on a movie title input.

---

## 📂 Folder Structure
```bash

SmartML_Projects/
│
├── House-Price/
│ ├── House-Price-Prediction-System.ipynb
│ └── house_price_data_1000.csv
│
├── Movie-Recommendation/
│ ├── Movie-Recommendation-System.ipynb
│ ├── movies.csv
│ └── ratings.csv
│
└── README.md
```
---

## 💡 How to Run

1. Clone this repository:
``` bash
git clone https://github.com/Sujith-2210/SmartML_Projects.git
```

2. Open the `.ipynb` files using Jupyter Notebook or Google Colab.

3. Run all cells to train and test the models.

---
