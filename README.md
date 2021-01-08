# Customer_Churn
  Analyzing and building prediction models for customer churn
  Prediction models: Logistic Regression, Random forest and Decision tree.

## What?
  Customer churn or customer attrition is the percentage of customers that stopped using your company's product or service during a certain time frame

## Why is it important?
  Its costs more to acquire new customers than to retain the old customers
  It helps in data driven retention strategy

## How?
  Understanding the reason for customer churn
  Estimate the risk with individual customers 

## How do we calculate?
  At some time period,
		Churn rate = no.of customer cancellations / No.of active customers

## Bases?
	  Know customer rate
	  at the time of Week
	  at the time of Month
	  Product line
	  Customer cohort
#### But,
### Churn is needed at a granular level.
  Cohort based churn model may not be enough for precise targeting / real time prediction as customers vary in Behaviour and preferences which influences the satisfaction and desire to churn.
  This is when the customer churn model is most useful.
  
## So How do we do it?
### Statistics and ML :
Uses Historical purchase data, Behavioural data-> predict customer churn

## Types of Churn:
  Contractual         
  Non contractual  
  Voluntary            
  in-Voluntary

## Use case:
First thing first, 
	Understand the use case and establish a clear use case. For what? Who is going to use? How it is going to be used?

Lets take an example of a Customer Care Center 

In customer care call center,
A customer calls -> connects to customer care agent -> customer care agent’s portal shows him the customers information and Customer churn score -> if the churn score is high, he executes the retention strategy like offering promotions, discounts or others

#### How is this possible?
This is when we data scientist comes into actions, We
	Collect data -> Treat & Explore the data ->  Build a churn model -> deploy the model by integrating it with the customer care software -> O/P of the model is the Churn risk score(more granular level - for each customers)
