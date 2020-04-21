# 使gitignore文件生效


如果.gitignore不是git初始化的时候添加的，比如后面添加的，中途修改的；不会生效，生效方法：
```shell
$git rm -r --cached .  #注意后面的点

$git add .

$git commit -m ".gitignore is now working"
```
