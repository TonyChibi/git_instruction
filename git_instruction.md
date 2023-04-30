># wtf is git?

-*if only i knew*

-Don't worry kido, I will tell ya.

The GIT is a weird ancient program, that translate as Great Intriging Thing, or maby it is just a git. It was created by one ancient wizzard who caled himself Linux, or something like that. But that not the point.

The Git can remember versions of your projects. He can memorized every stroke in versions of project, and can tell you if they are different from version to version. And there is more features in it, but the main purpose is to control versions of yours.

-*But how can i find it?*

-It's simple, kido. Here is your [reference](https://git-scm.com/downloads) . Just choose your version thoroughly comparing to the sistem of yours and be gratefull.

-*Wow! What shall i do now?*

-Oh, kido... Im 238 years old, bring your grand some brandy and give him some rest, wouldn't ya? I'll leave you some guidence below
___
***
---
## <a name="first time">First time</a>
 __You need to <a name="Login">identify</a> yourself:__

 git config --global user.name "your_name"

 git config --global user.email your_email

 __To initialize project and create repository use<a name="init"> init</a> comand like this:__ 
 
 git init

 __Add and stage files for commitment to <a name="track">track</a> them:__
 
 git add "file_name"

 git add . (*-to add all files in the folder*)

 __To <a name="commit">commit</a> staged files in folder:__

 git commit -m "comment about this version, which is stricly necessarry"

 __Also you may want some files to be <a name="untracked_files">untracked</a>. For this you may create a folder with name "git.ignore" then stage and commit that changes. Then all files you don't want to be tracked you can just place in that folder, and they wouldn't show up__

## <a name="branching">Branching</a>
__To <a name="create_branch">create branch</a> the command is folowing:__

git branch branch_name

__To <a name="delete_branch"> delete branch</a>:

git branch -d branch_name

## <a name="observing">Observing</a>

__To <a name="observe_commits">observe commits</a> use *log* comand:

git log (-*shows you all commits relative to your current position*)

git log --all (-*shows you all commits existing in whole tree*)

git log --graph (-*shows you relative commits with a graphical illustration of tree's branches*)

__You can mix command's option's suffixes to fit your wills. For example:__

git log --all --graph (-*shows you all existing in tree branches and commits within them with graphical illustration*)

__To observe the <a name="difference">difference</a> between current not staged version and the last commit:__

git diff 

__You can compare current not staged version to some commit you wish:__
git diff code_of_commit (-*first four symbols of commit code would be enough*)

## <a name="crossing">Cross-over</a>
__To cross over versions or branches:__

git checkout branch_name (-*move you to another branch*)

git checkout code_of_some_commit 
(-*move you to another commited state. You can use only four first symbols of a commit code*)


git checkout main (-*to return on your latest commit on main branch or for some one - master branch*)

## <a name="merging">Merging</a>

__To <a name="merge">merge</a> branches or commits:__

git merge branch_name_or_commit_code (-*merge the current version with a chosen one*)

__There may be conflict between versions of a project if the same stroke appears to be different. You may choose between options there, eithere chose current, other or both to be in a state. You will need to commit resultad state then__

___

# THE USEAGE OF <a name='remote_rep'>REMOTE REPOSITORY</a>

**To <a name="clone">clone</a> remote repository use:**
---
git clone link_to_remote_repository (-*will clone remote repository inside your current file's dirrectory* )

**__see more of [clone](https://git-scm.com/docs/git-clone) function__**
___
**Then you can <a name="push">push</a> to and <a name="pull">pull</a> from that remote repository**:
---
git push (-*will merge your changes to remote repository*)

git pull (-*will merge remote repository with yours*)


