<p align="center">
<img src="https://img.shields.io/badge/Vagrant-blue.svg"/>
<img src="https://img.shields.io/badge/LINUX-darkgreen.svg"/>
<img src="https://img.shields.io/badge/Shell-ligthgreen.svg"/>
<img src="https://img.shields.io/badge/Git-orange.svg"/>
<img src="https://img.shields.io/badge/Markdown-black.svg"/>
	
</p>
	
---

# [Optional] Vagrant

<p align="center">
  <img width="350"  
        src="https://www.datocms-assets.com/2885/1620083141-blog-library-product-vagrant-logo-dark-graphics.jpg"
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
	
This project contains some tasks for learning about the basics of **`VM`**, and **`Vagrant`**.
 
## Concepts
For this project, look at these concepts:
- [Source code management](https://intranet.hbtn.io/concepts/22) 
- [Git and Github cheat sheet - Everything in less than 30 seconds](https://intranet.hbtn.io/concepts/57) 
- [The Framework](https://intranet.hbtn.io/concepts/75) 
- [Using Vagrant on your personal computer](https://intranet.hbtn.io/concepts/81) 
- [Approaching a Project](https://intranet.hbtn.io/concepts/350) 

## Resources :books:
Read or watch:
	
[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2f/Google_2015_logo.svg/80px-Google_2015_logo.svg.png)](https://www.google.com/search?q=git+bash+commands&ei=VLYzYpr0BJWUwbkP3oaJsAQ&oq=git&gs_lcp=Cgdnd3Mtd2l6EAEYATIECAAQQzIECAAQQzIKCC4QxwEQ0QMQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzIECAAQQzoHCAAQRxCwAzoHCAAQsAMQQzoLCC4QgAQQxwEQ0QM6BQgAEIAEOgsILhCABBDHARCjAkoECEEYAEoECEYYAFDp_QJY7f8CYMC1A2gBcAF4AIABrQGIAcEDkgEDMC4zmAEAoAEByAEKwAEB&sclient=gws-wiz)

[![M](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Logo_of_YouTube_%282015-2017%29.svg/70px-Logo_of_YouTube_%282015-2017%29.svg.png)](https://www.youtube.com/results?search_query=vagrant+commands)	
	
- [Zero day](https://intranet.hbtn.io/rltoken/NcuS4-7zF9-edjbo157uQQ) 
- [Virtual machine](https://intranet.hbtn.io/rltoken/v2RbeSrU14w3KTwbGYH3Fw) 
- [man uname](https://intranet.hbtn.io/rltoken/3AHxDiZwhZwPM_GiHox0gQ) 
- [Resources to learn Git](https://intranet.hbtn.io/rltoken/i2CtlPhs4zaAbtEUdY2l3A) 
- [About READMEs](https://intranet.hbtn.io/rltoken/86HNyB59eoxAhtIahOXKGQ) 
- [How to write a Git commit message](https://intranet.hbtn.io/rltoken/4szBlqEXwOgr1YON9bxhPQ) 


## Requirements
### General

* A `README.md` file at the root of the repo, containing a description of the repository.
* A `README.md` file, at the root of the folder of this project (i.e.`0x00-vagrant`), describing what this project is about.

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
### Warning
This project can’t be done in Sandboxes  - it can be done only in your local computer.

## Tasks
### 0. Create and setup your Git and GitHub account.

You will need Git for this project, you might have to **[install it](https://intranet.hbtn.io/rltoken/TJrA7MIEl9LxnkGNH_ddmw)**
  on your computer if it’s not done yet.
* Configure your basic info (name, email) on your local machine – they will be part of your commits. [Tips](https://intranet.hbtn.io/rltoken/72jmwYpf2OeuoOn9XM3vQg) 

On [GitHub.com](https://intranet.hbtn.io/rltoken/m27bKy8K40cIkyHWQ36i2w):

* Using the graphic interface on the website, create the repository (if it’s not done yet)
	* Description: `This is my first repository as a full-stack engineer` 
	* Public repo: `zero_day` 
	* No `README`, `.gitignore`, or `license`.

On your computer, open a terminal and do the following:

* Navigate to your home directory. [Tips](https://intranet.hbtn.io/rltoken/-odz94uVNOsPV1ovYZLuyw) 
* Create a directory `zero_day`. [Tips](https://intranet.hbtn.io/rltoken/AHYBfU0itf9qEiwLdiaVJw) 
* Navigate to this new directory. [Tips](https://intranet.hbtn.io/rltoken/9g9c-qBPHWSGcpxbs69ASw) 
* Initialize git and add the remote origin
* Create a file `README.md` with Emacs (or other command line editors) and write a small [Markdown](https://intranet.hbtn.io/rltoken/Ru3ANLuzGs4g0v2qsN3efA) 
 text to present this project. This file is mandatory in projects
* Add this new file to git, commit the change with this message “My first commit” and push to the remote server/origin (Note: You will probably need to set your login/password to push to the remote server)<br>

**Good job!**

You pushed your first file in your  `first repository`  of the  `first task`  of your `first School project`.

### 1. Hello Ubuntu

+ **[0-hello_ubuntu](./0-hello_ubuntu)**
	
	* Inside the `zero_day` repo, create a new directory called `0x00-vagrant`. Add a `README.md` file to this directory. 
	`ssh` into your `Ubuntu VM`. What does the command `uname` print when you run it without any option? 
	Type your answer into a file in the `0x00-vagrant` directory and push it to GitHub. Name your file is **`0-hello_ubuntu`**.

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
