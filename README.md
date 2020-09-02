# GitBash Commands
- Basic Gitbash commands for beginners 

# Add Files to GIT using Git bash
- Create repository in github

- Install Git

- Open Git Bash

- Configure Git

```
$ git config --global user.name "Enter github username"
$ git config --global user.email "Your github emailid"
```
	
- Move to the folder you want to turn into a git Repository like "cd \Foldername"
```
$ git init
```
		
- Add files to Git Repository
```
$ git add .
```

- TO remove warning - LF will be replaced by CRLF in git 
 
		-If you want, you can deactivate this feature in your git core config using
    ```
    $ git config core.autocrlf false
    ```
		- But it would be better to just get rid of the warnings using
    ```
    $ git config core.autocrlf true
    ```
		
- If warnings not removed add files using 
```
$ git add *
```

- Commit Files in Git Repository
```
$ git commit -m "My first Commit"
```

- To see the status
```
$ git status
```
		
- Git push
```
$ git remote add origin https://github.com/your_github_user_name/repository_name.git
$ git push -u origin master
```		
		
Output Note:

1.create a new repository on the command line
```
echo "# Symptoms-Based-Disease-Tracker" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/your_github_user_name/repository_name.git
git push -u origin master
```

2.push an existing repository from the command line
```
git remote add origin https://github.com/your_github_user_name/repository_name.git
git branch -M master
git push -u origin master
```
                
	
