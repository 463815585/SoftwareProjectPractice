# 课程所需软件安装

## 安装Android Studio

1. 到官网下载Android studio最新版
2. 根据指导依次进行安装即可
3. 之后在Android studio中或者IDEA中下载所需SDK包。

## 安装Anaconda(Window系统)

注：先安装Anaconda时因为安装完Anaconda有可能会自带jupyter notebook（基于网页的用于交互计算的应用程

序。其可被应用于全过程计算：开发、文档编写、运行代码和展示结果）。

1. 官网下载exe安装文件，

2. 下载成功点击该文件进行安装

3. 以此进行点击next即可，注：点击“Just Me”，

4. 在“Advanced Installation Options”中**不要**勾选“Add Anaconda to my PATH environment variable.”（“添加Anaconda至我的环境变量。”）。因为如果勾选，则将会影响其他程序的使用。如果使用Anaconda，则通过打开Anaconda Navigator或者在开始菜单中的“Anaconda Prompt”（类似macOS中的“终端”）中进行使用。

   除非你打算使用多个版本的Anaconda或者多个版本的Python，否则便勾选“Register Anaconda as my default Python 3.6”。

   ![](https://github.com/463815585/SoftwareProjectPractice/blob/main/img/installAnaconda.png)

5. 然后点击“Install”开始安装。如果想要查看安装细节，则可以点击“Show Details”。

6. 验证安装结果。可选以下任意方法：

   ① “开始 → Anaconda3（64-bit）→ Anaconda Navigator”，若可以成功启动Anaconda Navigator则说明安装成功。

   ② “开始 → Anaconda3（64-bit）→ 右键点击Anaconda Prompt → 以管理员身份运行”，在Anaconda Prompt中输入 ***conda list\*** ，可以查看已经安装的包名和版本号。若结果可以正常显示，则说明安装成功。

## 安装Jupyter Notebook

注：因为安装Anaconda也有可能会没有安装Jupyter Notebook，所以此时需要自己安装

1. 使用Anaconda安装

   如果你是小白，那么建议你通过安装Anaconda来解决Jupyter Notebook的安装问题，因为Anaconda已经自动为你安装了Jupter Notebook及其他工具，还有python中超过180个科学包及其依赖项。

   你可以通过进入Anaconda的[官方下载页面](https://link.jianshu.com?t=https%3A%2F%2Fwww.anaconda.com%2Fdownload%2F%23macos)自行选择下载；如果你对阅读**英文文档**感到头痛，或者对**安装步骤**一无所知，甚至也想快速了解一下**什么是Anaconda**，那么可以前往我的另一篇文章[Anaconda介绍、安装及使用教程](https://link.jianshu.com?t=https%3A%2F%2Fzhuanlan.zhihu.com%2Fp%2F32925500)。你想要的，都在里面！

   常规来说，安装了Anaconda发行版时已经自动为你安装了Jupyter Notebook的，但如果没有自动安装，那么就在终端（Linux或macOS的“终端”，Windows的“Anaconda Prompt”，以下均简称“终端”）中输入以下命令安装：

   ```shell
   conda install jupyter notebook
   ```

2. 验证是否安装成功(启动Jupyter Notebook)

   在终端中输入以下命令：

   ```shell
   jupyter notebook
   ```

   执行命令之后，在终端中将会显示一系列notebook的服务器信息，同时浏览器将会自动启动Jupyter Notebook。

   - 注意：之后在Jupyter Notebook的所有操作，都请保持终端**不要关闭**，因为一旦关闭终端，就会断开与本地服务器的链接，你将无法在Jupyter Notebook中进行其他操作啦。

