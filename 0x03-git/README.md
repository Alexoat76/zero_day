<p align="center">
<img src="https://img.shields.io/badge/LINUX-darkgreen.svg"/>
 <img src="https://img.shields.io/badge/Git-orange.svg"/>
<img src="https://img.shields.io/badge/Markdown-black.svg"/>
	
</p>
	
---

# 0x03. Git

<p align="center">
  <img width="350"  
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/2560px-Git-logo.svg.png"
  >
</p>	

# Getting Started :running:	
<div style="text-align: justify">
	
## Table of Contents
* [About](#about)
* [Resources](#resources-books)
* [Requirements](#requirements)
* [Tasks](#tasks)
* [Credits](#credits)

## About
	
This project contains some tasks for learning about the basics of **`Git`**.
  
## Concepts
For this project, look at these concepts:
- [Source code management](https://intranet.hbtn.io/concepts/22) 
- [Git and Github cheat sheet - Everything in less than 30 seconds](https://intranet.hbtn.io/concepts/57) 
- [The Framework](https://intranet.hbtn.io/concepts/75) 
- [Approaching a Project](https://intranet.hbtn.io/concepts/350) 

## Resources :books:
Read or watch:
	
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/80px-Google_2015_logo.svg.png)](https://www.google.com/search?q=git+bash+commands&ei=VLYzYpr0BJWUwbkP3oaJsAQ&oq=git&gs_lcp=Cgdnd3Mtd2l6EAEYATIECAAQQzIECAAQQzIKCC4QxwEQ0QMQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzoHCAAQRxCwAzoHCAAQsAMQQzoLCC4QgAQQxwEQ0QM6BQgAEIAEOgsILhCABBDHARCjAkoECEEYAEoECEYYAFDp_QJY7f8CYMC1A2gBcAF4AIABrQGIAcEDkgEDMC4zmAEAoAEByAEKwAEB&sclient=gws-wiz)

[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Logo_of_YouTube_%282015-2017%29.svg/70px-Logo_of_YouTube_%282015-2017%29.svg.png)](https://www.youtube.com/results?search_query=git+tutorial)	
	
- [Resources to learn Git](https://intranet.hbtn.io/rltoken/rOOPwBFp4ezRunQ0G0YHYQ) 
- [About READMEs](https://intranet.hbtn.io/rltoken/4CwCa3MmQvJfXu5poTRVQw) 
- [How to write a Git commit message](https://intranet.hbtn.io/rltoken/zkdCE4WEr9H91WlOpfNlGA) 

Resources for advanced tasks  (Read only after finishing the mandatory tasks):
- [Learning branching](https://intranet.hbtn.io/rltoken/514Jj2WL9uL6wOyOYWejdA) 
- [Effective pull requests and other good practices for teams using GitHub](https://intranet.hbtn.io/rltoken/ZUE0eoAWDKadJd4QCQkzQg) 

## Requirements
### General
* A  `README.md`  file at the root of the repo, containing a description of the repository.
* A  `README.md`  file, at the root of the folder of this project (i.e.`0x03-git`), describing what this project is about.
* Do not use GitHub’s web UI, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
* Your answer files should only contain the command, and nothing else.

## More Info
### Install git

**If `git` is not already installed on your terminal:**

``` 
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```
### Basic usage

**At the end of this project you should be able to reproduce and understand these command lines:**

```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```
## Tasks

### 0. Create and setup your Git and GitHub account

You will need Git for this project, you might have to  [install it](https://intranet.hbtn.io/rltoken/n2SJyaVuu1tuhVgHSKw5Sg) 
  on your computer if it’s not done yet.
* Configure your basic info (name, email) on your local machine – they will be part of your commits. [Tips](https://intranet.hbtn.io/rltoken/WCZwvMlDTWNwo7D2h5RXiw) 

On  [GitHub.com](https://intranet.hbtn.io/rltoken/YNvmlBzyEYR4EcwFclIbwQ) 
 :
* Using the graphic interface on the website, create the repository (if it’s not done yet)* Name: `zero_day` 
* Description: `This is my first repository as a full-stack engineer` 
* Public repo
* No `README`, `.gitignore` , or `license`.

Update your Intranet profile by adding your Github username [here](https://intranet.hbtn.io/rltoken/18IAhpoWtIm4rxdhYLU3kg) 
  - if it’s not done,  the Checker won’t be able to correct your work
On your computer, open a terminal and do the following:
* Navigate to your home directory. [Tips](https://intranet.hbtn.io/rltoken/nSl91LBC_er1QmayRs60Rg) 

* Create a directory `zero_day` . [Tips](https://intranet.hbtn.io/rltoken/qE0DHC3e86f7eZF6mlqFyQ) 

* Navigate to this new directory. [Tips](https://intranet.hbtn.io/rltoken/hgr3egDWXiBW_PIDqBAWDA) 

* Initialize git and add the remote origin
* Create a file `README.md` with `Emacs` or `Vi` (or other command line editors) and write a small [Markdown](https://intranet.hbtn.io/rltoken/Na_yqM9Y5nNNXtvjVAxZKA) 
 text to present this project. `This file is mandatory in all School projects`.<br>
* Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)<br>
Good job! <br>
You pushed your first file in your `first repository` of the `first task` of your first `School project`.

---

### 1. Repo-session

Create a new directory called `0x03-git` in your `zero_day` repo.<br> 
Make sure you include a not empty `README.md` in your directory:<br>

- at the root of your repository `zero_day`<br> 
- AND in the directory `0x03-git` <br>
	
And important part: Make sure your commit and push your code to Github - otherwise the Checker will always fail.

---
 
### 2. Coding fury road

For the moment we have an empty project directory containing only a `README.md`. It’s time to code!
* Create these directories at the root of your project: `bash`, `c`, `js`.
* Create these empty files:

	*  `c/c_is_fun.c` 
	*  `js/main.js` 
	*  `js/index.js` 

* Create a file `bash/best` with these two lines inside: `#!/bin/bash` and `echo "Best"` 
* Create a file `bash/school` with these two lines inside: `#!/bin/bash` and `echo "School"` 
* Add all these new files to git
* Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

---

### 3. Collaboration is the base of a company

A branch is like a copy of your project. It’s used mainly for:
* adding a feature in development
* collaborating on the same project with other developers
* not breaking your entire repository
* not upsetting your co-workers
The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.
For this project, create a branch `update_script` and in this branch:
* Create an empty file named `bash/98` 
* Update  `bash/best` by replacing `echo "Best"` with `echo "Best School"` 
* Update  `bash/school`  by replacing  `echo "School"` with  `echo "The school is open!"` 
* Add and commit these changes (message: “My personal work”)
* Push this new branch [Tips](https://intranet.hbtn.io/rltoken/w-vaOsoyqzITnQQ2NoSf6g) 

Perfect! You did an amazing update in your project and it’s isolated correctly from the  main  branch. 
Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:
* Change branch to `main` 
* Update the file `bash/best` by replacing `echo "Best"` with `echo "This School is so cool!"` 
* Delete the directory `js` 
* Commit your changes (message: “Hot fix”) and push to the origin
Ouf, hot fix is done!

---

### 4. Collaboration: be up to date
	
+ **[up_to_date](/up_to_date)**

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.
For this task – and only for this task – please update your file `README.md` in the main branch from GitHub.com. It’s the  only time you are allowed to update and commit from GitHub interface.
After you have done that, in your terminal:
* Get all changes of the main branch locally (i.e. your `README.md` file will be updated)
* Create a new file `up_to_date` at the root of your directory and in it, write the git command line used
* Add `up_to_date` to git, commit (message: “How to be up to date in git”), and push to the origin

---

### 5. HAAA what did you do???
	
+ **[best](/bash/best)**

Collaboration is cool, but not really when you update the same file at the same time…
To illustrate that, please merge the branch `update_script` to `main` : “Cool, all my changes will be now part of the main branch, ready to be deployed!”
**HHHHHHHAAAAAAAA**

```
CONFLICT (content): Merge conflict in bash/best
```

As you can see, you have conflicts between two branches on the same file.
Your goal now is to resolve conflicts by using the version of the branch `update_script`, and push the result to the origin.
At the end, you should have all your work from the branch `update_script` (new file and two updated files) and all latest `main` commits (new files, delete folder, etc.), without conflicts.

---	
	
### 6. Never push too much

+ **[.gitignore](/.gitignore)**
	
	* Create a `.gitignore` file and define a rule to never push `~` files (generated by Emacs). [Tips](https://intranet.hbtn.io/rltoken/0ANsyvhObT_TYAToY8-lbA)

---

## Credits

## Author(s):blue_book:

Work is owned and maintained by 
	**`Alex Orland Arévalo Tribaldos`**  and credits for `group projects` are displayed in the respective `README.md` files.

<3915@holbertonschool.com>
	
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/25px-Octicons-mark-github.svg.png)](https://github.com/Alexoat76)
[![M](https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/25px-Twitter_Bird.svg.png)](https://twitter.com/aoarevalot)
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/25px-LinkedIn_logo_initials.png)](https://www.linkedin.com/in/Alexoat76/)

## Acknowledgments :mega: 

### **`Holberton School`** (*providing guidance*)
	
This program was written as part of the curriculum for Holberton School.
Holberton School is a campus-based full-stack software engineering program
that prepares students for careers in the tech industry using project-based
peer learning. For more information,  please visit [this link](https://www.holbertonschool.com/).
![Brand](https://assets.website-files.com/6105315644a26f77912a1ada/610540e8b4cd6969794fe673_Holberton_School_logo-04-04.svg)
