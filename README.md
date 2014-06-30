# karma-mocha-as-promised

##Note:
The the majority of this is just barely modified from karma-mocha-as-promised upstream. If I do or write something stupid, call me out on it!

[Jasmine as promised](https://github.com/ThomasBurleson/jasmine-as-promised) for [Karma](http://karma-runner.github.io)

* It uses (and will always use) the latest compatible versions of every library.
* It uses `peerDependencies` only.
* No `bower` dependency.

<!--- ## Installation

Install the plugin from npm:

```sh
$ npm install karma-mocha-as-promised -\-save-dev
```
-->

## Usage

After installing [karma-jasmine](https://github.com/karma-runner/karma-jasmine),
add `jasmine-as-promised` before `jasmine` to the `frameworks` key in your Karma configuration:

```js
module.exports = function(config) {
  config.set({

    // frameworks to use
    frameworks: ['jasmine-as-promised', 'jasmine']

    // ...
```

### Usage with karma-requirejs

If you are going to use [karma-requirejs](https://github.com/karma-runner/karma-requirejs), make sure you place `requirejs` first in the order of your frameworks.

```js
frameworks: ['requirejs', 'jasmine-as-promised', 'jasmine']
```


## Contributors
[Javier Mendiara](https://github.com/jmendiara): karma-mocha-as-promised, which I gratuitously copied
[Martin Hansen](https://github.com/mokkabonna): Documentation update in karma-mocha-as-promised


## License
MIT Licensed

