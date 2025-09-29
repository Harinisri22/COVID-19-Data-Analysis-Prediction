# COVID-19 Data Analysis and Prediction using Machine Learning

## 📌 Project Summary
A complete data-science workflow that analyzes COVID-19 trends across Indian States/UTs and predicts future cases using multiple machine-learning models.

---

## 🗂️ Dataset
* Daily COVID-19 records for all Indian States/UTs  
* Key columns: **Date**, **State/UT**, **Total Confirmed**, **Deaths**, **Recovered**, **New Cases**, **New Deaths**, **New Recovered**  
* Covers a continuous time period with daily updates

---

## 🎯 Project Goals
* **Analyze** trends in confirmed, recovered, death, and active cases  
* **Predict** Total Cases, New Cases, and Active Cases with high accuracy (target ≥ 95 % R²)

---

## 🛠️ Steps & Workflow
1. **Data Exploration**  
   * Checked dataset shape, info, missing values, duplicates  
2. **Data Cleaning & Feature Engineering**  
   * Fixed negative values  
   * Converted `Date` column to datetime  
   * Created new features: `Active Cases`, `Month`, `Day`  
3. **Exploratory Data Analysis (EDA)**  
   * Correlation heatmap  
   * Daily & monthly trend graphs  
   * Top states by cases  
   * Death vs. recovery comparisons, death-rate by state, active-case distribution  
4. **Machine Learning**  
   * Train/test split (80 % / 20 %)  
   * Models: **Random Forest**, **Gradient Boosting**, **Linear Regression**  
   * Preprocessing: Label Encoding, Standard Scaling  
   * Metrics: **MAE**, **MSE**, **R² Score**  
   * Automatic best-model selection  
5. **Results & Insights**  
   * Strong correlation between total cases, deaths, and recoveries  
   * Clear temporal trends (“waves”)  
   * Random Forest and Gradient Boosting delivered best predictive performance  

---

## 🧩 Key Findings
* States such as Maharashtra and Tamil Nadu showed the highest case counts  
* Time-series plots revealed distinct pandemic waves  
* Achieved strong predictive accuracy (close to 95 % R² despite real-world noise)

---

## 🛡️ Tools & Libraries
* **Language/IDE**: Python 3.x, Jupyter Notebook / VS Code  
* **Core Libraries**:  
  `pandas`, `numpy`, `matplotlib`, `seaborn`  
* **Machine Learning**:  
  `scikit-learn` (RandomForestRegressor, GradientBoostingRegressor, LinearRegression, train_test_split, LabelEncoder, StandardScaler, metrics)

---

## 📈 Skills Demonstrated
* Data Cleaning & Preprocessing  
* Feature Engineering  
* Data Visualization & Insight Generation  
* Machine Learning Model Building & Evaluation  
* Interpretation of Real-World Noisy Data

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
