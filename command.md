# Command Line学习笔记

##快捷键

- ctrl c 中断
- ctrl d 退出 ends of file , not any more input coming
- ctrl r 搜索命令
- Tab Completion - 自动完成到可以完成的最远的地方 Tab Again


##命令

- ls
- curl http://udacity.github.io/ud595-shell/stuff.zip -o things.zip
- brew install cowsay
- date
- host udacity.com
- echo you rock
- expr 2+2
- uname -a
- history
- hostname - Domain Name System (DNS)
- uptime
- unzip
- cat - concatenate (reading short files)
- wc - word count (lines, words, bytes)
- diff- 比较文件的不同





- cowsay All is not butter that comes from the cow.
- cowsay Hello World!
- cowsay -e ^^ Hello World!
- cowsay -f tux Tux is Linuex\'s mascot!



- man - manual (q - quit)
- man cowsay
- ls -l（“d” directory     “-” file）

- apropos working directory -find commands relevant to particular keywords
- ping 8.8.8.8
- bc - calculator



- less - display text one page at a time
( D, Space,  arrow keys - 翻页;U 上翻页;> 最后一页)
- line number-跳转到某一行
- /   search     ; n 下一个；N上一个)


- nano - text editor

- pwd - print working directory


- cd - change directory 
- cd ..
- cd /     (回到root目录；abusolute path)
relative path（从working directory开始）
- cd ~ (回到home directory)
- cd (回到home directory)



- mv - move (or rename)
- cp - copy
- mv junk trash  
如果有trash目录 move junk to trash目录  
如果没有trash目录  rename junk to trash  


- mkdir - create new directories
- rmdir - remove directories
- rm -r junk 删除非空的junk目录


-man glob（globbing）

- ls *s
- ls app.{css,html} (花括号代表寻找其中任一个)
- ls a?c
- ls be[aeiou]r.png (方括号代表其中任何一个字母)  beer bear 

- diff -u old.html new.html


## 参考资料
Udacity
