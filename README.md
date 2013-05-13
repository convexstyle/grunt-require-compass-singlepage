# [HTML5 Boilerplate](http://html5boilerplate.com)

<<<<<<< HEAD
HTML5 Boilerplate is a professional front-end template for building fast,
robust, and adaptable web apps or sites.

This project is the product of many years of iterative development and combined
community knowledge. It does not impose a specific development philosophy or
framework, so you're free to architect your code in the way that you want.

* Source: [https://github.com/h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate)
* Homepage: [http://html5boilerplate.com](http://html5boilerplate.com)
* Twitter: [@h5bp](http://twitter.com/h5bp)


## Quick start

Choose one of the following options:

1. Download the latest stable release from
   [html5boilerplate.com](http://html5boilerplate.com/) or a custom build from
   [Initializr](http://www.initializr.com).
2. Clone the git repo — `git clone
   https://github.com/h5bp/html5-boilerplate.git` - and checkout the tagged
   release you'd like to use.


## Features

* HTML5 ready. Use the new elements with confidence.
* Cross-browser compatible (Chrome, Opera, Safari, Firefox 3.6+, IE6+).
* Designed with progressive enhancement in mind.
* Includes [Normalize.css](http://necolas.github.com/normalize.css/) for CSS
  normalizations and common bug fixes.
* The latest [jQuery](http://jquery.com/) via CDN, with a local fallback.
* The latest [Modernizr](http://modernizr.com/) build for feature detection.
* IE-specific classes for easier cross-browser control.
* Placeholder CSS Media Queries.
* Useful CSS helpers.
* Default print CSS, performance optimized.
* Protection against any stray `console.log` causing JavaScript errors in
  IE6/7.
* An optimized Google Analytics snippet.
* Apache server caching, compression, and other configuration defaults for
  Grade-A performance.
* Cross-domain Ajax and Flash.
* "Delete-key friendly." Easy to strip out parts you don't need.
* Extensive inline and accompanying documentation.


## Documentation

Take a look at the [documentation table of contents](doc/TOC.md). This
documentation is bundled with the project, which makes it readily available for
offline reading and provides a useful starting point for any documentation you
want to write about your project.


## Contributing

Anyone and everyone is welcome to [contribute](CONTRIBUTING.md). Hundreds of
developers have helped make the HTML5 Boilerplate what it is today.
=======
Grunt.js, Require.js and Compass/Sass based project workflow.

## How To Get Started
* [Read node.js documentation.](http://nodejs.org/api/)
* [Read volo documentation.](https://github.com/volojs/volo/wiki/)
* [Read grunt-init documentation.](https://github.com/gruntjs/grunt-init-gruntfile)


### Install Node.js
The easiest way to install node is going to [Node.js](http://nodejs.org/) and download the installer.

### Create a project directory
<pre>
cd ~/Desktop/
mkdir test_project
cd test_project/
</pre>

### Install Grunt command line interface globally
<pre>
npm install -g grunt-cli
</pre>

If you install grunt-cli correctly, you will see it in the list of installed packages.
<pre>
npm list -g
├─┬ grunt-cli@0.1.7
</pre>

### Install volo globally
<pre>
npm install volo -g
</pre>

Check whether you installed volo correctly or not.
<pre>
volo -v
volo v0.2.8
</pre>

### Download HTML5 boilerplate
<pre>
volo create _source h5bp/html5-boilerplate
cp -R _source/ ./
rm -rf _source/
</pre>

### Create package.json file from npm init.
<pre>
npm init
</pre>
Follow the steps and input the required data if necessary.

### Install grunt-init command
Install grunt-init globally.
<pre>
npm install -g grunt-init
</pre>

Check whether grunt-init has been successfully installed or not.

### Download the grunt-init-gruntfile
<pre>
git clone https://github.com/gruntjs/grunt-init-gruntfile.git ~/.grunt-init/gruntfile
</pre>

### Create Gruntfile.js
<pre>
grunt-init gruntfile
</pre>
>>>>>>> 4e842a9f4d54b616a5c52c3b0a6fdd975409b235
