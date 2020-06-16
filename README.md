CURRENCY SUM VALIDATOR

A function bill_count that takes two arguments. The first argument is the amount of money the user has and the second 
is the list of money bills available. It returns the minimum count of money bills required to equal the user money amount.

The key is to verify the input arguments, such that 1) Amount of money is greater than 2) List of Money Bills
available because the vice versa is an invalid condition. Also make sure that there are no negative value inputs and the 
List of Money Bills are to be taken from Standard Indian Currency System.

Example :

bill_count(1001,[1,10,20])
# User Money = Rs 1001 and Bills Available = [Rs 1, Rs 10, Rs 20]

bill_count(1001, [1, 10, 20]) ->51 because 20 * 50+ 1 * 1 = 1001
# We require 50nos of  20Rs bill and 1 no of 1Rs bill to equal Rs 1001.
# Therefore, Minimum Count Money Bills is 50 + 1 = 51.
