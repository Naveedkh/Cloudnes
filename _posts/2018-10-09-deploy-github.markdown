---
layout: post
title:  "Steps to deploy github pages!"
date:   2018-10-09 11:02:54 +0300
categories: jekyll update
---
You can commit your website to GitHub Pages. The only thing you need is your Github account and  have git installed on your Mac. In our case we are using Jekyll template and Ruby.

To get started, on terminal initialize git inside your root directory and this will creat .git files:

$ git init

To add all files run below command on terminal:

$ git add --all

Type in below command to save the changes with a message:

$ git commit -m "inital commit"

Now Set up the remote repo to push to, in this case we will push the changes to Master branch:

$ git remote add origin https://github.com/your-username/repo_name.git

push your changes to the remote repository:

$ git push -u origin master
