You are a Data scientist working for a consulting firm. One of your colleagues from the auditing dept has asked you to help them access the financial statement of organisation X.

You have been supplied with 2 lists of data: monthly revenue and monthly expense for the financial year in question. Your task is to calclate the following financial metrices:

Profit for each month.
Profit after tax for each month (the tax rate is 30%).
profit margin for each month- equals to profit after tax divide by revenue.
Good months- where the profit after the tax was greater than the mean for the year.
Bad months- where the profit after the tax was lesser than the mean for the year.
The best month- where the profit after the tax was max for the year.
The worst month- where the profit after the tax was min for the year.

All reslts need to be presented as lists

Results for dollars values needs to be calculated with $0.01 precision, but need to be presented in units of $1000 (ie., 1K) with no decimal points.

Results for the profit margin ration need to be presented in units of % with no decimal points

Note: Your colleague has warned you that it is okay for tax for any given month to be negative (in accounting terms, negative tax translates into a deferred tax asset)

Dataset:
  Revenue: [14574.49,7606.46,8611.41,9175.41,8058.65,8105.44,11496.28,9766.09,10305.32,14379.96,10713.97,15433.50]
  Expenses: [12051.82,5695.07,12319.20,12089.72,8658.57,840.20,3285.73,5821.12,6976.93,16618.61,10054.37,3803.96]
