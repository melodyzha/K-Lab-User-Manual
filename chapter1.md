# Notebook
Notebook是用户登录科赛网并打开K-Lab后，在浏览器端所看到的交互式编写界面，由**Header**、**Code Cell**、**Markdown Cell**和**代码收藏区**组成。
## Header
Add some explanations and pics here. 
## Code Cell
Code Cell是Notebook的代码编写单元。用户在Code Cell内编写代码(目前科赛网支持**Python2 & 3**和**R**等主流编程语言)，代码由后端的Kernel运行，并返回结果到Code Cell。通过这样一个工作流，用户来**解决数据分析中如数据导入、模型搭建、数据可视化、参数调优等问题**。    

![Code Cell](image/cell-code.jpg)
![image description](image/code-cell.png)
Code Cell有**编辑模式**和**命令模式**两种状态，状态可以相互切换：编辑模式下，按`Enter`键进入命令模式；命令模式下，按`ESC`键进入编辑模式。

* 编辑模式：表示该cell允许被编辑，界面上显示cell单元框线为绿色，即用户可以在cell中键入代码或注释。
 ![image description](image/code-cell-green.png)
 <img src="image/code-cell-green.png" alt = 'testing,will be deleted later' width="400" height="40">
* 命令模式：表示该cell允许被执行，界面上显示cell的单元框线为蓝色，即用户可以通过点击`运行`按钮或快捷键`Shift + Enter`来运行cell。
  ![image description](image/code-cell.png)




## Markdown Cell
Markdown Cell是K-Lab的文本编辑单元，用户通过在Markdown Cell中输入Markdown格式的文本，来**完成数据分析中的报告撰写任务**。
![image description](image/cell-markdown.jpg)

Markdown Cell也有**编辑模式**和**命令模式**两种状态，编辑模式下，按`Enter`键进入命令模式；命令模式下，按`ESC`键进入编辑模式。
* 编辑模式：表示该cell允许被编辑，界面上显示cell单元框线为绿色，即用户可以在cell中键入Markdown格式文本。

  ![image description](image/markdown-cell-green.png)
* 命令模式：表示该cell允许被执行，界面上显示cell的单元框线为蓝色，即用户可以通过点击`运行`按钮或快捷键`Shift + Enter`来完成Markdown文本渲染。
 ![image description](image/markdown-cell-blue.png)
 


K-Lab支持标准Markdown语法，常用Markdown语法示例展示如下：

# 一级标题
## 二级标题
### 三级标题

普通文本    
**加粗文本**    
*斜体文本*

* 无序列表
    * Case1
    * Case2

1. 有序列表
    1. Case1
    2. Case2
2. 有序列表



渲染后的Markdown文本展示如下：     
![image description](image/markdown-cell-run.png)
  
更多K-Lab Makrdown使用示例，[请参考链接](https://www.kesci.com/static/markdown_guide.html)。

## 代码收藏区
在Notebook页面左侧点击星标按钮，即能看见代码收藏区。分为**公有库**和**我的收藏**。
* 公有库：收集的常用的代码可供用户使用。        
![image description](image/code-storage.png)

* 我的收藏：用户私人收藏的代码。