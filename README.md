Titanic Survival Prediction using Machine Learning

 Project Overview

This project focuses on analyzing the famous Titanic dataset and building a machine learning classification model to predict whether a passenger survived the Titanic disaster.

The objective is not only to train a model, but also to understand the complete machine learning workflow, including data exploration, visualization, preprocessing, model training, evaluation, and interpretation of results.



---

 Dataset Information

 Dataset Name: Titanic Dataset
 **Source: Publicly available Titanic dataset
 Total Records: 891 passengers
 Target Variable: `Survived`

   `0` → Passenger did not survive (Died)
   `1` → Passenger survived

Each row in the dataset represents one passenger with demographic and travel-related information.

---

 Project Workflow

The project follows a standard machine learning pipeline:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Visualization
4. Data Preprocessing and Feature Engineering
5. Model Building
6. Model Evaluation
7. Results Interpretation and Conclusion

---

 Exploratory Data Analysis (EDA)

Initial exploration of the dataset was performed to understand:

 Number of rows and columns
 Data types of features
 Presence of missing values
 Summary statistics of numerical features

Key observations:

 Missing values were found in features such as `Age`, `Cabin`, and `Embarked`
 The dataset contains both numerical and categorical variables

---

 Data Visualization

Several visualizations were created to understand survival patterns:

1. Survival Distribution

A bar chart was used to compare the number of passengers who survived versus those who did not.

Observation:

 The majority of passengers did not survive the disaster

 2. Survival by Gender

A grouped bar chart was created showing Died vs Survived on the x-axis and Male vs Female as bars.

Observation:

 Female passengers had a significantly higher survival rate than male passengers
 This reflects the historical evacuation policy of prioritizing women
 3. Age Distribution

A histogram was used to visualize the age distribution of passengers.

Observation:

 Most passengers were young to middle-aged adults
 Children showed relatively better survival chances
 Age is a secondary factor compared to gender

---

 Data Preprocessing

To prepare the data for machine learning, the following steps were performed:

 Handled missing values (e.g., filling missing `Age` values)
 Removed irrelevant or non-informative columns such as `Name`, `Ticket`, and `Cabin`
 Encoded categorical variables such as `Sex` and `Embarked` into numerical form
 Ensured the dataset contained only numerical features suitable for model training

Each preprocessing step was applied to improve model performance and reliability.

---

 Model Building

 The dataset was split into features (X) and target (y)
 Data was divided into training and testing sets
 A classification model was trained to predict passenger survival

 possible outcomes.

---

Model Evaluation

The trained model was evaluated using:

 Accuracy Score
 Confusion Matrix

The confusion matrix was used to analyze:

 Correct predictions
 False positives and false negatives

 Results and Interpretation

 Gender is the strongest predictor of survival
 Passenger class and fare also influence survival chances
 Age plays a secondary role


 Limitations

 The dataset size is relatively small
 The model does not capture all real-world complexities of human behavior during disasters


Conclusion

This project demonstrates the complete machine learning workflow, from raw data exploration to model evaluation and interpretation.

The analysis highlights how demographic and travel-related features influenced survival during the Titanic disaster, and how machine learning models can learn such patterns from labeled data. Tools and Libraries Used
 Python
 Pandas
 Matplotlib
 Scikit-lear


Author

Name: Eklavya vijay

Program: M.Sc Physics (MNIT)
