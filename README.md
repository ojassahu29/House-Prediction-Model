#  House Price Prediction

##  Overview
This project predicts house prices using machine learning based on features such as income, location, population, and housing characteristics.

It uses the **California Housing Dataset** and implements a **Linear Regression model**.

---

## Features
- Data exploration and visualization
- Handling missing values
- Feature normalization (StandardScaler)
- Train-test split
- Linear Regression model training
- Evaluation using MSE and R² score
- Visualization of predictions

---

##  Dataset
The dataset is automatically loaded using `sklearn.datasets`.

It includes features like:
- Median Income (`MedInc`)
- House Age (`HouseAge`)
- Average Rooms (`AveRooms`)
- Population
- Latitude & Longitude

Target:
- House Price (`PRICE`)

---

##  Installation

Install required libraries:

    pip install pandas scikit-learn matplotlib seaborn

---

##  How to Run

1. Clone the repository:

    git clone https://github.com/your-username/house-price-prediction.git
    cd house-price-prediction

2. Run the script:

    python house_price.py

---

##  Workflow

1. Load dataset  
2. Explore data (summary, distributions, correlations)  
3. Handle missing values  
4. Normalize features  
5. Split into training and testing sets  
6. Train Linear Regression model  
7. Evaluate performance  
8. Visualize results  

---

##  Model Used

### 🔹 Linear Regression
- Simple and interpretable model  
- Assumes linear relationship between features and target  
- Good baseline for regression problems  

---

##  Evaluation Metrics

- Mean Squared Error (MSE)
- R² Score

Example result:
- MSE ≈ 0.55  
- R² ≈ 0.57  

---

##  Visualizations
- Price distribution histogram  
- Feature correlation heatmap  
- Actual vs Predicted scatter plot  

---

##  Example Output

Input:
    Sample housing features from dataset

Output:
    Predicted Price: ~4.15

---

##  Limitations
- Linear Regression may underfit complex relationships  
- Dataset has capped values (price max = 5.0)  
- Does not capture non-linear patterns  

---

##  Future Improvements
- Use Polynomial Regression  
- Try Random Forest / Gradient Boosting  
- Feature engineering for better accuracy  
- Hyperparameter tuning  

---

##  Author
Ojas Sahu
