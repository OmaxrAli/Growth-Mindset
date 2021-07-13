## Git

![Git](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQpVK3RQC6LtSy6ZAV69TsEHZFxKfGSxhfSiMRKCQSVBi76HeALh2H_huzUWy9WgwFGA10&usqp=CAU)

#### What Is Git ?

well **Git** is the most popular **(Version Contro System)** in the world, a version control system records the changes made to our code over time in a special database called repository we can look at our project history and see who has made what changes when and why, and if we screw something up we can easily revert our project back to an earlier state without a version control system we'll have to constantly store copies of the entire project in various folders.

this is very slow and doesn't scale at all especially if multiple people have to work on the same project you would have to constantly toss around the latest code via email or some other mechanisms and then manually merge the changes.

with a version control system we can track our project history and work together
version control systems fall has two categories **centralized** and **distributed** 

### **centralized**
in a centralized system all team members connect to a central server to get the latest copy of the code and to share their changes with others subversion and Microsoft team foundation server are examples of centralized version control systems the problem with the centralized architecture is the single point of failure if the server goes offline we cannot collaborate or save snapshots of our project so we have to wait until the server comes back online.

### **distributed** 
in distributed systems we don't have these problems every team member has a copy of the project with its history on their machine so we can save snapshots of our project locally on our machine if the central server is offline we can synchronize our work directly with others
git and mercurial are examples of distributed version control systems out of all these **git** is the most popular version control system in the world because it's 
1.	free 
2.	open source
3.	fast
4.	scalable

operations like branching and merging are slow and painful in other version control systems like
subversion so git is almost everywhere more than 90% of software projects in the world use git that's why almost every job description for a software developer mentions git
know how it works and how to use it to

### How does it works?

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit
![Git Working Flow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

the work flow works through this kind of cycle and by using commands we can atchive this kind of work flow

![Git Cycle Working Flow](https://support.nesi.org.nz/hc/article_attachments/360004194235/Git_Diagram.svg)
