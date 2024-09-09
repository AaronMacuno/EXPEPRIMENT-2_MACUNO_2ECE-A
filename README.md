# MACUNO, Aaron Josh F. 

# PROBLEM 1:

In Problem 1, we were tasked with creating a randomized 5x5 ndarray and storing it in the variable X. Furthermore, we had to normalize the variable X and save it as X_normalized.npy. 

To proceed with this task, we were told to use the following Python calls: .mean() & .std() to obtain the element-wise mean and standard deviation (std). We were also given the following normalization formula:  Z = matrix - mean / standard deviation.  Firstly, a random 5x5 array is generated with ‘np.random.rand(5,5)’ and stored inside the variable X. It is then run through the given formula for normalization and saved in ‘X_normalized.npy’. Lastly, the code is printed in the following order: the matrix, the mean, the std, and the normalized matrix.

## Code:
![image](https://github.com/user-attachments/assets/2c0d6beb-3604-4fbd-9aea-c24cdc24a4d3)
![image](https://github.com/user-attachments/assets/5ca622b6-bb79-4f40-8aa8-4ab30426560a)

# PROBLEM 2:

Firstly, using ‘np.arrange (1,101)**2’, an array was made with the contents inside being 1-100, but each number is in its squared form (ex. 2 = 4, 3 = 9, 4 = 16); this array was then stored inside the variable A. Furthermore, using ‘A.reshape(10,10)’, the following array was arranged in a 10x10 format, and a function was created to separate and use only those numbers divisible by 3. This was achieved using indexing and the modulus syntax (%). After splitting the numbers divisible by 3 to those that are not, it is saved inside ‘div_by_3.npy’. Lastly, the code is printed in the following order: the matrix with squared values ranging from 1 to 100 and a matrix with squared values; however, only those divisible by three are included.

## Code: 
![image](https://github.com/user-attachments/assets/55de32f4-1024-4020-ac8e-5b06bc62179f)
![image](https://github.com/user-attachments/assets/7e3b6224-aad0-4ca0-99e3-df305fb68dc3)

