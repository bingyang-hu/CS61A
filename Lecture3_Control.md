##3.1 Print and None
-2 vs. print(-2):结果看似没有区别。
“Go Bears!” vs. print(‘Go Bears!’) : 前者带引号后者不带。
None vs. print(None):前者啥也没有后者打印出啦None.
print(print(1),print(2)): 1 2 None None

The special value None represents nothing in Python.
A function that does not explicitly return a value will return None.
None is not displayed by the interpreter as the value of an expression. (That is the reason why >>>None return nothing.)

Pure Functions and Non-Pure Functions


##3.2 Multiple Environment
A name evaluates to the value bond to that name in the earliest frame of the current environment in which that name is found.
一个name的值，是在当前envionrment中最早的frame里与这个name bond的值。

An environment is a sequence of frames:
The global frame alone
A local, then the global frame

##3.3 Miscellaneous Python Features
3.3.1 Two types of divisions
True division: / or from operator import truediv
Floor division: // or from operator import floorfiv
3.3.2 Multiple Return Values
3.3.3 Docstrings
3.3.4 Doctests

##3.4 Conditional Statement
A statement is executed by the interpreter to perform an action.
A statement consists of clauses. A clause consists of a header and suite.
E.g.

以下是一个if statement:
```Python
if x == 1:  // clause 1 的header
	return 1 // clause 1的suite
elif x ==2: //clause 2的header
	return 2//cluase 2 的suite
else: //caluse 3的header
	return 3 // clause 3的suite
```

+ Boolean value
False values in Python: False, 0, ‘ ‘,None
True values in Python:Anything else

3.5 Iteration
