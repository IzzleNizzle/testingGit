## Steps in git

1. Clone Project
```bash
$ git clone https://github.com/IzzleNizzle/testingGit.git
```
2. Create your own branch
``` git checkout -b branch-name```
3. Make changes
4. Push changes to your branch
```git add .```
```git commit -m 'Some message"```
```git push```
You may need to do this (If it's your first time)
```git push --set-upstream origin branch-name```

Then when you want to download the most up to date code, do a 

```git pull origin master```