# Task2（2day）

## 1. 列表（list）
      1)标志
            list = []
            slicing:
               [start_index: end_index: step] //py3 支持切片操作的数据类型有
               list、 tuple、 string、 unicode、 range。
      2)基本操作(创建，append(),pop(),del(),拷贝)
            list.append()
            pop = list.pop()
            del list[]
            list.copy()
      3)列表相关方法
            len(list)
            max(list)
            min(list)
            list(tuple) //将元组转化为list
            list.count(obj) //统计某元素在列表中出现的次数
            lsit.extend(seq) //追加
            list.index(obj) //位置
            list.insert(index, obj) //插入
            list.remove(obj) //移除第一个匹配项
            list.sort() //排序
            list.reverse() //倒序 == list[::-1]
            list.clear() //清空
            
## 2.元组（tuple）
      1)标志
            tuple = () // 元祖中元素不允许修改
            
      2)基本操作(创建及不可变性)
            del tuple
            len()
            max()
            min()
            tuple(list)
            tuple[]
            + * in for
            
## 3.string字符串
      http://www.runoob.com/python3/python3-string.html
      1)定义及基本操作(+，*，读取方式)
            "hello world" // 使用引号（‘ or “） 
            
      2)字符串相关方法
            
      4.字符串格式化问题
            转义字符
            print（"age is %d, name is %s." % (20, "聪")）
            
