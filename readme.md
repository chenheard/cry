将本地目录上传到github的步骤：
1.cd <本地目录>
2.git init
3.touch .gitignore
4.vim .gitignore
排除一些目录，比如/bin之类的
5.git add .
添加所有的文件，注意：add后面一个点
6.git commit -a -m "提交时的描述信息"
此时只是提交到本地
7.在github网页上新建一个github仓库，比如：nuptboyzhb/GLSurfaceViewBmpDemo · GitHub
8.git remote add origin nuptboyzhb/GLSurfaceViewBmpDemo · GitHub
将本地分支添加到远程
9.git push origin master
将本地分支推到远程
10.touch readme.md
如果你需要一个readme文件，先新建
11.vim readme.md
编辑，不会？请看这里：StackEdit – In-browser markdown editor
12.git add readme.md
将文件添加进来
13.git commit -a -m "add the readme.md"
提交到本地
14.git push origin master
推送到远程
