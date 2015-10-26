### How to Edit the Content of this Website

If you are seeing this then you have a functioning copy of [mdwiki kickstart template](https://github.com/dkebler/mdwiki-kickstart-template). This is a simple template for a [MDwiki based website](http://dynalon.github.io/mdwiki/#!index.md)

Here is github repo of this template wiki that you can clone and has more details on usage and deployment.  [mdwiki kickstart template](https://github.com/dkebler/mdwiki-kickstart-template)

Use any plain text editor to edit the .md files in the folder.  [Sublime text editor version 3](http://www.sublimetext.com/) is a great choice. 

There is a canned menu structure found in the navigation.md file.  If you change the names of choices and associated files and rename them as well you can customize and change to suit.

The Site name on the nav bar taken from the top line heading in the navigation.md file.

The title used in the browser window (and tab) is set in the config.json file.  Config.json holds the few site configurations.

index.html is the actual MDwiki program and contains all the javascript to render and load the markdown (.md) pages.

You can pick a canned bootswatch theme and set the default in the navigation.md file.   It is possible to do custom styling but that involves a custom theme.  (see the [MDwiki website](http://dynalon.github.io/mdwiki/#!index.md))

index.md is the "home" page and is rendered and loaded by default when index.html is loaded.

The MDwiki site has some basic markdown syntax but a search of the internet will find you many resources and cheat sheets.
[markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

Since MDwiki does not require a backend server (it's essentially a "static" site) you can deploy most anywhere like S3 or Githubs gh-pages.  See the repo [mdwiki kickstart template](https://github.com/dkebler/mdwiki-kickstart-template)


For version control, backup and collaboration I suggest using git (smartgit is a good git gui).  









