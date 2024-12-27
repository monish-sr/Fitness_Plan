# Personalized_Fitness_Plan_kNN
This project creates a Fitness Plan Recommendation System using the K-Nearest Neighbors (KNN) algorithm to predict personalized fitness plans based on user data, including fitness goals, activity levels, and dietary preferences. The model is evaluated using a confusion matrix and classification metrics, offering accurate fitness plan recommendations.

## Project Overview
This project builds a Fitness Plan Recommendation System using machine learning to predict the best fitness plan based on user data, including fitness goals, activity level, and dietary preferences. The dataset is preprocessed with label encoding and missing values handling. A K-Nearest Neighbors (KNN) model is trained and evaluated using a confusion matrix and classification report. The system predicts fitness plans like Cardio, Strength, or Mixed Plans, based on user inputs. Implemented in Python with libraries such as Pandas, Scikit-learn, and Matplotlib, this tool helps users find personalized fitness plans tailored to their needs.

## Dataset
The dataset used in this project contains information related to individuals' fitness goals, activity levels, dietary preferences, and the recommended fitness plans based on their profiles. Here, Fitness Goals, Activity Levels, Dietary Preferences are the features of the dataset. Recommended Fitness Plans is the target.

## Execution Plan
The execution plan, of this project follows a series of steps to build a Fitness Plan Recommendation System using machine learning. 

**1. Data Collection & Preprocessing:** The dataset is loaded, categorical variables like Fitness_Goals, Activity_Level, Dietary_Preferences, and Recommended_Plan are label encoded, missing values are checked, and descriptive statistics are calculated to understand the data's structure and potential issues.

**2. Feature Selection:** Relevant features such as Fitness_Goals, Current_Fitness_Metrics, Activity_Level, and Dietary_Preferences are selected as input variables (X), while the Recommended_Plan serves as the target variable (y).

**3. Data Splitting:** The dataset is split into training and testing sets using train_test_split. The model is trained on the training set (80%) and evaluated on the testing set (20%).

**4. Model Training:** A K-Nearest Neighbors (KNN) classifier is chosen as the machine learning model. The KNN algorithm classifies a user’s fitness plan by finding the majority vote of the nearest neighbors based on the input features.

**5. Model Evaluation:** The trained model is evaluated using a confusion matrix, classification report, and heatmap visualization to assess accuracy, precision, recall, and F1-score.

**6. Prediction:** The model is used to predict the fitness plan for a given set of inputs (e.g., fitness goals, activity level). The user can also input their data to get personalized recommendations.

## Results
The KNN model accurately predicted fitness plans, with evaluation results including a confusion matrix showing correct and incorrect classifications, and an overall high accuracy score, demonstrating effective recommendation of personalized fitness plans.
