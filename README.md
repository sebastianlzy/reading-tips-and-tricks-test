
-and-tricks-for-css
A sharing of tricks/tips/hacks on Test that make things happen

---
### To include sub directories when running test, add double quotes!
``` js
NODE_PATH=./shared/src mocha --compilers js:babel-core/register './server/src/**/*.spec.js'
```
