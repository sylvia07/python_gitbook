#Python介绍
---
###目标：
* 会处理常见错误
* 会使用pycharm
* 掌握算数运算符优先级
* 理解什么是关键字
* 标识符命名规范

---
#####Python语言：**面向对象**的**解释型**计算机程序设计语言。
#####创始人：吉多·范罗苏姆（Guido van Rossum）
#####python优缺点：
- 优点：简单、易学、免费、开源、高层语言、可移植性、解释性、面向对象、可扩展性、丰富的库、规范的代码<br/>
- 缺点：运行速度慢、国内市场较小、中文资料匮乏、构架选择太多
####Hello python常见问题
- 输入错误：NameError:name 'prnt' is not defined<br/>
- 缩进错误: IndentationError:unexpected indent<br/>
- 语法错误: SyntaxError:invalid syntax<br/>
####Pycharm调试按钮说明：
- 【Step Over】键进行程序单步执行，快键键【F8】
- 【Resumn program】键放行程序向下执行，快捷键【F9】

---
<font color="red" size=12 face="黑体">*考点</font>
####注释：
- `#`[空格]说明性文字信息
	快捷键：ctrl + /
- """说明性文字信息"""
	快捷键：无
---
####算数运算符优先级
- 乘方 > 乘、除、整除、取余 > 加、减
- 相同等级的运算顺序为从左到右
- 可以使用括号改变运算顺序
####关键字：
- 已被占用的具有特殊含义的符号
- 常见关键字：
`and	 		as 				assert 	break	
class 		continue 		def 		del 		
elif 		else 			except		finally 	
for 			from 			global 	if 		
import 		in 				is 			lambda	
nonlocal 	not 			or 			pass 		
raise 		return 		try 		while 	
with 		yield						 
False 		None 			True`
####标识符：指用来标识某个实体的符号
---
<font color="red" size=12 face="黑体">*考点</font>
- #####规范：
1.只能由数字，字母，_（下划线）组成<br>
2.不能以数字开头<br>
3.不能是关键字<br>
4.区分大小写<br>
---
<!-- - #####命名约束：
1.下划线分隔法（推荐）：<br>
	多个单词组成的名称，使用全小写字母书写，中间使用_分隔。<br>
first_name		user_name		card_id<br>
2.驼峰命名法：<br>
多个单词组成的名称，每个单词首字母使用大写字母书写，其余字母使用小写字母书写。<br>
FirstName		UserName		CardId -->
####变量：
- 概念：用于描述计算机中的数据存储空间
- 作用：在计算机内存中保存数据
- 语法格式：变量名 = 值
- 变量类型：`int float bool str`
- type():获取对应数据类型





