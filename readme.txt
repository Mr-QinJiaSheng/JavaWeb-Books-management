
名称：JavaWeb 图书管理系统
技术：springboot+jpa+mybatis+springsecurity+swagger+javaex
使用步骤：
	1.将book-manager导入到开发工具中(idea/eclipse)均可
                	- idea：直接open打开源码文件夹，记住是pom文件所在的目录
		- eclipse： 直接导入- 选择已存在导入maven项目
		- 检查maven是否配置好，建议使用阿里云加速，这样等待时间比较短
		
	2.将sql文件夹下的sql文件导入MySQL数据库中, 修改数据库连接！！！ 注意用户名密码的修改，以及useSSL=true属性，5.7以上应该为true，5.7以下应为false
	否则可能会启动报错！此是mysql自己版本问题。
	
	3.等待依赖下载完成，启动ManagerApplication, 访问http://localhost:8080即可


