## 各种包名详细介绍：
1. jar 包： 存放着需要用到的jar包，包括一下内容：
        （1）JDBC的驱动 ---》 mysql...
        （2）Apache公司的jar包，用来发送手机验证码（阿里云），以及发送短信验证码用到的jar包
        （3）Commons工具包对应的jar包

2. main 包：存放着主界面相关的类
        （1）UIFrame 类，注册登录界面

3. javabean 包： 封装了很多javabean对象，用来存储对象到数据库
        （1）User 类，对应数据库 bigwork中的user表，用来存放用户个人信息

4. jdbc 包：各种与JDBC相关操作的类，用来将数据存储到数据库
        （1）JDBCUtil 类，封装的基本操作的 工具类
        （2）

db.properties ---》 资源文件： 用来存储jdbc连接的基本信息，如用户名，密码等

待解决问题：
-----》    试题的删除             OK
----->      试题的编辑           OK
----->      AddSubjectToPaper       第146行，解决更新数据到数据库的过程   没毛病啊
