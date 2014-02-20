*This repository is a mirror of the [component](http://component.io) module [eldargab/google-maps](http://github.com/eldargab/google-maps). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/eldargab-google-maps`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# google-maps

Load google maps from JavaScript

## Installation

```
$ component install eldargab/google-maps
```

## API

```javascript
var gmaps = require('google-maps')({
  protocol: 'https',
  v: '3',
  libraries: ['drawing']
  //...
})

gmaps(function (err, api) {
  // use api
})
```

## License

MIT
