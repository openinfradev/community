# 전체 작업흐름도 이미지 삽입 Here

### 1 Fork in the cloud

1. Visit https://github.com/kubernetes/kubernetes
2. Click `Fork` button (top right) to establish a cloud-based fork.

### 2 Clone fork to local storage

Per Go's [workspace instructions][go-workspace], place Kubernetes' code on your
`GOPATH` using the following cloning procedure.

[go-workspace]: https://golang.org/doc/code.html#Workspaces

Define a local working directory:



### 3 Branch





#### Build


### 4 Keep your branch in sync


### 5 Commit

Commit your changes.


### 6 Push



### 7 Create a pull request



#### Get a code review



#### Squash commits


To squash your commits, perform an [interactive
rebase](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History):

1. Check your git branch:

 

2. Start an interactive rebase using a specific commit hash, or count backwards from your last commit using `HEAD~<n>`, where `<n>` represents the number of commits to include in the rebase.

 
3. Use a command line text editor to change the word `pick` to `fixup` for the commits you want to squash, then save your changes and continue the rebase:


 
4. Force push your changes to your remote branch:

### Merging a commit



### Reverting a commit



- [Create a Pull Request](#7-create-a-pull-request) using this branch.
