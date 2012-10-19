
## introduction

This set of scripts will help you to preview an XML file in your web browser. 

## setup

1. ensure that git is installed
1. Install Chrome. 
1. `$cd /Sites` 
1. `$git clone git://github.com/hubgit/macrodocs.git`
1. `$cp macrodocs/* .`
1. `$git clone git@github.com:elifesciences/production-tools.git`
1. `$cp production-tools/xml-preview-in-browser/* .`

You will now have a file `transform.html` and all of the required css and js files sitting in your /Sites folder. 

## pointing the script to the XML file. 

Copy the xml file that you want to preview into the /Sites folder. Edit the `transform.html` file, and replace the YOURXMLFILE.xml in that file with the name of your xml file. 

Open chrome with a flag set to enable chrome to load local files. You can do this with the following command:

* `$ /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --allow-file-access-from-files`

## previewing your XML file

Open transform.html in chrome, it shold preview the XML file in HTML

