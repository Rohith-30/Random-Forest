# Random-Forest
Have performed Regressive type Random Forest on the Boston dataset, wherein medv is the label and there are 13 attributes.   
Algorithm for Random Forest was created from scratch without using any direct libraries.
100(B) Bootstrapped Training Sets (BTS) were created, for which each BTS was trained for a decision tree with a height of h = 3 and at each node, only a sample of attributes were considered, i.e., p/3 where p is the number of atrributes.
Training MSE and Test MSE were determined, after which the same were calculated for different values of B and h.
