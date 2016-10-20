# HelloWorld
HelloWorld

推送到多个远程仓库:

编辑本地仓库的.git/config文件
```
[remote "all"]

    url = https://github.com/Xlongshu/HelloWorld.git

    url = https://git.oschina.net/longshu/HelloWorld.git

```
或者:
```
git remote add all https://github.com/Xlongshu/HelloWorld.git
git remote set-url --add all https://git.oschina.net/longshu/HelloWorld.git
```