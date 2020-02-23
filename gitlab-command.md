Git的基本操作

1.创建版本库

bash :在创建的文件夹下，右键打开“git bash”,输入git init,文件夹下出现.git隐藏文件夹

添加到暂存区 git add aaa.txt,   git add . 添加多个文件

再添加到本地仓库 git commit (此处必填操作日志) git commit -m '简单的日志'

查看当前工作状态 git status

查看文件版本区别 git diff

还原修改内容 git checkout HEAD aaa.txt

删除内容 git rm aaa.txt

生成公钥私钥：ssh-keygen -t rsa

连接远程仓库： git remote add origin git@192.168.160.14:lichang/esop.git

查看远程仓库状态： git remote -v

推送到远程仓库： git push -u origin master

查看所有分支：git branch -a

创建分支：git branch dev (例如创建了dev分支)

切换分支：git checkout dev (在文件中修改数据，返回master分支会查看不到)

合并分支：git merge dev 合并分支后，会看到修改的内容

TortoiseGit:

右键，在此地方建立版本库即可

添加到暂存区：右键选择TortoiseGit,添加，确定

添加到本地仓库：右键commit即可

查看文件版本区别: 右键版本库，git diff

查看日志：右键版本库，查看日志

还原修改内容:右键空白区域，选择Tortoise,还原

删除内容：右键，Tortoise,删除，或删除保留本地

从远程克隆：git clone git@github.com:1x940112/aaa.git

拉取远程最新代码：git pull

推送到远程仓库：

配置SSH：右键，Tortoise->设置->网络->ssh->"选择git 下的ssh.exe文件D:/git/Git/usr/bin/ssh.exe"

配置凭证：右键，Tortoise->设置->Git->远端

> URL:填仓库地址URL

> 推送URL：填仓库地址URL

> Putty密 ：选择私钥文件

添加，应用，确定

推送：右键，Tortoise->推送（PUSH）

克隆：右键，git clone,填写clone的git的SSL地址,"确定"就可以

拉取远程代码（Pull）:右键，Tortoise->拉取(Pull)    =获取（Fetch）+ 合并

创建分支，右键，Tortoise->创建分支->
