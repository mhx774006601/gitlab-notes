我们在使用 gitlab down项目的时候，有时候会遇到master下所建的分支，并没有‘克隆’这一个功能点，这个时侯如果需要把项目切到分支下进行开发的话，方法如下：
先使用 master 下的 git clone http://ip地址/shuaizc/XXXX.git  把项目down下来
然后进入到本地项目的根目录下，打开 git bash 窗口，通过 git branch -r 可以查看 master 下的所有分支
然后再使用 git checkout origin/分支名  语句 切换到想进的分支里面去
这样就可以在自己想要开发的分支下边进行开发项目了
