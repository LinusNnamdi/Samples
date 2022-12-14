MY GIT SUMMARY

1.	
INTRODUCTION
Git is a software used for free and open source version control system. It is a tool that tracks the changes of  your code over time.
GitHub is a web site to host your repositories online. It help many programmers to work on a project easily.
Version Control is the management of changes to documents, computer programs, large web sites, textbooks and other collections of information. There are kinds:
•	Local version control system
•	Centralized version control system, where there is a central server that is been managed by individuals directly.
•	Distributed version control system, here all contributor have the file locally which they use to manage the central/remote repository like GitHub, BitBucket, …etc .

2.	
TERMS AND MEANING
DIRECTORY is another name for folder. 
add is a github command used to track your files and changes in Git.
cd means change directory in your command line. 
CLI means command line interface.
clone is a github command used to get a repository that is hosted somewhere like GitHub into a folder on your local machine.
commit is a github command used to save your files in Git. 
GPG( Gnu privacy guard) is used to create a privacy means to send information through the network. it is mostly used for signin tags and commits.
pull is a github command used to download changes from remote repo to your local machine. 
push is a github command used to upload Git commit to a remote repo, like Github. 
Repository is a project or folder where your project is kept. 
SSH( secure socket shell or secure shell) is used to create a secure channel of sending information, mostly through the internet. it is mostly used for authentication.
Terminal is another name for Command Line, which is an interface for text command. Go to your PC search tab and search ‘cmd’, then hit enter to see what I meant.



3.	
INSTALLATION AND LOGIN
SIGNUP AND LOGIN:
1.	Firstly, search ‘Github’ in your device browser
2.	Then click the command that will take u to sign-up. To sign-up, you need Username, Email and a password.

INSTALLATIONS:
Installing Git:-
Installing Editor(s):-

4.	
COMMANDS AND THEIR USES

 
Image of git repo stages.
EDITING COMMANDS: 
git archive master --format=zip –output=../file_name.zip command is used to archive the master branch or any other branches.
git add . command is used to add every file that are not added to a specific branch that you on but when you use the file_name instead of “.”, as in the below, it will add only that file.
git add <file_name> command is adds our file to the staging area, as shown in the above image.
git branch command prints out all the branches you have with the branch name with asterisk being the branch you are presently on.
git branch any_name command is used to create a new branch.
git bundle create ../repo.bunbler master command is used to create a new bundle of your master branch.
git checkout branch_name command is used to switch from present branch to another branch.
git commit –m “small description about the file” command adds/commits your file that are added to the staging area with git add command to your local repo.
git config --global user.email  “EarnDee1@gmail.com” command isused to set your git account email address.
git config --global user.name “EarnDee” command set your git account Username.
git config -l command is used to list out all configurations u have made like user.name, user.email, … etc.
git clone the_link_you_copied is downloads a repository to your local device.
git fork … create original copy of a repository to your github account. 
git init command is used to initialize a new repository in git locally(without internet).
git log/log branch_name  command gives you a summary of all the commits, like time, id, email, associated to the branch you are in or you specified.  
git log --oneline command helps to print out log info in single line for each commit.
git log --online branch_name command helps you to print the log associated with the specified branch_name no matter the branch you are presently on.
git ls-file command list all available files that can be seen by git in your repo( local or remote). uncommitted files can’t be seen.
git merge branch_name command is used to merge a particular branch (branch_name)with branch that you presently on.
git pull origin master command pulls remote repo to your local repo for you to easily make change and test.
git push origin --delete master command is used to delete the master branch in the remote repository associated with origin.
git push origin master command pushes your local repo changes to the remote/central repo. This will request for your Username and password for the remote repo. origin is the alias, which can be any name and master is the branch that you want to push it to.
NB: if the remote repo is more updated than the local repo, you will require to pull b4 pushing.
git rebase master command is used to change the base of the present branch to include what is in the master_branch , which will now have different address.
git remote command is used to print out all the available remote repository name (alias).
git remote add origin remote_repo_link command lets you link a remote repo with your local repo.
git remote rename formal_alias new_alias command is used to rename a remote repo.
git remote remove/rm alias command is used to remove a remote repository
git remote -v command helps you to check if you have linked your remote repo to the local repo by printing out the remote repo path, like http…
git show few_part_of _that_particular_commit_id command show more about the changes made by a particular commit done in the local or remote/central repo.
Example:
PS C:\src\practices\my_project\nfcs> git show 933f902
commit 933f90203e5539ebddd6ae0e421078780b9bfa65 (HEAD -> master)
Author: Nnamdi <linusnnamdi114@gmail.com>
Date:   Sat Aug 27 02:58:27 2022 +0100

    NFCS app

diff --git a/.gitignore b/.gitignore
new file mode 100644
index 0000000..a8e938c
--- /dev/null
+++ b/.gitignore
@@ -0,0 +1,47 @@
+# Miscellaneous
+*.class
+*.log
:

git stash and git stash apply command is used to save uncommitted files into a temporary local.
git status command tells you more about your account adds, commit, … etc . 
#  is used to add main header to text.
.md is a file extension associated with github’s  readme file( README.md). it is an abbreviation for markdown.

BUTTON COMMANDS:
Your profile command takes you to your about page. Here You can edit your profile like picture, other account, email, … etc.
GitHub Logo when clicked, take you to your dash board.
The plus-sign at the top right or the new green button helps you to create a new repository.


5.	
FILE CREATION AND MANAGEMENT

CREATING A NEW REPOSITORY:
1.	Click the green button to create a new repository. You will be brought to the below page.
 
2.	The only required input in the above image is repository name, other inputs help you to make some restrictions and add flavor to the repository you want to create.
3.	Description is a small message that explains your repository.
4.	public let every one view and use your repository.
5.	private make you select who can view or use your repository.
6.	Add README file creates a readme file where you specified more description, do and don’t that are associated to your repository.
7.	Add .gitignore helps you to select files that won’t be pushed or pulled to or from your repository.
8.	choose a license help you to make your repository an open source.
9.	
10.	Repository name is adviced to be short.
11.	Then click create repository below, to move to the next image below.

ADDING NEW FILE:
1.	Click on create a new file under quick setup as in the image below to create a new file.
 
2.	Click on uploading an existing file under quick setup as in the image below to...
3.	The last two sections in the above image are just another way to create or add new repository or file.

EDITING FILES:
1.	When you click on create a new file, you will be  take to the below image. Here, you can edit filename like mine in the below image is README.md.
 
2.	# is used to make MY DART SUMMARY bold.
3.	After you have inputted your text, click commit new file as in the below image.  The Add an optional extended description in the below image is used …
 

CLONING A FILE:
Cloning a file is a means to download file(s) to your local machine so that You can use it offline. You can clone both your file and other peoples file provided that it is public.
GitHub provides three secure roots to clone your files, which are https, SSH, and Github ClI( used by contributors). 
To clone a file, open the repository and click the green code button as in the image below.
https is mostly used by those that have no ssh in their github account to clone a file to a local device.
SSH is used by those that have included it in their github account.
GitHub CLI is used …
 
After selecting the root you want to clone your file from, go to your PC command line (cmd) . Search with cd to the file you want to include the repo on, then type:- 
git clone the_link_you_copied
then hit enter.
NB: You must have git installed and a network connection.

6.	.

