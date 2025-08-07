# C++

cin如何判断输入类型：



## 字符串

cin>>不丢弃换行符

### 输入带空格字符串

*对字符数组*

1. getline读入整行数据，使用回车键输入的换行符来确定输入结尾,换行符被丢弃 

```c
cin.getline(str,len)
```

2. cin.get，换行符留在流中

```c
cin.get(str,len)
```

*对string*

```c
getline(cin,str)
```



## 类型转换

static_cast

dynamic_cast

const_cast

reinterpret_cast
