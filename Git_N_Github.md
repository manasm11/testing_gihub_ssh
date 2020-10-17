# INSIDE MASTER BRANCH AGAIN !!!!!!
# Topics
## 1. [Setup commands](#_SETUP_)
- ### [Configure](#_CONFIGURE_)
    - ### [Cloning](#_CLONING_)
    - ### [Creating New](#_CREATING_)

## 2. [Frequently used ones](#_FREQUENT_)
- ### [Get current remote repo (pull and branch)](#_PULL_)
- ### [Update changes to local repo (add and commit)](#_UPDATE_)
- ### [Sending changes to remote repo (merge and push)](#_UPDATE_)
## 3. [Rest Misc Commands](#_MISC_)
### 

<div style="page-break-after: always"></div> 
<a name="_PULL_"></a>

# Setup <a name="_SETUP_"></a>
## Configure (git config) <a name="_CONFIGURE_"></a>
- Username:<br>
```git config user.name "Homo Sepian"```
- Email:<br>
```git config user.email "abcd@xyz.com"```
>This name and email is used to track who has committed which changes.

>Use git config --global *\<rest code>* to avoid configuring these for each repository


## Cloning<a name="_CLONING_"></a>
```git clone <link to repository>```

## Creating<a name="_CREATING_"></a>
Go inside the project folder then:<br>
```git init```
```git remote add origin <link to remote repository>```

<div style="page-break-after: always"></div> 
<a name="_PULL_"></a>

# Frequently Used Commands <a name="_FREQUENT_"></a>
## git fetch


<div style="page-break-after: always"></div> 
<a name="_PULL_"></a>

# Miscellaneous Commands <a name="_MISC_"></a>
## Create branch
```git branch <branch name>```
## Switch branch
```git checkout <branch name>```
>To create and checkout the branch, use

```git checkout -b <branch name>```
## Go to just previous commit
```git checkout -f```
## View commits
```git log```
>To view commits with differences

```git log -p```
>To view *5* commits, use

```git log -p -5```

