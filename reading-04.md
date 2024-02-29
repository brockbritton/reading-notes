# Reading 04 - React and Forms

## Things I want to know more about

### How to use Forms in React
What is a ‘Controlled Component’?
   - a compenent that has a value set by react states
Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
   - we should wait to store them until they submit the form, so that if a user never clicks submit or makes a mistake, we dont record data prematurely
How do we target what the user is entering if we have an event handler on an input field?
   - event.target.value

### The Conditional (Tertiary) Operator Explained
Why would we use a ternary operator?
   - to shorten if statements to one-liners
Rewrite the following statement using a ternary statement:
```javascript
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```
to:
```javascript
console.log(x===y ? true : false)
```
