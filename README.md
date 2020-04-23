# 631-rtopics

* R lecture materials
* RMarkdown
* Github

[generated html files are checked in here](https://abecode.github.io/631-rtopics/)

## R Lecture Materials

The R lecture materials are here so that they are accessible outside of Canvas.

## RMarkdown

These files are either RMarkdown or generated from RMarkdown.

## Github

This Markdown file is part of a Git repository (repo) which is stored on GitHub.  Git keeps all of the files in these directories under version control and GitHub is a web-based platform build on top of Git, much like RStudio is build on top of R.  

GitHub repos can be loaded ("cloned") as a project in RStudio, but we need to set up RStudio:

* First [install git first](https://cfss.uchicago.edu/setup/git/).
* Then [make sure that RStudio can use git](https://cfss.uchicago.edu/setup/git-with-rstudio/)
* In RStudio go to File -> New Project ... -> Version Control -> Git
  * for repository url put "https://github.com/abecode/631-rtopics"
  * for project directory name put "clone-of-631-rtopics" (this you
    can modify to a name of your liking)
  * for "Create project as subdirectory of" use Downloads (or other
    directory of your choosing)
  * choose "open in new session" if you want RStudio to keep your old
    session

Forking is a more advanced GitHub technique that will copy someone's repo to your own account. Forking is more advanced than simply cloning. Cloning is fine if it's your repo or if you only plan to read/download/"pull" from someone else's repo.  However, forking is important for collaborating because it allows one to write/upload/"push" changes to your own repo and then share it back to the original repo. It is a kind of social feature Github adds to Git and is not build into Git itself but is widely used. We won't go into forking too much in class, but we'll take a first small step by forking this repository:

* set up a [Github acccount](https://github.com) if you don't have one already.
* go to https://github.com/abecode/631-rtopics
* at the top right, select "Fork"" (after "Watch" and "Star")
* Now, you can go back and use the "File -> New Project ... -> Version Control -> Git" command to substitute your forked repository
  * if your username is me2020 the url would be https://github.com/me2020/631-rtopics
  * for the directory name use "fork-of-631-rtopics"
  * you can put it into the parent directory same as above

This will create the repo in your own account. Now, if you modify it, you'll be able to upload/write/"push" the changes to made to your own account. To do this first you will change a file.  When a file is changed, you'll then see an "M" next to the file in the Git tab in the top right window of RStudio.  Check "Staged" and then click "Commit".  Then you will add a message to describe your commit.  Then you'll click "Push" and then the commit (a specific snapshot) will be uploaded to your copy of the repo. 

Our textbook and slides are also Github repos:

* textbook https://github.com/OpenIntroStat/openintro-statistics
* slides https://github.com/OpenIntroStat/openintro-statistics-slides

You can try cloning or forking these and playing around with them.  They are more $\LaTeX$ than R, but you can use RStudio to open a .tex file and it will give you the option to "Compile PDF".  However, the pdfs are already checked into the repo so this isn't strictly necessary, just to show that RStudio is capable of generating the textbook and slides.