# YuQue1
用于完成语雀作业1
高校学生选课系统使用说明书
配置源程序
附加MySQL数据库
（1）将MR\10\WebRoot\Database文件夹中的扩展名为db_database10.sql的文件拷贝到本地机器中。
（2）打开MySQL的“MySQL Administrator”，并登录（本系统需要使用root和111登录），然后单击restore节点，在右侧单击“Open backup File”按钮，在弹出的对话框中，选择db_database10.sql文件，并单击“打开”按钮。 
（3）单击“Open Restore”按钮，即可完成数据库的附加操作。
将程序导入到MyEclipse中，并发布运行
（1）将“MR\10\”文件夹拷贝到MyEclipse的工作空间中。
（2）启动MyEclipse，在左侧的“包资源管理器”中，单击鼠标右键，选择“Import”菜单项，在弹出的对话框中，展开General节点，并选择“Existing Projects into Workspace”子节点，如图1.1所示。
 
图1.1  Import对话框
（3）单击“next”按钮，进入到Import Projects对话框中，选择工作空间中的10，单击“Finish”按钮，完成项目的导入。
（4）将程序所需的MySQL数据库驱动包（mysql-connector-java-3.0.16-ga-bin.jar）以及Srtuts1框架需要的jar包、Hibernate3.0框架需要的jar包、Spring框架需要的jar包，拷贝到工程的WebRoot\WEB-INF\lib文件夹中。
（5）单击工具栏中的 按钮，在弹出对话框的project下拉列表框中，选择项目名称10，单击add按钮，在弹出的new deployment对话框的server下拉列表框中选择要使用的服务器这里为MyEclipse Tomcat，单击Finish按钮，返回到Project Deployments对话框中，单击OK按钮。
（6）单击工具栏中的 按钮的三角形，在弹出菜单中选择“MyEclipse Tomcat/Start”菜单项，开启Tomcat服务器。
（7）打开IE浏览器，在地址栏中输入http://localhost:8080/10，并按下Enter键，进入本程序主页面。
使用说明
系统介绍
对于高校学生选课系统来说，针对的用户一般为学生，所以根据用户的需求，要求高校学生选课系统界面设计美观大方、操作简捷灵活，同时在该系统中用户要求必须实现课程信息的具体管理，学生查看历史选课情况，学生注册和选课，已选课学生信息的统计功能。
操作注意事项
本系统的后台用户名为：mr，密码为：mrsoft
操作流程
（1）访问本系统，首先进入系统登录页面。也可通过首页的“新用户注册”超链接注册新的用户。
（2）本系统将用户角色分为两种，分别为学生模块和管理模块，学生可以选择课程，管理员可以添加、修改、删除课程。



