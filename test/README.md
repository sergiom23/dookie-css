#Test dookie-css with mocha.js & casper.js

Dookie uses [mocha.js](http://visionmedia.github.io/mocha) for unit testing of mixins and [casper.js](https://github.com/n1k0/casperjs/) for visualizing them.

##Unit

You can run unit tests with several commands from project root:

```bash
npm test
```

##Screenshots

To test Dookie visually you'll need to install all server dependencies in ``./test`` folder before running:

```bash
npm install
```

and then start testing with this command (be sure that you have [casper.js installed](http://casperjs.org/installation.html) on your machine):

```bash
node ./runner.js
```

Then you can check how mixins actually look like on screenshots in the folder.