![Screenshot 2024-10-13 165054](https://github.com/user-attachments/assets/5f90f840-c642-450b-9bf8-9356749e96c5)

# Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

This project performs data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The analysis helps us understand patterns, trends, and relationships between variables that influenced the survival of passengers on the Titanic.

## Dataset

The Titanic dataset is available on [Kaggle](https://www.kaggle.com/c/titanic/data), which includes information about the passengers such as age, gender, class, fare, and whether they survived the Titanic disaster.

---

## Steps Included in the Project

### 1. Data Cleaning
- **Handling Missing Values**:
  - Missing `Age` values are imputed using the median age.
  - Missing `Embarked` values are filled with the most frequent embarkation port (mode).
  - The `Cabin` column is dropped due to excessive missing values.

- **Fixing Data Types**:
  - The `Pclass` and `Survived` columns are converted to categorical variables for easier analysis.

### 2. Exploratory Data Analysis (EDA)

EDA helps uncover trends, relationships, and patterns in the data. Below are the visualizations and insights gained from the Titanic dataset:

#### 2.1. Survival Distribution
- Visualizes the overall survival distribution.
- Shows that ~38% of passengers survived, while ~62% did not.

#### 2.2. Age Distribution
- A histogram shows the distribution of passenger ages.
- The dataset contains a higher concentration of younger passengers, and the age distribution is right-skewed.

#### 2.3. Survival Rate by Passenger Class
- First-class passengers had the highest survival rates.
- Third-class passengers had the lowest survival rates, reflecting socio-economic inequalities in survival outcomes.

#### 2.4. Survival Rate by Gender
- Female passengers had a much higher survival rate than males.
- The gender disparity is significant, likely due to the "women and children first" evacuation policy.

#### 2.5. Age vs. Survival
- A boxplot shows that younger passengers, particularly children, had better survival chances than older passengers.

#### 2.6. Survival Rate by Gender and Class
- First-class females had the highest survival rate, while third-class males had the lowest survival rate.

#### 2.7. Fare Distribution
- Passengers who paid higher fares were more likely to survive, suggesting wealthier passengers had better access to safety measures.

#### 2.8. Correlation Heatmap
- Visualizes correlations between numerical variables like `Age`, `Fare`, etc.
- The heatmap shows no strong correlation between age and survival, but a positive correlation between fare and survival.

---

## Key Insights from the Analysis

1. **Survival Distribution**:
   - Around 38% of passengers survived the disaster.
   
2. **Age Distribution**:
   - Younger passengers were more likely to survive compared to older passengers.
   
3. **Survival by Class**:
   - First-class passengers had a significantly higher chance of survival compared to second and third class.
   
4. **Survival by Gender**:
   - Female passengers had a much higher survival rate than male passengers.

5. **Fare**:
   - Passengers who paid higher fares had better survival rates, indicating potential advantages for wealthier individuals during the evacuation.

6. **Family Size**:
   - Passengers who were traveling alone had a lower survival rate.

---

## Requirements

To run the analysis in this project, you need the following libraries:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

Install them via pip:

```bash
pip install pandas numpy seaborn matplotlib

