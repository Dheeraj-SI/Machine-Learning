Feature Selection Techniques in Human Activity Recognition Dataset
Dataset
The dataset used in this project revolves around the recognition of human activities using smart phones. It includes various features extracted from smart phone sensors to identify different activities performed by individuals.

Feature Selection Techniques
1. Removing Duplicate Columns
Duplicate columns, if present in the dataset, can introduce redundancy and do not contribute additional information. In this step, duplicate columns are identified and removed to streamline the dataset.

2. Variance Threshold
Features with low variance may not contain significant information for the task at hand. Variance thresholding is employed to exclude low-variance features, helping to reduce dimensionality and focus on the more informative ones.

3. Correlation
Highly correlated features might provide redundant information. Correlation analysis is performed to identify and eliminate features that are strongly correlated, ensuring that the dataset is composed of diverse and independent features.

4. ANOVA (Analysis of Variance)
ANOVA is a statistical technique used to analyze the differences among group means in a dataset. Applied in the context of feature selection, ANOVA helps identify features that have a significant impact on the target variable, allowing the model to focus on the most relevant features for accurate predictions.

File Overview
This file demonstrates the application of various filter-based feature selection techniques to enhance the quality of the dataset for the subsequent machine learning tasks. By systematically removing duplicate columns, filtering based on variance, addressing feature correlation, and utilizing statistical analysis (ANOVA), the goal is to improve the efficiency and interpretability of machine learning models applied to the Human Activity Recognition dataset.

