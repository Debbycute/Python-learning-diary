# Debby的Python学习笔记
从2022年的1月15号开始，决定在这里做笔记，防止遗忘嘻嘻。  
目前阶段学习的渠道主要是图书：《Python编程从入门到实践》。之后可以依程度增加。  
以下为学习笔记：  
## 学习笔记
以时间轴的形式记录。
### 2022.1.15
**1、大小写转换：**  
```python
name = "ada lovelace"  
print(name.title()) #字符串首字母大写  
print(name.upper()) #字符串全部变为大写  
print(name.lower()) #字符串全部变为小写
```
**2、合并字符串：**  
```python
first_name = "Debby"
last_name = "Chen"
full_name = first_name+" "+last_name #若双引号中含有字符，则输出结果合并同时中间加字符。
print(full_name)
```
>输出结果：Debby Chen  

补充：
```python
print("Hello,"+full_name.title()+"!")
```
>输出结果：Hello,Debby Chen!

### 2022.1.19
**1、添加空白**  
制表符：\t  
换行符：\n  
换行并制表：\n\t  
**2、删除空白**  
删除头空白：对变量.lstrip()  
删除尾空白：对变量.rstrip()  
删除全部空白：对变量.strip()  
