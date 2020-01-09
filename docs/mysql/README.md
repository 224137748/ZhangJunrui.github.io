# Mysql

![](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1576227498832&di=f9a9c6dc8b003624e8f23b7159035912&imgtype=0&src=http%3A%2F%2Fpic.downcc.com%2Fupload%2F2015-3%2F20153179412.png)

`MySQL` 是最流行的关系型数据库管理系统，在`WEB`应用方面`MySQL`是最好的 RDBMS(Relational Database Management System：关系数据库管理系统)应用软件之一。

## 特点

- 1.数据以表格的形式出现
- 2.每行为各种记录名称
- 3.每列为记录名称所对应的数据域
- 4.许多的行和列组成一张表单
- 5.若干的表单组成 `database`

## RDBMS 术语

在开始学习 `MySQL` 数据库前，先了解下 `RDBMS` 的一些术语：

- 数据库: 数据库是一些关联表的集合。
- 数据表: 表是数据的矩阵。在一个数据库中的表看起来像一个简单的电子表格。
- 列: 一列(数据元素) 包含了相同类型的数据, 例如邮政编码的数据。
- 行：一行（=元组，或记录）是一组相关的数据，例如一条用户订阅的数据。
- 冗余：存储两倍数据，冗余降低了性能，但提高了数据的安全性。
- 主键：主键是唯一的。一个数据表中只能包含一个主键。你可以使用主键来查询数据。
- 外键：外键用于关联两个表。
- 复合键：复合键（组合键）将多个列作为一个索引键，一般用于复合索引。
- 索引：使用索引可快速访问数据库表中的特定信息。索引是对数据库表中一列或多列的值进行排序的一种结构。类似于书籍的目录。
- 参照完整性: 参照的完整性要求关系中不允许引用不存在的实体。与实体完整性是关系模型必须满足的完整性约束条件，目的是保证数据- 的一致性。