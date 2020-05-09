# Files
Multiple projects dedicated to file handling in Windows with Python.


Each project will be its own branch named 'master_branch-name' from solution 2 at - 
https://stackoverflow.com/questions/14679614/whats-the-best-practice-for-putting-multiple-projects-in-a-git-repository


> #### repo 1
>
> git push origin master:master-1
>
> #### repo 2
>
> git push origin master:master-2


## How To Add Another Project

### File structure

- Files
  - .git
  - .gitignore
  - README.md
  - Project-1
    - trunk
      - .git
	  - Project-1 files
	- branch
  - Project-2
    - trunk
	  - Project-2 files


### Git Command Line

cd "Project-2"

git init

git add .

git status

git commit -m 'your message'

git remote add origin 'https://github.com/PeterGeras/Files.git'

git push origin master_Project-2