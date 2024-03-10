
# Reading 10 - In Memory Storage

## Things I want to know more about

### Understanding the JS Call Stack
What is a ‘call’?
How many ‘calls’ can happen at once?
What does LIFO mean?
- last in first out: it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.
Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
What causes a Stack Overflow?
- when a recursive function does not have an exit point

### Javascript Error Messages
1. What is a ‘reference error’?
- when a variable is called but not yet defined
2. What is a ‘syntax error’?
- when the syntax of the file breaks somehow
3. What is a ‘range error’?
- when there is an invalid length for an object that has length
4. What is a ‘type error’?
- when types are incompatible with each other
5. What is a breakpoint?
- a breakpoint stops code at a certain point when a condition is set
6. What does the word ‘debugger’ do in your code?
- it creates a breakpoint