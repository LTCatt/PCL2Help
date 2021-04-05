

<div align="center"><img src="https://z3.ax1x.com/2021/04/05/cMgvw9.jpg" alt="PCL2 内置帮助库"/></div>

<div align="center"><img src="https://img.shields.io/github/stars/LTCatt/PCL2Help">&nbsp; <img src="https://img.shields.io/github/forks/LTCatt/PCL2Help?color=%23f8e71c">&nbsp;<img src="https://img.shields.io/github/issues/LTCatt/PCL2Help?color=%237ed321"></div>

## 💎简介

 PCL2 内置帮助库 —— PCL2 启动器 (Plain Craft Launcher 2) 内置可供查阅一些关于启动器及Minecraft的在线帮助库，由广大PCL2用户及Minecraft玩家共同编写维护

## ✨它有什么用？

许多PCL2用户在使用时出现了一些问题，为了帮助这些用户，就出现了本帮助库，本帮助库将提供 

- 完善的PCL2使用教程
- 完善的PCL2常见问题解答
- 完善的Minecraft常见问题解答
- 完善的Minecraft常见启动错误
- 完善的整合包及服务器客户端 专用启动器制作指南
- 等

当然，帮助库建立初期，内容较为空缺，非常需要你的参与！

## 🎨我如何参与编写？

首先你需要Star本项目再Fork本仓库，并安装[Git](https://git-scm.com/downloads)，当然有很多方法，例如：vscode的git插件、github桌面版等，你的所有编写将在你Fork的仓库中进行修改，再与本仓库提交合并，接下来将提供简单的过程如果想了解更多方法，请前往PCL2帮助库中的“参与完善PCL2帮助库”条目中了解更多。

1.打开PCL2启动器的文件夹，并进入PCL文件夹内，创建名称为：<code>Help</code>的文件夹

2.进入文件夹，右键鼠标，单击<code>Git Bash Here</code>

3.在启动的Git窗口中，逐行输入

①目的是生成公钥和私钥，与你的Github账号建立连接

```
ssh-keygen -t rsa -C "此处填写邮箱" 
```

建立过程中需要确认，请一直按回车

②再使用记事本打开

```
C:\User\你目前登录的电脑账户\.ssh\id_rsa.pub
```

③进入网页版Github的设置中，打开<code>ssh and GPG keys</code>项，点击<code>NEW ssh key</code>，标题任意，内容粘贴打开文件的内容

④设置用户信息（填写和上述操作一致的邮箱）

```git
git config --global user.name "此处填写名称"
git config --global user.email "此处填写邮箱"
```

⑤初始化仓库及建立连接

```
git init.
git remote add origin 此处为仓库SSH（以.git结尾的链接）
```

⑥克隆仓库到本地

```
git pull --rebase origin master
```

⑦开始在克隆的仓库中编写，编写完成后推送编写的文件到远程仓库

```
git add .
git commit -m "此处填写修改记录"
git push -u origin master
```

⑧再提交合并信息即可

以上为简单的过程，如果看不懂，建议百度：使用Git本地项目远程上传到Github



## 🎲遇到问题怎么办？

如果遇到无法解决的问题，请在上方Issues中新建一个问题，并详细说明情况，即可收到回复（除非是智商问题）

## 📣更多~

欢迎━(*｀∀´*)ノ亻!访问 龙腾猫跃 的爱发电主页，为你喜欢的PCL2启动器作者赞助吧~ 

[点此访问](https://afdian.net/@LTCat)