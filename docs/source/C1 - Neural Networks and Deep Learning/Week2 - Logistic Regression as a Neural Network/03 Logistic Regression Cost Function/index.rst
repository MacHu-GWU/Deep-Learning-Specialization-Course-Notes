Logistic Regression Cost Function
==============================================================================
传统的LMS误差对于二值分类来说不是一个好的Cost Function，因为会导致Cost Function Non Convex。

逻辑回归的Cost Function长这个样子：``Cost(y', y) = - ( y * log(y') + (1 - y) * log(1 - y') )``

我们的参数优化目标就是Minimize Cost Function的值。