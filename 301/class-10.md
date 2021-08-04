# In Memory Storage

## JavaScript Call Stack

1. **What is a ‘call stack’?**
   * Its how “function hierarchy and execution order” works in the JavaScript engine. Furthoremore, it is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

***

2. **How many ‘calls’ can happen at once?**
   * The call stack is single, function(s) execution, is done, one at a time.

***

3. **What does LIFO mean?**
   * It means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

***

4. **What causes a Stack Overflow?**
  * A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

## JavaScript error messages

1. **What is a ‘refrence error’?**
   * Occurs when you try to use a variable that is not yet declared you get this type os errors.

***

2. **What is a ‘syntax error’?**
   * Occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using `JSON.parse`. 

***

3. **What is a ‘range error’?**
   * Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

***

4. **What is a ‘tyep error’?**
   * Errors show up when the types (number, string and so on) you are trying to use or access are incompatible.

***

5. **What is a breakpoint?**
   * Is a point in the program where the code will stop executing.

***

6. **What does the word ‘debugger’ do in your code?**
   * Allow you to halt the execution of the program, examine the values of variables, step execution of the program line by line, and set breakpoints on lines or specific functions that, when hit, will halt execution of the program at that spot.
