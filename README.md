# Interest-Calculator
A Tkinter based project to calculate interest.

The following formula can be used to calculate the balance Bk after k payments (balance index), starting with an initial balance (also known as the loan principal) and a period rate r: 
Bk = [(1+r)^k] * B0 - {[(1+r)^k - 1]/r} * p
where 
rate = interest rate in percent, e.g. 3 %
i = rate / 100, annual rate in decimal form
r = period rate = i / 12
B0 = initial balance, also called loan principal
Bk = balance after k payments
k = number of monthly payments
p = period (monthly) payment
If we want to find the necessary monthly payment if the loan is to be paid off in n payments one sets Bn = 0 and gets the formula: 

p = {[(1+r)^n] * B0 - Bn }/ {[(1+r)^n] - 1}
where
n = number of monthly payments to pay back the principal loan 
