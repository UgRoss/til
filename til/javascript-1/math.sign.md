---
description: 'ℹ️ Use to detect whether a number is positive, negative, or zero.'
---

# Math.sign\(\)

### Description

`Math.sign()` function returns the sign of the value, indicating whether a number is positive, negative, or zero. It the following values:

* `1` - for positive numbers
* `-1` - for negative numbers
* `0` - for positive zero
* `-0` - for negative zero
* `NaN` - in all other cases

_The argument passed to this function will be converted to `number` type implicitly._

### Example

```javascript
Math.sign(3); //-> 1
Math.sign(Infinity); //-> 1
Math.sign(-Infinity); //-> -1
Math.sign(-1000); //-> -1
Math.sign(0); //-> 0
Math.sign(-0); //-> -0
Math.sign(NaN); //-> NaN
Math.sign('foo'); //-> NaN
Math.sign(); //-> NaN
```

