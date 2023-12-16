# Amazon-Reviews-BigData

A semester-long undergraduate project, that integrates building a complete machine learning pipeline incorporating big data technologies using a cloud infrastructure.

For this project, I will only be using the 'amazon_reviews_us_Beauty_v1_00.tsv' data set, but the script can be used for other individual files from the Amazon Reviews data set. This file was downloaded individually on the AWS CLI using an API command provided by the link below. All files in this project will be stored in it's respective folders from my AWS S3 bucket. All scripts were produced using the Databricks Community Edition.

- **Link to Kaggle Data Set**: https://www.kaggle.com/datasets/cynthiarempel/amazon-us-customer-reviews-dataset
- **Link to Databricks Community Edition**: https://docs.databricks.com/en/getting-started/community-edition.html

**Note: This dataset is 22 GB. Please consider copying the API command that is available at the link to download individual files that you will be working with.**

## Exploratory Data Analysis (EDA) Statistical Graphs**:
- <img width="441" alt="Number_of_Reviews_by_Date" src="https://github.com/garyanmai/Amazon-Reviews-BigData/assets/145724601/558c04a3-8f2f-4c69-a324-188f32093bcb">

- <img width="450" alt="star_ratings_by_star_rating" src="https://github.com/garyanmai/Amazon-Reviews-BigData/assets/145724601/94fce237-44dd-40b7-b6f8-bc80498ad66b">

- <img width="445" alt="num_reviews_by_dayofweek" src="https://github.com/garyanmai/Amazon-Reviews-BigData/assets/145724601/c28cbeb9-376f-4872-813e-ac18c0be8848">

## Predictive Modeling Graphs**
- <img width="641" alt="LinearRegression_model1" src="https://github.com/garyanmai/Amazon-Reviews-BigData/assets/145724601/3c39b2fe-76c6-4645-ac0d-50434ff51d63">

- <img width="634" alt="LogReg_model1" src="https://github.com/garyanmai/Amazon-Reviews-BigData/assets/145724601/50568834-82cf-4bc4-89c1-9ac16e2e65a5">

- <img width="636" alt="LogReg_model2" src="https://github.com/garyanmai/Amazon-Reviews-BigData/assets/145724601/5ff9cb13-5995-44c9-b425-2a7ae11fb341">

- <img width="634" alt="LogReg_model3" src="https://github.com/garyanmai/Amazon-Reviews-BigData/assets/145724601/5a5ca555-24db-4ae3-b1b4-0b295bdd1fd6">

## Steps:
1. Exploratory Data Analysis and Data Cleaning: ('EDA_Cleaning_Script')
2. Feature Engineering, Modeling, and Data Visualization: ('FeatureEngineering_Modeling_Script')







