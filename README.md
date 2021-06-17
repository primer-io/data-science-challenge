# Data Science Challenge

One of the objectives of Team Data at Primer is to help improve authorisation rates for our merchants - the Authorization Rate is defined as:

```
# of authorized payments / # payments attempted
```

As part of the challenge, I have generated a fake dataset of payments that we will be using. The dataset can be found in the repo under `data.csv` and it is described below:

```
created_at: Timestamp when the payment was created
amount_usd: Integer representing the amount in USD cents (if you see a value of 100 it is equal to $1). We have converted the values from their local currency to USD for simplicity
currency: String representing the original currency 
payment_instrument_type: String - one of Paypal, GoCardless, Klarna, PaymentCard, or Apple Pay
card_brand: String representing the brand of the card used for the payment 
issuing_country: String representing the country where the card was issued
processor: String representing the entity responsible for processing the payment
authorized: Integer (0/1) indicating if the payment was authorized or not
```

# The Challenge
The challenge has two parts:
1. Exploratory Data Analysis
2. Bayesian modeling

### EDA
Perform exploratory data analysis to better understand the data and summarise your findings. Please use well-labeled charts and tables during the analysis. To get you started, these are some questions that could be interesting

- What is the total authorization rate?

- Which Processor has the highest authorization rate?

- What is the distribution of payment amounts?

- Is there a relationship between any of the following features and whether or not a payment is authorized? 
	- amount_usd
	- currency
	- card_brand
	- payment_instrument_type
	- issuing_country

### Model Building

Build Bayesian Logistic Regression model that predicts if a payment will be authorized. Once complete, summarise your model, the approach (e.g. how did you select your priors), the results, and how well it performed. 

Please complete the tasks using Python or R and you are free to use any and all third party libraries to help you. 


