## ngSublimeSnippets

A useful little collection of code snippets for Sublime Text 3, including a corresponding starter spec. These are pretty closely based on John Papa's [AngularJS 1.x Style Guide](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md).

If you're going old school, use the [ES5](https://github.com/coblr/ngSublimeSnippets/tree/master/es5) snippets.

If you're transpiling with something like Babel, you can use the [ES6](https://github.com/coblr/ngSublimeSnippets/tree/master/es6) snippets for consistent ES6 code (i.e. not sprinkled with `function()`s that trigger OCD).

### Installation

 1. Clone Fork or Download this repo.
 2. Go to Sublime > Preferences > Browse Packages...
 3. In the file browser window that opens, locate and open the `User` directory.
 4. Copy the sublime snippets from this repo into the `User` directory.
 5. Restart Sublime.

### Included Snippets

 - ngModule
 - ngConfig
 - ngRun
 - ngController / ngControllerSpec
 - ngDirective / ngDirectiveSpec
 - ngFactory / ngFactorySpec
 - ngFilter / ngFilterSpec

### Usage

As with any snippet, after the snippets are installed, you just need to type out the name of the snippet and press `tab`. The snippet code will be loaded into you file.

Your cursor will also be placed in the first editable spot. For non-spec files, this will be the name of the module. For specs, this will be the first `describe` label. After you fill in this value, press `tab` to auto-navigate to the next input pointer, and so on.
