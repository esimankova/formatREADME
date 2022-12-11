# How to get started with GIT?

## Configuring and running GIT and Visual studio code

* download GIT and Visual studio code
* install GIT and Visual studio code

### Open Git Bash Here

1. input: git version

*this is Git activation*

2. input: git config --global user.name "name"
3. input: git config --global user.email "emai@mail.ru"

*this is user initialization*

4. input: git configuration --list

*this is a test of whether Git remembers the user or not*

## Getting Started in Visual studio code

1. To close Git Bash Here
2. Open Visual studio code

Click: File -> Open Folder -> Open a folder from the desktop

In the folder from the desktop, create a file -> Assign the file the name "GB Home Work.md " -> right-click on the name on GB Home Work.md , select "open in integrated Terminal"

1. input: git version
2. input: git init

*Git initialized the repository. The directory has become a repository.*

*Directory - directory, directory, folder — an object in the file system that simplifies the organization of files.*

*Repository — a place where any data is stored and maintained.*

**Entering data for the first version of events**

1. Press the keys: Ctrl + S
2. input: git add GB+Tab 

*if you enter the first two letters of the repository name then press Tab the name will be entered automatically*

*we have added the text to the version control system*

3. input: git status

*a message that changes have been added to the version control system*

4. input: git commit -m "text"

*we have created the first version of the project and a comment on it*

5. input: git log

*message: comment/ its author/ date and time. This is a log that displays event versions*

**If you enter: Git checkout & the first four characters from the version name, we move on to the specific version**

**If you enter: Git diff we will see the difference of versions**

We have gone through the process of creating a file and committing to it.

# How to pick up someone else's repository from github.com and start working with it Visual studio code


**How to pick up someone else's repository from github.com and start working with it Visual studio code**

* Create a new folder on the desktop

* Visual studio code -> open folder

* github.com

* select repository

* copy the repository code

* Visual studio code

* git clone https://...

* cd (changing the directory)

*We took someone else's repository with github.com and we can work with it in Visual studio code*

# How to create a remote repository

* Create a new folder on the desktop 

* Visual studio code 

* open folder 

* new file 

* create text_file.md 

* git status 

* git add text_file.md 

* git commit -m "text" 

* github.com 

* new repository 

* git remote add origin https://... 

* Visual studio code 

* git branch -M main 

* git push -u origin main 

* github.com 

* update repository

*Remote repository created*

# How is the overall work on one project carried out

* github.com

* fork (someone else's repository is copied to my personal account in github.com)

* copy the repository code

* Visual studio code

* Open a folder

* git clone https://...

* cd (changing the directory)

* git branch name (new branch)

* git checkout name (transfer to the desired branch)

* new file READme.md

* editing

* git status

* git add READme.md

* git commit -m "text"

* git push -- set up stream origin description

* github.com

* compare &

* pull request create pull request message

*So there is a general work on one project*