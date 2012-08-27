# Configure Your JavaScript Coding Environment

## Install jsiohint

`jsiohint` is a "lint" checker that detect errors and potential problems in
your JavaScript code. Some are actual errors which will break your
program, and some are best practice suggestions for style you
*should* follow when writing JavaScript. `jsiohint` is derived from
[jshint](http://www.jshint.com), you can read up there about
configuration options. The most basic way to run the program is at the
command-line like:

Install [jsiohint](https://npmjs.org/package/jsiohint) as a
global `npm` package:

~~~
$ npm install -g jsiohint
~~~

Now you can run `jsiohint` from the command line an a file,
for example:

~~~
$ jsiohint ./src/Application.js
~~~


## Configure your editor

### Vim

1. Install [Vim-pathogen](https://github.com/tpope/vim-pathogen)
2. Install [Syntastic](https://github.com/scrooloose/syntastic)

With these prerequisites installed, symlink `jshint` to `jsiohint`:

~~~
$ ln -s $(which jsiohint) $(which jshint)
~~~

### Sublime Text Editor

Install the following:

1. [Sublime Package Manager](http://wbond.net/sublime_packages/package_control/installation)
2. [JSHint plugin](https://github.com/uipoet/sublime-jshint)
3. jsioHint (as described above)


With these prerequisites installed, symlink `jshint` to `jsiohint`:

~~~
$ ln -s $(which jsiohint) $(which jshint)
~~~