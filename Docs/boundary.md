#Boundary Value Analysis

Boundary value analysis involves dividing the input set into partitions and then selecting input values for testing such that the values lie near the boundary of the partition. This is similar to Equivalence Partitioning where the input data to a software system is partitioned into sets of equivalent data. Each partition is then called the basis. Since the basis sets are placed next to each other, we can select test values from the values which are on each side of the boundary between two basis sets. This technique of Software testing is called Boundary Value analysis.

For example, consider the function which takes two integers as input and calculates the greatest common divisor:

`int gcd(int a, int b);`

 We can divide the input test set into the following partitions:
 
+ `a` and `b` are both positive integers
+ `a` is positive and `b` is negative
+ `a` is negative and `b` is positive
+ `a` and `b` are both negative
+ `a` is positive and `b` is zero
+ `a` is zero and `b` is positive
+ `a` and `b` are both zero

Taking the Boundary values from each class, we can get the inputs to be:

+ `a = 1` and `b = 1` 
+ `a = 1` and `b = -1`
+ `a = -1` and `b = 1`
+ `a = -1` and `b = -1`
+ `a = 1` and `b = 0`
+ `a = 0` and `b = 1`
+ `a = 0` and `b = 0`

For each partition, test cases must be generated so that they cover each side of a given boundary. This means that there are two test cases for every boundary in the input set. The boundary value must be the largest or the smallest value at the boundary of the partition. Although equivalence partitioning encourages the selection of test cases from invalid partitions, boundary value analysis does not need the same. The test cases are designed in such a way that any value in the invalid test set can be handled by the software system appropriately. 


[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/equivalence.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/graph.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
