

import pdb

def sum_values(a, b):
    return a + b

def test_function():
    pdb.set_trace()  #we have added a breakpoint here. The code pause execution here.
    print('This is the first line')
    print("This is the second line.")
    value  = sum_values(2,1)
    print('The code is done!')
    return value 


test_function()
############### OUTPUT ######################

test_function()
This is the first line
This is the second line.
The code is done!
3
