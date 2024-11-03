# Student-Performance-Factors



###  Project Overview 
This project analyzes factors influencing student exam performance using a dataset of various student attributes and their corresponding exam scores.


### Goal and Objective
The objective of this analysis is to explore the factors influencing student exam performance using a dataset containing various student attributes. The analysis aims to:
- Identify key predictors of academic success.
- Understand the relationships between different factors and exam scores.
- Provide actionable insights and recommendations for educators and policymakers to enhance student performance.


#### Dataset
The dataset includes features such as:
- Hours studied
- Attendance
- Parental involvement
- Access to resources
- Sleep hours
- Previous scores
- And more...

### Analysis Performed
#### 1. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling

#### 2. Exploratory Data Analysis (EDA)
- Distribution of exam scores
- Correlation analysis
- Visualizations (histograms, scatter plots, box plots, 3D plots)
#### 3. Feature Importance
- Random Forest feature importance
- XGBoost feature importance

#### 4. Model Building and Evaluation
- Linear Regression
- Random Forest
- XGBoost
- Comparison of model performances (R2 score, MSE)

#### 5. Cluster Analysis
- K-means clustering 
- Analysis of cluster characteristics

### Key Findings
1. Attendance, Hours Studied, and Previous Scores are consistently the top predictors of exam performance across different models.
2. The relationship between tutoring sessions and exam scores is complex, showing a negative correlation in 3D visualizations despite being an important feature in predictive models.
3. Cluster analysis revealed distinct groups of students with varying characteristics, suggesting the need for tailored educational approaches.
4. Linear Regression outperformed more complex models like Random Forest and XGBoost, indicating predominantly linear relationships in the data.


### Recommendations
1. Focus on improving student attendance and encouraging more study hours as these are strongly correlated with better exam performance.
2. Investigate the quality and targeting of tutoring sessions to understand their negative correlation with exam scores.
3. Develop personalized learning strategies based on the identified student clusters.
4. Consider the impact of parental involvement and access to resources, especially for students in lower-performing clusters.


## Conclusion
The analysis reveals that while certain factors like attendance and study hours have a clear positive impact on exam scores, others like tutoring sessions have more complex relationships. The effectiveness of different educational interventions may vary across different student groups, as identified by the cluster analysis. The strong performance of the linear regression model suggests that many of the relationships in educational data are predominantly linear, but there are also nuanced interactions that require careful interpretation. Future educational strategies should consider these findings to create more targeted and effective interventions for improving student performance.


###
###
###

The data for this project was obtained from Kaggle. Special thanks to  [lainguyn123](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)  for providing the dataset.
