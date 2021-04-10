# ML-Bootcamp

### 1. Linear and Logistic Regression

_First and foremost, explored Python (Source- W3Schools) in order implement the algorithms efficiently, and completed the 5 week Andrew Ng course._

a).Tried writing the mathematical code of gradient descent, by using matrices ( by numpy library), using for loops for iterations and for nested loop for calculating theta (parameter) matrix in a single iteration.

b). Normalized the data to bring it into a single scale (0 to 1), cleaved the data into training and test sets by using the sklearn library's train test split.

c). Calculated and printed the cost/error using the cost function.

d). Defined a single function for gradient descent and cost function for simplicity of inputing the data by the user (like how many iterations, learning rate, etc)

e). Plotted an error v/s iterations graph using the matplotlib library to make the work presentable.

##### Observations:
Tried many values of iterations and learning rate, to try and observe what change does it cause in the error/cost and how does the graph of error v/s iterations varies with their different values. Greater values of learning rate caused the cost function to be constant and subsequenly increased after alpha was increased further. 
Increased number of iterations caused the cost v/s iterations graph to have a negative slope i.e. cost decreased with each passing iteration.

Tried values of iterations- 5,10,20 and 50 ; and values of alpha tried- 1, 0.1, 0.0000001, 0.00000000000000001 for each iteration.

Tried to run the code with and without normalization of data, to know how the run time of code and the result is affected.

Also tried calculating the hypothesis without splitting the data into train and test sets, and observed the error and graph in that case, comparing it with the the case when data was splitted.



