#Cause Effect Graph

One technique of software testing is to map the inputs to the outputs of the program. In this case, the inputs are the causes and the outputs are the effects. We thus, get a directed graph from the inputs to the outputs. Intermediate node may be present to combine multiple inputs to generate one output. These intermediate nodes may combine the multiple inputs using logical operations.

It is possible to have some constraints on the causes and the effects. The constraint are represented using labels alongside a dashed line connecting the two causes or the two effects. Although all required constraints ca be represented using AND, OR and NOT, some additional constraints may be used. For example, the exclusive constraint which ensures that not more than one cause is true; the Inclusive Constraint which ensures that at least one cause is true; the One and Only One constraint which ensures that exactly one of the causes is true and the Requires constraint which ensures that if the first cause is true, then the second cause must be false.

Constraints can also be added on the effects. A valid constraint for the effects is Mask which masks the output in effect 1. The constraint Mask from effect 1 to effect 2 ensures that if effect 1 is true, then effect 2 is false. The constraint Mask is applicable only on effects. A graph can be structured in such a way that there is only one intermediate node between an input and an output. This graph can then be used to generate a decision table which can then be used to perform decision table testing.


#Error Guessing

One technique of software testing is Error Guessing which is employed by very experienced testers. Error guessing is a software testing technique in which experienced and good testers think of situations in which the software may not function correctly. In this method, the tester draws from his past experience with software systems to guess the type of problems that typically occur in software systems. Some common errors found his way are DivideByZero exceptions, NullPointer exceptions and more. The test cases could be generated from the program specifications or from some unexpected error that occurs during testing.

The success of Error guessing depends on the skill of the tester. The better the tester, the more likely they are to guess where the errors can be found. Error guessing technique can be very effective when applied after more formal techniques have already been used. While using the more formal techniques of system testing, the tester gains a better understanding of the system that is being tested. Then, the tester becomes better at guessing where the more hidden errors can be found. The tester can then list all the possible things that can go wrong with the system and then build test cases around these potential failures.


[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/boundary.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/References.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
