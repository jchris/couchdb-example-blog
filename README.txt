This project has been renamed. Sorry "couchdb-example-blog" doesn't exactly 
roll off the tongue. 

*Welcome to Sofa!*

The new project lives at:

http://github.com/jchris/sofa/tree/master

If you have branches based on this repo, you can get back in sync with 
my repo in a couple of simple steps:

First, "fork" the new Sofa repo on github, then in your newly old "couchdb-example-blog" checkout, run this command:

git remote add neworigin git@github.com:THISISYOU/sofa.git

And to get your work into the new repo, run:

git push neworigin mytopicbranch

If you have been working on "master" you'll probably need to branch it to another name before you can push.

Once you have it in your new github repo, you can do a fresh git-clone to 
get the new codes, and then maybe merge your topic branch into your master, if you like.
