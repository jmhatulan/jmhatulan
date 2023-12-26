## 📖 Introduction

Greetings! I am Joshua Miguel J. Hatulan.

- You may refer to me as **JM** or  **Joshua**
- I am currently a *B.S. Computer Science* student in Mapúa Malayan Colleges Laguna

<br/>

I aim to...

- Learn and develop myself to become a competent programmer
- Find myself on whether I want to become a *game developer* or a *data scientist*
- Be open with myself more and be more approachable

<br/>

I find enjoyment spending most of my time at home

- Watching Anime
- Playing Honkai: Star Rail

<br/>

## 📞 Contacts 

Feel free to contact
 me if you have any inquiries through the following channels.

- ✉️ Gmail: joshuapyguelhatulan@gmail.com
- 📣 Facebook: https://www.facebook.com/jshhtln 

<br/><br/>

# 🤖 Cheat Sheet



## 1. git init

### 🔧 Usage 
> Create an empty Git repository or reinitialize an existing one

### ✍🏻 Parameters
```
git init <directory>
```
> *Directory* specifies the path to the directory where you want to initialize the Git repository. If it is not specified, the Git will initialize the current working directory.

### 🔨 Example

> Say you want to create a new Git repository for an existing code base
```
cd /path/to/my/codebase
git init      (1)
git add .     (2)
git commit    (3)
```
1. Create a /path/to/my/codebase/.git directory.
2. Add all existing files to the index.
3. Record the pristine state as the first commit in the history.

## 2. git add
### 🔧 Usage 
> Adds file contents to the index

### ✍🏻 Parameters
```
git add <file or directory>
```
> *File/Directory* specifies the file/path to the directory where you want to be included in the next commit.

### 🔨 Example #1
> Say you want to add a single file named Example.txt
```
git add Example.txt
```

### 🔨 Example #2
> Say you want adds content from all *.txt files under Documentation directory and its subdirectories. <br/> Note: the asterisk * lets the command include the files from subdirectories of Documentation/ directory.
```
git add Documentation/\*.txt
```

## 3. git diff
### 🔧 Usage 
> Show changes between commits, commit and working tree, etc.

### ✍🏻 Parameters
```
git diff [<options>] [<commit>] [--] [<path>]
```
> All items indicated below are *optional* <br/>
*Options* are used to indicate the output's format.  <br/>
*Commit* are used to specify a commit or branch name to compare. If not indicated the Git compares the working directory to the staging area. <br/>
*Path* specifies the file(s) to show the difference for. If not indicated the Git will display differences for all modified files.

### 🔨 Example

> Say you want to see the different between a specific file commit and the current working directory
```
git diff oneTwoThree -- Example.txt
```
## 4. git commit
### 🔧 Usage 
> Record changes to the repository

### ✍🏻 Parameters
```
git commit [-m <msg>]
```
> *-m \<msg\>*  allows you to input a specific commit message in command line as a sort of tag to remember what changes there are in the new file. <br/>
*Don't forget to add quotation marks "" in \<msg\>, otherwise it will not work properly.**

### 🔨 Example

> Say you want to commit the changes with a commit message for this Learning Task
```
git commit -m "Added Cheat Sheet 4"
```
## 5. git fetch 
### 🔧 Usage 
> Download objects and refs from another repository. (It doesn't merge in the current branch)

### ✍🏻 Parameters
```
git fetch [<options>] [<repository>]
```
> *Options* are used to determine a specific remote. When no remote is specified, by default the origin remote will be used, unless there’s an upstream branch configured for the current branch. <br/>
*Repository* can be either a URL or the name of a remote.

### 🔨 Example #1

> Say you want to fetch changes from the default remote repository, origin, for all branches
```
git fetch
```

### 🔨 Example #2

> Say you want to fetch changes for a specific branch from the remote repository
```
git fetch origin main
```
## 6. <!--insert command 6 here, and remove this comment (collab 1)-->
```

```
## 7. <!--insert command 7 here, and remove this comment (collab 2)-->
```

```