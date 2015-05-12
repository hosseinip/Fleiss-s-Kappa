# Fleiss-s-Kappa
This function is for calculating the Fleiss`s Kappa measure using C#.NET
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
Fleiss' kappa (named after Joseph L. Fleiss) is a statistical measure for assessing the reliability of agreement between a fixed number of raters when assigning categorical ratings to a number of items or classifying items. [Wikipedia]
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
An example of the Fleiss table (the input of the function):

              Category #1     Category #2     Category #3
    Subject #1    0               1               1
    Subject #2    0               2               0
    Subject #3    1               1               0
    Subject #4    1               0               1
    Subject #5    0               0               2
    
    n = 5, k = 3, m = 2
