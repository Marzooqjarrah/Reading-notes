


ORDER OF EXECUTION:
To find the source of an error, it helps to know how scripts are processed.



The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.


In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it.


Each time a function is called, it gets its own execution context and va r i ables object.


If a variable is not found in the variables object for the current execution context, it can look in the
variables object of the parent execution context.

If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code.


When an exception is thrown, the interpreter stops and checks the current execution context for
exception-handling code.


Error objects can help you find where your mistakes are and browsers have tools to help you read them.



The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be.


If you open the errors . html file from t he sample code in your browser, and then open the console,
you will see an error is displayed.


Browsers that have a console have a console object, which has several methods that your script can use to display data in the console.


You can pause the execution of a script on any line using breakpoints. Then you can check the
va lues stored in variables at that point in time.


If you know your code might fail, use try, catch, and finally Each one is given its own code block.
