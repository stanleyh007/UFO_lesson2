**10 Rules** <br>
1. FieldNamingConventions
2. ClassNamingConventions
3. VariableNamingConventions
4. ShortVariable/LongVariable
5. LawOfDemeter
6. UnusedFormalParameter
7. IfStmtsMustUseBraces/ForLoopsMustUseBraces/IfElseStmtsMustUseBraces
8. AvoidDeeplyNestedIfStmts
9. EmptyCatchBlock
10. CyclomaticComplexity

**Reasons why I pick those 10 rules:** 

Rules 1-4 is most likey a naming issus, that make the codes diffcult for reader to follow, 
which will cause the misunderstanding for codes. <br>
Rule 5 is one of the important rule to follow, which is part of the **GRASP-Principle**, the low coupling. <br>
Rule 6 is the design issus, that giving a method or constructor one or more useless/unnecessary parameters, which can cause the 
misunderstanding for readers and also for who that code it. <br>
Rule 7 is the code style issus, that make the code diffcult to follow and can be a problem 
when someone needs to controll the code. <br>
Rule 8 is again a design issus, that cause the program harder to read and maintain. <br>
Rule 9 is the errorprone issus, that cause the program harder to debug, because there are not any output of errors. <br>
Rule 10 cause the same problem as rule 5, this can affects maintenance costs and readability and 
make the method hard to read and change. <br>

Those 10 rules are all about the understanding of the codes for reader and how easy are the codes to maintain.
Because this is very important in the real world, that the follows can understanding your codes.
