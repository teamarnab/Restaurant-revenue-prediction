# Restaurant Revenue Prediction Project

This project predicts the revenue of a restaurant based on several key features like location, cuisine, customer reviews, and other factors. The goal is to build a machine learning model that provides accurate revenue predictions and offers insights into the most impactful features affecting restaurant revenue.

---

## 📂 Dataset Description

The dataset consists of the following columns:
- **Location**: The geographical location of the restaurant.
- **Cuisine**: The type of cuisine served.
- **Rating**: The overall customer rating of the restaurant.
- **Seating Capacity**: The number of seats available in the restaurant.
- **Average Meal Price**: The average cost of a meal.
- **Social Media Followers**: The number of followers on social media platforms.
- **Chef Experience Years**: Years of experience of the head chef.
- **Number of Reviews**: Total reviews submitted by customers.
- **Avg Review Length**: Average length of customer reviews.
- **Ambience Score**: A score representing the ambience of the restaurant.
- **Service Quality Score**: A score representing the quality of service.
- **Parking Availability**: Whether parking is available (Yes/No).
- **Weekend Reservations**: The number of reservations on weekends.
- **Weekday Reservations**: The number of reservations on weekdays.
- **Revenue**: The target variable (restaurant revenue).

---

## 🛠️ Project Workflow

### 1. **Exploratory Data Analysis (EDA)**:
   - Analyzed data distributions, patterns, and correlations.
   - Visualized relationships between features and revenue using plots.

### 2. **Data Preprocessing**:
   - Handled missing values and outliers.
   - Encoded categorical features such as `Cuisine` and `Parking Availability`.
   - Normalized/Standardized numerical features.

### 3. **Feature Engineering**:
   - Selected important features based on their correlation with revenue.
   - Created additional features for better predictions.

### 4. **Model Training and Evaluation**:
   - Trained multiple regression models including:
     - **Linear Regression**
     - **Random Forest Regressor**
     - **Gradient Boosting Regressor**
     - **XGBoost Regressor**
   - Evaluated models using metrics such as:
     - Mean Squared Error (MSE)
     - Mean Absolute Error (MAE)
     - \( R^2 \) Score

### 5. **Results and Insights**:
   - Identified key features driving revenue predictions.
   - Compared model performance to select the best one.

---

## 📊 Results

- The best-performing model achieved an \( R^2 \) score of **X.XX** and a Mean Squared Error (MSE) of **XX.XX**.
- Top 3 influential features on revenue:
  1. **Average Meal Price**
  2. **Rating**
  3. **Number of Reviews**

---

## 🛠️ Tools and Libraries Used

- **Programming Language**: Python
- **Libraries**:
  - Pandas, NumPy (Data manipulation and analysis)
  - Matplotlib, Seaborn (Data visualization)
  - Scikit-learn, XGBoost (Modeling and evaluation)

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/restaurant-revenue-prediction.git
   cd restaurant-revenue-prediction
   ```
2. Install dependencies:
   ``` bash
   pip install -r requirements.txt  
   ```
3. Run the notebook:
  Open the Jupyter Notebook file (resturant_revenue_prediction.ipynb).
  Execute the cells to see the data analysis, model training, and evaluation.



🤝 Contribution
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
