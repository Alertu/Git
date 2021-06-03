## Git新建项目



##### 1、初始化

    git init



##### 2、自己要与origin master建立连接（下划线为远程仓库链接）

```shell
git remote add origin git@github.com:XXXX/test.git
```



##### 3、把远程分支拉到本地

```
git fetch origin dev（dev为远程仓库的分支名）
```



##### 4、在本地创建分支dev并切换到该分支

```
git checkout -b dev(本地分支名称) origin/dev(远程分支名称)
```



##### 5、把某个分支上的内容都拉取到本地

```
git pull origin dev(远程分支名称)
```

