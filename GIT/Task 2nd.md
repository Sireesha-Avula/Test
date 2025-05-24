```
git clone <<create a new git repo url>>
pwd
ls
cd .\test25azv01\
ls
New-Item -type f -name 1.txt
ls
git status
git add .
git status
git commit -m "sample 1.txt file via terminal"
git push
```
# we will get error, create a PAT (Personal Acces token)
- go to user > settings > developer settings > Personal access token > create a classic token

```
git push

```
# merge issues
- add some content on GitHub.com directly
- add some content locally
```
git add .
git commit -m ""
git push ---> fail
git pull
```
- resolve the merge conflicts manually

```
git add .
git commit
git push
```