# Github Pull Request Basics

## Objectives:

1. Understand what a pull request is
1. Identify how to create a pull request from one fork to another
2. Identify how to add commits to an existing pull request

## Overview:

The concept of a pull request is unique to Github. It is a request for the
owner of a receiving repository (`learn-co-students` in the case of labs) to
"pull" an update from _your_ "fork" of that repository.

Pull requests are what power the open source community. Through this process,
anyone can fork a repo, make changes and submit a pull request. Now instead of
just the owner working on their codebase, anyone can work on it.  [Here][pr] is
a great example of a pull request on the `Ruby` codebase.

Let's go over a conceptual example. It's OK if this feels a bit confusing at
first, you'll work through this countless times and eventually your brain
and fingers will both grasp what's going on.

### Pull Request to a Source Repository

1. Suppose you "fork" a repo from `https://github.com/learn-co-students/awesome-lab`.
2. You now have a _copy_ of that repo on your Github account i.e.
   ``https://github.com/your-user-name/awesome-lab`. Technologiests would say
   you "forked" the `awesome-lab` repo from the `learn-co-students` organization
   to the `your-user-name` organization.
3. But you still don't have a *local* copy of this repository on your computer.
   To do so you will...
4. Clone from **your** fork to your computer. There's no reason you _couldn't_
   clone from the _original_ repo. However, most repo owners don't want random
   people on the Internet (that's you!) committing to their repo. What you're
   going to do is establish a "parallel" repo in _your_ org and then tell the
   "source" repo "Hey, I added something awesome, I'm requesting that you _pull_
   it in."
5. Make some changes on your local machine
6. Push your code from your local system _back_ to _your_ fork
7. Create a pull request that requests your improved code be "pulled" into the
   source repo.

### Pull Request From One Fork To Another

Here's a story:

1. You fork the repository `https://github.com/learn-co-students/awesome-lab`
   to `https://github.com/your-user-name/awesome-lab`.
1. You make some changes to your newly forked repo.
1. Another student forks the repository
   `https://github.com/learn-co-students/awesome-lab` as
   `https://github.com/their-user-name/awesome-lab`.
1.  You make some changes and you want to send a pull request to their fork
    `https://github.com/their-user-name/awesome-lab`. How do you do this?

Amazingly, `git` doesn't care whether one repository is the "source" or is
"another fork of the source." Amazingly, if GitHub were to be wiped off the
earth tomorrow, local copies on hundreds of laptops 'round the world are _just
as good as the copy that GitHub_ had! This is why `git` is called a
"Distributed Version Control System." So, to share a pull request with another
student follows the same process as forking some famous project (like Ruby or
jQuery).

### Step 1

Click on the New Pull Request button.

![](https://curriculum-content.s3.amazonaws.com/gitpulls/2.png)

### Step 2

Here you can choose the base fork, which will be `their-user-name/awesome-lab`.
Then choose the head fork, which will be `your-user-name/awesome-lab`

Now click Create pull request.

![](https://curriculum-content.s3.amazonaws.com/gitpulls/4.jpg)

### Add Commits To An Existing Pull Request

Let's say you make a pull request from
`https://github.com/your-user-name/awesome-lab` to
`https://github.com/learn-co-students/awesome-lab`. Then you notice you made a
typo in your code. All you have to do is fix the typo, commit it and push up
the changes to your branch. As long as the pull request already exists, the
commits will be added automatically.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/github-pull-request-basics' title='Github Pull Request Basics'>Github Pull Request Basics</a> on Learn.co and start learning to code for free.</p>

[pr]: https://github.com/ruby/ruby/pull/1051
