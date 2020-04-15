### 查看编码
`echo $LANG`
### 查看命令使用帮助
`man ls`  
`ls --help`
### 切换目录
`cd/` 切换到根目录  
`cd..` 返回上一级  
`cd~` 进入个人主目录  
### 目录操作
`mkdir test` 创建test目录  
`rmdir test` 删除test目录  
### 创建空文件
`touch test.txt`
### 查看文件内容
`cat test.txt`  
`cat -n test.txt` 查看并显示行号  
`tac test.txt` 由最后一行到第一行反向在屏幕上显示出来"  
### 文件操作
`echo '123' > test.txt` 覆盖原有内容会自动创建文件  
`echo '1234' >> text.txt` 追加内容  
### 更改用户权限
 `chmod [who] [+ | - | =] [mode]` 文件名  
`u` 表示"用户（user）"，即文件或目录的所有者  
`g` 表示"同组（group）用户"，即与文件属主有相同组ID的所有用户  
`o` 表示"其他（others）用户"  
`a` 表示"所有（all）用户"。它是系统默认值  
`+` 添加某个权限  
`-` 取消某个权限  
`=` 赋予给定权限并取消其他所有权限  
### 拷贝
`cp test.txt test2.txt` 拷贝一份文件为test2.txt
### 移动目录
`mv test1.txt test2.txt` 同一目录下会将test1.txt直接改名为test2.txt  
`mv test.txt ./Desktop/` 移动test.txt文件到Desktop桌面
如果文件已经存在，则会有提示是否覆盖  
`-f` ：force 强制的意思，如果目标已经存在，不会询问而直接覆盖  
`-i` ：若目标已经存在时，就会询问是否覆盖  
`-u` ：若目标已经存在，且 source 比较新，才会更新 (update)  
### 删除文件/目录
`rm test` 删除test目录
### 查询文件
`find ./Desktop/test.txt` 查找desktop桌面下的test.txt文件
### 查看环境变量
`echo $PATH` 查看环境变量  
`which ls` 查看ls命令所在目录
### 搜索内容
`grep 2020 test.txt` 在test.txt文件中搜索2020
### 查看文件行数
`wc test.txt`  
`head -n test.txt` 查看test.txt文件前n行  
`tail -n tet.txt` 查看test.txt文件后n行
### 剪切提取
`待更...`
