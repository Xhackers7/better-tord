# Better-tord
This api gives you questions for the game truth or dare

## List of functions:
```
get_question,
amount_of_questions
```

## Sample Code
```js
const r = require('better-tord');
const question = r.get_question();
console.log(question);

const amount = r.amount_of_questions();
console.log(amount);
```