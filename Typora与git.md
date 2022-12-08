# Typora与git（Mac版）

为啥只有Mac版本，因为鼠鼠只有mac。

下面两个合体等于嫖着GitHub的云空间，做何时何地都能查看的云笔记和下载笔记，还有历史更改记录。

#### 1.Typora是一款Markdown编辑器和阅读器（以前免费，现在收费，F**K，或者某宝）

​	Markdown可以让你专注于内容的创造，而不用像word一样动不动用鼠标去做排版（以前试过，蠢！）所有工作几乎可以用键盘全部搞定。

​	包括代码块/数学公式/图表/超链接......

#### 2.git 高大上点说法：开源的分布式版本控制系统

​	最早接触git是帮师姐做项目，在gitee做版本管理（那时候就觉得这东西咋样都得学会），简单来说就是一个拥有目前项目所有更改历史，然后还可以分支开花的项目管理的东西。（在云上，怕你删库跑路）

## 步骤

#### 1.下载git  Mac下载git简单  终端 里面输入git 会让你选择是否去安装，或者你有Xcode，就直接自带git。

#### 2.打开(尊贵的学生认证)的GitHub账户  Creat New *repository*（数据库，仓库，贮藏室）    名字用note 代替

#### 3.回到终端：

（1）ssh-keygen -o 

   (2)会问你保存在哪，输入后为file名    格式 file.pub

再问你密码和确认密码（建议不要 不然麻烦）

（3）完了后会显示被编码后的密钥，cat file.pud   查看密钥 复制

找到Github Settings - Access-SSH and GPG keys

点击 New SSH key  粘贴进去

（4）点击你创建的repository  note  点击SSH 并且复制

终端里面输入 git clone SSH（你复制的）

显示warning: You appear to have cloned an empty repository.  成功

 （5）cd note   (简单linux命令)

git status 查看状态

mkdir 创建文件夹    touch 创建文件.格式     Markdown文件格式为.md

​    (6)  git add .

​		git commit -m "add all"    添加到缓存区

​		git push 提交到远程仓库

​        git clone 拉取到本地



​																													bin

​																													2021.7.2

### 最近总算搞清楚 Typora如何上传图片到GitHub了，用uPic

文档稍后写写
