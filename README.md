# Customer-Transaction Prediction

## INTRODUCTION
with the problem of identification of the customers who will make a transaction with the bank in future, irrespective of the amount of money transacted previously with the bank, the dataset contain 200000 observation with 202 columns with 200 columns having values for var_1 to var_200, one column for ID code and one column for target

## BUISNESS CASE:
BASED ON GIVEN FEATURE OF DATASET WE NEED TO PREDICT WHICH CUSTOMER MAKE TRANSACTION IN THE FEATURE IRRESPTIVE OF THE AMOUNT OF MONEY TRANSACTED

## TASK:  BINARY CLASSIFICATION TASK

### NOTE:
•	In this data we not do any domain analysis  and eda because the data is contain private information of bank customer
•	In this data we only check the distribution of feature and target column

## DOMAIN ANALYSIS and EDA:
### TARGET COLUMN == TARGET [0, 1]
* 0 Represent -- CUSTOMER DID NOT DO A TRANSACTION
* 1 Represent -- CUSTOMER DID DO THE TRANSACTION
![image](https://user-images.githubusercontent.com/101791322/177703431-a72ef0b2-6b52-4f7c-9b6e-03722ed35a33.png)

OBSERVATION:
* In this plot we are clearly seen the 90% customer are did not do a transaction and 10% customer are did do the transaction
* This target feature is imbalance so we need to balance the data with the help of oversampling.

