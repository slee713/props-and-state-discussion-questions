# Props vs. State Discussion Questions

1. What is the difference between *props* and *state* in React?
    - props are pieces of information that is sent down from parent to child. (child can send data back to parent via callback functions)
    - state is data that can be changed within the component
2. When would you use state instead of props?
    - when we know that the value is expected to change during the components life
3. Assuming `UserDetail` is a component, what will its *props* be if it's rendered as follows:

```js
const user = {name: 'Spider Man', age: 32}

<UserDetail title="Profile Page" dog="Fido" user={user} />
```

4. Take a look at `https://learn.co`. Pretend you were going to recreate a specific page. What top level components would you have? What props would they receive and what state would they own? What components would they have as children?




