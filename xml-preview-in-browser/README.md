
## introduction

This set of scripts will help you to preview an XML file in your web browser. 

## setup

1. ensure that git is installed
1. Install Chrome. 
1. Ensure that you have a `~/Sites` folder: `$mkdir ~/Sites`
1. `$cd ~/Sites` 
1. `$git clone git://github.com/hubgit/macrodocs.git`
1. `$cp macrodocs/* .`
1. `$git clone git@github.com:elifesciences/production-tools.git`
1. `$cp production-tools/xml-preview-in-browser/* .`

You will now have a file `drop.html` and all of the required css and js files sitting in your /Sites folder. 


## previewing your XML file

Open chrome with a flag set to enable chrome to load local files. You can do this with the following command:
* `$ /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --allow-file-access-from-files`

Open drop.html in chrome. Drop the file you wish to preview onto the box, and the file will be rendered on the page. You can drop another file onto the box, and it will replace the currently displayed file.

