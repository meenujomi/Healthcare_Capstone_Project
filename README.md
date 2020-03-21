# Healthcare_Capstone_Project
## Objective
CMS rates hospitals in the US on a scale of 1-5, with the objective of making it easier for patients and consumers to compare the quality of services offered by hospitals.
The ratings directly influence the choice of hospitals made by consumers and may significantly impact hospitals' revenues. Thus, it is extremely important for hospitals to understand the methodology that CMS uses for calculating the ratings so that they can work on improving the factors that affect their ratings.This project is focused on developing an approach to calculate hospital ratings and using it to identify areas of improvement for certain hospitals. It will also require a thorough understanding of the rating system developed by CMS.
## Steps Followed
- Reading Data
- Cleaning Data
- Exploratory Data Analysis
- Linear Regression
: Splitting the Data into Training and Testing Sets
-- Feature Scaling
-- Model Building
-- RFE
-- Building model using statsmodel, for the detailed statistics
-- Removing variables manually for model
-- Residual Analysis of the train data of model
-- Predicting on test set
- Logistic Regression
- Random Forest
: Hyperparameter Tuning
-- Tuning max_depth
-- Tuning n_estimators
-- Tuning max_features
-- Tuning min_samples_leaf
-- Tuning min_samples_split
-- Grid Search to Find Optimal Hyperparameters
-- Fitting the final model with the best parameters
- PCA and Clustering
: Screeplot
-- Coorrelation Matrix
-- Outliers Treatment
-- Hopkins Statistics
-- K- Means
-- Silhouette Analysis
-- Sum of Squared Distances
-- Analysis of clusters formed
-- Plotting
- Recommendations for Evanston Hospital
## Details of files given
- Healthcare Capstone Project_Final.ipynb : The python file showing coding and data analysis
- Capstone Project_Star Rating.pdf : Presentation showing conclusion
- Capston+Prj_Plan.pdf: The basic plan on how the project is done
- https://data.medicare.gov/data/archives/hospital-compare (Hospital_Revised_FlatFiles_20161110) : Data worked on
