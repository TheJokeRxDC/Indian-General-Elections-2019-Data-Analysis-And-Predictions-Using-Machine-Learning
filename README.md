# Indian General Elections 2019: Data Analysis And Predictions Using Machine Learning
<p align="center">
  <img src="http://ForTheBadge.com/images/badges/made-with-python.svg">
  <img src="http://ForTheBadge.com/images/badges/built-by-developers.svg">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Last%20Commit-June 2021-brightgreen"> 
  <img src="https://img.shields.io/badge/Project%20Status-Open-brightgreen">
</p>

<img src="https://www.ft.com/__origami/service/image/v2/images/raw/http%3A%2F%2Fcom.ft.imagepublish.upp-prod-us.s3.amazonaws.com%2F5c2322c8-7deb-11e9-81d2-f785092ab560?fit=scale-down&source=next&width=700" width="900">

## Table of contents
1. Introduction :white_check_mark:
2. Environment Setup :white_check_mark:
3. Gathering The Data :white_check_mark:
4. Features :white_check_mark:
5. Data Preprocessing and Basic Exploratory Data Analysis (EDA) :white_check_mark:
6. Data Analysis :white_check_mark: <br>
    6.1 Lok sabha 2019: Election results<br>
    6.2 Party-wise vote share<br>
    6.3 Age distribution of candidates<br>
    6.4 Caste distribution of candidates<br>
    6.5 Criminal records of candidates<br>
    6.6 Key battlegrounds of the election<br>
7. Preparing the data :white_check_mark:<br>
    7.1 Scaling the data<br>
    7.2 Resampling the data<br>
8. Machine learning model experimentation :white_check_mark:
9. Evaluating the model :white_check_mark: <br>
    9.1 Classification report<br>
    9.2 Confusion matrix<br>
    9.3 ROC Curve<br>
    9.4 Cross-validated metrics<br>
10. Conclusion :white_check_mark:

## Results

**Note: The accuracy may vary with different runs**


| Model	                    |Training Accuracy (%) | Training Precision (%) | Training Recall (%)  | Training F1 (%) |	Test Accuracy (%) | Test Precision (%) | Test Recall (%) | Test F1 (%)      | 10-Fold CV Timing (seconds)|
|---	                    |---	           |---	                |---	           |---	         |---	          |---	           |---          |---           |---                         |
| XG Boosting	            | 87.83	       | 87.78	        | 88.02	       | 87.50	 | 86.81	  | 75.65	   | 73.24	 | 74.43	| 3.34|
| Cat Boosting	            | 88.37	       | 88.71	| 88.11	| 88.10	| 86.64	| 74.52	| 74.52	| 74.52	| 43.52|
| LG Boosting	            | 88.81	| 88.77	| 89.00	| 88.56	| 86.47	| 74.05	| 74.52	| 74.28	| 3.98|
| Gradient Boosting	        | 85.51	| 86.59	| 84.17	| 85.08	| 86.31	| 72.45	| 77.07	| 74.69	| 1.77|
| Random Forest	            | 87.78	| 88.03	| 87.81	| 87.55	| 85.14	| 73.28	| 68.15	| 70.62	| 2.20|
| K-Nearest Neighbors	    | 84.87	| 81.54	| 90.35	| 85.63	| 83.47	| 64.79	| 80.89	| 71.95	| 0.15|
| ADA Boosting	            | 82.66	| 84.53	| 79.84	| 81.81	| 82.47	| 65.85	| 68.78	| 67.28	| 0.86|
| Decision Trees	        | 84.23	| 83.15	| 84.94	| 83.52	| 80.46	| 61.76	| 66.87	| 64.22	| 0.19|
| Support Vector Machines	| 66.65	| 66.53	| 66.89	| 66.66	| 70.28	| 45.91	| 75.15	| 57.00	| 1.26|
| Logistic Regression	    | 64.03	| 62.80	| 68.86	| 65.65	| 62.27	| 37.89	| 68.78	| 48.86	| 0.27|
