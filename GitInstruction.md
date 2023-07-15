# Work with Git
## 1. Git installation check
`Git version`  command in terminal.
If Git has installed appearing message about git version else error message
## 2. Git installing

Download Git from site [Download](https://git-scm.com/downloads).
Default installing.
## 3. Git configuration
First needed - appearance. For that insert in terminal two commands:
```
git config --global user.name «Your name»
git config --global user.email your email
```

```C#
while(n<0)
{
    n++
}
```
## 4 Repo initiating

Go to target folder in terminal. Execute command:
```
git init
```

## 5 Record changes in repository

Use command 
```
git add 
```
for add file to tracking files and then
use command 
```

git commit -m
```
to fix file changes and name this fixation after -m 
or use single command
```
git commit -am
```
instead previous two command
## 6 Commit history view
For this use command
```
git log
```
for detailed changes or
```
git log --oneline
```
to view general info in one line by commit
## 7 Move from commite to commit
Moving to the commit carried out by command
```
git checkout
```
after this command write some hash symbols from the commit
To turn back use command
```
git checkout master
```
This command turns last commit in master branch

## 8 Ignore Files 

for except file or folder  create file ***.gitignore*** and record there folder or files names ot templates

## 9 Creating branches

Default branch name - **master**

To create branch use command 
```
git branch <new branch name>
```

All branches view with command 
```
git branch
```
Current branch have marker: *\*master*

## 10 Merge branches and resolve conflicts
To merge the branch with current use command 
```
git merge <branch name>
```
If part of file was changed in different branches it follow conflict. It requires to resolve conflict manually

## 11 Delete branch

To delete branch use command 
```
git branch -d <branch name>
```
after this write branchname you wish to delete. For delete branch in force instead *-d* use *-D*

## 12 Difference between commits

Use command 
```
git diff <hash commit 4 symbols >
```
to see difference between current commit and scpecified commit

## 13 Checkout branches

For this use command 
```
git checkout <branch name>
```
or 
```
git switch <branch name>
```

## 14 Images insert
To insert image use follow command:
```
![<Text>](<fileName>)
```
 Example ![GitHubLogo](github_logo.png) 
 
## 15 Work with remote repository
1. Create account on GitHub
2. Create local repository
3. Create remote repository
4. To link remote and local repositories
To add remote repository to project
```
git remote add <repository name> <repository URL>
```
```C#
while(count>0)
{
count--;
}
```
To get merged changes from remote repository use command `git pull`
To get unmerged changes from remote repository use command `git fetch`

## 16 Work with not owned projects
1. Find project and push button `Fork`
2. Clone this fork on your local machine by command 
```
git clone
```
3. Should be right to create **new** branch by command described above
4. Make your changes and commit it by command described in  block `5 Record changes in repository`
5. Push your changes to remote repository by command
```
git push
```
6. Create Pull Request in remote repository.