#Code Coverage

 Code coverage is used to describe the degree to which the code of a program is tested by a particular test case. A program with high code coverage has been more thoroughly tested and has a lower chance of containing software bugs than a program with low code coverage. Different metrics can be used to calculate code coverage; some of the most basic are the percent of program subroutines and the percent of program statements called during execution of the test suite.
To measure what percentage of code has been tested by a code coverage test case, one or more coverage criteria are used. Coverage criteria is usually defined as a rule or requirement, which test cases need to satisfy.

#######Basic Coverage criteria:
- Function coverage - Has each function in the program been called?
- Statement coverage - Has each statement in the program been executed?
- Branch coverage - Has each branch of each control structure (such as in if and case statements) been executed? 
- Condition coverage (or predicate coverage) - Has each Boolean sub-expression evaluated both to true and false?
let us explain these conditions with an example:

```
int example (int a, int b)
{
    int c = 0;
    if ((a>0) && (b>0))
    {
        c = a;
    }
    return a;
}

```

If during this execution function 'example’' was called at least once, then function coverage for this function is satisfied.
Statement coverage for this function will be satisfied if it was called e.g. as example(10,15), as in this case, every line in the function is executed including c = a;.
Tests calling example(1,1) and example(0,1) will satisfy branch coverage because, in the first case, the 2 if conditions are met and c = a; is executed, while in the second case, the first condition (a>0) is not satisfied, which prevents executing c = a;.
Condition coverage can be satisfied with tests that call example(1,1), example(1,0) and example(0,0). These are necessary because in the first two cases, (a>0)evaluates to true, while in the third, it evaluates false. At the same time, the first case makes (b>0) true, while the second and third make it false.
Condition coverage does not necessarily mean that all branches are covered. For example, consider the following fragment of code:

```
if a and b then
```

Condition coverage can be satisfied by two tests:

```
a=true, b=false
a=false, b=true
```

However, this set of tests does not satisfy branch coverage since neither case will meet the if condition.
modified coverage:
A combination of function coverage and branch coverage is called decision coverage. This criterion requires that every point of entry and exit in the program have been called at least once, and every decision in the program have taken on all possible outcomes at least once. In this context the decision is a boolean expression composed of conditions and zero or more boolean operators.
Condition/decision coverage requires that both decision and condition coverage been satisfied. This criterion extends condition/decision criteria with requirements that each condition should affect the decision outcome independently. For example, consider the following code:

```
if (a or b) and c then
```

The condition/decision criteria will be satisfied by the following set of tests:

```
a=true, b=true, c=true
a=false, b=false, c=false
```
However, the above tests set will not satisfy modified condition/decision coverage, since in the first test, the value of 'b' and in the second test the value of 'c' would not influence the output. So, the following test set is needed:

```
a=false, b=false, c=true
a=true, b=false, c=true
a=false, b=true, c=true
a=false, b=true, c=false
```
Multiple Coverage:
This criteria requires all the combinations of all the conditions need to be tested.

```
a=false, b=false, c=false
a=false, b=false, c=true
a=false, b=true, c=false
a=false, b=true, c=true
a=true, b=false, c=false
a=true, b=false, c=true
a=true, b=true, c=false
a=true, b=true, c=true

```
So, for a condition involving three variable there will be a total of 8 conditions that need to be tested.


[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/whitebox.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/fault.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
