>Copy repository to github folder

```
cd github
git clone https://github.com/Ripley6811/TAIMAU-WEB
```

>Copy changed folders to main app folder

```
cp -a github/TAIMAU-WEB/views/. Documents/TAIMAU-WEB/views
```

>Restart process if there are server side changes (client-side changes do not need restart)

```
 sudo forever stop app.js --prod
 sudo forever start app.js --prod
```
