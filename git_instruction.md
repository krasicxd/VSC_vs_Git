# **Git instruction**
Git - popular version control system created by Linus Torvalds back in 2005

Instruction below explores program features and explains it's meaning 

Setting up Git profile:

* git config --global user.name "user_name"
* git config --global user.email "email@address.com"

### **Main cmd line**

These are the most common commands to begin with Git:

* **git init** - initiates folder for Git
* **git commit** - adds a commit
* **git status** - checks current ststus

### ***Usefull status cmd's***

1. **git log** - checks the commit tree
2. **git diff**  - shows the difference between commits
3. **git checkout** - switches branch
## **Branch works**

### *Main cmd's*

Branching makes it easier to work on certain areas of the file

* **git branch** - shows the list of existing branches
* **git branch branch_name** - creates new branch
* **git checkout branch_name** - switches between branches

### *Additional cmd's*
* **git log --graph** - calls for the log sorted by branches
* **git branch -d branch_name** - deleting merged branch
* **git branch -D branch_name** - deleting branch without merging

### *Merging*

Merging allows to add changes made to the file in certain branch to others

Add info from branch to another use cmd:

* **git merge branch_name** - adding printed branch to current one

### *Merging conflict*

Conflict takes place if content from one branch located on the same lines with original one.

Merging will open up a window allowing to do followings:

* Accept current change
* Accept incoming change
* Accept both changes
* Compare files

!pic

### *Deleting a branch that isn't merged with the **master** branch will call up an error:*

!pic

### *You'd have to merge branch to master or delete it without merging using " -D "*

## **Image works**

To add and image
Set the path to the image from folder:
### **! [Image] (file_name)**
1. ! - to work with images
2. [_] - File name for consumer
3. (_) - Name of the file 

 *text_no_spaces

 !pic
## **Git vs Github**

### 