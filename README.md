# sublime-settings

## Pulling down to other machines...

Quit Sublime Text 3, then run these commands:

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
git init
git remote add origin https://github.com/<github name>/<repo name>.git
rm Package\ Control.sublime-settings
git fetch
git checkout -t origin/master
```
