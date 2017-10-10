# Link

llk1为简单连连看游戏。

llk2采用Mysql数据库，可以在游戏之前实现简单的登录、注册

------------------------------------------------

运行环境 JDK1.8，建议使用eclipse 

llk1运行方式：

eclipse默认编码为GBK，请修改编码为UTF-8后导入项目，否则中文会产生乱码。
游戏界面采用javafx布局，请导入文件中的jfxrt.jar包，否则无法运行。
导入项目使不要弄丢llk1中bin目录下的图片。
导入项目后检查bin文件夹中图片是否存在，若不存在复制一份images中的图片粘贴进去，否则无法运行。
导入项目无误后运行llk1中的BeginMain.java文件，开始游戏(〃'▽'〃)。

llk2运行方式

eclipse默认编码为GBK，请修改编码位UTF-8后导入项目，否则中文会产生乱码。
游戏界面采用javafx布局，请导入文件中的jfxrt.jar包，否则无法运行。
导入项目使不要弄丢llk2中bin目录下images文件夹，若丢失复制一份进去。
Mysql数据库安装自行搜索。
请修改LoginMain.java、ReginsterPane.java、Grade.java三个文件中数据库的密码
请在Mysql数据库中用如下语句建立数据库并在该数据库中建立下表。

  create datbase Mydata;

  create table userMessage (

        name varcahr(8),

        gender varchar(1),

        acountNumber varchar(32) primary key,

        passwords varchar(16),

        lowTime int,

        normalTime int,

        difficultTime int

  );

运行LoginMain.java文件，开始游戏(*^▽^*)

----------------------------------------------

