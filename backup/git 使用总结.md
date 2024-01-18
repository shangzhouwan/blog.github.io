```
git chekout -b branchname

git reset --hard origin/release/2.3.0
```



然后  add

再然后 commit



最后一步

`git push origin HEAD`



————————————————————————

回退版本

       回退一个：`git reset --soft HEAD^`



删除远程分支：

      
```

git branch -a
# *master
#  test
#  remote/origin/master
#  remote/origin/test

```
```
git push origin --delete test
# To <URL of your repository>.git
#  - [deleted]         test

```
怎么查看自己clone 的 是https还是ssh 的

`git remote -v`