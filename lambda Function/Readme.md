


# calculate multiplication using lambda
multiplication = lambda x: x*x
print('Using lambda multiplication (5): ', multiplication(5))

# calculate exponent using lambda
exponent = lambda x: x**x
print('Using lambda exponent (5): ', exponent(5))

# power function 
pow_1= pow(2, 3)
print("The result of power pow(2, 3) = " ,pow_1)
 
 ###################### OUTPUT #################################################
 
Using lambda multiplication (5):  25
Using lambda exponent (5):  3125
The result of power pow(2, 3) =  8


############################# LAMBDA FUNCTION FOR FACTORIAL #####################

import math 
print ("Log value for base 10: ") 
print (math.log10(2))

# factorial function in lamdba function
x = lambda num : 1 if num <= 1 else num*x(num-1)
number = int(input('Enter number: '))
print('%d != %d' %(number, x(number)))

######################################### OUTPUT #################################

Log value for base 10: 
0.3010299956639812

Enter number: 5
5 != 120



