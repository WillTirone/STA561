# STA561 Homework 3

The homework is divided into two parts within the *.ipynb* file.

    1. Function Definition.
    2. Function Implementation.
    
 **Function Definition**
 
The function *tune_bb* is defined to take inputs to automate the tuning of blackbox regression methods, more information on the inputs is included within the function definiton. To ensure stability of the function, error cases are defined. Further, the training data is standardized to make it internally consistent. Following which regularization-specific tuning is mapped out where-in the k-fold (with a user-defined value for k) cross validation is performed to achieve optimum values for the parameters which are used to generate more data. Once, the optimum parameters are achieved and more data is generated, the existing training data is transformed and the tuned model is fitted and returned.
 
 **Function Implementation**
 
 The function is implemented on the *iris* dataset to demonstrate the function's use on two regression methods, Ridge Regression and Linear Regression with MSE and MAD/MAE as their criterions respectively. It can be observed that the coeffecients and the criterions obtained by all 3 methods when applied the two models achieve approximately the same result, with minor deviations.
 
 
Similarly, the function can be implemented on different datasets with other blackbox models to optimize a specified criterion.
