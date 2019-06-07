# Terminal Commands

The instructors are going to put list of terminal commands here.

### Requirements

If you are using windows, these commands may work on command promt shell (CMD), however; it may or may not display all the information.
Therefore, please go to the following link (https://gitforwindows.org/) and download Git Bash.

Other operating system users already have terminal available to use.

#### Current Directory
Displays current directory from file system.

```
$ pwd
```

#### Change Directory
Changes to directory indicated by folder_name

```
$ cd folder_name
```
Changes to parent directory

```
$ cd ..
```

#### Listing
List all files & folders within the current directory
```
$ ls
```

List all files & folders within the current directory with more information
```
$ ls -l
```

List all files & folders within the current directory including hidden files & folders
```
$ ls -a
```

List all files & folders within the current directory with more information including hidden files & folders
```
$ ls -la
```

#### Creating new directory
Create a new directory with folder_name
```
mkdir folder_name
```

#### Creating new file
Create a new file with filename
```
touch filename
```

#### Opening file with text editors
Opening file in the current directory using Atom
```
atom filename
```

Opening file in the current directory using Visual Studio Code
```
code filename
```

#### Deleting file
Removing file within the current directory
```
rm filename
```
Removing all html files in the current directory
```
rm *.html
```


#### Deleting directory
Delete directory with folder_name within the current directory
THE FOLDER MUST BE EMPTY
```
rmdir folder_name
```
