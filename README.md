# Git CLI Usage
## On Git Server
You must create a bare repository.
```
git init --bare new-repo
```
## On Local Server
Seta  email and a username that you can modify on user's directory
```
git config global user.email "o.o"
git config global user.name "o'
```
Clone the repo
```
git clone git@server:/path/repo
```
Since you add or change files, add the changed files to temporary area.
```
git add .
```
Add commment
```
git commit -m "News"
```
Push to remote repository
```
git push -u origin main
```
