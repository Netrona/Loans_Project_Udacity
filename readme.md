# Loans Data Exploration

## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1604462328041000&usg=AOvVaw1WSULW2SFjvtoIWcb36ni9),
with feature documentation available [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1604462328042000&usg=AOvVaw105jGEPqiHIq4HXCfO03Nj).


## Summary of Findings

In the exploration, I found that there was a strong relationship between between the Borrower APR and the Borrower Rate which is expected. Also, there a slight anti-correlation between the number of investors and the the Borrower APR.
Also, It seems like the Prosper Rating is strongly correlated to the Borrower rate, meanwhile, we see that ProsperScore is distributed across all the Prosper Rating categories and so it's correlation to the Borrower Rate is deacreased.
Exploring different relationships between the features suggested that some strengthened each other, for example, shorter term durations in combination with higher Prosper Score results in decreated Borrower Rate. 


Same with the relationship between Term Durations and the Income Range, also Employment Status accompanied with Home ownership has an effect on the borrower rate. 
We also found that employment status doesn't make much difference if it's accompanied with high prosper score. However, the lower the prosper score gets,  emplyment status is then taken into consideration for deciding on the borrower rate. 
We also found that Higher Income Range with shorter term durations has lower borrower rates. 


