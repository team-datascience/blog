---
id: numpy
title: numpy
sidebar_label: numpy
---
**NUMPY**

**Numpy**

 >Numpy stands for Numerical Python, is a library consisting of multidimensional array objects and a collection of routines for processing those arrays. Using NumPy, mathematical and logical operations on arrays can be performed. It also discusses the various array functions, types of indexing, etc.

**History of Numpy**

>The ancestor of NumPy, Numeric, was originally created by Jim Hugunin with contributions from several other developers. In 2005, Travis Oliphant created NumPy by incorporating features of the competing Numarray into Numeric, with extensive modifications. NumPy is open-source software and has many contributors.

**Numpy installation**

* First make sure pip has been installed on your OS. If not installed please refer article How To Install Python/Pip On Windows.

* Run pip install command to install related packages. pip install numpy. 

* Run pip uninstall command to uninstall related packages.

**Why Use NumPy ?**
* In Python we have lists that serve the purpose of arrays, but they are slow to process.

* NumPy aims to provide an array object that is up to 50x faster that traditional Python lists.

* The array object in NumPy is called ndarray, it provides a lot of supporting functions that make working with ndarray very easy.

* Arrays are very frequently used in data science, where speed and resources are very important.

**Where is NumPy used?**

> NumPy is a package in Python used for Scientific Computing. NumPy package is used to perform different operations. The ndarray (NumPy Array) is a multidimensional array used to store values of same datatype. These arrays are indexed just like Sequences, starts with zero.

**NumPy Creating Arrays**

Create a NumPy ndarray Object

* NumPy is used to work with arrays. The array object in NumPy is called ndarray.

* We can create a NumPy ndarray object by using the array() function.

```
import numpy as np

arr = np.array([1, 2, 3, 4, 5])

print(arr)

print(type(arr))

``` 




**NumPy range**

The range() function is used to generate a sequence of numbers over time

![range](assets/numpy/range.png)

****
**NumPy arange**

NumPy arange() is one of the array creation routines based on numerical ranges. It creates an instance of ndarray with evenly spaced values and returns the reference to it.
```
import numpy as np
a=np.array([0,1,2,3])                                  
print(a)
print(np.arange(10))

```
**timeit** 

timeit() method is available with python library timeit. It is used to get the execution time taken for the small code given. The library runs the code statement 1 million times and provides the minimum time taken from the set. It is a useful method that helps in checking the performance of the code.
```

a = np.arange(1000)
%timeit a**2

```

**Load Data File With NumPy**

we can load dataset using numpy.numpy. **loadtxt()** function

![load](assets/numpy/load.png)


**Shape of an Array**

The shape of an array is the number of elements in each dimension.
```

import numpy as np

arr = np.array([[1, 2, 3, 4], [5, 6, 7, 8]])

print(arr.shape)

```
**NumPy Array Reshaping**

* Reshaping arrays
* Reshaping means changing the shape of an array.

* The shape of an array is the number of elements in each dimension.

* By reshaping we can add or remove dimensions or change number of elements in each dimension.

```
import numpy as np

arr = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12])

newarr = arr.reshape(4, 3)

print(newarr)

```
**NumPy Joining Array**

* joining means putting contents of two or more arrays in a single array.

* We pass a sequence of arrays that we want to join to the concatenate() function, along with the axis. If axis is not explicitly passed, it is taken as 0.

```
 import numpy as np

 arr1 = np.array([1, 2, 3])

 arr2 = np.array([4, 5, 6])

 arr = np.concatenate((arr1, arr2))

 print(arr)

```
**Splitting NumPy Arrays**

* Splitting is reverse operation of Joining.

* Joining merges multiple arrays into one and Splitting breaks one array into multiple.

* We use array_split() for splitting arrays, we pass it the array we want to split and the number of splits.

```
import numpy as np

arr = np.array([1, 2, 3, 4, 5, 6])

newarr = np.array_split(arr, 3)

print(newarr)
```
**Searching Arrays**

* You can search an array for a certain value, and return the indexes that get a match.

* To search an array, use the where() method.

```
import numpy as np

arr = np.array([1, 2, 3, 4, 5, 4, 4])

x = np.where(arr == 4)

print(x)
```
**Sorting Arrays**

* Sorting means putting elements in a ordered sequence.

* Ordered sequence is any sequence that has an order corresponding to elements, like numeric or alphabetical, ascending or descending.

* The NumPy ndarray object has a function called sort(), that will sort a specified array.

```
import numpy as np

arr = np.array([3, 2, 0, 1])

print(np.sort(arr))

```
**Advantages NumPy**



Advantages NumPy	 |
---------|
 Broadcasting Functionality|
 Processing Speed| 
 Many Convenience Methods|
 Memory Footprint	|




