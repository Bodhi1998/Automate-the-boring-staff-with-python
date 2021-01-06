# Chapter 11 Debugging
## 1. Write an assert statement that triggers an AssertionError if the variable spam is an integer less than 10.
spam=int(input()) 

assert spam>10
##  2. Write an assert statement that triggers an AssertionError if the variables eggs and bacon contain strings that are the same as each other, even if their cases are different (that is, 'hello' and 'hello' are considered the same, and 'goodbye' and 'GOODbye' are also considered the same).
eggs=input()

bacon=input()

assert eggs==bacon
## 3. Write an assert statement that always triggers an AssertionError.
finger=input()

assert finger==int

## 4. What are the two lines that your program must have in order to be able to call logging.debug()?
logging.basicConfig(level=logging.DEBUG, format='%(asctime)s -  %(levelname)s -  %(message)s')

logging.debug('End of program')

## 5. What are the two lines that your program must have in order to have logging.debug() send a logging message to a file named programLog.txt?
logging.basicConfig(level=logging.DEBUG, format='%(asctime)s -  %(levelname)s -  %(message)s')

logging.debug('End of program')


## 6. What are the five logging levels?
Debug,Info,Warning,Error,Critical

## 7. What line of code can you add to disable all logging messages in your program?

logging.disable(logging.CRITICAL)

## 8. Why is using logging messages better than using print() to display the same message?
 log messages: fill your program with as many as you like, and you can always disable them later by adding a single logging.disable(logging.CRITICAL) call. 
 
 Unlike print(), the logging module makes it easy to switch between showing and hiding log messages.

## 9. What are the differences between the Step Over, Step In, and Step Out buttons in the debugger?
 
 Step Over: Executes next line of code(subsequent)
 
 Step In: Executes next line of code(subsequent) and pause again.
 
 Step Out: Execute lines of code at full speed until it returns from the current function. 
 
 ## 10. After you click Continue, when will the debugger stop?
 It runs normally and terminates when it reaches a breakpoint.
 
 ## 11. What is a breakpoint?
 It can be applied on a specific line of code, and makes the debugger stop/pause when it reached breaking point.
 
 ## 12. How do you set a breakpoint on a line of code in Mu?
 Setting a breakpoint using an if conditional. It causes it to terminate after the condition is satisfied.It belongs in loop, and a red dot appears next to it.



 
 
 
 
 
 
