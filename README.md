$ config user.name "Jack Gell"
$ config user.email "jack.gell@students.plymouth.ac.uk"



# Lab session 1
## Software engineering for roboticists

### Step 1 - Write your first Markdown document

The text below is our first attempt at using the markdown syntax.

# ROCO222
## Introduction to Sensors and Actuators

**This is an example of bold text**

*This is an example of italics*

~~Strikethrough~~

1. Item 1
2. Item 2
..* Sublist of item 2
3. Item 3

### Step 2 - Command-line 101

opened the terminal amd tried a few commands

**$ ls**

This command gives us a list of directories.

**cd /tmp**

This command changes directories, in this case to tmp.

**cd $HOME**

cd is used to change a directory.In this case, the home directory. The dollar sign means a normal user as opposed to a 'root' user. 

**mkdir**

mkdir is for making new directories.

**echo "hello" > hello.md**

echo is a built in command that writes its arguments to standard form. This writes "Hello" in a markdown document named hello.md

**cat hello.md**

cat is short for concatenate. cat allows use to create single or multiple diles , view contents of a file, concatenate files and redirect the output in terminal or files. Using this command, the terminal ouput "Hello", thereby showing what we wrote in the markdown document.

**cp hello.md hello-again.md**

This copies the contents of hello.md into a new markdown named hello-again.md

**mv hello-again.md hello-hello.md**

This renames "hello-again.md" to "hello-hello.md"

**rm hello.md**

This has deleted the hello.md directory.

**rm -rf** the rm -rf is the same as rm -r -f the -r meaning "remove directories and their contents recursively" the -f will "ignore nonexistent files and arguments, never prompt"

**cat /proc/cpuinfo**

This command lists characteristics of the computer's cpu, incluidng number of cores.



