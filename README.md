# Hello

## This writeUp is my walkthrough in the challenge on the web site [wechall](http://wechall.net)

The challenge name is [`Training: Warchall - The Beginning`](https://www.wechall.net/challenge/warchall/begins/index.php)

The first step to do is to make registration on the site.  
On the level 0, you need to enter a password that is not the password you entred on your registration,
but a provisor password to access to on the server with ssh protocol.
When your entry is correct, a message is giving to you to connect with SSH protocol.  
The message is like this `SSH on username@wechall.net -p 19198`.
The server create an account as simple user with limitation access for you.

For the first time login via ssh, there is a message like this that appear:
 "Welcome to Ubuntu 22.04.3 LTS (GNU/Linux 5.4.0 x86_64)
    *Documentation:  https://help.ubuntu.com
    *Management:     https://landscape.canonical.com
    *Support:        https://ubuntu.com/pro/usr/bin/xauth:  
    file /home/user/username/.Xauthority does not exist"

So on my home directory, I have some files and directories.
I try to read the content of the first file name "WELCOME.md".
Into this file, I can read where the solutions of all challenges sould be find.

## Level 0

The level 0 is just an introduction. It is just consist to read the file where the solution was write.

## Level 1

For this level, the solution is store on directory. But it is bored to search under each directory one by one.
So I just use the commande "find -readable" to find all files that should be read for human.

## Level 2

This level is exactly the same as the previous but the file where the solution is store is under a hidden directory.

## Level 3

As the previous level the solution is under a hidden directory, but the permission to access to the file is denied.
But seen it with 'ls', I can see the file is under my control. So it is just consiste to change is access with 'chmod' command.

## Level 4

For this level, when I enter to the level directory. It shows me a message to find the solution under my home directory.
So like the previous level, when I found the file where the solution is stored. It is just consist to change the privilege of the file.

## Level 5

Like the level 0, it is just read the file on the main directory of the level.

_____________________________________________________________________________________________________________________
## It was so frustrated when you understand what you shoud do, but you don't know how to do this.
