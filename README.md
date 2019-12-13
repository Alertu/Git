首先在文件中 git init
然后 git add 添加需要添加文件
然后 git remote add origin ssh://gqf@121.42.229.168:29418/19ApiInterfaceDocumentation.git（添加版本库的连接 也就是连接版本库）
然后 git commit -m '修改说明'
然后 git push -u origin master 推送
下次git push -u origin master 之前需要 git  pull
