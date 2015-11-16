#Software Testing Methodologies

##White Box Testing

White box testing is a testing technique where the implementation, design or internal structure of the item being used is known to the tester. The tester chooses the inputs such that all the paths of the code are exercised and the appropriate results are determined. Programming details and the tester should know how to code. White box testing goes into the nitty- gritty of the code and tests beyond the user interface of the code.
The white box testing is like a clear box where all the details of the application or product are known to the tester at the code level.

#####White Box testing technique:
Procedure to derive a test case based on the analysis of the internal structure of the code.

#####Example:
A tester, usually a developer as well, studies the implementation code of a certain field on a webpage, determines all legal (valid and invalid) AND illegal inputs and verifies the outputs against the expected outcomes, which is also determined by studying the implementation code.
White Box Testing is like the work of a mechanic who examines the engine to see why the car is not moving.



##Black Box Testing

Black box testing is a behavioral testing methodology by which the internal structure, design or implementation of the software is not known to the tester. These tests can either be functional or non-functional but are generally functional in nature.
Black box testing is named so because, the tester does not know what the software program, to him it is like a black box where he only knows the input and the expected output.
Black box testing attempts to find errors in the following areas:

- Incorrect or missing functions
- Interface errors
- Errors in data structures or external database access
- Behavior or performance errors
- Initialization and termination errors

#####Black box testing techniques:
It is the process to derive or select test cases based on the analysis of the specification, either functional or non functional, of a component or structure without reference to its internal structure.
- Equivalence partitioning:In equivalence partitioning, the given test data is divided into valid and invalid test data. One value from each data set is selected as the representative for the particular data set.
- Boundary value analysis:It is a software test design technique that involves determination of boundary values and selecting values that are just inside or outside or at the boundary of the test data
- Cause effect graphing: It is a software test design technique that involves identifying the input(cause) and the outputs(effect) and then producing a cause- effect graph and generating test cases accordingly.

#####Example:
A tester, without knowledge of the internal structures of a website, tests the web pages by using a browser; providing inputs (clicks, keystrokes) and verifying the outputs against the expected outcome

##Gray Box Testing

Gray Box testing is a testing method which is a combination of white box and black box testing.  In gray box testing the internal structure is partially known. This involves having access to the internal data structures and algorithms at high level for the purpose of designing test cases, but the testing, at the user or black box level.
Gray box testing is named so because the internal structure of the program is partially known, it is like a gray box whose contents are partially known.

#####Example:
An example of Gray Box Testing would be when the codes for two units/ modules are studied (White Box Testing method) for designing test cases and actual tests are conducted using the exposed interfaces (Black Box Testing method).

[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/Intro.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/whitebox.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
