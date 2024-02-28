
# Reading 02 - Passing Functions as Props

## Things I want to know more about
- what other built-in hooks are there than useState? Are they commonly used?
- how can you pass functions to the parent if props flow top down? (video)

### Read Docs - Lists and Keys
1. What does .map() return?
   - it returns a new array of changed values from the original array
3. If I want to loop through an array and display each value in JSX, how do I do that in React?
   - map() the original array and display the value in a component that has a text field
5. Each list item needs a unique **key**.
6. What is the purpose of a key?
   - the purpose is to identify each list item even if the list is changed

### The Spread Operator
1. What is the spread operator?
   - it allows for iterables to be expanded into its distinct elements 
2. List 4 things that the spread operator can do.
   - function arguments, array literals, object literals, string literals
3. Give an example of using the spread operator to combine two arrays.
   ```javascript
   let arr1 = [0, 1, 2];
   const arr2 = [3, 4, 5];

    arr1 = [...arr1, ...arr2];
    // arr1 is now [0, 1, 2, 3, 4, 5]
   ```
4. Give an example of using the spread operator to add a new item to an array.
   ```javascript
   const isSummer = true;
   const fruits = ["apple", "banana", ...(isSummer ? ["watermelon"] : [])];
   // ['apple', 'banana', 'watermelon']
   ```
5. Give an example of using the spread operator to combine two objects into one.
   ```javascript
   const obj1 = { foo: "bar", x: 42 };
   const obj2 = { bar: "baz", y: 13 };

   const mergedObj = { ...obj1, ...obj2 };
   // { foo: "bar", x: 42, bar: "baz", y: 13 }
   ``` 

### Video: How to Pass Functions between Components
1. In the video, what is the first step that the developer does to pass functions between components?
   - place a function nested into the parent component
3. In your own words, what does the handleClick function do?
   - handleClick allows the program to capture the click event
5. How can you pass a method from a parent component into a child component?
   - pass the function as a prop
7. How does the child component invoke a method that was passed to it from a parent component?
   - it takes the method as a prop, and connects it to an event listener
