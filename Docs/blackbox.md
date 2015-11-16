#Black Box Software Testing Techniques

#Monkey Testing

Random testing is one of the categories of testing that falls under the classification of black box testing. Random inputs are given to a system to test the general performance of the system independent of other test cases. One such random testing technique is Monkey Testing. Monkey testing is performed by entering completely random strings as input. This is done to check how the system responds in case garbage data is provided as input. The input given is similar to something a monkey would type when it has access to a computer, hence the name “Monkey Testing”.

There are two types of monkeys in Monkey Testing<sup>[1]( https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/References.md)</sup>:

#####Smart Monkeys

+ Have a brief idea about the application
+ They know that the inputs they are providing are valid or invalid.
+ They work or focus to break the application.
+ They are aware of the menus and the buttons.
+ Good to do stress and load testing.

#####Dumb Monkey

+ They have no idea about the application.
+ They don’t know that the inputs they are providing are valid or invalid.
+ They test the application randomly and are not aware of any starting point of the application or the end to end flow.
+ They don’t have much idea about the UI and functionality

There are four different categories of Money Testing<sup>[2]( https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/References.md)</sup>:

#####Monkey Button Push Testing

This kind of testing requires a testing procedure to be repeated over and over again without any intellectual effort by the tester. The tester needs to just follow the step by step procedure and verify that the result is accurate.

#####Smart Monkey Testing

Smart Monkey testing generates inputs based on the expected usage statistics. Thus the inputs are not completely random, but are based on real world user behaviors. These inputs may be generated using different IQ levels of the monkey doing the testing. The lowest IQ level generates each input to the system independent of all the other inputs. The highest IQ level testing generates correlated inputs based on usage statistics of all the inputs to the system. 

#####Brilliant Monkey Testing

This type of Monkey testing has the highest IQ level of the tester monkey. Similar to Smart Monkey Testing, the inputs are generated based on probability distributions based on actual usage of the system. In addition, the sequence of inputs given also depends on the usage statistics for the system, whereas in Smart Monkey Testing, each input was considered to be an independent scenario.

#####Dumb Monkey Testing

This type of Monkey testing has the highest IQ level of the tester monkey. The inputs are generated without any regard to the usage statistics and hence, this method of testing is very random.

[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/static.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/fuzz.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
