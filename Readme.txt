
#Version 1.0.0
#Author: James Rao
#Time: 29/8/2015


#Version 1.0.1
#Time: 29/8/2015
#Note: 1. change method name FindEnWordsRelated into FindRelatedEnWords; 2. modify used flag at this function. make sure unused letter would be accessed by next letter.

#Version 1.0.2
#Time: 29/8/2015
#Note: 1. add class BoggleGrid and BoggleGridFlag; 2. change method names which distinguish between the first dice and others; 3. modify the error which failed to handle unused dice.

#Version 1.0.3
#Time: 29/8/2015
#Note: 1. amend the function failing to deal with unused letter; 2. change a new dictionary; 3. still can be optimised

#Version 1.0.5
#Time: 30/8/2015
#Note: 1. use Dictionary to build key point - adjacent points relationship; 2. use Route concept to record all used points, pushed when used and poped when released; 3. optimise words match algorithm, not use Contains Startwith anymore, but use self-defined dichotomy. it can run out with 1 second with 100,000 words dictionary
