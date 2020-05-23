# ProsperLoanData Exploration

## Dataset

The dataset shows the loan dadata for 113937 listing and has 81 variables including listing Key, loan status, borrowerAPR and so on.


## Summary of Findings

There is no unusual unusual points in the data, most of the variables has long-tailed distribution which fit our common sense. In addition, the distribution of income range very similar to normal distribution and shows the the common income range of listing between 25,000 - 74,999. 
There is no unusual distributions in the data, however, the distribution of 'DelinquenciesLast7Years' variable and 'LoanCurrentDaysDelinquent' variable not only shows the long-tailed attribute but also shows that most of the listing has 0 delinquencies.

Although there seems to be no linear relationship between 'LoanCurrentDaysDelinquent' with other numerical variables, however,by taking look at the scatter plot, we could find that 'LoanCurrentDaysDelinquent' shows some really interesting attributes. For instance, we could see that when 'recommendations', 'MonthlyLoanPayment' and 'investors' exceeds certain point, the 'LoanCurrentDaysDelinquent' drop to 0. 
In addition, from the boxplot we could see that the lower the 'CrreditGrade', the higher the 'LoanCurrentDelaysDelinquent' could be.From the ListingCategory boxplot, we could see that type 4 personal loan has higher 'LoanCurrentDelaysDelinquent' compared to others.From the 'IncomeRange' plot we could see that incomerange with 0 are more likely to have higher 'LoanCurrentDelaysDelinquent' compared to others. 

Generally, as 'MonthlyLoanPayment' increases and exceeds 1000, the 'LoanCurrentDaysDelinquent' will drop significantly. However, this only applied to listing with employed 'EmploymentStatus'. 
Even though 'investors' increases,this does not lower the 'LoanCurrentDaysDelinquent' with HR 'CreditGrade'.

## Key Insights for Presentation

We expect that if one listin has no 0 'DelinquenciesLast7years', he/she should have less 'LoanCurrentDaysDelinquent'. However, there is no relationship between this with 'LoanCurrentDaysDelinquent', since even 'DelinquenciesLast7years' is 0, the 'LoanCurrentDaysDelinquent' has many different values. 

Besides, We expect that 'Not-employed' tends to have higher 'LoanCurrentDelaysDelinquent'. However,we could see that 'retired' employment status tends to have higher 'LoanCurrentDelaysDelinquent' compared to others.
