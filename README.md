# OverView

# 工具和资源
## 学习使用Git
[快速入门](https://docs.github.com/zh/get-started/quickstart)，目前了解账户的创建、[仓库的创建和拉取](https://docs.github.com/zh/get-started/quickstart/hello-world)、[Git的使用](https://docs.github.com/zh/get-started/quickstart/set-up-git)和页面的功能即可
### MarkDown
轻量级标记语言，[MarkDown编写文档](http://itmyhome.com/markdown/index.html)在GitHub中应用广泛。例如本文件```OverView.MD```就是通过MarkDown语言编写

### Code
将本地文件夹的项目仓库同步至GitHub的远程仓库后的界面化显示，可在网页上实现对代码文件的直接阅读
### Issues 
在学习过程中遇到疑问可通过[issues](https://github.com/DigitalMediaRD/OverView/issues)板块创建记录遇到的问题，也可在该板块内通过关键字检索相关联的记录

在该页面下创建issues内容
    
    点击New issue，打开issue内容的创建页面
    在Title输入框内输入该issue的标题
    在Write输入板块内输入该issue的内容，例如对问题的描述、代码片段的展示
    完成后点击Submit new issue 发布

创建页面还包括其他工具和组件，例如输入板块内可更改字体格式、插入超链接、增加分段说明和@等基本功能，以及任务分配、issue类别定义标签等在多人开发模式下的协作功能




## 学习资源
### 编程基础&扩展理论类相关学习书籍
[书籍库](https://github.com/XiangLinPro/IT_book)，涵盖打基础和进阶，根据实际需要自由学习

解压密码x20200427

### 在线资源
[菜鸟教程](https://www.runoob.com/)，包罗万象，各类程序语言的语法基本都能在上面找到
[Github](https://github.com/)，主要内容为用户上传的开源项目，后续深入可以尝试拉取感兴趣的开源项目并观察源代码进行学习

除此之外各种编程语言的官方文档包含了更详细的说明例如[Java](https://dev.java/learn/getting-started/)、[微软](https://learn.microsoft.com/zh-cn/dotnet/csharp/tour-of-csharp/#code-try-0)等


# 学习方向
## 其他方向
对开发兴趣不大的可先学习该书籍
- [AUTOMATE THE BORING STUFF WITH PYTHON](https://automatetheboringstuff.com/2e/chapter0/)，从长远方向来看建议学会阅读英文原版；若实在吃力可阅读[中文译版]()

- 建议
	- 熟练掌握Chapter 1-Chapter 11的内容，Chapter 12-Chapter 20根据情况自行需要选择学习
	- 在编程实践时，能够根据当前场景并结合任务一的学习内容，设计相对适合的数据结构和处理方式

### 图形图像
待补充
- 可结合HTML进行网页页面设计


### 三维模型
待补充
- 可结合Unity或Unreal开发引擎进行三维模型展示或交互


## 应用开发为主

编程语言，两种熟悉并掌握一种即可
- C：后续可转向C++，并学习在Unreal中实现C++开发(相比之下Unreal的蓝图开发易上手，但从程序开发的角度来看，建议意志坚定的选择Unreal和C++的开发类型)
- Java
    - 生态环境良好，选择范围广；包括Web后端开发、客户端\移动端应用开发等多种方向，有兴趣的可自行搜索
    - 兴趣不大的可在熟悉语言逻辑结构后转向C#学习，并学习在Unity中实现C#开发(C#和Java的逻辑结构相似度较高，基础语法除去部分关键字和表达方式不一样外无明显差异)


创建网页的标记语言HTML和网页编程语言[JavaScript](https://www.runoob.com/js/js-tutorial.html)
- 对Web前端开发有兴趣的，可搭配CSS深入学习
- 兴趣不大的了解HTML的层次结构和各UI元素功能即可，为后续学习Unity或Unreal开发节省学习UI界面的时间。JavaScript在程序语言的逻辑上和其他编程语言相似，在重合度较高的语言中学会熟练使用一种即可


Unreal中使用C++开发、Unity中使用C#开发、HTML和JavaScript的结构都可归属为软件工程中的[MVC设计架构](https://www.runoob.com/design-pattern/mvc-pattern.html)，相比直接学习Unreal和Unity引擎的使用，先从结构简洁的HTML和UI功能入手有利于降低学习难度，减少学习成本。在有程序语言基础和程序结构认知的情况下，后续只需要专注于学习引擎工具，需要什么，查阅官方文档的相关说明即可

### 横向延伸
数据库
- 待补充

服务器
- 待补充


了解以下集成开发环境，并根据实际情况熟练掌握一类

#### Conda

其特点在于可创建多个不同版本的python环境实现互相独立的多环境管理；缺点在于多个虚拟环境的创建将占用大量硬盘空间，并且当涉及其他需要额外进行编译操作的程序时，操作处理起来略微繁琐

- [Anaconda](https://www.anaconda.com/)/[Minconda](https://docs.conda.io/en/latest/miniconda.html)，作用类似，前者相比后者集成了其他开发工具和可视化界面的操作；后者仅包括精简的命令行窗口功能

	- [英文文档](https://docs.conda.io/projects/conda/en/latest/user-guide/index.html)/[中文文档](https://anaconda.org.cn/anaconda/user-guide/getting-started/)

- 包含git代码管理功能

Conda移植虚拟环境到其他设备的[操作方法](https://blog.csdn.net/buweifeng/article/details/124733123?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-1-124733123-blog-115385868.t0_layer_searchtargeting_sa&spm=1001.2101.3001.4242.2&utm_relevant_index=3)

	#安装打包资源库
	conda install -c conda-forge conda-pack
	#当前虚拟环境导出包
	conda pack -n env_name
	#登陆需要安装环境的机器
	cd yourpath
	# 解压
	tar zxf target_file.tar.gz
	# 激活环境
	conda activate /yourpath/bin/activate 
	# 查看python的路径
	which python


#### Pycharm

常用的Python语言IDE

- [说明文档](https://pycharm.iswbm.com/)

- 包含git代码管理功能

#### Visual Studio

微软出品，支持C、C++和C#开发

- 包含git代码管理功能























