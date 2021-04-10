# ML-Bootcamp

### 1. Linear and Logistic Regression

_First and foremost, explored Python (Source- W3Schools) in order implement the algorithms efficiently, and completed the 5 week Andrew Ng course._

a).Tried writing the mathematical code of gradient descent, by using matrices ( by numpy library), using for loops for iterations and for nested loop for calculating theta (parameter) matrix in a single iteration.

b). Normalized the data to bring it into a single scale (0 to 1), cleaved the data into training and test sets by using the sklearn library's train test split.

c). Calculated and printed the cost/error using the cost function.

d). Defined a single function for gradient descent and cost function for simplicity of inputing the data by the user (like how many iterations, learning rate, etc)

e). Plotted an error v/s iterations graph using the matplotlib library to make the work presentable.

#### Observations:
Tried many values of iterations and learning rate, to try and observe what change does it cause in the error/cost and how does the graph of error v/s iterations varies with their different values. Greater values of learning rate caused the cost function to be constant and subsequenly increased after alpha was increased further. 
Increased number of iterations caused the cost v/s iterations graph to have a negative slope i.e. cost decreased with each passing iteration.

Tried values of iterations- 5,10,20 and 50 ; and values of alpha tried- 1, 0.1, 0.0000001, 0.00000000000000001 for each iteration.

Tried to run the code with and without normalization of data, to know how the run time of code and the result is affected.

Also tried calculating the hypothesis without splitting the data into train and test sets, and observed the error and graph in that case, comparing it with the the case when data was splitted.

#### Problems faced:
Code took hell lot of time to run {around 8 hours for 50 iterations and learning rate= 10^(-17)}, so had to wait and spend a lot of time upon it, just to observe what output the code gives, while also dealing with continuously disconnecting google colab due to internet issues. Hence was not able to explore higher iterations and reach the minima of the cost function.

Error observed is higher than expectations, so probably a bug in the code, but couldn't figure out what.

### 2. KNN (K-Nearest Neighbours)

Loaded the data, split it into training and test data sets.

Defined a function to find out the nearest k neighbours of the point that shall be inputed by the user. The distance between the test/input point and all the training points calculated uing the Euclidean Distance formula, and then printing the nearest k neighbours and along with their index(in the training set).

The distance between the test point selected and all the training points calculated by using the for loop, and therefore printing the nearest neighbours.

#### Observations
 Tried taking multiple values of K (2,4,6,8...) in the defined function, and also tried inputing different test data points and observing their nearest neighbours.
 
 Later, also printed the K (=4) nearest neighbours of all the test data points in a single code using the for loop, and observing the distances at once.





