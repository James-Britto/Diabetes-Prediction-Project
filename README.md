# Diabetes Prediction Project

**Objective:** To create a supervised machine learning model to predict whether a person has diabetes or not using a set of features.

#### Introduction:
Diabetes is a disease that occurs when your blood glucose, also called blood sugar, is too high. Blood glucose is your main source of energy and comes from the food you eat. Insulin, a hormone made by the pancreas, helps glucose from food get into your cells to be used for energy. Sometimes your body doesn’t make enough — or any — insulin or doesn’t use insulin well. Glucose then stays in your blood and doesn’t reach your cells.

According to WHO about 422 million people worldwide have diabetes. Since diabetes affects a large population across the globe and the collection of these datasets is a continuous process and it comprises of various patient related attributes such as age, gender, symptoms, insulin levels, blood pressure, blood glucose levels, weight etc. We are working on Pima Indians Diabetes Dataset (PIDD), extracted from the University of California, Irvine (UCI) machine learning repository.

#### Feature Description:
1. Pregnancies : Number of times pregnant
2. Glucose: Oral Glucose Tolerance Test result
3. BloodPressure: Diastolic Blood Pressure values in (mm Hg)
4. SkinThickness: Triceps skin fold thickness in (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index
7. DiabetesPedigreeFunction: Diabetes pedigree function
8. Age: Age in years
9. Outcome: Class 1 indicates person having diabetes and 0 indicates other.

**Data Outline:**
   - The dataset has total 768 observations and 8 feature columns and a targe variable 'Outcome'.
   - It has 2 float datatypes and 7 int datatypes feature columns.

**Insights:**
  - On an average a person had 3 Pregnancies
  - The average glucose level of a person is 120 which is just above the normal level of 70-110. The Maximum glucose level goes upto 199.
  - The average Blood Pressure of a person is 69 which is below than normal level of 80.
  - 50% of the people had skin thickness of 23mm.
  - The average Insulin level of a person is 79 which is beyond the optimum level of 2 to 20 mlU/mL
  - The average age of a person from this data is 33 and the maximum age is 81.
  - The changes of having diabetes is less when the number of pregnancies count is less than 2. The possibility of having diabetes increases as the number of pregnancies increases.
  - People with less BMI (<30) and skin thickness (<40) are more likely to have the diabetes.
  - People with Glucose level of less than 100 and Blood Pressure less than 80 have higher change to be a diabetic patient. People with Glucose level of greater than 160 less likely to be a diabetes patient.
  - People between age 22 to 30 and having DPF (Diabetes Pedigree Function) of <1 were more susceptable to the diabetes.

### Summary:

   - Imported the necessary modules for the project and checked the outline of the data.
   - Performed exploratory analysis to **visualize the distribution of the different features and to identify the relationship between multiple features.**
   - Performed preprocessing steps to **treat the missing values and Outliers**
   - Used multiple feature selection techniques to find the most important features from the available features.
   - Used **SMOTE over sampling method** to treat the **imbalance nature of the dataset.**
   - Used <font color='green'>**6 Models (Logistic Regression, KNN, Random Forest, XGBoost, Decision Tree and SVM)**</font> to find the best model for predicting the Diabetes Outcome.
   - Evauleted the performance of the various models using **Accuracy, Precision, Recall and F1-Score.**
   - Based on the Performance Evaluation, it was found that **SVM Classifier.** performed well in predicting the Diabetes Outcome.
   - Based on the activities performed, concluding that <font color='green'>**SVM is the best model for predicting (Average Recall Score - 96% ) the Diabetes Outcome as an individual model.**



