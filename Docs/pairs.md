#All Pairs Testing

All-Pairs Testing is an efficient way of test all the combinations of input without having to test all the possible combinations. This technique involves testing all possible combinations for each pair of input parameters to a system. This results in a thorough testing with a lot less test cases than if all possible combinations were considered. For example, consider the following set of inputs<sup>[8]( https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/References.md)</sup>:

| Parameter Name | Value 1 | Value 2 | Value 3 | Value 4 |
|----------------|---------|---------|---------|---------|
| var1           | True    | False   | -       | -       |
| var2           | 1       | 2       | 3       | -       |
| var3           | a       | b       | c       | d       |

Taking a combinations of all possible values of all three parameters would result in (2*3*4) = 24 combinations. On the other hand, if we take the All-pairs approach, it results in only as many test cases as the product of the possible values of the two parameters with the largest number of values. In this case the total number of test cases using the all pairs approach would be 3*4 = 12.

In the All Pairs approach, we take all possible values of each pair of parameter and combine these to get the total number of test cases. In this example, the possible pairs are var1 and var2, var2 and var3, and var1 and var3. The possible combinations of values of these pairs would be as follows:

######var1 and var2 Pair

| var1               | var2 |
|--------------------|------|
| True               | 1    |
| False              | 1    |
| True               | 2    |
| False              | 2    |
| True               | 3    |
| False              | 3    |

######var1 and var3 Pair

| var1               | var3 |
|--------------------|------|
| True               | a    |
| False              | a    |
| True               | b    |
| False              | b    |
| True               | c    |
| False              | c    |
| True               | d    |
| False              | d    |

######var2 and var3 Pair

| var2               | var3 |
|--------------------|------|
| 1             | a    |
| 2              | a    |
| 3               | a    |
| 1              | b    |
| 2               | b    |
| 3              | b    |
| 1               | c    |
| 2              | c    |
| 3              | c    |
| 1               | d    |
| 2              | d   |
| 3              | d    |

Combining these three test case combinations, we get a complete set of 12 test cases as:

| var1  | var2 | var3 |
|-------|------|------|
| True  | 1    | a    |
| False | 1    | b    |
| True  | 1    | c    |
| False | 1    | d    |
| False | 2    | a    |
| True  | 2    | b    |
| False | 2    | c    |
| True  | 2    | d    |
| True  | 3    | a    |
| False | 3    | b    |
| True  | 3    | c    |
| False | 3    | d    |



[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/Decision.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/equivalence.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
