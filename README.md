<strong>
  <span style="border-bottom:2px dashed black;">
    <font color=#0099ff size=4>
    本项目热烈欢迎各位围观……之余，严正警告各位，唔好有期望，唔好有要求，做人呢，最紧要系<font color=#ff0000>开！心～</font>。
    </font>
  </span>
</strong>

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/happy.png?raw=true" width=99% height=99% /></div>

***

GitHub 不支持直接显示 Excel 表格，欲知菜单详情，既可打开`一周菜单.md`，也可以把`一周菜单.xlsx`获取到本地。获取`一周菜单.xlsx`方法有三：

> 1.  安装 `Git for Windows`，克隆项目到本地。[克隆项目](#克隆项目)；

> 2.  下载项目的压缩包。[下载压缩包](#下载压缩包)；

> 3.  直接下载`一周菜单.xlsx`。[直接下载](#直接下载文件)。

**<font color=#ff0000>推荐克隆项目到本地</font>**。


# 克隆项目

## 1、下载安装 Git for Windows

<strong>Ⅰ、下载 Git for Windows</strong>

浏览器打开 <https://gitforwindows.org/>，点击 `Download`，即可下载到合适的 Git for Windows 安装包。如图所示：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-git-0.png?raw=true" width=100% height=100% /></div>

下载到的 Git for Windows：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-git-1.png?raw=true" width=36% height=36% /></div>

<strong>Ⅱ、安装 Git for Windows</strong>

会安装 QQ 就会安装 Git for Windows，具体过程如下：

运行 Git 安装包：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-0.png?raw=true" width=61% height=61% /></div>

同意许可：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-1.png?raw=true" width=63% height=63% /></div>

选定安装目录：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-2.png?raw=true" width=63% height=63% /></div>

选择需要安装的组件：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-3.png?raw=true" width=63% height=63% /></div>

创建开始菜单目录：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-4.png?raw=true" width=63% height=63% /></div>

选择默认的文本编辑器：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-5.png?raw=true" width=63% height=63% /></div>

不把 Git 添加到环境变量：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-6.png?raw=true" width=63% height=63% /></div>

选择 HTTPS 传输后端：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-7.png?raw=true" width=63% height=63% /></div>

配置行结束转换：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-8.png?raw=true" width=63% height=63% /></div>

配置终端模拟器以与 Git Bash 一起使用：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-9.png?raw=true" width=63% height=63% /></div>

额外的选项：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git-x.png?raw=true" width=63% height=63% /></div>

<strong>Ⅲ、安装 Git 2.19.0</strong>

上文安装的 Git for Windows 版本号为 2.18.0，最新版为 Git 2.19.0。两个版本的安装过程大同小异，新版 Git 的安装过程：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/install-git%20%202.19.gif?raw=true" width=81% height=81% /></div>

> :fire::fire: **Git 2.19.0 以后的新版不再演示安装过程。** :fire::fire:


## 2、克隆项目到本地

<strong>步骤一：</strong>在你想要保存本项目的目录下打开 `Git Bash` 窗口。

进入 `D:\GitHub\` 目录（此目录可随意自选），鼠标右击弹出菜单，点击 `Git Bash Here`。如下图所示：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/clone-repository-0.png?raw=true" width=70% height=70% /></div>

Git Bash 窗口：
<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/clone-repository-1.png?raw=true" width=75% height=75% /></div>

<strong>步骤二：</strong>在打开的 `Git Bash` 窗口输入 `git clone https://github.com/KoobKooc/KoobKooc/.git` 后回车。

执行完之后的结果如图示：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/clone-repository-2.png?raw=true" width=70% height=70% /></div>

从截图可知，在 `D:\GitHub\` 目录下多了一个名为 `KoobKooc` 的目录，进入 `KoobKooc` 目录，内容如下：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/clone-repository-3.png?raw=true" width=51% height=51% /></div>

> :fire::fire: ~~**FBI WARNING: Do Not Remove .git Directory!**~~ :fire::fire:

第一次从 GitHub 获取本项目可以克隆，经过第一次的克隆之后，以后查看每周最新的菜单，只需要拉取即可。详见下面的`3、从 GitHub 拉取更新`。

## 3、从 GitHub 拉取更新

<strong>步骤一：</strong>进入 `KoobKooc` 目录，在此目录下打开 `Git Bash`：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/clone-repository-4.png?raw=true" width=51% height=51% /></div>

<strong>步骤二：</strong>执行 `git pull origin master`：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/clone-repository-5.png?raw=true" width=51% height=51% /></div>

### :zap::zap: trick

如果觉得 `git pull origin master` 太长，可以设置别名（alias）。

在任意目录打开 Git Bash 窗口，执行 `git config --global alias.pom "pull origin master"`，自此之后，需要执行 `git pull origin master` 一律可以输入 `git pom`。

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/clone-repository-6.png?raw=true" width=75% height=75% /></div>


# 下载压缩包

浏览器打开 <https://github.com/KoobKooc/KoobKooc>，先点击 `Clone or download` 后点击 `Download ZIP`：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-zip-0.png?raw=true" width=50% height=50% /></div>

执行上述步骤，会下载到一个压缩包：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-zip-1.png?raw=true" width=50% height=50% /></div>

解压：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-zip-2.png?raw=true" width=50% height=50% /></div>

进入解压目录：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-zip-3.png?raw=true" width=45% height=45% /></div>


# 直接下载文件

浏览器打开 <https://github.com/KoobKooc/KoobKooc>，直接点击 `一周菜单.xlsx`：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-xlsm-0.png?raw=true" width=30% height=30% /></div>

跳转之后点击 `View Raw` 即可将`一周菜单.xlsx` 下载到本地：

<div align=center><img src="https://github.com/KoobKooc/Images/blob/master/download-xlsm-1.png?raw=true" width=100% height=100% /></div>


# 相关

想了解更多关于 Git/GitHub 的内容，可查阅：

[Pro Git](https://gitee.com/progit/)

[Git - Book](https://git-scm.com/book/zh/v2)

[git - 简易指南](http://www.bootcss.com/p/git-guide/)

[Git飞行规则(Flight Rules)](https://github.com/k88hudson/git-flight-rules/blob/master/README_zh-CN.md)

[SegmentFault 技术周刊 Vol.28 - GitHub —— 你不得不上的交友网站](https://segmentfault.com/a/1190000009985489)

[廖雪峰 | Git 教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)