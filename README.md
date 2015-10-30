#Github Pull Request Basics

##Objectives:
1. Create a pull request from one fork to another
2. Understand how to add commits to an existing pull request

##Overview:
The concept of a pull request is unique to Github, meaning it does not exist outside of Github. Conceptually, it is a request for the owner of a receiving party (learn-co-students in the case of labs) to pull from you, because it would be rude to push your code onto someone else.

Let's go over a familiar example. Let's say you fork a repo from
`https://github.com/learn-co-students/awesome-lab`. You now have a copy of that repo on your Github account here
`https://github.com/your-user-name/awesome-lab`.

So you clone down that fork to your computer, make some changes and now you want to make a pull request back up to `https://github.com/learn-co-students/awesome-lab`.

Basically you are saying, "I have made these changes to the original repo, will you accept them?" You are requesting that learn-co-students take your changes and combine them into the original repo that you've forked. It's a way for you to work on someone else's code without breaking their codebase.

Pull requests are what power the open source community. Through this process, anyone can fork a repo, make changes and submit a pull request. Now instead of just the owner working on their codebase, anyone can work on it. [Here](https://github.com/ruby/ruby/pull/1051) is a great example of a pull request on the `Ruby` codebase.

###Pull Request From One Fork To Another

Let's say you fork repository `https://github.com/learn-co-students/awesome-lab` as `https://github.com/your-user-name/awesome-lab`. Then you make some changes to your newly forked repo. Another student forks the repository `https://github.com/learn-co-students/awesome-lab` as `https://github.com/their-user-name/awesome-lab`.

Now you make some changes and you want to send a pull request to their fork `https://github.com/their-user-name/awesome-lab`. How do you do this?

###Step 1
Navigate to your forks page, `https://github.com/your-user-name/awesome-lab` and click on pull requests in the top right corner.

![](http://readme-pics.s3.amazonaws.com/gitpulls/1.jpg)

###Step 2
Click on the green New Pull Request button.
![](http://readme-pics.s3.amazonaws.com/gitpulls/2.jpg)

###Step 3
Here you can choose the base fork, which will be
`their-user-name/awesome-lab`. Then choose the head fork, which will be `your-user-name/awesome-lab`
Now click Create pull request.
![](http://readme-pics.s3.amazonaws.com/gitpulls/4.jpg)
