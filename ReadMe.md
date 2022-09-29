#   GIT-GITHUB 101

### Hello everyone! You can follow this ReadMe file to install, setup and practice git and github on your desktop/laptop. If you face any trouble then reach out to me on any of my social handles which are mentioned in my profile.

<br />

## Version Control System(VCS)

- Track changes in files.
- See previous versions of individual files.
- Work on the same project with others, without affecting their work.

<img src="./VCS.png"> 

<br/>

## Git

- It is actually a distributed version control system designed to handle everything from small to very large projects with speed and efficiency.(Bookish language) XD
- Basically, Git is a tool that helps us in handling the files as explained in VCS.

<br />

## Git Installation

- Install Git from this [link](https://git-scm.com/downloads).
- Click on **next** in all the required settings while installing.

<br />

## Git Setup

- Configuring username:
`git config --global user.name “github uername”`
- Configuring email:
`git config --global user.email “github mail-Id”`

<br />

## Using Git

### To use git you must know certain basic commands as follows:

- `git init` : Initialize a git repository.

- `git clone` : To retrieve a repository from any code hosting platform.

- `git add filename`  or  `git add .` : Stage one or all the untracked files in the repository.

- `git status` : To check the Tracked and Untracked files in the working tree.

- `git reset filename` : To unstage a file while keeping the changes in the working directory.

- `git diff` : To check the unstaged changes.

- `git commit -m "message"` : To commit the staged files with a commit message explaining about the changes.

- `git branch` : To list all the branches of the current repository.

- `git branch [branch-name]` : Create a new branch.

- `git checkout` : TO switch to another branch.

- `git merge [branchName]` : To merge the current branch wiht the specified one.

- `git log` : To show all commits in the current branch's history.

- `git remote add [alias] [url]` : To add a git URL as an alias. (Alias help to shorten git command)

- `git push [alias] [branch]` : To transfer the local branch commits to remote repository branch.

## Fork and Pull Request

There are more amazing features which help us in working with other developers on GitHub:

1. **Fork**: It helps us to create a copy of an existing repository and make changes to the project without affecting the original repository.

2. **Pull Request** : Once we have made the changes and we are sure that the changes are valid, we can create a pull request for our changed code base in the original repository. This will let the author of the original repository review our code and merge it with the original code base.

3. **Fetch** : This helps us to fetch the changes from the original repository that have been made by other contributors.