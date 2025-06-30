#  Task 5: Decision Trees and Random Forests
##  **Objective**
Implement and understand **Decision Tree** and **Random Forest** classifiers using the Heart Disease dataset.  
Key goals:
- Train and visualise decision trees
- Analyze overfitting and control tree depth
- Train a random forest and compare performance
- Interpret feature importances
- Evaluate using cross-validation


##  **Dataset**
- **Name:** Heart Disease Dataset
- **Source:** [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Columns:** Various patient health metrics (age, sex, cp, trestbps, chol, etc.) with **target** as presence of heart disease.


##  **Tools & Libraries**
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

##  **Steps Performed**

1. **Imported Libraries & Dataset**
   - Loaded `heart.csv`
   - Checked null values and dataset info

2. **Exploratory Data Analysis (EDA)**
   - Visualised target class distribution

3. **Train-Test Split**
   - Split data into training (80%) and testing (20%) sets

4. **Decision Tree Classifier**
   - Trained with `max_depth=3`
   - Visualised using `plot_tree`
   - Evaluated accuracy and classification report

5. **Overfitting Analysis**
   - Tested accuracy across depths 1–10
   - Plotted training vs testing accuracy

6. **Random Forest Classifier**
   - Trained with 100 estimators
   - Evaluated accuracy and classification report

7. **Feature Importance**
   - Plotted top features contributing to model performance

8. **Cross-Validation**
   - Performed 5-fold cross-validation to check model generalisation

##  **Results**

| Model            | Accuracy |
|------------------|----------|
| Decision Tree    | ~80%     |
| Random Forest    | ~85%     |
| Cross-Validation | ~83% avg |

