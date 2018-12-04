# ganwuwu-link0.2
land.php内存放更新内容。


1，数据库配置文件是/admin/user.php
	2，数据库有两个表，需要自己创建，手动设置。

	user表:
	id [int(12) 主键，自增]
	name [varchar(16)]
	password [varchar(16)]
	date [int(11)]

useradd表：
	id [int(12) 主键，自增]
	date [int(11)]
	linkname[varchar(25)]
	link[varchar(200)]
	image[varchar(50)]
	user[varchar(16)]
