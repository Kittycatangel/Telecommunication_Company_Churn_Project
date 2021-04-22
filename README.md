
#Customer churn in the telecomunication industry

In this project, machine learning models are made to predict possible customer churn in a telecomunication industry. Our models are powerful which can determine churn factors and we can give a company the advantage of taking action before losing customers.

##Business Problem
1.	What are the most important factors affecting the customer churn?
2.	What are the factors which are increasing churn in the compnany?
3.	What are the factors that decrese churn and therefore retain customers in the company?

##Data
The data used is derived from the following file "bigml_59c28831336c6604c800002a.csv" found in this repository. The machine learning modelling results can be found in the following file Customer_Churn_Model.ipynb" found in this repository. The presentation of the results can be found in a pdf file as "CustomerChurn_presentation.pdf"

##Methods
OSEMN approach is used in this project. The data is , scrubbed, cleaned, explored, visualized, modelled and interpreted.

Differnt machine learning models were used to examine the most precise and accurate one including Random Forest, DescisionTree and SVM Classifiers ...ect.

## Results 
Our models produced were able to predict up tp 65-100% true churn.

The top five factors contributing to churn in the company are :

1.	Total day charge
2.	Customer service calls
3.	Total evening charge
4.	Total internaional charge

![image](https://user-images.githubusercontent.com/53411455/115775508-f797e380-a380-11eb-8232-486b482f3cf8.png)


Top factors contributing to retention of customers are :

1.	Having a voice mail plan
2.	Having no international paln

![image](https://user-images.githubusercontent.com/53411455/115775525-febef180-a380-11eb-9df1-df6ee19572d5.png)


##Recommendations

1) Decrease call charge for day and special charges for evening calls.

2) Have a better international plan.

3) Customer service calls is a measure usually for bad experience. Look what are the main causes of complaints and improve the quality of phone service.

4) Keep up the good work with the voice mail plan which is the best feature that keeps customers in the company.

5) Compete with other companies on this strongly recommended feature"voice mail plan" and make better offers for the customers. This can attract customers from competeing rivals.

##Future Work
More important data is needed to predict the churn of customers.

1) Competitor Information

Customer churn usually occurs when a rival company makes a good offer to our customers Comparison of other companies phone charges (day, night, international) and internet service will be good fator to be used in the models to predict the churn of customers.

2) Internet package information

Internet speed informaction, charge of internet per usage, the internet technology (fiber optic), internet package offer details including speed, data usage, TV streaming ...ect. All this information is important to include in our customer churn models.

3) Contract Information

Month to month contract, 6 month contract, a year contact or 2 years contarct. This information is important to know and definitely affects the churn or retention of customers.

5) Payment method

How the customers pay for the sevice: mailed check, automatic credit card payments, electronic check, automatic bank transfers. The less complex the payment method is, the more likely customers will not churn???

6) Complaint data

Text data from e-mails and customer service phone calls can be used to find the possible complaints and solve them before they cause customer churn.

7) Tenure data

Tenure data of customers is important throughout the years which can show us loyality and churn of customers.

