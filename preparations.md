---
title: "Preparation for the course"
output: html_notebook
---
![](https://user-images.githubusercontent.com/37149324/46141952-b0dbbe80-c255-11e8-9cca-da81fc04bbb2.png)  



#### Welcome to Algorithms and Programming 2018 course!  



During this course you will learn to use R efficiently. In adition to learning R, (and perhaps more importantly) throughout this course you will use GitHub as a version control system. 



#### About version control



When you write any code, it will change a lot. Even when you do simple tasks for the first time, after few days your code will get much prettier than the first day. Trouble begins when you start to code for work. After finishing a project you will store it properly and never open it again.. for a month or two until it needs to be revized. After few months you will probably have few documents named project_finalcode.R, project_finalcode_FINALVERSION.R, project_finalcode_FINALVERSION_NEWEST.R .....



This happens to everyone. We will prevent this from happening to you.



The way to prevent this is to use [version control](https://vimeo.com/41027679). It enables you to see all saved changes in a file, all changes in each of the version, and go back to any version if needed. You can continue to work on some old version, in which case the document will "replicate" itself, and both new files will be saved. At any time you can see differences between different versions and merge them together. This is cool not only because it makes it easy for you to track your steps and changes, but it allows other people to work on the same document you are working on withouth creating clashes. And it integrates very well with Rstudio.



So lets avoid unneccessary mistakes and start clean from the start: installing Git.



# Setting up to Git and Rstudio



### 1. Download [Git](https://git-scm.com/downloads)

#### Make an account on [GitHub](https://github.com/join)



Use meaningful email, name and password. You will use this account throughout the course and hopefully later in life as well. If you use your university provided email, you will be able to have private repositories as well, which can not be seen by others. However, for the purpose of this course, you can use any email you want and all your repositories connected to this course will be private.





### 2. Download [R >= 3.5]()

### 3. Download [Rstudio >= 1.1](https://www.rstudio.com/products/rstudio/download/#download)

### 4. Connect GitHub to Rstudio:



Open Rstudio, Tools -> Shell. Type:



```{bash}

git

```



If this command does not produce an error, continue. Otherwise ask for help!

To connect your git hub account to Rstudio, you need to provide user name, email and eventually password. You can set up those to stay remembered (globally) by the following commands:



```{bash}

git config --global user.name "MaKuzman"

git config --global user.email "your@email.com"

git config --global user.password "somesuperstrongpassword"



```

If this is all done, you are ready to accept your first assignment!

### Accepting assignments!

In GitHub, many projects are open source. This means that you can see all the files (and all code) for them. If you create a gitHub account with any email adress, all your repositories will be publicly available. This means that when you do your homework and push it to your account, anyone who gooogles you will see the code. We don't want this now, so we will make private repositories for homeworks. This is why we will use GitHub Classroom - a gitHub service for educational purposes which lets you copy the assignment which I had prepared, to your own private directory. This directory is easy to access and copy locally with Rstudio. After you change the document (solve the homework, update the lectures), it is very easy to upload it back to your GitHub folder.

Here is the link to the first assignment you will have to accept, so lets try! 

After you accept the assignment, a private repository will be created for you with the name: https://github.com/UNIZG-PMF-Bioinfo/test-assignment-YOURNAME 

This repository now belongs to you and you can work on it. 

### Cloning repository to RStudio

1) Open Rstudio  
2) File -> New Project -> Version Control -> Git
3) Copy the link for your repository to the Repository URL and create project 
![gitclonerepo](https://user-images.githubusercontent.com/37149324/46141829-5cd0da00-c255-11e8-9eb3-4cf4ad3e5592.JPG)

4) Open the .Rmd file and edit it. Save.  
5) Upload the saved file to github:  
  i) Version control button -> commit  
   ![committing](https://user-images.githubusercontent.com/37149324/46142587-bfc37080-c257-11e8-82d3-ce15c6738832.JPG)

  ii) Select the files you would like to upload, write a description of what you did, Puch it online.  
  ![commiting](https://user-images.githubusercontent.com/37149324/46142588-bfc37080-c257-11e8-9842-8449508c4ea9.JPG)

#### That is all!
