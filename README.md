# qujing_university
#### https://leiyt.github.io/qujing_university/demo/view/login.html
### git命令
* git innit                    初始化一个git仓库
* git add fileName             把文件修改添加到暂存区
* git commit -m "des"          把暂存区的所有内容提交到当前分支 -m 后面描述提交改变
* git status                   查看仓库当前状态
* git diff                     查看更改
* git pull URL                 拉取一个请求 URL为实际项目地址
* git push -u origin master    把更改内容推到主分支
* git reset --hard HEAD^       回退到上一个版本(HEAD^^上上个版本，HEAD~100上100个版本)
* git checkout -- readme.md    把readme.md文件在工作区的修改全部撤销(还原文件)
* git reset HEAD file         把暂存区的修改撤销掉(还原文件)
* git rm file                 删除文件
* git checkout -b dev         创建dev分支，并切换到dev分支
* git branch dev              创建dev分支
* git checkout dev            切换到dev分支
* git branch                  查看当前分支
* git branch -d dev           删除dev分支
* git merge dev               合并dev分支到当前分支


## 协同开发步骤
1. git clone https://github.com/leiyt/qujing_university.git  克隆项目
2. git pull https://github.com/leiyt/qujing_university.git 拉取项目(开始开发前拉取一下最新项目)
3. git checkout -b zhouyun 创建分支zhouyun(避免冲突)
4. git add lyt.md  添加我新增/修改的文件 lyt.md
5. git commit -m "add new file" 提交修改 -m 后面要写描述
6. git push -u origin zhouyun 把我的修改推到github上得zhouyun分支(首次加-u，后面不需要加)

项目原地址：http://www.zcool.com.cn/work/ZMjM0NTY5NjA=.html
