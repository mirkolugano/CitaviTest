# CitaviTest
This is my first repository I have created on GitHub and I am trying to get it straight... 

##How does it work?
I'd like to know that as well.

Here is a link to a list of instructions on how to write this readme file: 
https://help.github.com/articles/markdown-basics/

The first step is to create a repository on GitHub or go to an existing one.

Then you can select "Clone in Desktop" and map the repository to a local directory on your
hard drive.

Then you need to go to Visual Studio and in order to be able to open a project from the files
you got from the repository, do New -> Project from existing code. Choose the directory you 
have mapped right before. Give a name to the project and select C# as the project type
(the other 2 are also ok if we are modifying an existing repository)

Now we are ready to do some changes. Create a branch and change for example the readme file. 

Then go to Changes (inside visual studio) enter a comment for the commit, then do Commit. Now 
if you go to Unsynced Commits and you click on Push, you will be able to see the changes already
on github.com inside your branch, even though these changes will not yet be there for the master.

Now we need to create a pull request.

Go to github.com and inside the branch click on create pull request (green button). You will see 
all commits you have pushed to the server. After pulling the request and having maybe a discussion 
about the changes, the branch can be merged to the master. At this point the changes are visible
online in the master as well.
