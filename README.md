# gndr: Determine gender programmatically

`gndr` is a breakthrough in automated gender detection.

It uses advanced techniques and algorithms to determine the gender of a user by **just fucking asking them.**

The API couldn't be simpler. All you need to do is **ask the user what gender they identify as** along with **what pronouns they use**, and the library will give you back which gender they are with 100% accuracy. Incredible.

## Example

```js
const identifyGender = require('gndr')

// 🤔 what is this user's gender and pronouns?
const gender = identifyGender("non-binary", [ "he", "they" ])

/**
 * Result:
 * {
 *   "gender": "non-binary",
 *   "pronouns": [ "he", "they" ]
 * }
 * /
```

## License

MIT, but I hope you aren't actually thinking of using this