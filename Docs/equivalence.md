#Equivalence Partitioning

Equivalence Partitioning is a technique of software testing where the input data to a software system can be partitioned into sets of equivalent data. The test cases are then derives from each of these partitioned. This technique helps reduce the time needed for testing by reducing the number of test cases to one for each type of error that could be in the software system. Typically, the partitioning of test data is done on the inputs and not on the outputs and the partitioning is typically based on the attributes of the inputs specified in the requirements.
For example, consider a function which takes two integers as input and calculates the greatest common divisor:

`int gcd(int a, int b);`

Some possible classes of input could be:

+ `a` and `b` are both positive integers
+ `a` is positive and `b` is negative
+ `a` is negative and `b` is positive
+ `a` and `b` are both negative
+ `a` and `b` are relatively prime
+ `a` is positive and `b` is zero
+ `a` is zero and `b` is positive
+ `a` and `b` are both zero

The input range may be valid or invalid. For example, in the above instance a floating point value of `a` would be invalid. The test cases can be taken even from invalid partitions. This helps to check the behavior of the program in case incorrect input is provided. In the above example, we could see if the program handles receiving floating point numbers as input to the `gcd()` function or if it results in the failure of the program. 

Only one test case is necessary from each partition. Taking multiple cases from a single partition does not help in finding more faults in the system. The additional test cases would be redundant. So, instead of testing multiple cases from the same partition, the tester could focus on some invalid partitions and see how the program behaves then. This results in a much more thorough testing with fewer test cases.

Although Equivalence partitioning comes under black box testing, it can also be implemented as a grey box testing technique. If the tester has some idea of the implementation of the system, he would be able to partition the inputs much better. Also, Equivalence partitioning alone is not enough to obtain the test cases. Once the partitions are made, we also need to perform a boundary value analysis to select the best possible values of the inputs from these partitions.

[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/pairs.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/boundary.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
