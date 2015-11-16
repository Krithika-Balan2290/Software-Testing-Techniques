#Decision Table Testing

Decision Tables are a great way to model a combination of inputs and so, decision tables are very useful in formulating test cases for decision based statements. A Decision table consists of four parts:

| Conditions | Condition alternatives |
|------------|------------------------|
| Actions    | Action entries         |

Each condition can be true or false and the possible combinations of all truth values can be entered in the Condition Alternatives part of the table The actions that depend on the Conditions are entered in the Actions quadrant of the table and the Action entries specify whether the action will be perform or not and what will be the outcome of the action performed. Actions may also not depend on any of the conditions present in the table. In this case the value in the condition entry could be a ‘-‘ implying that the action does not have any dependency on that condition.

Once the decision tables have been designed in this way, they can be used to design test cases based on different conditions in the decision tables. Some of the advantages of using decision tables are <sup>[7]( https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/References.md)</sup>:

>+ Decision tables provide a systematic way of stating complex business rules, which is useful for developers as well as for testers.
>+ Decision tables can be used in test design whether or not they are used in specifications, as they help testers explore the effects of combinations of different inputs and other software states that must correctly implement business rules.
>+ It helps the developers to do a better job can also lead to better relationships with them. Testing combinations can be a challenge, as the number of combinations can often be huge. Testing all combinations may be impractical if not impossible. We have to be satisfied with testing just a small subset of combinations but making the choice of which combinations to test and which to leave out is also important. If you do not have a systematic way of selecting combinations, an arbitrary subset will be used and this may well result in an ineffective test effort.


[Prev Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/LSU.md) | [Next Page](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Docs/pairs.md)
 
 [Back to contents](https://github.com/Krithika-Balan2290/Software-Testing-Techniques/blob/master/Index.md)
