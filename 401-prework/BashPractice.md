# Learning bash and navigating the terminal

## Lesson 1 and 2

- use ls -l to print a more detailed list of the current directory!
- the -l flag stands for long listing, and allows the user to get a lot of information in this sort of coded way. `drwxr-xr-x` stands for some sort of permissions, im guessing each of them stands for a type. It will be cool to learn how to read it.
- in my terminal ls -l printed over 300 things in my director when I was expecting maybe 10...
- ~ tilde refers to the home directory like `/home/frolic/` ... so `~/Documents` is the documents folder
- running cd without arguments takes you home.... wow... i wish I knew that forever ago haha...
- I did not think that the terminal had tab completion either so now I'm gonna go crazy...

## Lesson 3

- Its cool that linux treats even the keyboard and the screen as a file. An interesting concept. And I quickly began to see that files in linux for some reason did not care about extensions, which is no matter, so it's also cool to now that linux decides on its own what files should be considered. On top of that it is possible to use spaces in filenames and also easily hide files to make navigation easier. Hidden files aren't encrypted they are just invisible without searching for them on purpose with a flag like `ls -a`. Very cool!

## Lesson 4

- Manual pages have keyword search using `-k` flag and press n to move to the next term. I tried searching for something with `man -k l` and it gave me a long list of 1000 things with no details. and then tried man `-k `ls and it gave me the contents for ls and put me in a special viewing mode for the manual. pretty nice! I also found out I can clear the screen with the clear command.

## Lesson 5

- mkdir has flags too, -p created parent directories as needed when specifying a list of directories, and -v tells the terminal to print back to you what its doing for when you are making changes!
- cp [options] <source> <desitination> is the copy command
  -rmdir is for directors only, and rm is for files. you can add a -r flag to copy or remove (and maybe more) to repeat the action for various files/directories. There is not basic rename command, so you can move a file to a new 'path' to rename it. like `mv file1 file1.5`

# Lesson 6

- Always keep a cheat sheet and remember there are manual pages with `man` command... [Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
