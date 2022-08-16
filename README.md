# npm-version-test

## history

```shell
$ history | awk '{$1=""; print $0}'
npm init
npm i
git add .
git commit
npm version patch
npm version minor
npm version major
npm version patch -m "Upgrade to %s"
npm --no-git-tag-version version patch
git add .
git commit
```
