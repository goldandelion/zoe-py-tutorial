# 用python打开网页

## 第一次尝试 遇见webbrower
搜索how to open web browser in python，学习到了webbrower

```
import webbrowser  
webbrowser.open(url)
```

发现是是Safari打开的，我想用chrome打开

## 第二次尝试 使用chrome
搜索python webbrower chrome
发现
[Python webbrowser.open() to open Chrome browser @stackoverflow](http://stackoverflow.com/questions/22445217/python-webbrowser-open-to-open-chrome-browser)
非常棒的解决方案，好好学习

```
import webbrowser

url = 'http://docs.python.org/'

# MacOS
chrome_path = 'open -a /Applications/Google\ Chrome.app %s'

# Windows
# chrome_path = 'C:\Program Files (x86)\Google\Chrome\Application\chrome.exe %s'

# Linux
# chrome_path = '/usr/bin/google-chrome %s'

webbrowser.get(chrome_path).open(url)
```

## 第三次尝试 在python外运行
参见[Running Programs from the Command Line](http://zoejane.gitbooks.io/zoe-py-tutorial/content/running_programs_from_the_command_line.html)

设置好后，可以直接在terminal输入
```./open-web.py```  运行程序

## 第四次尝试 制定不同的网址（使用参数）
尝试搜索 python webbrowser parameter|argument  
看不懂  
试着使用sys.argv未果  
不过正好链接到了我在学习的Automate the boring stuff的课程  
于是决定继续学习课程