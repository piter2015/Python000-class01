学习笔记

# 不可变类型（整数、浮点数， 字符串、元组）传对象， 可变类型(列表，字典)传对象的引用
# 不可变类型 优点 不管有多少引用 ，相同对象只占用一块内存
# 缺点 对变量改变要先创建对象
# 可变类型 值变化不会新建对象，地址不会变，只是地址中的内容变了，地址得到扩充
# requests 请求中， 会话对象：在同一个 Session 实例发出的所有请求之间保持 cookie， 期间使用 urllib3 的 connection pooling 功能。向同一主机发送多个请求，底层的 TCP 连接将会被重用，从而带来显著的性能提升。

# 序列 可分为， 扁平序列 和 容器序列
# 字符串属于 扁平序列， 只能容纳这一种类型， 列表、元组， 是属于 容易容器序列，可以存放不容类型的数据
# 注意深拷贝和浅拷贝
# 非容器（数字、字符串、元组）类型没有拷贝
# 元组推导式要显示使用tuple(),不能直接使用 （1,）是元组， （1）代表数字



# 文件的读写操作过程中，使用with 方式， 可以省略 close 操作
# ex: with open('test.text', 'w')as f: 

# request 大文件下载~~
