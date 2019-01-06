# Phrase object (with palindrome detector)

This is a sample NPM module created in [*Learn Enough JavaScript to Be Dangerous*](https://wwww.learnenough.com/javascript-tutorial) by Michael Hartl.

The Module can be used as follow:

```
$ npm install --global uwe-palindrome
$ vim test.js
let Phrase = require("uwe-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$node test.js
true
```