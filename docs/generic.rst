=============
Generic 说明
=============

Genric是什么？
---------------

在编写View相关的代码时，我们遇到最多的处理恐怕就是：列表显示、添加、删除、更新、修改
了，一般的叫法是CRUD(Create, Read, Update, Delete)这里没有List。那么Generic的目的
就是把这些常见的处理进行封装，并且它可以和Uliorm相结合，可以比较容易地对表中的
记录进行处理。在Uliweb的utils/generic.py中提供了上述的功能。

在generic中，针对不同的处理提供了不同的View Class，下面分别进行介绍。

ListView
-----------

