## 个人持久化工作区

用户在Notebook进行数据分析的过程中，如果生成了新的文件，这些文件将会保存在一个**容量为100M的特定持久化工作区**里面，在下次登录时可继续访问这些文件，而其余文件将被初始化。这个工作区可在Notebook中的Code Cell中输入Linux命令的方式进行访问,具体访问指令如下：

### 访问工作区


`bash
%%bash
ls /home/kesci/work/
`

### 工作区常用命令

* ls
    * 作用：查看特定路径下的文件/文件夹
    * 示例：```ls /home/kesci/input/```
* rm
    * 作用：删除特定路径下的文件/文件夹
    * 示例：```rm /home/kesci/work/tmp.txt``` 
* mkdir 
    * 作用：创建特定路径下的文件夹
    * 示例： ```mkdir /home/kesci/myfolder/```
* mv:
    * 作用：移动原路径下的文件/文件夹到新路径下
    * 示例：```mv /home/kesci/work/tmp.txt /home/kesci/myfolder/```
* cp:
    * 作用：拷贝原路径下的文件/文件夹到新路径下
    * 示例：``` cp /home/kesci/work/tmp.txt /home/kesci/myfolder/```
