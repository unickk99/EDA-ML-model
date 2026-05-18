1. Exploratory Data Analysis (EDA)

In this step, the dataset was explored to understand its structure and quality.

Tasks Performed
Checked dataset shape
Viewed dataset columns
Checked data types
Checked missing/null values
Generated summary statistics
Identified categorical and numerical features
Visualizations Used
Histogram
Count Plot
Box Plot
Heatmap
Pair Plot
Distribution Plot
Objectives of EDA
Understand feature distributions
Detect outliers
Identify relationships between variables
Analyze the effect of smoking, BMI, and age on insurance charges
2. Data Preprocessing

Data preprocessing was performed to prepare the dataset for machine learning and statistical analysis.

Steps Performed
Handling Categorical Variables

The following categorical columns were converted into numerical form:

Sex
Smoker
Region
Encoding Techniques Used
Label Encoding
One-Hot Encoding

Example:

Feature	Transformation
sex	male/female → numerical
smoker	yes/no → numerical
region	one-hot encoded
3. Feature Engineering

Additional features were created to improve analysis and feature selection.

BMI Categorization

BMI values were converted into categories such as:

Underweight
Normal
Overweight
Obesity

This helps in understanding how BMI groups affect insurance charges.

4. Feature Selection

Feature selection techniques were used to identify important variables.

Pearson Correlation

Pearson Correlation was used to measure linear relationships between numerical variables.

Purpose
Identify highly correlated features
Understand positive and negative relationships
Reduce unnecessary features
Example Analysis
Smoker status showed strong correlation with insurance charges
Age and BMI also showed moderate correlation
Chi-Square Test

Chi-Square Test was applied to analyze relationships between categorical features and the target variable.

Purpose
Select important categorical features
Measure dependency between variables
