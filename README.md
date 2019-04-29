# UsageOfFork
---
Memo about usage of Git GUI client, Fork.  

## Table of contents
---
<!-- TOC -->

- [UsageOfFork](#usageoffork)
    - [Table of contents](#table-of-contents)
    - [Introduction](#introduction)
    - [About Fork](#about-fork)
    - [Downloading and Installation](#downloading-and-installation)
    - [GUI](#gui)
    - [Clone](#clone)
    - [Repository Manager](#repository-manager)
    - [Commit](#commit)
    - [Push](#push)
    - [Create Branch](#create-branch)
    - [Merge Branch](#merge-branch)
    - [Merge Conflict](#merge-conflict)
    - [Conclusion](#conclusion)

<!-- /TOC -->


## Introduction
---
I tried to use Git GUI client, Fork.  
This article is a memo about usage of Fork.  

## About Fork
---
You can see an explanation about Fork on the following web site.  
[Fork - a fast and friendly git client for Mac and Windows](https://git-fork.com/)

## Downloading and Installation
---
You can download an installer on the above web site and choose the one for Mac or for Windows.  

![](2019-04-28-21-50-41.png)

After you executed the installer, the following window will be opened.  

![](2019-04-28-22-04-01.png)

On this window, you need to enter your full name as user name and your e-mail address.  
Finally, you need to select source folder and push 'Finish' button.  

## GUI
---
GUI of Fork is this.  

![](2019-04-28-22-22-34.png)

There are 2 kinds of color theme, white and black. You can switch the color by pushing 'Theme' button as follow. The button is located on the upper right of GUI.  

![](2019-04-28-22-35-56.png)

The black color theme is as follow.  

![](2019-04-28-22-49-54.png)

## Clone
---
Open 'File' menue on the upper left of GUI and select 'Clone'.  
![](2019-04-28-23-13-10.png)
After 'Clone' was selected, the following window will be opened. You need to enter Repository URL, Parent folder and Repository name. Finally, you need to push 'Clone' button.  
![](2019-04-28-23-11-11.png)

## Repository Manager
---
On the left side of GUI, Git repositories in your PC like this.  
![](2019-04-28-23-36-39.png)

When you chose a repository, the informations about the repository will be displayed as follow.  
![](2019-04-28-23-54-35.png)

By pushing 'Open' button on the upper right, GUI will be switched to the one for staging and committing as follow.  

![](2019-04-29-00-04-59.png)

## Commit
---
You can see all of files which are changed and uncommitted by choosing 'Changes' on the left side menue.  
![](2019-04-29-00-12-03.png)

After 'Changes' was chosen, all of unstaged files are displayed as follow. The changed of each file are displayed by choosing the file.
![](2019-04-29-00-13-47.png)

When you want to commit them, you need to select files you want to commit and push 'Stage' button on unstaged files GUI. After that, you can enter commit subject, description and push 'Commit ~ Files' button on the lower right of GUI.  
![](2019-04-29-00-17-58.png)

## Push
---
'Push' button is located on the upper left of GUI as follow.  
![](2019-04-29-19-48-15.png)

You can see the following window by pushing 'Push' button. You can push the commited files to a remote repository on this window.  
![](2019-04-29-19-47-41.png)

## Create Branch
---
You can see all of branches on the left of GUI. In the following figure, a current checked out branch is master branch. When you create a new branch, you need to do right click on the original branch and select 'Create New Brach...' menue.  
![](2019-04-29-20-04-36.png)

For example, 2 new branches are created and displayed on the GUI like this.  
![](2019-04-29-20-15-19.png)

## Merge Branch
---
Firstly, you need to check out working branch. And then, you need to right click on the merge branch and select 'Merge into ~'. You can see the following Merge Branch window and can merge those branches.  
![](2019-04-29-21-36-56.png)

## Merge Conflict
---
If there is a conflict between 2 branches, a warning message 'The merge will require manual conflict resolution.' on Merge Branch window as follow.  
![](2019-04-29-22-24-08.png)

After you pushed 'Merge' button, a merge conflict message will be displayed like this.  
![](2019-04-29-22-27-29.png)

You need to close the above message and fix the conflict. Fork has a conflicts resolver which you can resolve the conflict easily. On the Fork GUI, you can see a 'resolve' button on the upper right. When you pushed the button, the resolver GUI will be opened as follow.  
![](2019-04-29-22-39-20.png)

On the GUI, you can choose the remote modification or local modification. If you want to choose the local modification, you should remove a check box of remote one as follow.  
![](2019-04-29-22-42-46.png)

Finally, you should push a button, 'Choose local (ours)'. And then, the conflict will be resolved and those branches will be merged automatically.  
![](2019-04-29-22-47-40.png)

The following figure is a commit log which merged branch 'branch_conflict' into master.  
![](2019-04-29-22-54-41.png)

## Conclusion
---
In this article, I explained about usage of Git GUI client, Fork. I think that there is not any much difference between another Git GUI client, for example, SourceTree. But, as I mentionted, Fork has a conflict resolver and it is very useful because I can fix the conflict easily on GUI. So, I think Fork is more useful than SourceTree.