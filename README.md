# grunt-boilerplate
A simple grunt setup to use on Udacity projects.  The idea is that you can use this repo as a starting point for each of your projects where you want to use grunt.

## Getting Ready

* verify node is installed, can do `node -v` to check version, if doesn't error we are good.
* update npm to latest version `npm update -g npm`
* create a directory for you project and cd into it.
* once in your directory install grunt-cli `npm install -g grunt-cli`

if all went well above the we are ready to use Grunt.

## Clone Repo

* from your project root directory clone project `git clone git@github.com:javsalazar/grunt-boilerplate.git .`
* add directory app/, dist/, and images_src/ at the root of your project.


## Place Your Project Files In The app/ Folder

remember that if you cloned this directory there is already a git repo at the root of the project, if you clone the project repo like so: `git clone git@github.com:udacity/frontend-nanodegree-resume.git app` remember to delete the .git folder in app so it won't be a repo within a repo, that would be a problem. If you are familiar with submodules by all means us it.

## Install Grunt Plugins

since we have the packages.json file we don't have to manually install each plugin like so: `npm install grunt-responsive-images --save-dev`.  Instead do `npm install` on the root directory of project to install all plugins at once. 

** Ready For Gruntfile.js

Now that the project and directories structure is set take a look at Grunfile.js and make any necessary changes to the settings or options of each task.
