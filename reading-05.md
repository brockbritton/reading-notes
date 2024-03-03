
# Reading 05 - Putting it all together

## Things I want to know more about

### Thinking in React
1. What is the single responsibility principle and how does it apply to components?
  - each component should only do one thing - if a component does more than one thing, break it up
2. What does it mean to build a ‘static’ version of your application?
  - to build a site without interactivity that renders the projected UI
3. Once you have a static application, what do you need to add?
  - interactivity
4. What are the three questions you can ask to determine if something is state?
  - Does it remain unchanged over time? If so, it isn’t state.
  - Is it passed in from a parent via props? If so, it isn’t state.
  - Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!
5. How can you identify where state needs to live?
  - Identify every component that renders something based on that state.
  - Find their closest common parent component—a component above them all in the hierarchy.
  - Decide where the state should live:
    - Often, you can put the state directly into their common parent.
    - You can also put the state into some component above their common parent.
    - If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.
  

### High Order Functions
1. What is a “higher-order function”?
  - functions that operate on other functions   
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  - it is returning a boolean, if m is greater than n (presumably numbers)
3. Explain how either map or reduce operates, with regards to higher-order functions.
  - map uses foreach under the hood making it a higher order function
