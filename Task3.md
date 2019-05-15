# Task3
## 1. Dict字典
    1） 定义
        字典是一种可变容器模型， 且可存储任意类型对象。
        dict = {key : value}
        dict[] = key
        dict['key'] = value //键不可重复，value可以
        
    2） 创建
    3） 字典的方法
        dict['key'] = value
        如果字典里有对应键则更新键的值，如没有则添加
        del dict['key'] // 删除键
        dict.clear //清空字典
        del dict // 删除字典
        cmp(dic1, dic2) //比较两个字典元素
        len(dict) //
        str(dict) //
        dict.copy
        dict.fromkeys(seq[.val]) //创建一个新字典，以序列seq中元素做字典的建，val为字典所有键对应的初始值
        dict.get(key, default=None) //返回指定键的值，否则返回default的值
        dict.has_key(key) //true/false
        dict.items() //以列表返回可遍历的（键，至）元组数组
        dict.values() //以列表返回字典中的所有值
        dict.keys() //以列表返回一个字典的所有键
        dict.setdefault(key, default=None) //和get（）类似，但如果键不存在字典中，将会添加键设为default
        dict.update(dict2) //把字典dict2的键/值更新到dict里
        pop(key[.default]) //删除字典给定键key对应的值，返回值为被删除的值
        popitem() //随机返回并删除字典中的一对键和值
        
## 2. 集合
    1） 特性
        集合set 是一个无序的不重复元素序列
    2） 创建
        set（） //不是{}
    3） 方法
        http://www.runoob.com/python3/python3-set.html
## 3. 判断语句（要求掌握多条件判断）
## 4. 三目表达式
    循环语句
