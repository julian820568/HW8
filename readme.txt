Base on algorithm SimpleCART, I tried to change the the way we calculate impurity
from using "gini index" to using "entropy".

In "IKDDhw8.java", I rewrite function "computeGini" so this function return 
entropy instead of gini index, and I did not change the function name.

In function "toString", I put a little change so "IKDDhw8.java" can output the
entropy when it ends.