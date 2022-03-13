# Command Line:
### Background
- The command line is a text interface for your computer. It’s a program that takes in commands, which it passes on to the computer’s operating system to run.

- From the command line, you can navigate through files and folders on your computer, just as you would with Windows Explorer on Windows or Finder on Mac OS. The difference is that the command line is fully text-based.


-  Commands

```cd
$ cd Desktop/
cd takes a directory name as an argument, and switches into that directory.

$ cd jan/memory
To navigate directly to a directory, use cd with the directory’s path as an argument. Here, cd jan/memory/ command navigates directly to the jan/memory directory.```

```cd ..
$ cd ..
To move up one directory, use cd ... Here, cd .. navigates up from jan/memory/ to jan/.
```

```HOME
$ echo $HOME
The HOME variable is an environment variable that displays the path of the home directory.```

```ls
$ ls
2014  2015  hardware.txt
ls lists all files and directories in the working directory```

```mkdir
$ mkdir media
mkdir takes in a directory name as an argument, and then creates a new directory in the current working directory. Here we used mkdir to create a new directory named media/.```

```pwd
$ pwd
/home/ccuser/workspace/blog
pwd prints the name of the working directory```

```rm
$ rm waterboy.txt
rm deletes files. Here we remove the file waterboy.txt from the file system.```

```rm -r
$ rm -r comedy
rm -r deletes a directory and all of its child directories.```