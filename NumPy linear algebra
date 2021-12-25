# -*- coding: utf-8 -*-
"""
Created on Fri Dec 24 15:36:37 2021

@author: lc
"""

# -*- coding: utf-8 -*-
"""
Created on Sun Apr  5 14:58:07 2020

@author: sana.rasheed
"""
import numpy as np

# linear algebra 
import numpy.linalg as la 

my_mat = np.array([[1,2], [3,4]])
# calculate determinant
det = la.det(my_mat)
# calculate inverse of a matrix. Inv = adj(matrix)/det(matrix). NOTE: Make sure its not SINGULAR!
inverse_mat = la.inv(my_mat)
# calculate eigen values. NOTE: make sure the matrix is SQUARE [eigen values do not exit for matrix whose dimensions are mxn where m!=n]!
eig_values, eig_vectors = la.eig(my_mat)
# calculate cholesky factorization. NOTE: make sure matrix is Positive Definite!
cholesky = la.cholesky(np.array([[7,2], [2,1]]))
# calculate rank of a matrix. Rank of a matrix is the number of linearly independent columns/rows in a matrix.
rank = la.matrix_rank(my_mat)

########################################################### output ######################################################################

Python 3.8.8 (default, Apr 13 2021, 15:08:03) [MSC v.1916 64 bit (AMD64)]
Type "copyright", "credits" or "license" for more information.

IPython 7.22.0 -- An enhanced Interactive Python.

my_mat = np.array([1,2], [3,4])
Traceback (most recent call last):

  File "<ipython-input-1-11eb5b331796>", line 1, in <module>
    my_mat = np.array([1,2], [3,4])

NameError: name 'np' is not defined


runcell(0, 'D:/numpy linear algebra.py')
Traceback (most recent call last):

  File "D:\numpy linear algebra.py", line 19, in <module>
    my_mat = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


eig_values, eig_vectors = la.eig(my_mat)
Traceback (most recent call last):

  File "<ipython-input-3-5909c4cf6910>", line 1, in <module>
    eig_values, eig_vectors = la.eig(my_mat)

NameError: name 'my_mat' is not defined


my_mat = np.array([1,2], [3,4])
Traceback (most recent call last):

  File "<ipython-input-4-11eb5b331796>", line 1, in <module>
    my_mat = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


runcell(0, 'D:/numpy linear algebra.py')
Traceback (most recent call last):

  File "D:\numpy linear algebra.py", line 19, in <module>
    my_mat = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


my_mat
Traceback (most recent call last):

  File "<ipython-input-6-d6989c2243e1>", line 1, in <module>
    my_mat

NameError: name 'my_mat' is not defined


runcell(0, 'D:/numpy linear algebra.py')
Traceback (most recent call last):

  File "D:\numpy linear algebra.py", line 19, in <module>
    my_mat = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


det = la.det(my_mat)
Traceback (most recent call last):

  File "<ipython-input-8-68c0c70e7470>", line 1, in <module>
    det = la.det(my_mat)

NameError: name 'my_mat' is not defined


my_mat = np.array([1,2], [3,4])
Traceback (most recent call last):

  File "<ipython-input-9-11eb5b331796>", line 1, in <module>
    my_mat = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


runcell(0, 'D:/numpy linear algebra.py')
Traceback (most recent call last):

  File "D:\numpy linear algebra.py", line 19, in <module>
    my_matt = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


my_matt = np.array([1,2], [3,4])
Traceback (most recent call last):

  File "<ipython-input-11-d5ba10f139e5>", line 1, in <module>
    my_matt = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


my_mat = np.array([1,2], [3,4])
Traceback (most recent call last):

  File "<ipython-input-12-11eb5b331796>", line 1, in <module>
    my_mat = np.array([1,2], [3,4])

TypeError: Field elements must be 2- or 3-tuples, got '3'


my_mat = np.array([1,2,3], [3,4,7])
Traceback (most recent call last):

  File "<ipython-input-13-e501e7aaf76d>", line 1, in <module>
    my_mat = np.array([1,2,3], [3,4,7])

TypeError: Field elements must be 2- or 3-tuples, got '3'


runcell(0, 'D:/numpy linear algebra.py')
Traceback (most recent call last):

  File "D:\numpy linear algebra.py", line 19, in <module>
    my_mat = np.array([1,2,3], [3,4,7])

TypeError: Field elements must be 2- or 3-tuples, got '3'


runcell(0, 'D:/numpy linear algebra.py')
Traceback (most recent call last):

  File "D:\numpy linear algebra.py", line 19, in <module>
    my_mat = np.array([1,2,3], [3,4,7])

TypeError: Field elements must be 2- or 3-tuples, got '3'


my_mat = np.array([[1,2], [3,4]])

my_mat
Out[17]: 
array([[1, 2],
       [3, 4]])

det = la.det(my_mat)

det
Out[19]: -2.0000000000000004

inverse_mat = la.inv(my_mat)

inverse_mat
Out[21]: 
array([[-2. ,  1. ],
       [ 1.5, -0.5]])

eig_values, eig_vectors = la.eig(my_mat)

eig_values
Out[23]: array([-0.37228132,  5.37228132])

eig_vectors
Out[24]: 
array([[-0.82456484, -0.41597356],
       [ 0.56576746, -0.90937671]])

cholesky = la.cholesky(np.array([[7,2], [2,1]]))

cholesky
Out[26]: 
array([[2.64575131, 0.        ],
       [0.75592895, 0.65465367]])

rank = la.matrix_rank(my_mat)

rank
Out[28]: 2


