# A-Project-on-Loan-Default--Analysis-using-Streamlit-

Developed a model that could predict and forecast the incidence of Loan default occuring.

# Introduction
2.1 Background

Loan defaults represent a serious issue for financial institutions, leading to significant monetary losses. Early identification of high-risk borrowers is crucial for mitigating these risks. 

Machine learning offers the ability to automatically detect patterns in large datasets, enabling the creation of predictive models that can forecast loan defaults with higher accuracy. In this project, we utilize data from a Kaggle dataset to develop a Stream-lit web application that leverages machine learning models to predict loan defaults.	

2.2   Purpose

 Development process of an interactive web application that incorporates machine learning models to predict the likelihood of loan defaults. The application is designed to assist lenders in making more accurate and efficient lending decisions, 


# Data Overview

Dataset Description
The dataset used in this project is sourced from Kaggle and contains historical data on borrowers, including their demographic details, financial history, and loan characteristics.

The key features of the dataset include:

	Applicant-Income: Income of the loan applicant.

	Co-applicant-Income: Income of the co-applicant, if applicable.

	Loan-Amount: The amount of the loan requested.

	Loan-Amount-Term: The term of the loan in months.

	Credit-History: A binary indicator of whether the applicant has a positive credit history (1) or not (0).

	Property-Area: The area where the property is located (Urban, Semiurban, Rural).

	Loan-Status: The target variable, indicating whether the loan was approved (1) or denied (0).
 
The dataset consists of approximately 614 instances, with multiple features that vary in data type, including numerical, categorical, and binary. There were 1.9% missing observations in the data.

 
<img width="958" height="410" alt="Machine 2" src="https://github.com/user-attachments/assets/358e0a85-3533-41c2-9bfa-3dc486a6b9fb" />


	Visualizations:

USING HISTOGRAM

<img width="994" height="596" alt="machine 3" src="https://github.com/user-attachments/assets/fc68a4e8-1e6f-479f-8370-1308453db3ec" />

USING CORRELATION MATRIX

Correlation Matrix: 

A heatmap was used to visualize correlations between numerical attributes, identifying potential relationships that could influence loan default.

<img width="933" height="464" alt="machine 4" src="https://github.com/user-attachments/assets/ff199de4-f0d5-4fd5-ac82-64dbb0792292" />



# Data Preprocessing
	Handling Missing Values
The dataset contained missing values.

<img width="520" height="491" alt="sat 1" src="https://github.com/user-attachments/assets/9aada2a5-0651-4342-945b-e47ae0df48e4" />

These were handled using mean imputation, where missing values were replaced with the mean of the respective columns. This approach ensured that the dataset remained intact without losing valuable information.

<img width="316" height="206" alt="sat 2" src="https://github.com/user-attachments/assets/464a8848-85a4-486b-8b0a-a92a71c44974" />



	Encoding Categorical Variables


<img width="294" height="179" alt="machinnn" src="https://github.com/user-attachments/assets/8c9dda9e-96c3-4f16-9bd6-e73ded65488c" />


OUR DATA IS NOW PROCESSED AMD READY FOR TESTING AND TRAINing

WE TRAINED THE DATA USING RANDOM FOREST AND NAVIE BAYES 

<img width="1001" height="490" alt="eva 1" src="https://github.com/user-attachments/assets/6234b716-498f-4c6c-aadd-f05201f11d8b" />

From our model evaluation Random forest had the best accuracy score, F1 score and Precision & recall score .

<img width="956" height="477" alt="eva 12" src="https://github.com/user-attachments/assets/3d970fa2-7b67-4b5c-9308-e2eca1c4e304" />


The model was deployed using the Random Forest to make future predictions of the instance of a customer defaulting on a loan payment.



# APPENDIX


<img width="768" height="346" alt="Codes" src="https://github.com/user-attachments/assets/e266e4cd-056c-45cf-9c90-af6ae00c0ce8" />

Load the Datasets


Deploy using Streamlit'


<img width="738" height="350" alt="codes 1" src="https://github.com/user-attachments/assets/ec9a9629-077d-4a35-9c1b-7c7e7c94baf8" />

<img width="751" height="283" alt="code 7" src="https://github.com/user-attachments/assets/d5f0ca6e-fd0d-47a0-a306-d72b604a9e10" />
<img width="504" height="292" alt="code 6" src="https://github.com/user-attachments/assets/41627f67-1a63-45f7-919c-58fc0675a7df" />


SETTING THE RISK RANGE : for customer churn or default on their loan paymnents 

<img width="735" height="313" alt="code 5" src="https://github.com/user-attachments/assets/eb1e3fe5-6dfb-4ac0-a788-6c3eb99b01a5" />



Pre - processing the data;   encode the categorical observations into numerical using :

            1. Label Encoding
            
            OR
               
            2. One Hot encoding
            
Pre - processing the data;

Identify missing values in the data
   
<img width="706" height="307" alt="code 4" src="https://github.com/user-attachments/assets/a09c2af3-74c8-43e0-9f81-58c6e57641ae" />
<img width="468" height="320" alt="code 3" src="https://github.com/user-attachments/assets/d845c193-157f-43d6-bfd0-5c7c4bde589e" />

