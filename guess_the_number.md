# 小游戏：guess the number

## 分析input和output
### input
- 游戏者的名字
	- name=input()
- 游戏者猜的数字
	- guess=input()

### output
- 向游戏者的问候
	- Hello, what is your name?
	- Hi, xxx , let's play a game - guess the number.
- 游戏引导（介绍数字的范围）
	- Well, I am thinking a number between 1 and 20.
	- Take a guess.

- 游戏提示
	- 	数字太大
		- Your guess is too high.
	-  	数字太小
		- Your guess is too low.
- 游戏结束
	- 正确猜出（给予赞扬）
		- Good job! xxx, You guessed my number in x guesses!
	- 没有猜出（告知答案）
		- Nope. The number I was thinking of was x.

## 分析progress
- 用random生成一个随机数字。 secretNumber
- 比较secretNumber和guess的大小，if...elif...
- 可以猜x次。for i in range（）