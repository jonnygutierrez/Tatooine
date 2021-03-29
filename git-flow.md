# list about the git flow

![github logo](https://miro.medium.com/max/2400/1*WaaXnUvhvrswhBJSw4YTuQ.png) 

---

![github](https://csharpcorner.azureedge.net/article/git-and-github-version-control-local-and-remote-repository/Images/Git%20And%20Github%20Version%20Control.png) 

## step 1
the first step for a git flow is create a directory, and then clone in the repository, this do it in the terminal,  this is with the command 
``git clone + link of repository``


![github clone](https://docs.github.com/assets/images/help/repository/https-url-clone.png) 

---
## step 2
 when create a repository in github must choose an license, we choose the license of MIT, also choose create a fille readme.md

![readme](https://fileinfo.es/images/file-format/md.png) 

---
## step 3
then create a branch in the repository with the name "develop", inside develop create other branch with some name, for example "01-git",for create a new branch is with the next command:
``git checkout -b 01-git ``
![branch from git](https://backlog.com/app/themes/backlog-child/assets/img/guides/git/collaboration/using_branches_001.png) 

---

## step 5
then check the status with 
`` git status ``
and nothing to commit cause we don't change nothing

---
## step 6
inside of branch 01-git we modify some file, in a text editor and save.

---
## step 7
 in the terminal add in the branch 01-git with command git add + name of file, for example:

``git add readme.md	 ``

---

## step 8
then check the status with 
`` git status ``
now we watching that have changes to be committed 

![status](https://www.toolsqa.com/wp-content/gallery/git/git_status_untracked_file-1.png) 
the picture is a example
---
## step 9
 then used the command :
`` git commit -v `` 
and then we can create a comment, save the file

also we can write a message with the next command:
``git commit -m "this is a new message" ``

---
## step 10 
 in the terminal wait for watching the changes 

---
## step 11
then check the status with 
`` git status ``
and nothing to commit cause we don't change nothing cause are in commit
---

## step 12
now, do a push this is with the command 
`` git push origin 01-git``
this must do from branch en where we are 

![push origin](https://assets-global.website-files.com/5d514fd9493b0575f03520bd/5e2a15c9b3437b2c33018f6f_1*E1Ypr2GO9CVgbbqrguB2Qw.gif) 


---
## step 13
must write our account from github and our password
---

## step 14
then in git change from branch a develop, this is with the command
`` git checkout develop``

![git checkout ](https://static.javatpoint.com/tutorial/git/images/git-checkout.png) 
---

## step 15
the write the command 
`` git push origin develop ``
---
 
## step 16
now, must write our account and our password from github 
---
 
## step 17

we must check that the base "develop" and compare with 01-git

---

## step 18
from github we create a pull request and then we do the merge pull request

and confirm the merge

in the server we have the change in develop

## step 19
when we do merge in develop must delete the branch in where did the first change 
![merge](https://developers.sap.com/tutorials/webide-github-merge-pull-request/_jcr_content.github-proxy.1608398416.file/p6_4.png) 
---

## step 20
then inside from terminal do a "pull", this with the command 
``git pull origin develop  `` 
![github logo](https://64.media.tumblr.com/9fb0685ca9c513197d3be0f4fd186e12/tumblr_inline_ps7dd2ta811wthf4f_540.png) 
---