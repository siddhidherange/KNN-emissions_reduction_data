# Emissions Reduction Classification using K-Nearest Neighbors (KNN)

This project applies the **K-Nearest Neighbors (KNN)** algorithm to classify environmental data points into categories based on their potential for emissions reduction.

## Project Overview
The goal is to build a predictive model that identifies whether a specific set of environmental and technological factors will lead to a successful emission reduction (binary classification).

## Dataset
The project utilizes the `emissions_reduction_data.csv` dataset, which contains 10,000 records with the following features:
* **energy_efficiency**: Measurement of how effectively energy is being used.
* **renewable_ratio**: The proportion of energy derived from renewable sources.
* **technology_cost**: The cost associated with the technology being implemented.
* **emission_reduction**: The target variable (0 or 1) indicating whether an emission reduction occurred.

## How it Works: K-Nearest Neighbors
The KNN algorithm classifies a data point by looking at the 'k' closest points in the training set and assigning the most common class among them.


## Technical Stack
The analysis is implemented in Python using the following libraries:
* **Pandas & NumPy**: For data manipulation and numerical operations.
* **Matplotlib & Seaborn**: For exploratory data analysis and visualization.
* **Scikit-learn**: 
  * `KNeighborsClassifier` for the machine learning model.
  * `StandardScaler` for feature normalization.
  * `accuracy_score`, `confusion_matrix`, and `classification_report` for performance evaluation.

## Project Workflow
1. **Data Loading**: Importing the emissions dataset.
2. **Exploratory Data Analysis (EDA)**: Visualizing the relationships between features, such as Energy Efficiency vs. Emission Reduction.
3. **Data Cleaning**: Handling missing values and ensuring data integrity.
4. **Preprocessing**: Scaling numerical features to ensure that the distance-based KNN algorithm is not biased by different units of measurement.
5. **Model Training & Testing**: Splitting the data and training the classifier.
6. **Evaluation**: Generating a confusion matrix and classification report to assess accuracy.

## How to Use
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/emissions-knn-classification.git](https://github.com/yourusername/emissions-knn-classification.git)
