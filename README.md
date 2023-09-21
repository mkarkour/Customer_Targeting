# Project: Optimizing Marketing through Customer Targeting

## Dataset
- `train_marketing`
- `test_marketing`

## Description

The project focuses on optimizing marketing strategies for a leading marketing company, working on behalf of a retail business client. Using customer data and their responses to previous marketing campaigns, the goal is to predict customer reactions to an upcoming fifth marketing campaign. This predictive information will guide resource allocation and improve the overall success of the marketing efforts. Applying data science techniques to analyze the data provides valuable insights and enhances the company's marketing strategy.

## Data Dictionary
The project utilizes two datasets: `train_marketing` and `test_marketing`, each containing valuable information about customers and their interactions with previous marketing campaigns. Here is a summary of the key variables in the dataset:
- `birth`: The year the customer was born (Numeric).
- `education`: The highest level of education completed by the customer (Categorical).
- `marital_status`: The marital status of the customer (Categorical).
- `income`: The yearly household income of the customer (Numeric).
- `number_of_children`: The number of children in the customer's household (Numeric).
- `days_since_last_purchase`: The number of days since the customer's last purchase (Numeric).
- `customer_enrollment_date`: The date on which the customer enrolled with the company (Date).
- `customer_complaint_status`: Indicates whether the customer has made a complaint within the last 2 years (1) or not (0) (Boolean).
- `discounted_purchases`: The number of purchases made using a discount (Numeric).
- `website_purchases`: The number of purchases made through the company's website (Numeric).
- `catalogue_purchases`: The number of purchases made using a catalogue (Numeric).
- `store_purchases`: The number of purchases made directly in stores (Numeric).
- `web_visits_month`: The number of visits to the company's website in the last month (Numeric).
- `campaign1_accepted`: Indicates whether the customer accepted the offer of the first campaign (1) or not (0) (Boolean).
- `campaign2_accepted`: Indicates whether the customer accepted the offer of the second campaign (1) or not (0) (Boolean).
- `campaign3_accepted`: Indicates whether the customer accepted the offer of the third campaign (1) or not (0) (Boolean).
- `campaign4_accepted`: Indicates whether the customer accepted the offer of the fourth campaign (1) or not (0) (Boolean).
- `campaign5_accepted` (Target Variable): Indicates whether the customer accepted the offer of the fifth campaign (1) or not (0) (Boolean).

## Project Workflow

The project involves a supervised machine learning classification task. It comprises two stages:

### 1. Training Stage
- Utilizes customer data from past marketing campaigns (1 through 4) and the current fifth campaign.
- Develops a predictive model (classifier) to accurately predict the outcome of the 5th campaign based on customer characteristics and past reactions to previous campaigns.

### 2. Testing Stage
- Uses the predictive model developed in the training stage to predict which customers from the "test set" are likely to be interested in the fifth campaign.
- Resource allocation is based on these predictions to optimize the marketing strategy.

## Dependencies

Ensure you have the following libraries and packages installed:

- NumPy
- Pandas
- Scikit-Learn
- Jupyter Notebook (for running the analysis)

## How to Use

To use the project:

1. Clone this repository to your local machine.
2. Install the required dependencies mentioned above.
3. Open and run the Jupyter Notebook file to perform the analysis and predictions.
4. Modify and adapt the predictive model as needed for your specific marketing campaigns.

## Questions or Assistance

If you have any questions, issues, or require assistance with the project, please feel free to reach out to the project maintainers or open an issue in the repository. We are here to help and improve the project.

Best of luck with your marketing optimization efforts!
