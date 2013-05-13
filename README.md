grunt-require-compass-singlepage
================================

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
<pre>

### Create Gruntfile.js
<pre>
grunt-init gruntfile
</pre>
