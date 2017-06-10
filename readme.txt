git init
git add filename
git commit -m “detail”

git remote -v 查看远程仓库
git remote add repository_name git_url 添加远程仓库
git remote rm repository_name 删除远程仓库

git branch b_name 创建本地分支
git checkout b_name 切换分支
git checkout -b b_name 创建变切换到新分支
git branch -d b_name 删除分支  -D 强制删除
git merge b_name 合并分支
git branch -a 查看所有分支
git branch -r 查看远程分支
git branch    查看本地分支

git reset --hard 回退到上一个版本
git reset id 回退到某个版本

cocoapods 安装
gem sources -l #(查看当前ruby的源)
gem sources --remove https://rubygems.org/ #(移除当前ruby的源)
gem sources -a https://ruby.taobao.org/ #(设置当前ruby的源为我天朝的)
gem sources -l #(再次查看当前ruby的源)
如果gem太老，可以尝试用如下命令升级gem：在Terminal输入以下命令：
sudo gem update --system
升级成功后会提示: Latest version currently installed. Aborting.
sudo gem install -n /usr/local/bin cocoapods
pod setup
