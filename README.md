Tutorial on version control
========

#### Version control
* [Version what?](https://github.com/TGuillermeTeaching/VersionControl/blob/master/VersionControl.pdf)

#### Links
* [Everything you need to do!](http://rogerdudler.github.io/git-guide/)
* [Everything you need to know!](https://www.sbf5.com/~cduan/technical/git/)

## Tutorial

This quick tutorial will cover two main parts:

 * The basic clicking git pipeline: where we're going to look at the basic pipeline for using version control without using any coding.
 * The basic collaborative pipeline: where we're going to look at how it works in a team.

### What you need before the tutorial?

Throughout this tutorial, I'll assume you have the following basic computer skills (i.e. you answer yes to the following questions):
 
 * You know how to install a software?
 * You know how to navigate on your computer (i.e. you know where your files are)?
 * You have a basic text editor (preferentially not Word)?

There is also two optional pre-requisites if you want to follow the tutorial:

 * You have a GitHub account (create one here: https://github.com/).
 * You have the GitHub desktop GUI (download it here: https://desktop.github.com/).

I'm going to run the whole tutorial using GitHub but there are other git platforms like BitBucket (https://bitbucket.org/) or many more alternatives (https://alternativeto.net/software/github/).
They're all good in their own right and feel free to use them, you'll just have to adapt my tutorial to your specific software.

### The basic clicking git pipeline

They are many tutorials on how to use git from the terminal (like this one: http://rogerdudler.github.io/git-guide/) which is probably the "purest" way to use version control with git.
However, here we're going to look at the basic principles just by using a GUI (graphical user interface) which will just involve clicking around.

 1. Open the GitHub Desktop GUI
 2. Log in with your GitHub account
 3. Add a new repository (using File>New Repository or File>Add Local Repository)
 4. Create a text file (or whatever - something easy to edit) and type something
 5. Create your first commit
 6. Push your first commit (publish the repository)
 7. Do another modification, commit and push.
 8. Do step 7 again (remember to give go names to your commits)
 9. Realise that that was unecessary, roll back one commit
 10. Do step 7 again.
 11. Realise that this whole thing is actually not really serious so go back to step 5.

### The team version

 1. Send me your GitHub account name.
 2. Clone my repo through your app.
 3. Wait until I commit and push something.
 4. Refresh your repo and realise I changed something.
 5. Add your own grain of salt: change something, commit it and push it.
 6. Realise we now all have the same document with many modifications.
 7. Think about all this mess and how you need unit testing and continuous integration...
