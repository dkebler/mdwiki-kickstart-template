### How to Edit the Content of this Website

If you are seeing this then you have a functioning copy of mdwiki kickstart template

This is a simple template website for an MDwiki based website.

For details see the [MDwiki website](http://dynalon.github.io/mdwiki/#!index.md)

Here is the readme for the github repo of this template wiki that you can clone


Use any plain text editor to edit the .md files in the folder.  [Sublime text editor version 3](http://www.sublimetext.com/) is a great choice. 

There is a canned menu structure found in the navigation.md file.  If you change the names of choices and associated files and rename them as well you can customize and change to suit.

The Site name on the nav bar is set at the top of the navigation.md file

The website title used in the browser is set in the config.json file

index.html is the actual MDwiki program and contains all the javascript to render and load the markdown (.md) pages.

You can pick a canned bootswatch theme and set the default in the navigation.md file.   It is possible to do custom styling but that involves a custom theme.  (see mdwiki site)

index.md is the "home" page and is rendered and served by default when index.html is loaded (which should be the default file name on your server or be changed to match...e.g. default.htm)

The MDwiki site has some basic markdown syntax but a search of the internet will find you many resources and cheat sheets.

config.json holds the few site configurations

when you want to deploy it's as simple as moving a copy of the directory wherever you want to serve it.  Amazon Web Services(AWS) S3 is a nice option and they have a free tier and you can assign your (sub)domain to a bucket is using AWS Route 53.

For version control, backup and collaboration I suggest using git (smartgit is a good git gui).  If you go the AWS route then it's easy to use jgit to maintain a bare remote repository on S3.  Here is a link to more details on using jgit with S3.

http://www.fancybeans.com/blog/2012/08/24/how-to-use-s3-as-a-private-git-repository/









