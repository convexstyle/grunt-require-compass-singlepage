grunt-require-compass-singlepage
================================

Grunt.js, Require.js and Compass/Sass based project workflow.

## How To Get Started
* Read node.js documentation. [Node.js](http://nodejs.org/api/)
* Read volo documentation. [Volo](https://github.com/volojs/volo/wiki/)


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
