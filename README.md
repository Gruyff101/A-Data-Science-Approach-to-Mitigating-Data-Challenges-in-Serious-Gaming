# A-Data-Science-Approach-to-Mitigating-Data-Challenges-in-Serious-Gaming
This project focuses on employing data science techniques to analyze and mitigate data challenges encountered in citizen science projects, specifically in serious gaming environments. The data was collected from an escape room scenario designed by JGM (Jeffery Griffin Meijer), a serious gaming company. The analysis examines team dynamics, communication patterns, and leadership behaviours.
The dataset includes 291 observations and 55 variables related to team performance metrics (e.g., communication patterns, leadership behaviors).
The data is collected from behavioral transaction logs in escape room scenarios, analyzed to derive insights into teamwork under pressure.


The main code is organized into the following sections:
Data Preprocessing: This section handles the cleaning and preparation of the dataset for analysis. It includes:
Handling missing data
Imputation of missing values using mean values and specific assumptions based on the nature of the missing data.
Data type consistency checks (converting string to numeric or NaN as necessary).
Filtering out columns and rows with significant missing data or irrelevant entries.
Conversion of time variables into a standard format.

Exploratory Data Analysis (EDA): Provides descriptive statistics and visual insights into the dataset. Key aspects include:
Descriptive statistics for variables related to communication, collaboration, and leadership constructs.
Correlation analysis between variables to detect multicollinearity.
Heatmaps for visual representation of correlations between the main variables.

Statistical Analysis: Statistical tests are applied to evaluate differences between winning and losing teams. This section includes:
T-tests to identify statistically significant differences across key constructs (e.g., knowledge sharing, environmental awareness).
Analysis of coefficients and confidence intervals for the variables involved in team performance prediction.

Machine Learning Models: This section applies logistic regression models to classify outcomes (e.g., team success) based on behavioral metrics.
The code includes regularization to avoid overfitting and uses bootstrapping to validate the reliability of model coefficients.
Visualization of the logistic regression results via coefficient plots with confidence
