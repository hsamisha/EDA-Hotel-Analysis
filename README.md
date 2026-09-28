# Heart Health Analysis - Exploratory Data Analysis

## Project Overview

Pulse of Prevention: Analyzing Heart Health for Better Outcomes is a Python-based data analysis project focused on exploring heart-health data and identifying patterns associated with heart disease.

The project performs data cleaning, exploratory data analysis, statistical analysis, data visualization, feature preprocessing, and machine learning using the heart health dataset.

The analysis focuses on understanding patient demographics, clinical measurements, risk factors, relationships between variables, and differences between patients with and without heart disease.

## Objective

The main objectives of this project are to:

- Analyze patient heart-health data.
- Understand patient demographics and clinical measurements.
- Identify patterns associated with heart disease.
- Analyze important heart-disease risk factors.
- Compare patients with and without heart disease.
- Identify relationships and correlations between variables.
- Detect potential outliers in numerical features.
- Normalize numerical features for machine learning.
- Build a Logistic Regression model.
- Evaluate the performance of the machine learning model.
- Generate meaningful insights from the exploratory analysis.

## Dataset Description

The project uses the `heart.csv` dataset.

The dataset contains patient-level information related to heart health and includes demographic, clinical, and diagnostic attributes.

### Important Columns

| Column | Description |
|---|---|
| `age` | Age of the patient |
| `sex` | Sex of the patient |
| `cp` | Chest pain type |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol |
| `fbs` | Fasting blood sugar |
| `restecg` | Resting ECG result |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression |
| `slope` | Slope of peak exercise ST segment |
| `ca` | Number of major vessels |
| `thal` | Thalassemia category |
| `target` | Heart disease outcome |

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

## Approach / Methodology

The project was completed through the following stages.

### 1. Data Collection

The heart health dataset was loaded from the `heart.csv` file using Python.

### 2. Data Cleaning

The dataset was examined and prepared for analysis by checking:

- Missing values
- Duplicate records
- Data types
- Numerical variables
- Categorical variables
- Potential outliers
- Data consistency

### 3. Exploratory Data Analysis

Exploratory analysis was performed to understand:

- Patient age distribution
- Sex distribution
- Chest pain types
- Resting blood pressure
- Cholesterol levels
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Major vessels
- Thalassemia categories
- Heart disease outcome

### 4. Statistical Analysis

Statistical analysis was performed to examine relationships and differences between important variables.

Correlation analysis was also used to understand relationships between numerical features.

### 5. Data Visualization

Visualizations were created using Matplotlib and Seaborn to identify:

- Distributions
- Relationships
- Comparisons
- Correlations
- Outliers
- Differences between target groups

### 6. Feature Preprocessing

Numerical features were normalized or standardized before applying the machine learning model.

### 7. Machine Learning

A Logistic Regression model was developed to analyze the relationship between the selected features and the heart disease target variable.

### 8. Model Evaluation

The trained model was evaluated using appropriate classification evaluation metrics.

## Analysis & Key Findings

The exploratory analysis focuses on identifying patterns in patient characteristics and clinical measurements associated with the heart disease outcome.

The analysis covers the following areas:

### Patient Demographics

Patient age and sex were analyzed to understand the demographic distribution of the dataset.

### Clinical Measurements

Important clinical measurements such as:

- Resting blood pressure
- Cholesterol
- Maximum heart rate
- ST depression

were explored to understand their distributions and relationships with the target outcome.

### Chest Pain Analysis

Different chest pain categories were analyzed to understand their distribution across patients and their relationship with the heart disease outcome.

### Heart Rate Analysis

Maximum heart rate achieved during exercise was examined and compared across heart disease outcome groups.

### Exercise-Induced Angina

Exercise-induced angina was analyzed as one of the clinical characteristics available in the dataset.

### Correlation Analysis

Correlation analysis was performed to identify relationships between numerical variables and understand which variables show stronger associations within the dataset.

### Outlier Analysis

Potential outliers in numerical variables were identified using exploratory visualization and statistical techniques.

### Machine Learning Analysis

Logistic Regression was implemented to model the relationship between the selected patient characteristics and the heart disease outcome.

The model evaluation results are presented in the project notebook.

## Analysis & Key Insights

The final insights from the EDA should be based on the actual analysis performed in the notebook.

The completed analysis should summarize:

- Important demographic patterns.
- Differences between patients with and without heart disease.
- Important patterns observed in clinical measurements.
- Relationships between heart disease and chest pain categories.
- Patterns observed in maximum heart rate.
- Observations related to exercise-induced angina.
- Important correlations between numerical variables.
- Significant outliers identified during the analysis.
- Machine learning model performance.
- Variables that showed notable relationships with the target outcome.

These insights should be interpreted from the actual charts, statistical analysis, and model results rather than assumptions.

## Dashboard Overview

This project is primarily an Exploratory Data Analysis and Machine Learning project.

No separate dashboard is included in the current project.

The analysis results are presented through Python visualizations in the Jupyter Notebook.

## Recommendations

Based on the analysis performed in the project, the following analytical recommendations can be considered:

- Examine important clinical variables together rather than relying on a single variable.
- Use exploratory analysis to identify patterns that require further investigation.
- Consider demographic and clinical characteristics when analyzing heart-health datasets.
- Use correlation analysis to understand relationships between numerical variables.
- Investigate potential outliers before applying machine learning models.
- Apply appropriate feature preprocessing before model training.
- Evaluate classification models using multiple performance metrics.
- Use the findings as analytical insights rather than as a substitute for professional medical diagnosis.

## Conclusion

The Heart Health Analysis project demonstrates the use of Python-based data analysis techniques to explore patient health data and identify patterns associated with heart disease.

The project covers data cleaning, exploratory data analysis, statistical analysis, visualization, feature preprocessing, and Logistic Regression.

The analysis provides a structured approach to understanding the dataset and demonstrates practical skills in Python, data analysis, visualization, statistical analysis, and machine learning.


## Key Insights

Based on the completed exploratory data analysis, the following key insights were identified:

- Booking distribution: [Add the main finding from the hotel-type and booking analysis.]
- Cancellation pattern: [Add the main cancellation finding, including the relevant percentage or comparison.]
- Arrival trend: [Add the month or period with the highest booking activity.]
- Pricing trend: [Add the important ADR finding across hotel types, market segments, or years.]
- Guest behavior: [Add the key finding from new versus repeated guest analysis.]
- Room demand: [Add the most frequently reserved room type.]
- Distribution channel: [Add the channel with the highest booking volume and the relevant observation.]
- Lead time and cancellation: [Add the relationship identified from the analysis.]
- Special requests and ADR: [Add the observed relationship from the visualization or statistical analysis.]
- Operational implication: [Explain how the most important findings could support hotel planning, pricing, inventory, or cancellation management.]

These findings are based on the analysis performed in this notebook and should be interpreted within the context of the dataset.


