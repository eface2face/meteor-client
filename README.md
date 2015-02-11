# meteor-client
This project encapsulate the original [Meteor](https://www.meteor.com/) client libraries so they can be used with browserify without the Meteor server side. The main pourpose is to be able to use Blaze templates with Tracker reactive data binding from any web application.

The followed packages are included:
   * [Meteor] 
   * [Meteor.Base64] 
   * [Meteor.EJSON]
   * [Meteor.Random]
   * [Meteor.IdMap]
   * [Meteor.OrderedDict]
   * [Meteor.Tracker]
   * [Meteor.ObserveSequence]
   * [Meteor.HTMLJS]
   * [Meteor.HMLTools]
   * [Meteor.ReactiveVar]
   * [Meteor.Blaze]
   * [Meteor.BlazeTools]
   * [Meteor.Templating]
   * [Meteor.Spacebars]
   * [Meteor.SpacebarsCompiler]

Also it include the following custom packages:
   * [Meteor.ReactiveObjectMap]

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
