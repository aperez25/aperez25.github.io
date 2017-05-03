---
published: true
title: 3 Tools to Use Before Your Bootcamp Starts
tags: bootcamp-prep
categories: bootcamp-prep
label: bootcamp-prep
---
Among the things I wasn't prepared for starting CB was the amount of tools I'd be installing. Here are three you'll probably use regardless of which CB you attend:

<img src="/images/StockSnap_F21WWLQO5T.jpg" class="fit image">

## Don't be _bashful_

You might already know that a shell is a program that executes text commands. The standard OS X shell (i.e. the one installed on Macs) is called Bash. You'll hear "open your terminal" a lot during CB, which is basically the UI for your shell. Terminals look something like this: 

<img src="/images/computer-425208_640.png" class="fit image">

It's intimidating because instead of pointing and clicking to open folders and find files, you're typing in commands. But will you break your computer? Probably not.

Here are some basic bash commands to play around with in the terminal:
- `ls` "list" files and folders for your current directory
- `cd <folderName>` "change directory" to folderName 
	- example: `cd Downloads`
- `mkdir` => "make directory" creates a folder
	- example: `mkdir MyStuff` makes a new folder called MyStuff
- `touch <fileName>` creates or updates a file
	- example: `touch index.js` makes a new Javascript file 
- `pwd` => "print working directory" i.e. it prints the file path
	- example: `pwd` outputs "/Users/your_username/Downloads"


A comprehensive list can be found on this [cheat sheet](https://learncodethehardway.org/unix/bash_cheat_sheet.pdf).

<img src="/images/StockSnap_A28WZDTYEY.jpg" class="fit image">

## Replacing repl.it 
Up until CB prep work I had been using some sort of online coding interface, mainly repl.it, to write and run coding problems. This quickly changed once my CB prep work started. The two text editors I've heard mentioned the most are [Sublime](https://www.sublimetext.com/) and [Visual Studio Code(VSC)](https://code.visualstudio.com/). 

My brother, who's studying Computer Sciemce, is using VSC, so I went with that. The biggest difference I've noticed between VSC and Sublime is that VSC has a "Code Runner" extension that works in the editor itself - really helpful when you're testing and debugging. 

Other than that, I think it's all about personal preference, as both have lots of packages/extensions to make writing code easier. 

## Git Outta Here
Git is the most commonly used VCS, or Version Control System. A high-level description is it records changes to a file or set of files over time. I won't say much more than that as Git is important enough that you should take the time to download and research what it is and how to use it. Here is a [simple guide](http://rogerdudler.github.io/git-guide/) to get you started.

An important part to your experience with git will be github.com. I have only been using both of these tools for a month(!), but here are some workflows you'll definitely use again and again. As I said, I will leave it you to research what each step does!:
- Create a new repository by typing `git init` in your terminal
- Use github.com's `Fork` button to create a copy of someone else's project
	- clone your fork in the terminal with `git clone [URL-TO-YOUR-FORK]` (don't include the brackets!)
- Add some files and make changes to your files with your text editor
- `git add -A` 
- `git commit -m "YOUR COMMIT MESSAGE HERE"`
- `git push origin master`


