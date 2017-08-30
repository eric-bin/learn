Mac 操作
========

### 快捷键

*	`ctrl + fn + F3` => 显示Dock使其获得可操作的焦点

### 终端指令

#### 目录操作
*	`mkdir` => `mkdir [dirname]`
	创建目录
*	`rmdir` => `rmdir [dirname]`
	删除目录,只能删除空目录，非空目录需使用`rm -rf [dirname]`递归删除
*	`mv` => `mv [dir1] [dir2]`
	改变文件名或移动文件或目录（经测mvdir在新的mac osx10.12不可用，统一使用文件操作的mv指令）
*	`cd` => `cd [dirname]`
	改变当前目录路径
*	`pwd`
	显示当前目录的路径名
*	`ls`
	显示当前目录的内容，-1一行只输出一个，-l列出详细信息，-a列出全部包含隐藏文件

#### 文件操作
*	`cat` => `cat [filename]`
	显示查看文件
*	`cp` => `cp [dirname] [newdirname]`
	复制文件或目录，-R参数递归复制目录
*	`mv` => `mv [dir1] [dir2]`
	改变文件名或移动文件或目录（经测mvdir在新的mac osx10.12不可用，统一使用文件操作的mv指令）
*	`rm` => `rm [filename]`
	删除文件或目录,非空目录需使用`rm -rf [dirname]`递归删除
*	`file` => `file filename`
	显示文件类型
*	`open` => `open filename`
	使用默认的程序打开文件

### 时间操作
*	`date`
	显示系统的当前日期和时间
*	`cal`
	显示日历
*	`time`
	统计程序的执行时间