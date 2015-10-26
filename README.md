# MDWiki Quickstart Template
This a directory that can be cloned or downloaded to get going quickly with a [mdwiki](http://dynalon.github.io/mdwiki/#!index.md) based web .
After cloning you just point your browser to the file path and then edit away on [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) files with your favorite editor (e.g. sublime)

The details of what and how are found on the homepage once you get it up and running or just look in the index.md file

#### No server needed

The beauty of MDwiki is that all the javascript code to render and display the markdown is inside one file (index.html) that runs all inside your browser.  That means your browser does the markdown rendering...no server needed!

This makes an MDwiki site portable.  Just put it anywhere and point your browser to that location be it a url or a local file path.

This means MDwikis can be put places like an S3 bucket at Amazon Web services or as simple as pushing the repo you cloned to a repo at your Github account using a [gh-pages branch](http://www.damian.oquanta.info/posts/one-line-deployment-of-your-site-to-gh-pages.html)

Here you can [see the template site](http://david.kebler.net.s3.amazonaws.com/mdwiki-template/index.html#!index.md) served from an S3 Bucket). 

Here you can [see the template site](http://dkebler.github.io/mdwiki-kickstart-template/#!index.md) served from a gh-pages branch of the repo). 

Of course it can be "served" from any regular server like Apache.

Tip: __IIS Server__

If you deploy to a Windows IIS there a few cavets.  
See this page http://dynalon.github.io/mdwiki/#!tutorials/iis/iis.md

plus you'll need to add in a mime for .json as well