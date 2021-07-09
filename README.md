# Segmentation of Credit Card Users
In this project, I performed behavioral segmentation on credit card customers. I go through the data science process from data preparation, exploration, modeling through unsupervised learning, evaluation, and ultimately to profiling of the segments. The steps taken here and techniques utilized are applicable to any company looking to derive insights from their customers' behaviors and seeking to improve on targeted marketing. 

For this particular dataset, I clustered the data into six segments and created six customer profiles, which offer business value to a company’s marketing or risk department.
Check out the code notebooks below by clicking the hyperlinks in the table of contents for extensive details on the steps taken.

# Table of Contents
---------------------------------------------------------
## [Introduction and Problem Statment](https://github.com/mhahm/Credit-Card-User-Segmentation/blob/master/Introduction%20and%20Business%20Problem.pdf)
* Hypothetical business problem
* Information about dataset
* Data Science Approach
* Deliverables

## [Data Wrangling, EDA, and Initial Modeling](https://nbviewer.jupyter.org/github/mhahm/Credit-Card-User-Segmentation/blob/master/Data%20Wrangling%2C%20EDA%2C%20Initial%20Modeling.ipynb)
* Wrangling of dataset - addressing missing values
* Exploratory data analysis
* Initial modeling w/ k-means
* Evaluation using elbow plot and silhouette score
* Visualization of Clusters with PCA

## [Addressing Outliers, Modeling, and Profiling](https://nbviewer.jupyter.org/github/mhahm/Credit-Card-User-Segmentation/blob/master/Outliers%2C%20Modeling%2C%20Profiling.ipynb)
* Addressing the outliers in the dataset using two techniques:
    * Interquartile Range
    * Binning
* Modifying the features with binned features
* Modeling w/ k-means using engineered bins
* Principal Component Analysis and Visualization of Clusters
* Profiling of Clusters


#### NOTE: In order to render and interact with the plotly graphs, the jupyter notebook headers in the README hyperlink to [nbviewer](https://nbviewer.jupyter.org). You can also manually paste the github notebook links into nbviewer

## Summary and Report
[Slide Deck](https://docs.google.com/presentation/d/1NY7i3QNlryLVD8RZJDVCXjY1jgZfOXSOzdDHlPLzFF4/edit?usp=sharing)
