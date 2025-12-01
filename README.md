# Git CLI Usage
## On Git Server
You must create a bare repository.
```
git init --bare new-repo
```
## On Local Server
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
