# Task4
## 1.函数关键字
  
## 2.函数的定义

## 3.函数参数与作用域

  必选参数
  默认参数
  可变参数 \*args args 接受的是一个tuple
  关键字参数 \*\*kw kw 接收的是一个dict
  
## 4.函数返回值
  
  无返回值
  return 0 //返回值为0
  return c //单返回值
  return（a, b, c) //多个返回值
  return func（） // 返回函数
  
## 5.File
  
  1）打开文件方式（读写两种方式）
    file obj = open(file_name\[,access_mode\]\[,buffering\]
    access_mode: 决定了打开文件的模式： 只读只写追加等。
    buffering： 如果为0，就不会有寄存。如果为1，访问文件时会寄存行。大于1，寄存区缓冲大小。负数，缓冲大小为默认值。
    http://www.runoob.com/python/python-files-io.html
  2）文件对象的操作方法
    obj.close()
    obj.write("") //会创建obj.txt文件，并写入
    obj.read(\[count\]) //
    obj.tell() //查找当前位置
    obj.seek(0,0) //重新定位到开头
    
  3）学习对Excel及CSV文件进行操作6
## 6.Os模块
  [Python 文件I/O]
  (http://www.runoob.com/python/python-files-io.html)
## 7.Datetime模块
  https://blog.csdn.net/shomy_liu/article/details/44141483
