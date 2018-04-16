# Shell基础
## Shell概述
### 基本概念
#### Shell
Shell是一个命令行解释器，它为用户提供了一个向Linux内核发送请求以便运行程序的界面系统级程序，用户可以用Shell来启动、挂起、停止甚至是编写一些程序。<br/>
Shell还是一个功能相当强大的编程语言，易编写，易调试，灵活性较强。Shell是解释执行的脚本语言，在Shell中可以直接调用Linux系统命令。<br/>
##### 作用
用户给计算机内核传递计算机命令：用户先在操作界面上输入命令，回车之后，Shell就会将用户输入的命令按照ASCII码表转换成ASCII码，将组合好的命令传递给计算机内核，计算机内核执行命令，执行后输出给Shell,Shell转换为用户可识别的信息。(内核只识别0和1，需要Shell等工具将用户输入的信息转换为内核可识别的内容)<br/>
- 接收输入的命令
- 翻译为0和1，传递给内核，内核处理。
#### Shell的分类
- Bourne Shell：sh
    - 主要包括：sh、ksh、**Bash**、平时、zsh
    - Linux中标准shell是Bash。
- C Shell
    - 主要包括：csh、tcsh
**两种语法彼此不兼容。**

查看当前使用的shell：echo $SHELL<br/>
查看Linux支持的shell：``/etc/shells``


## 脚本执行方式
###


