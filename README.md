

# **![image](https://github.com/CLAREISMO/Machine-Learning-Fundamentals/assets/63759427/4f05d5a8-920b-49f8-afb5-8e0d19da3fff)**<img src="https://media.tenor.com/eT_e-q0D5xoAAAAi/long-livethe-blob-sunglasses.gif" width="50px">


**In this repository, you will find the basics that every enthusiastic programmer needs to enter the amazing world of Machine Learning!**

**I will apply in all the development the most popular automatic differentiation libraries Pytorch and Tensorflow and of course, I will work in the most important programming language in ML Python, which is the base of these amazing libraries.**

**Enjoy!﻿**



## ***Data Structures for Algebra***


###**Introduction**



### ![image](https://github.com/CLAREISMO/Machine-Learning-Fundamentals/assets/63759427/9185fb8a-f966-423e-a849-61e0e4b0940c)

The most common data structure in linear algebra for machine learning is the tensor. Tensors are just a machine learning generalization of vectors or matrices to any number of dimensions.

+ The zero-dimensional tensor is called a scalar-tensor and is a single numerical value. Like the number 25. 

+ A vector tensor is a one-dimensional tensor. It has values in a specific order. It's an ordered list of values. And let's say this vector right here has a length of three. And its elements are X1 X2 X3, all three elements are scalar values. 

+ Going up another dimension, we have matrices. So a tensor matrix has two dimensions. It has a height and a width. So here's a two-by-two tensor matrix with one, two, three four individual elements. We'll talk about the details of numbering and notation later on. 

+ After that, you can continue to generalize to higher dimensional tensors. So this is a tensor of three, for example, a cube. It has one, two, three, four, five, six, seven, and then an eighth element hidden in the back. So it's a tensor of three, two by two by two by two, two wide, two high, two deep. Yeah, so this kind of generalization can go to higher dimensions. You can have four tensors, five tensors, 100 tensors, and 1000 tensors, but it's getting harder and harder for me to draw beyond a 3-tensor.

**We can conclude from the above that:**

+ A zero-dimensional tensor, we can mathematically call it a scalar and represents magnitude only. Just as the number 25 is a single value here. It could mean 25 meters. It represents magnitude only, size only. 

+ A one-dimensional tensor is a vector, and this is typically an array of numbers. And I should also say here that it doesn't have to be typically integers or stream values. It could be strings or character strings, but in machine learning it's typically numerical values, typically float values. So a vector tensor is likely to be a matrix of numbers, a one-dimensional array of numbers. 

+ A two-dimensional tensor is a matrix like a flat table, for example, a square or rectangle, a two-dimensional set of values. 


- And then in three dimensions, we have a three-dimensional tensor which is like this cube drawn here, or like a 3D table. 

+ And then in higher dimensionalities in n dimensions, we call this an n-tensor. So if it's six-dimensional, then it's a 6-tensor. And yes, this is higher dimensional and harder to visualize.


![image](https://github.com/CLAREISMO/Machine-Learning-Fundamentals/assets/63759427/3b5e0137-5bdc-4eb7-9162-e4d52fa74d28)



### 1. Scalars (Rank 0 Tensors) in Base Python ###


The simplest type of tensor has a dimension of zero and is called a scalar. Therefore a scalar is a single number that is denoted in lowercase and italics.

**Example:**

![image](https://github.com/CLAREISMO/Machine-Learning-Fundamentals/assets/63759427/412dd9db-4e84-468a-9a67-a1e7b4f1dbb5)


The simplest type of tensor has a dimension of zero and is called a scalar. Therefore a scalar is a single number that is denoted in lowercase and italics.

In VSC we can see how the scalar x is assigned the value of 25 and we print its type which is int.

Likewise, we create another scalar named with the letter y which is assigned the value of 3. 

We make the sum between the scalars x and y. We obtain as a result the value 28 which is stored in the variable sum. When we print the type of this variable we obtain the type int. This is due to the fact that both variables are of type integer.

We also observe the creation of the variable x_float which stores the quantity 25.0 and is of floating type when we add it with the variable y we obtain the quantity 28.0 of scalar type. This result is expected since it is typical behavior of the Python language; if we add an int with a float Python by default transforms the int to a float type value so the operation is performed between two float type values and the result will be a float type quantity.

We can see the output below:

![image](https://github.com/CLAREISMO/Machine-Learning-Fundamentals/assets/63759427/3c877cb5-10e1-4e28-8f40-924b259de424)




###2. Scalars in PyTorch###

First, we have to install the Pytorch library with the following steps
1. Upgrade pip with the command: python.exe -m pip install --upgrade pip
2. Create a virtual environment, if you have never created a virtual environment you can follow this video: https://www.youtube.com/watch?v=aJggnCVeacs
3. Install the library with the following command: pip install torch

The process is shown below  in my case I already have an env created from the beginning of the project, for this reason, there is no evidence of the creation at this point:

![image](https://github.com/CLAREISMO/Machine-Learning-Fundamentals/assets/63759427/40a5e704-14bb-4bc6-aa5e-a69200b79962)

![image](https://github.com/CLAREISMO/Machine-Learning-Fundamentals/assets/63759427/7a20a2fa-b696-4dff-a345-a9eb96c349c5)








﻿

🤝








 






