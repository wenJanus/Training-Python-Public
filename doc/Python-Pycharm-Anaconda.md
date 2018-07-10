## 安装步骤
- 本文是Anaconda+Pycharm的安装文档，如果您喜欢纯净版本的Python和Pydev+Eclipse的IDE环境，可以参考[这里](https://github.com/wu-wenxiang/Training-Python-Public/blob/master/doc/Python-Dev-Env.md) 
- 预装系统
	- Win7 / Win10
- 下载Anaconda
	- [下载页面](https://www.anaconda.com/download/#windows)，选择3版本
	- ![Anaconda-Download.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-Anaconda-Download.png)
	- 这里要看你的操作系统是32bit还是64bit，可以通过`我的电脑 / 右键`查看，如果不会看就选32bit
	- ![OS-Arch.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-OS-Arch.png)
	- 下载后可以开始安装，安装时一路默认安装，选安装路径的时候要记一下，不同的系统中安装路径不同
	- 比如，假设Anaconda默认会安装在`C:\ProgramData\Anaconda3`目录，将此目录添加到环境变量PATH
		- `我的电脑 / 空白处右键 / 属性 (Properties)`
		- `高级系统设置 (Advanced system settings)`
		- ![OS-Settings.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-OS-Settings.png) 
		- `环境变量 (Environment Variables)`
		- ![OS-Environment.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-OS-Environment.png)
		- 如果没有`PATH`这个环境变量，就新建一个
		- 然后将`;C:\ProgramData\Anaconda3;C:\ProgramData\Anaconda3\Scripts`添加到`PATH`环境变量末尾，环境变量中的各个字符串用分号隔开。注意，这里假设Anaconda的安装路径是C:\ProgramData\Anaconda3。如果安装在其它路径，要相应地修改。
		- ![OS-Env-Var.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-OS-Env-Var.png)
		- **重新打开**一个cmd窗口，运行：`python --version`
		- 出现：`Python 3.6.5 :: Anaconda, Inc.`，表示Python安装成功。
- 下载Pycharm
	- [下载页面](https://www.jetbrains.com/pycharm/download/#section=windows)，选择社区版
	- ![Pycharm-Download.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-Pycharm-Download.png)
	- 下载后一路默认安装，直至如下界面，勾选如下
	- ![Pycharm-Installation.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-Pycharm-Installation.png)
	- 安装完成后，首次打开Pycharm，会出现License说明，拖到最后，Accept就变成黑色，可以确认
	- ![Pycharm-License.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-Pycharm-License.png)
	- 之后就走到此页面，可以打开或者新建一个Python项目
	- ![Pycharm-Create.png](https://raw.githubusercontent.com/wu-wenxiang/Media-WebLink/master/qiniu/bec937bdec704aee995f610566dcebb0-Pycharm-CreateProject.png)