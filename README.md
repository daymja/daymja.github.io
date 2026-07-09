## Index

- [Install GitBash](#install-gitbash)

#### Pre-requisites
- Visual Studio Code




## Install GitBash
1. Download **Git for Windows**
```javascript
	https://git-scm.com/install/windows
```
2. During the Setup, select ***Use Visual Studio Code as Git's default editor***
3. Leave all other settings as default
4. Open the Gitbash terminal
5. Create a local folder
```javascript
Mkdir Git
```
5. Using the terminal, navigate to the new folder
```javascript
cd c:\Git
```
6. Clone an existing repository, type command
```javascript
git clone https://<name_of_repository>
```
7. You will see message ***cloning into <name_of_repo>...'*** and then prompted with a GitHub sign in popup
8. Select and click button **Sign in with your browser**
9. Login into your GitHub account
10. Open VSC and type command
```javascript
git --version
```
11. If you see error
```javascript
git: The term 'git' is not recognized as a name of a cmdlet, function, script file, or executable program.
```
12. Check that your System Variables has value
```javascript
C:\Program Files\Git\cmd
```
13. Once you start to use the Git commands, you will likely get error "Author identity unknown**
```javascript
 git config --global user.email "you@example.com"
 git config --global user.name "Your Name"
```
14. You will only need to configure this once
