# 👨‍💼👨‍💼 Application of Data Science to Reduce Employee Attrition 👨‍💼👨‍💼

![shutterstock_1696263217_edited](https://github.com/user-attachments/assets/71c6b958-801e-46dd-98c4-2f1b0a78ded1)
Employee attrition is a critical issue for organizations, and this project aims to address it using Data Science and Analytics. By analyzing IBM datasets from open sources, we seek to understand employee profiles and identify patterns leading to attrition. Data mining techniques will be employed to predict potential attrition, enabling managers to take proactive measures. The objective is to apply Data Science techniques to analyze and mitigate employee attrition in different scenarios.




## 🛑 Dataset Description 🛑

This dataset presents an employee survey from IBM, indicating whether there is attrition. With approximately 24,000 entries, the model is expected to provide modest improvement in identifying attrition compared to random probability allocation.

While some attrition is inevitable, minimizing it and preparing for unavoidable cases can enhance business operations. In the future, a larger dataset could be used for employee segmentation to identify "at-risk" categories, providing deeper insights into the drivers of attrition beyond what informational interviews can offer.

**👉 Target Feature(Categorical) :** `Attrition`

**👉 Categorical Features :** `Business Travel`, `Department`, `EducationField`, `Gender`, `JobRole`,  `MaritalStatus`, `Over18`, `OverTime`, `Employee Source.`
                          
**👉 Numerical Features :** `Age`, `DailyRate`, `DistanceFromHome`, `Education`, `EmployeeCount` ,` EmployeeNumber`, 
                        `Application ID`, `EnvironmentSatisfaction`,` HourlyRate`, `JobInvolvement`, `JobLevel`,
                        `JobSatisfaction`, `MonthlyIncome`, `MonthlyRate`, `NumCompaniesWorked`, `PercentSalaryHike`,
                        `PerformanceRating`, `RelationshipSatisfaction`, `StandardHours`, `StockOptionLevel`,
                        `TotalWorkingYears`, `TrainingTimesLastYear`, `WorkLifeBalance`, `YearsAtCompany`,
                        `YearsInCurrentRole`, `YearsSinceLastPromotion`, `YearsWithCurrManager`

👉 link  [ 🔗IBM_Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
## 🛑 Data Preprocessing 🛑

👉 **Exploratory Data Analysis (EDA):**
   - Visualized data using catplots, pie charts, and bar plots to understand feature distributions and relationships.

👉 **Data Cleaning:**
   - Removed irrelevant features.
   - Handled missing values appropriately.

👉 **Feature Engineering:**
   - Applied label encoding and one-hot encoding to categorical variables.

👉 **Model Evaluation:**
   - Used ROC and AUC metrics to evaluate model performance.

## 🛑 Libraries Used 🛑

👉 This project utilizes the following libraries:

- **Pandas**: Data manipulation.
- **Numpy**: Numerical operations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning, preprocessing, and evaluation.
  - Models: `LogisticRegression`, `GaussianNB`, `DecisionTreeClassifier`, `RandomForestClassifier`, `AdaBoostClassifier`, `GradientBoostingClassifier`, `KNeighborsClassifier`, `XGBClassifier`
  - Preprocessing: `StandardScaler`, `LabelEncoder`, `OneHotEncoder`
  - Sampling: `SMOTE`
  - Metrics: `accuracy_score`, `f1_score`, `roc_auc_score`, `roc_curve`, `classification_report`
  - Feature Selection: `RFE`, `SequentialFeatureSelector`
- **Statsmodels**: Statistical modeling.
- **Scipy**: Scientific computing.
- **Warnings**: Suppressing warnings.

👉 Additional settings:
- Display settings for DataFrame.
- Plot size adjustments.

## 🛑 Installation 🛑

👉 Clone the repository:

```bash
   git clone https://github.com/Bineet117/Employee-Attrition-Project.git
```

👉 To install required libraries:

```bash
  pip install -r requirements.txt
```
 

    
## 🛑 Model Performance 🛑

<div style="display:flex; justify-content:space-between;">
  <img src="https://github.com/user-attachments/assets/851175b0-0f63-4669-9efc-bdaeef8d0d8b" alt="Screenshot 1" width="400"/>
  <img src="https://github.com/user-attachments/assets/2fcf1cec-f936-4e61-b8b7-9586d1f1c4e1" alt="Screenshot 2" width="400"/>
</div>
Using several models, the XGBoost classifier provided the best results with:

👉 **Train Accuracy**: 99.98%    
👉 **Test Accuracy**: 99.81%

![output](https://github.com/user-attachments/assets/329fe168-1307-4f58-b7b5-3be6c9e98504)
👉 **ROC_AUC** 


## 🛑 Contact_Information 🛑
👉 For any questions or feedback, please contact me at bineetgupta117@gmail.com📧.
