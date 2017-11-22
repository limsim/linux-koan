# Linux Command Koan
koan 
*ˈkəʊɑːn,ˈkəʊan/Submit*

*noun*

a paradoxical anecdote or riddle without a solution, used in Zen Buddhism to demonstrate the inadequacy of logical reasoning and provoke enlightenment.

## How to navigate the file system
---
List all files in current directory
* ls
* ls -al
* ls -alh

Change directories
* cd /
* cd ~
* cd .
* cd .. 
* cd /bin


Change to the parent directory

Change to a child directory

Change to the current directory

What's the current directory

* pwd

## Where am I?
---
* apt-get install net-tools

Find out your address
* ifconfig

How to call home

## How do you to get on to the server anyway??
---
SSH

Creating a public key
* ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

Using the public key
* ssh -i id_rsa server_name.com

## Copying/Renaming/Moving files
---

Copy file
* cp file1 file2
* cp . ~/new-folder

Rename file
* mv file1 file2

Moving file
* mv file1 ./folder

## Viewing file
---
View log file
* tail logfile.log
* tail *.log
* cat logfile.log


Viewing log file as it's updated
* tail -f logfile.log

## Finding something in the log file
---
Find a particular string
* cat .bashrc | grep alias
* grep exception logfile.log

Find the number of occurance
* grep -o 'alias' .bashrc | wc -w

## How to make your life easier
---
How to download tools

## How to clean up the mess
---
How to clear your screen
* clear

How to clear line
* ctrl + u (not sure if this works everywhere)

## What's running on your machine
Find out what's runnng
* ps -axu

What's slowing down your machine
* top
* top -o CPU
* top -o MEM

How to kill a app
* kill -9 pid

## How to get Admin access
What to do when you need admin access
* sudo

## Curl

## tar

## ping
