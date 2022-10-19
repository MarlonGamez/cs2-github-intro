# cs2-github-intro
A basic intro to github + git for students

## Overview
Git is a distributed Version Control System (VCS), which means it is a useful tool for easily tracking changes to your code, collaborating, and sharing. With Git you can track the changes you make to your project so you always have a record of what you’ve worked on and can easily revert back to an older version if need be. It also makes working with others easier—groups of people can work together on the same project and merge their changes into one final source!

GitHub is a way to use the same power of Git all online with an easy-to-use interface. It’s used across the software world and beyond to collaborate and maintain the history of projects.


GitHub is home to some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step.

## Tasks
You will do a few things for this lab:
- Install git to your machine
- Create an account for Github
- Use git to clone this repository
- Create a new branch to make your changes on
- Make a change and commit your changes
- Push your branch + changes
- Open a pull request to add your change to the repository


## Install git to your machine
Depending on your OS, installing git may look different. Look at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git and get git installed on your machine

## Create an account for Github
https://github.com/join

## Fork the repository
Run `git clone https://github.com/MarlonGamez/cs2-github-intro.git` to clone the repository to your machine. This will copy the repository to your machine so you can work with it locally :)
![Screen Shot 2022-10-19 at 12 40 59 PM](https://user-images.githubusercontent.com/12601690/196776867-0abefcb8-5dce-4a28-ab38-2afa2a0438a1.png)
You can see the fork button in the screenshot

## Clone the repository
Run `git clone https://github.com/YOUR_GITHUB_USERNAME/cs2-github-intro.git` to clone the repository to your machine. This will copy the repository to your machine so you can work with it locally :)

## Create a new branch
Run `git checkout -b YOUR_BRANCH_NAME` to create a new branch to work on. Replace `YOUR_BRANCH_NAME` with whatever you'd like to call your branch.

By default you are on the `main` branch of the repository. It is common practice to create new branches to work on features, and then merge the changes on your branch into `main` once the feature is ready.

## Make a change and commit your changes
Make some change to `Main.java`. If you now run `git status`, you'll see that you have "Changes not staged for commit".
In order to include your changes in your next commit, you will have to run `git add Main.java`. This will add it to the list of files whose changes should be included in the next commit.

Commit your changes by running `git commit -m "SOME_MESSAGE_HERE"`. Replace `SOME_MESSAGE_HERE` with whatever message you'd like to associate with your list of changes. Using good commit messages is important for keeping track of changes to your code.

## Push your branch + changes
So far, everything you've done has only been on your local machine. None of the branches you've created or commits you've made exist remotely on the remote repository. To get them to our remote repository, you'll have to "push" them there.

To do this, run `git push -u YOUR_BRANCH_NAME` (Use your branch name from earlier). If you forgot your branch name, running `git status` will tell you what branch you're currently on.

## Open a pull request
Now your changes exist on the remote branch and can be viewed on Github. To get your changes merged into the `main` branch, we'll have to create a "pull request". Creating a pull request will allow us to view your changes and review them before we decide to merge them into our `main` branch.

## Closing
Now that you've merged your branch into `main` you can checkout the `main` branch on your local machine (`git checkout main`).
Run `git pull` and the changes that have been made to the remote branch will get synced down to your local branch. :)

From here, you can create any repositories you want! I highly recommmend to put any personal projects you have on git + Github. Working with git will make life a lot easier and less stressful.

You should try creating your own repo and putting some code there. You can create both public and private repos. Please DO NOT put any class projects in public repos :)
