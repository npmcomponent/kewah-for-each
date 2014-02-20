*This repository is a mirror of the [component](http://component.io) module [kewah/for-each](http://github.com/kewah/for-each). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/kewah-for-each`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# forEach

  Iterates an array

## Installation

    $ component install kewah/for-each

## API

```javascript
var forEach = require('for-each');

forEach([1, 2, 3, 4, 5, 6], function(num, index, arr, len) {
  console.log(num);

  if (3 === num) {
    return false;
  }
});

>> 1
>> 2
>> 3
```

## License

  MIT
