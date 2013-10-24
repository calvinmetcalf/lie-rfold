```javascript
var rfold = require('lie-lfold');
```

###fold right

```javascript
rfold(array of things,function,accumulator)
```

like Array.prototype.reduceRight, but the array may include promises or values and the function may return a promise or a value. `rfold` always return a promise.


## License

  MIT
