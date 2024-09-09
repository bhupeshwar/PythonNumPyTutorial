# Python NumPy Tutorial

# What is NumPy?

NumPy is a scientific computing package (library) for python programming language.

Numpy is a powerful Python programming language library to solve numerical problems.

# What is the meaning of NumPy word?

Num stands for numerical and Py stands for Python programming language.

Python NumPy library is especially used for numeric and mathematical calculation like linear algebra, Fourier transform, and random number capabilities using Numpy array.

NumPy supports large data in the form of a multidimensional array (vector and matrix).

# Prerequisites to learn Python NumPy Library
NumPy Python library is too simple to learn. The basic python programming and its other libraries like Pandas and Matplotlib knowledge will help to solve real-world problems.

Some basic mathematics like vector and metrics are plus point.

# Representation of NumPy multidimensional arrays

![image](https://github.com/user-attachments/assets/835ab9eb-d1d2-4ae8-bb64-c51d5997cf93)


# Why NumPy array instead of Python List ?
If you observe in Fig 1.1. To create a NumPy array used list. NumPy array and Python list are both the most similar. NumPy has written in C and Python. That’s a reason some special advantage over Python list is given below.

Faster
Uses less memory to store data.
Convenient.


# Why use NumPy for machine learning, Deep Learning, and Data Science?

![image](https://github.com/user-attachments/assets/e3262114-e505-4fc6-8dc0-da4fef05a68f)


To solve computer vision and MRI, etc. So for that machine learning model want to use images, but the ML model can’t read image directly. So need to convert image into numeric form and then fit into NumPy array. which is the best way to give data to the ML model.

![image](https://github.com/user-attachments/assets/8c405db7-c600-41ac-8815-eb12f0047116)


Machine Learning model also used to solve business problems. But we can’t provide ‘.tsv’, ‘.csv’ files data to the ML model, So for that also need to use NumPy array.


# Practical Session of Python NumPy Tutorial

How to install Python NumPy Library (package)?
To use the NumPy package first of all need to install it.

If you installed Anaconda Navigator and launched Jupyter Notebook or Spyder then no need to install NumPy. Anaconda Navigator installed NumPy itself. If you are using another IDE instead of Anaconda Navigator then follow below command in command prompt or terminal to install Python NumPy Library (Package).


<code> pip install numpy </code>


While entering the above command, your system has an internet connection because ‘pip’ package download ‘numpy’ package and then install it. After successful installation, You are ready to take the advantages of the NumPy package.

How to import NumPy Library in IDE or How to use it?
To use NumPy first import it. For import NumPy, follows below syntax in the python program file.

1
import numpy as np
import: import keyword imports the NumPy package in the current file.

as:  as is a keyword used to create sort name of NumPy.

np: np is a short name given to NumPy, you can give any name (identifier) instead of it. If we use NumPy name in the program repeatedly so it will consume typing time and energy as well so for that we gave a short name for our convenience.
