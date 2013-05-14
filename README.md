## Grunt Require Compass/Sass Sinple Page
=======
Grunt.js, Require.js and Compass/Sass based project workflow.

## How To Get Started
* Read [node.js](http://nodejs.org/api/) documentation.
* Read [volo](https://github.com/volojs/volo/wiki/) documentation.
* Read [grunt-init](https://github.com/gruntjs/grunt-init-gruntfile) documentation.
* Read [grunt-contrib-requirejs](https://github.com/gruntjs/grunt-contrib-requirejs) plugin.
* Read [grunt-contrib-compass](https://github.com/gruntjs/grunt-contrib-compass) plugin.
* Read [grunt-contrib-watch](https://github.com/gruntjs/grunt-contrib-watch) plugin.


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
If you successfully generate Gruntfile.js, then, you  will see it in the current directory.

### Install necessary grunt plugin locally
<pre>
npm install grunt --save-dev
npm install grunt-contrib-requirejs --save-dev
npm install grunt-contrib-compass --save-dev
npm install grunt-contrib-watch --save-dev
</pre>
If you install these plugins correctly, you will see some changes in package.json.
<pre>
{
  "name": "grunt-require-compass-singlepage",
  "version": "1.0.0",
  "description": "Grunt.js, Require.js, and Compass/Sass based procedure.",
  "main": "index.js",
  "directories": {
    "doc": "doc"
  },
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git://github.com/convexstyle/grunt-require-compass-singlepage.git"
  },
  "keywords": [
    "grunt",
    "require",
    "compass",
    "sass"
  ],
  "author": "convexstyle",
  "license": "BSD",
  <strong>"devDependencies": {
    "grunt": "~0.4.1",
    "grunt-contrib-requirejs": "~0.4.0",
    "grunt-contrib-compass": "~0.2.0",
    "grunt-contrib-watch": "~0.4.3"
  }</strong>
}
</pre>

### Edit Gruntfile.js to register grunt tasks

