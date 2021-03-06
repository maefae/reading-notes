# Class 3 Reading Notes [github tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
dvcs stand for: distributed version control system
## What is Git?
- it's a version control system (dvcs)
- it let's multiple developers work on the same code
- a history of changes to your files
- the ability to view, apply, and remove those changes
- it makes collaboration possible!

Commit: each successive version creates a new snapshot on the timeline of the project. **git** keeps track of what the file looked like in different points of time
Each **commit** (snapshot) has a label that points to it
- HEAD = "you are here" (most recent version)
- You can also assign messages to commit (what did you do here that makes it different)
- messages are like writing a caption for your snapshot

#snapshots in time
- Commits represent each successive version of a file or files
- commits are the equivalent of "Save as..."
- Each successive version creates a new snapshot on the timeline of the project

# What is Github?
- github can be either public or private. 
- github is not git
- public place to share and store code
- Github uses git to manage your team's work
- it uses version tracking, reviews changes, keep separate changes until you want to add them

# Git + GitHub = Awesomeness
With GIt (version control) and GitHub (online code storage), you can: 
- have lots of team members work together on the same files, without messing each other up
- keep a history of each file over time
- work on code on your computer, and sync it with what's online
**git is like the sport you play, whereas Github is like the arena or stadium in which you play**

# Repositories
A **repository** is a collection of files that you've told Git to pay attention to
- usually one project = one repo
- really large projects might have multi repos (front end and back)

# gitflow:acp (Add, Commit, Push) 

## Linking Repos

After making a new repository, you'll want to copy this repo onto your computer and connect the two repos together. 
Once connected, they can give/receive code from the other repo. TO do this, you must **clone** from the cloud (github) to our local machine (computer)

## Clone that Repo
1. On github, Click the green button that says **code** or **download** (ensure it says HTTPS)
2. Copy the URL using the copy clipboard button shortcut

## Start in your projects folder
- open up your terminal 
- use **cd** and **ls** to navigate into your **projects** directory
-  if it doesn't exist, go to your home directory: cd ~
-  and make a folder to hold all your repos: **mkdir projects**
-  then change it into: **cd projects**
-  check where you are with **pwd**

## Using Git Clone
**cloning** 
in the projects directory 
- type: git clone
- follow that with a space
- paste in the link you copied
ex: git clone https://blahblah.com
- then hit enter

Typing ls (list) into the terminal, you can see you have a new folder that is the same name of the repository. 
**cd** into your repo (ex: cd hello-world). It'll say git (main) which means it's tracking the saves and deletes of the repo.
- to see the **URL** of the repo, type: git remote -v
- typing ls, you should see the files within the repo (for ex: README file)

# Gitflow:ACP (Add, Commit, Push) (you can remove/add lines of code or delete/add files using this method)

## Using Git Status
open vs code with: code .
make a change, and save it.
open the terminal and type git status
it'll show red and it will convey the name of the project (README.md) so you need to type: git add README.md
type git status again, and it will be green. if there are multiple files that are coming up read, you can type: 
git add . (which conveys you are adding all files).

# Using Git Command
finally, take that snapshot!
- type: git commit  -m "your message goes here"
> git commit -m "adds initial greeting to the world"
- git commit is the shutter button to take the snapshot
- -m specifies the message 
- think of the message as being like a photo caption (what changes did you make
why are they significant?)

#Using Git Push (we want the repo on the terminal and vscode to be pushed up to github)
Now it's time to sync this code to your repo on GitHub
- Type: git push origin main
- git commit is what takes the snapshot
- this sends any new commits (the snapshots of your code) to GitHUb
- go to your repo on GitHub, and look for your files

# Pulling Files from computer (GitHub) to VScode through the terminal
- Type: git pull origin main (pulling from the cloud)
- you don't need to ACP Github to the computer

#GitHub Pages
- Any repo can be published with Github pages
- Each repo can be styled with a theme
- Whenever you push changes, the published site will update
- That's called "deployment." It transforms markdown into an actual Github page

When you delete file off of github and want vs code to match that, you type in your terminal (Ubuntu):
- git pull origin main
- result will be it to delete on vscode too

Let's say you want to delete some code on vscode. The file is called, "app.js" and you want github to match that,
type: git rm app.js
type: git commit -m "removed app file until later"
type: git origin push main

# verify on github
You can do that by clicking on the link next to the file (readme.md in this case)

(quick instructions to get your site from your local machine onto github)
- create a repo
- cd your way into whatever folder you want the file to live in
- copy the link and type into your terminal: git clone (link)
- git status to see what file isn't being tracked
- git add (name of file)
- git status to see it has turned green
- git commit -m "message in here"
- git push origin main
