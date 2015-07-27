# Setup

install Node.js from downloaded package
install the grunt client (make sure you use sudo or you will have to install node all over)

(sudo npm install grunt-cli -g)
(')

# NPM install takes the contents of package.json which has a list of project modules and dependencies which the project needs. It creates a folder called node_modules in the root directory. with all the modules mentioned in package.son

sudo npm install

NB problem with EACCESS BOWer 

http://stackoverflow.com/questions/22257726/eacces-error-with-bower-install

#Installing all the dependencies from the bower.json file

# bower-install-simple is a grunt script to install bower packages it creates a direcory called bower

sudo grunt bower-install-simple

# This builds the project based on the settings in the grunt file.js which in this case links to a grunt folder with all the details of each package broken down for ease.

sudo grunt build:dev
sudo grunt build:angular

https://www.npmjs.com/package/grunt-recess

Took a while to get my head around it. Essentially Node.js is the server and comes with node packet manager. We use NPM to install the grunt client. The grunt client used gruntfile.js to build the project every time. We use bower to install all the components needed. Now we can finally get down to development.

npm start

## Editing

To edit the left navigation use the  tpl/blocks/nav.html file
To edit the left navigation text go to L10n where the translation is stored
Titles and General Admin src/js/main.js

Changing the routing or the urls.py equiv is in /js/config.router.js user urlRouter and Statemanager




1: Please put the files on a server or local host to preview. 
eg: put the "/src" files under a localhost "src" folder

looks like:
"src/css"
"src/fonts"
"src/img"
"src/js"
"src/tpl"
"src/l10n"
"src/index.html"

then preview:  http://localhost/src/index.html  in your browser.

2: Documents locate "tpl/docs.html" or "http://localhost/src/index.html#/app/docs"
online: http://flatfull.com/themes/angulr/#/app/docs

3: Use Grunt and Bower

install node.js
go to the app root

>npm install -g grunt-cli
>npm install
>grunt bower-install
>grunt build:dev
>grunt build:angular
>npm start
