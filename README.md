# LearnPress

The most minimal WordPress theme starter ever :)

Designed for learning.


# Getting started

Download and extract the *zip* for this repository into your `wp-content/themes` folder.

Or, if you prefer, *clone* this repository into your `wp-content/themes` folder.



### Adding libraries

Such as HTML5 Boilerplate, Skeleton, Bootstrap etc.

Instead of manually finding libraries, downloading them, extracting them into the right folder.. we can use a little tool called **bower** which will do *that* (managing *packages*) for us. 

![](http://bower.io/img/bower-logo.png)

<!--It'll take a little set up, but once you're up and running evrything will be smooth-->

1. Open Terminal (Mac) or a [Command Prompt](http://windows.microsoft.com/en-gb/windows-vista/open-a-command-prompt-window) (Windows).  
* Install [Node.JS](https://nodejs.org/)   
	
	Check if you have Node.JS installed   
	In Terminal / CP, type `npm` and press the `↲` (Enter) key
* Install [bower](http://bower.io/)  

	Check if you have bower installed   
	Type `bower` and press the `↲` (Enter) key
* If you're on Windows, install [msysgit](https://msysgit.github.io/)
* Navigate to the LearnPress folder  

	In Mac, drag the LearnPress folder onto the Terminal app icon
	In Windows, drag the LearnPress folder inside CP, then change `C:` to `cd`, so that you'll end up with something like `cd  \wamp\www\YOUR_SITE_NAME\wp-content\themes\LearnPress`
* Type in `bower install` and press the `↲` (Enter) key

	Bower will install the components listed in `bower.json`.
	
	LearnPress comes with HTML5Boilerplate and Skeleton.
	
	If all goes well, you should end up with a new `bower_components` containing `html5-boilerplate` and `skeleton-css`
	
	```
	LearnPress
	|- bower_components
		|- html5-boilerplate
		|- skeleton-css
	```

<!--- [ ] Image of bower_components folder-->

### Want more libraries? 

Let's say you want to add Bootstrap.

`bower install bootstrap --save`

The `--save` bit will add the Bootstrap dependency to your `bower.json`

Check [libraries.io](https://libraries.io/bower/) for even more libraries.

### Troubleshooting

* If you're getting a `ECMDERR Failed to execute ...` error:

	`git config --global url."https://".insteadOf git://`
	
* If you're getting a `git is not installed or not in the PATH` error in Windows

	Follow [these steps](http://stackoverflow.com/questions/20666989/bower-enogit-git-is-not-installed-or-not-in-the-path)
