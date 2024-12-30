# Disease Prediction Using Patient Data

## Objective
To train and evaluate machine learning models to predict diseases such as heart disease using the UCI Heart Disease dataset.

## Dataset
The dataset used in this project was obtained from the Kaggle.

## Tasks

### 1. Dataset Loading and Exploration
- Loaded the dataset using pandas.
- Displayed the first few rows and dataset information to understand its structure.

### 2. Exploratory Data Analysis (EDA)
- Visualized feature distributions using histograms.
- Analyzed feature correlations using a heatmap.

### 3. Data Preprocessing
- Split the dataset into training and testing sets.

### 4. Model Training
Trained the following machine learning models:
- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**

### 5. Model Evaluation
Defined a function to evaluate models using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

Evaluated and compared model performances.

### 6. Results Visualization
- Created a bar chart to visualize and compare model performance metrics.

## Results
| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.79%   | 0.80%    | 0.79% | 0.79%   |
| Random Forest       | 0.98%   | 0.98%    | 0.98% | 0.98%   |
| SVM                 | 0.80%   | 0.81%    | 0.80% | 0.80%   |

## Dependencies
- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Author
Muhammad Waqar Ali