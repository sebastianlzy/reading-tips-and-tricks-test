
Tips-and-tricks-for-css
A sharing of tricks/tips/hacks on Testing that make it work

---
### To include sub directories when running test, add double quotes
``` js
NODE_PATH=./shared/src mocha --compilers js:babel-core/register './server/src/**/*.spec.js'
```
