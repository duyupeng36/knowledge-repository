- 关于 Python 这里提供下面两本书籍作为参考资料
	- ![Python编程：从入门到实践.pdf](../assets/Python编程：从入门到实践_1700372927021_0.pdf)  基础
	- ![流畅的 Python（第2版）.pdf](../assets/流畅的_Python（第2版）_1700372907463_0.pdf) 高级
- # Python 介绍与环境安装
  id:: 655992e7-da7c-4d67-a546-eadd49b28b02
  collapsed:: true
	- Python（英国发音：/ˈpaɪθən/；美国发音：/ˈpaɪθɑːn/），是一种广泛使用的[[$green]]==**解释型**==、[[$green]]==**高级**== 和 [[$green]]==**通用**== 的编程语言
		- [[$red]]==支持多种编程范型==，包括 [[$blue]]==**结构化**==、[[$blue]]==**过程式**==、[[$blue]]==**反射式**==、[[$blue]]==**面向对象**== 和 [[$blue]]==**函数式编程**==
		- 它拥有 [[$red]]==**动态类型系统**== 和 [[$red]]==**垃圾回收功能**==，能够自动管理内存使用，并且其本身 [[$red]]==**拥有一个巨大而广泛的标准库**==
		- 它的语言结构以及面向对象的方法，旨在帮助程序员为小型的和大型的项目编写逻辑清晰的代码
	- Python 是 [[$red]]==**解释型**== 的语言。如果你学过 C 语言，那么你会知道 C 语言是一种 [[$red]]==**编译型**== 语言。它们之间的区别在于
		- 解释型语言会在执行是将高级语言代码翻译为机器代码
		- 而编译型语言会在执行前所有的高级语言代码完全翻译为机器代码，执行时不需要在翻译
	- Python要执行需要一个称为 [[$green]]==**解释器**== 的程序将 Python 代码翻译为机器代码执行。目前，Python的解释器由许多语言实现，例如
		- [CPython](https://www.python.org/): 官方提供的解释器
		- [Jython](https://www.jython.org/)：Jython项目提供了Python在Java中的实现，为Python提供了在JVM上运行和访问用Java编写的类的好处
		- [PyPy](https://www.pypy.org/): Python的一个快速、兼容的替代实现
	- 下面我们开始安装 CPython 解释器
	- ## Windows 安装
	  collapsed:: true
		- 在Windows上安装方法由多种，我们这里介绍两种
		- ### 官网下载安装包
		  collapsed:: true
			- 首先到 [Python官网](https://www.python.org/downloads/) 进行下载安装
				- ![image.png](../assets/image_1700369647673_0.png)
			- 双击打开，即可进行安装
				- ![image.png](../assets/image_1700369667117_0.png)
				- ![image.png](../assets/image_1700369739322_0.png)
				- ![image.png](../assets/image_1700369790901_0.png)
				- ![image.png](../assets/image_1700369865416_0.png)
				- ![image.png](../assets/image_1700369923040_0.png)
				- ![image.png](../assets/image_1700370075308_0.png)
			-
		- ### scoop 包管理安装
		  collapsed:: true
			- 这里我们首先需要安装 [scoop](https://scoop.sh/) 包管理器
				- 下载 scoop 安装脚本
					- ```shell
					  irm get.scoop.sh -outfile 'install.ps1'
					  ```
				- 安装 scoop
					- ```shell
					  .\install.ps1 -ScoopDir 'D:\Applications\Scoop' -ScoopGlobalDir 'F:\GlobalScoopApps' -NoProxy
					  ```
			- 安装 Python
				- ```shell
				  scoop update --all
				  scoop install python
				  ```
	- ## Linux 安装
	  collapsed:: true
		- 根据不同的发行版使用不同的安装命令进行。例如 Archlinux 使用
			- ```shell
			  pacman -S python python-pip
			  ```
		- 其余的自行查看
	- ## Mac OS 安装
	  collapsed:: true
		- 参照官网
	- # 编辑器
	  collapsed:: true
		- 我们可选择使用 [vscode](https://code.visualstudio.com/) 作为编辑器
		- 当然还可以选择 [Pycharm](https://www.jetbrains.com/pycharm/) 作为编辑器
- # 变量与数据类型
  id:: 65599c68-b144-4b19-9b1a-825cf6e23fe9
	- ## 变量与赋值
		- 在 Python 中，变量与其他语言有所不同。Python 的 [[$red]]==**变量其实是对象的标签**==。例如，
			- ```python
			  number = 1
			  ```
			-
	-
	- ## Python 的内置类型
	-
-