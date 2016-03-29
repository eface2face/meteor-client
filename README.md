# meteor-client
This project encapsulate the original [Meteor](https://www.meteor.com/) client libraries so they can be used with browserify without the Meteor server side. The main pourpose is to be able to use Blaze templates with Tracker reactive data binding from any web application.

The followed packages are included:
   * [Meteor] (https://github.com/eface2face/meteor-core)
   * [Meteor.Base64] (https://github.com/eface2face/meteor-base64)
   * [Meteor.EJSON](https://github.com/eface2face/meteor-ejson)
   * [Meteor.Random](https://github.com/eface2face/meteor-random)
   * [Meteor.DiffSequence](https://github.com/eface2face/meteor-diff-sequence)
   * [Meteor.IdMap](https://github.com/eface2face/meteor-id-map)
   * [Meteor.OrderedDict](https://github.com/eface2face/meteor-ordered-dict)
   * [Meteor.Tracker](https://github.com/eface2face/meteor-tracker)
   * [Meteor.Minimongo](https://github.com/eface2face/meteor-minimongo)
   * [Meteor.ObserveSequence](https://github.com/eface2face/meteor-observe-sequence)
   * [Meteor.HTMLJS](https://github.com/eface2face/meteor-htmljs)
   * [Meteor.HMLTools](https://github.com/eface2face/meteor-html-tools)
   * [Meteor.ReactiveVar](https://github.com/eface2face/meteor-reactive-var)
   * [Meteor.Blaze](https://github.com/eface2face/meteor-blaze)
   * [Meteor.BlazeTools](https://github.com/eface2face/meteor-blaze-tools)
   * [Meteor.Templating](https://github.com/eface2face/meteor-templating)
   * [Meteor.Spacebars](https://github.com/eface2face/meteor-spacebars)
   * [Meteor.SpacebarsCompiler](https://github.com/eface2face/meteor-spacebars-compiler)

Also it include the following custom packages:
   * [Meteor.ReactiveObjectMap](https://github.com/eface2face/meteor-reactive-object-map)

## Dependencies
This project requires jQuery and underscore or lodash.

## Installation
With **npm**:

```bash
$ npm install meteor-client
```

## Usage in Node

```javascript
var Meteor = require('meteor-client')($,_);
```

## Documentation
Please refer to [Meteor documentation](http://docs.meteor.com/#/full/) for the detailed information about each package.

## See also
We have also made available a [jQuery plugin](https://github.com/eface2face/jquery-meteor-blaze) to make it easier to use dynamic blaze templates.

## Author

Sergio Garcia Murillo @eface2face

## License

MIT
