# 数组的基本概念

# 常见方法
## 创建数组
### 字面量方法
` let arr = [1,2,3]`
### new Array构造函数的方式
```let arr = new Array(3) //长度为3的数组
  let arr = new Array（"1","2",）
```
## 迭代器方法
在ES6中Array原型会暴露三个数组的内容检索方法
- keys()索引
- values（）元素
- entries（）返回多对数组，其中每一个数组是数组的键值对
## 复制和填充方法
### fill（）插入相同内容
- arr.fill(5)//把数组中都插入5
- arr.fill(5,2)//用5填充索引2之后的内容 不含2
- arr.fill(5,1,3)//用5填充索引1-3的，含1 不含3
- 如果表示索引的参数中出现了负数，表示的是倒数
### copyWithin（）浅复制数组中的部分内容
array.copyWithin(target, start, end)
|参数|描述|
|:---:|:---:|
|target|必需。复制到指定目标索引位置|
|start|可选。被复制元素的起始位置|
|end|可选。被复制元素的索引位置 (默认为 array.length)。如果为负值，表示倒数|

## 栈方法
- push()//push数组长度
- pop()//返回被pop的
## 队列方法
队列方法都是对数组头的操作
- shift（）//移除值
- unshift（）//添加值
## 排序
## 操作
## 搜索
## 归并

# 定性数组
# Map
# WeakMap
