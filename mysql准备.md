# SQL
    SQL：结构化查询语言，Structured Query language
SQL分为三个部分：

**DDL**：数据定义语言，Data Definition language

**DML**：数据操作语言，Data Manipulation language，如select，insert等。
   内部又分为`DQL`：Data Query language
   
**DCL**：数据控制语言，Data Control Language，负责管理用户权限。代表指令：grant，revoke等。

# MySql

> mysql是一种c/s结构的软件：客户端/服务器端。服务器一直运行，客户端在需要使用的时候运行。

## 交互方式

1.客户端连接认证：认证身份，mysql -hPup<br />

2.发送SQL指令

3 服务器接受SQL指令：处理SQL指令，返回结果

4 客户端接受结果

5 断开连接（释放资源，服务器并发限制）

