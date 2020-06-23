---
layout: post
title:      "Lending Club Loans analysis in a layman language"
date:       2020-06-23 04:41:54 +0000
permalink:  lending_club_loans_analysis_in_a_layman_language
---


**Introduction**

Lending Club is the world's largest peer-to-peer lending platform located in San Francisco, California, United States.
Jean de Dieu  Nyandwi has made an analysis on www.kaggle.com on Loan Pay Back Prediction for Lending Club borrowers
His goal was to use dataset provided to build a model that predict whether or not the borrower will pay back the loan. The model can help assess new borrowers if they will be able to pay the loan based on their historical information. Jean de Dieu has organized is analysis in four section that we will explain below.

**1- Loading the data**

He started by loading the data in his notebook: the data was comprised with 27 columns with their description: each column representing useful information on a potential borrower. We must acknowledge that this information is gathered by Lending Club from borrower at the time of the application and after the loan is issued.
After loading the data, he start to look at each column individually to see if they have missing values, are they properly represented, how relevant could the information be to the subject he is working on? In this part, Jean de Dieu also gets the tools he will use to analyze the data and also create the model. He moved on to the next step: exploring the data.

**2-Exploratory Data Analysis** 

This phase is where Jean de Dieu looked at the columns that may have a significant influence on the outcome of his future model. In this section he was able to figure out how many borrowers were able to fully pay their loans and those who defaulted on their loans. He looked at individual column and made these different findings:

* Loan amount versus number of loan: most of the loans were under $35,000.00 and many people took $10,000.00 loans

*	Installment which is the monthly payment is link to the loan amount. 

* They are 7 different classification in the Lending Club loan program ranging from A thru G called grade, A being the best and G the least good. If your loan has an A grade that means you have a very good credit. They are also some subgrades, but I will not elaborate on that as subgrade and grade are somehow linked. Most of the loans in the subgrade of F and G will default more than any other loan. After exploring the data, we now need to turn the data into something we can model on in data science lingo it is called “Data Preprocessing”.

**3- Data Preprocessing**

In this section, Jean de Dieu performed actions on missing data and non-numerical variables or objects. 

* He use a well-known code in the data science sector to determine the number of missing values per column, represented them as a percentage of the variable by column for comparison purpose.

* He went column by column to modify some values and turns them into numerical values.

* Jean de Dieu also replaced some of the missing values in some column using the average value of the column for some numerical variables.

*	He then dropped the remaining missing values and his data was ready for modeling.
 
**4- Creating the Model and Evaluating Model Performance**

Jean de Dieu has created a model using a well-known Machine Learning Algorithm and he was able to predict if a new borrower can default or no base on the available data of the new customer.

