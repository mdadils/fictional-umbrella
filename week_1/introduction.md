## Lets try to follow these pointers for maximizing our quality use of time.

- Avoid repeating the same things(effective utilization of time)
- Use chat-box to ask doubts
- Doubts/questions to be addressed in the follow-up session/ towards end of session.

## Pointers

### Mental Model

- “Thinking, Fast and Slow” by Daniel Kahneman

variables

```js
let a = 10;
let b = a;
a = 0;
```

```js
// Dan Abrmv - Mental model. Original object changes
var copyObj = {};

var original = {
  created: Date.now(),
  author: "James",
  cells: 5,
  metadata: {
    title: "Trip Expenses",
    version: "1.2"
  }
};

function duplicateSpreadsheet(original) {
  let copy = {
    created: Date.now(),
    author: original.author,
    cells: original.cells,
    metadata: original.metadata
  };
  copy.metadata.title = "Copy of " + original.metadata.title;
  return copy;
}

copyObj = duplicateSpreadsheet(original);
```

- immutabilty
