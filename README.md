# assembly_programming
汇编语言程序设计
## sum.asm:
从键盘输入两个数字(0-9)，最后在屏幕上显示两个数相加的结果
<a href="http://www.123elearn.com/2021/01/28/%E6%B1%87%E7%BC%96%E8%AF%AD%E8%A8%80%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1%EF%BC%883%EF%BC%89/#2-%E7%A8%8B%E5%BA%8F2-Sum">程序分析</a>
## subprogram.asm:
子程序有点像高级语言中的函数，通过子程序，我们可以把一段逻辑代码进行一个封装，执行同样的功能的时候，我们不需要重复的编写代码，只要调用子程序就行了。
<a href="http://www.123elearn.com/2021/01/28/%E6%B1%87%E7%BC%96%E8%AF%AD%E8%A8%80%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1%EF%BC%884%EF%BC%89/#5-%E5%AD%90%E7%A8%8B%E5%BA%8F%EF%BC%81">程序分析</a>
## 8259_program.asm:
8259中断程序设计，每隔1s显示一句Hello！一共显示10行
<a href="http://www.123elearn.com/2021/01/28/%E6%B1%87%E7%BC%96%E8%AF%AD%E8%A8%80%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1%EF%BC%885%EF%BC%89/">程序分析</a>
## 8250_program_1.asm（查询方式接收数据）:
软件编写汇编程序对PC系统的串行口进行内环测试，发送电文‘HELLO’，接收数据在屏幕上显示输出。发送用查询方式，接收用查询方式来编程。
<a href="http://www.123elearn.com/2021/01/28/%E6%B1%87%E7%BC%96%E8%AF%AD%E8%A8%80%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1%EF%BC%886%EF%BC%89/">程序分析</a>
## 8250_program_2.asm（中断方式接收数据）:
软件编写汇编程序对PC系统的串行口进行内环测试，发送电文‘HELLO’，接收数据在屏幕上显示输出。发送用查询方式，接收用中断方式来编程。
<a href="http://www.123elearn.com/2021/01/28/%E6%B1%87%E7%BC%96%E8%AF%AD%E8%A8%80%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1%EF%BC%886%EF%BC%89/">程序分析</a>
## count_max_min.asm:
统计负数的个数，并求最大数和最小数。
设数据段有8个有符号数：
NUM  DB -19,+28,37,-46,+55,61,-74,+255
请设计一个程序完成（1）统计并显示负数的个数
                   (2)找出真值最大和最小的数，并以十六进制的形式显示在屏幕上。
显示格式为  MAX=XXH;MIN=XXH.
