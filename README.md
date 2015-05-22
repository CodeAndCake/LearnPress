# LearnPress

The most minimal WordPress theme starter ever :)

Designed for learning.


# Getting started

Download and extract the *zip* for this repository into your `wp-content/themes` folder.

> Or, if you prefer, clone this repository into your `wp-content/themes` folder.



### Adding libraries

Such as HTML5 Boilerplate, Skeleton, Bootstrap etc.

Instead of manually finding libraries, downloading them, extracting them into the right folder.. we can use a little tool called **bower** which will do *that* (managing *packages*) for us. 

![](http://bower.io/img/bower-logo.png)

1. Open Terminal (Mac) or a [Command Prompt](http://windows.microsoft.com/en-gb/windows-vista/open-a-command-prompt-window) (Windows) 
* Install [Node.JS](https://nodejs.org/) 
* Install [bower](http://bower.io/)  

	Check if you have bower installed   
	Type in `bower` and press the `↲` (Enter) key
* If you're on Windows, install [msysgit](https://msysgit.github.io/)
* 
* Navigate to the Learnpress folder (explain how) 
* Type in `bower install` and press the `↲` (Enter) key

[ ] Image of bower_components folder

Want more libraries? Check [libraries.io](https://libraries.io/bower/)

### Troubleshooting





If you're getting an `ECMDERR Failed to execute ...` error:

Put this into your terminal
`git config --global url."https://".insteadOf git://`
then agree to the terms, then `bower install`


`git is not installed or not in the PATH`
http://stackoverflow.com/questions/20666989/bower-enogit-git-is-not-installed-or-not-in-the-path
https://msysgit.github.io/