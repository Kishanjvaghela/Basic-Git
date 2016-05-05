# Basic-Git

Introduction to a small help with git for beginners. Its not a tutorial, but just some basics.

##Version Control System (VCS)

VCS is a system to manage source code of software projects. Git, SVN are examples of such VCS tools.

##Why VCS are needed?

Software developers work in teams where codes are updated daily. VCS keep track of code modifications over time. If you by chance make a mistake, you can turn back the previous state of the code instantly, thereby not loosing the pace of the project. Code sharing between teammates is never easier. If two or more developers are working on the same project, each one doing fifferent features of bug fixing, all of them can have the updated code of the same project using VCS.

##GIT

It was developed in 2005 by Linus Torvalds, and it is free and open source. Git is a Distributed VCS(DVCS) meaning it has a distributed architecture. 
- Keeps a history of your files.
- Branching and Merging
- Traceability

##Setting Up A Repository

#### git init
Using `git init` you can create an empty repository or converting an existing project to git repository. A .git folder will be added to your project folder which will contain all the necessary metadata for the repo.

######Example
```
cd <project directory>
git init
```

###### Repository 
This is the place where you organise a project. You can add folders, code files, images, videos etc. to a repository associated with your project. 
###### Readme
A README file is commonly added to a repository, so that people who view your repository can understand what is your repository about and how to use it.



