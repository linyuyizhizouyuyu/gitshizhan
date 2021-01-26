##今天学习了MarkDown
MarkDown是一种超文本语言，今天是我第一次学习了它
'''Hello MarkDown！'''
接下来我还会学习：
1. Git的基础命令
1. Hexo框架
1. Hexo更换主题
用命令行敲命令是一种Geek行为，我觉得还挺有趣的

Git 提交的三部曲
1. git add
2. git commit
3. git push

git add 是提交的第一步，一般使用下面的命令：
git add -A (A是all的意思)

git commit是提交的第二步，一般使用下面的命令
git git commit -m "本次提交的修改的备注" 
（新创建的文件必须按照顺序进行提交，如果只是修改文件，并没有
创建文件，也可以使用 git commit -am "本次提交的修改的备注" 来合并前面两个步骤）

git push是提交的第三步，分为三种情形
1. 第一次提交到本分支
2. 第2——n次提交到本分支
3. 提交到其他分支

第一次提交到本分支命令比较长，命令为：
git push origin master

第2--n次提交到本分支，命令简化为
git push

提交到其他分支
这命令用的相对比较少，一般会切换到相应的分支并进行提交
如果需要提交到b分支，命令为：
git push origin b