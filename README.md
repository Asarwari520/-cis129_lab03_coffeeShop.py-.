# -cis129_lab03_coffeeShop.py-.
A program that allows customer to buy their coffee and muffine
customer_order1 = int(input('number of coffee  would you like to order  ?'))
customer_order2 = int(input('number of muffin would you like to order   ?'))
coffee = '$5'
muffin = '$4'
tax = '6/100'
print('-' * 30)
#*************************************
print('number of coffee', customer_order1)
print('number of muffin', customer_order2)
print('-' * 80)
#**************************************
#*************************************
print('coffee and muffin shop recite')
print(customer_order1, 'coffee', 'each', coffee)
print(customer_order2, 'muffin', 'each', muffin)
print('%6', 'tax')
print('-' * 35)
print('your total is', customer_order1 * 5 + customer_order2 * 4 + 6/100)
