# MLP
MLP model trained to determine whether a loan will be a good investment or not for the lender. Uses consumer credit data to make a prediction.

Model trained on the following parameters:

loan_amnt - The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.
funded_amnt - The total amount committed to that loan at that point in time.
funded_amnt_inv - The total amount committed by investors for that loan at that point in time.
int_rate - Interest Rate on the loan
installment - The monthly payment owed by the borrower if the loan originates.
annual_inc - The self-reported annual income provided by the borrower during registration.
dti - A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
delinq_2yrs - The number of 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years
inq_last_6mths - The number of inquiries in past 6 months (excluding auto and mortgage inquiries)
open_acc - The number of open credit lines in the borrower's credit file.
pub_rec - Number of derogatory public records
revol_bal - Total credit revolving balance
revol_util - Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.
total_acc - The total number of credit lines currently in the borrower's credit file
collections_12_mths_ex_med - Number of collections in 12 months excluding medical collections
mths_since_last_major_derog - Months since most recent 90-day or worse rating
acc_now_delinq - The number of accounts on which the borrower is now delinquent.
tot_coll_amt - Total collection amounts ever owed
tot_cur_bal - Total current balance of all accounts
total_rev_hi_lim  - Total revolving high credit/credit limit
emp_length - Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years. 
mths_since_earliest_cr_line - The number of months since the borrower's earliest credit line.
term - The number of payments on the loan. Values are in months and can be either 36 or 60.
grade - LC assigned loan grade
sub_grade - LC assigned loan subgrade
home_ownership - The home ownership status provided by the borrower during registration. Our values are: RENT, OWN, MORTGAGE, OTHER.
purpose - A category provided by the borrower for the loan request. 
addr_state - The state provided by the borrower in the loan application
initial_list_status - The initial listing status of the loan. Possible values are – W, F
emp_length - Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years. 



