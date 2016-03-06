# realmlocal
javascript localStorage Html5 jquery-plugin

一个jquery插件,以java ThreadLocal的风格封装了localStorage,提供保留变量类型的存取操作.

====

使用方法:

$.rl.put(key,value)//存放数据

$.rl.get(key)//取出数据

$.rl.remove(key)//移除指定键值对

$.rl.clear()//清空本地存储仓库

====

不能存放函数对象,如果存放了正则表达式对象,将会使用eval来解析
