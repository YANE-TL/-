# -sql
第一步
使用 Navicat 15 for mysql创建数据库
1，新建mysql连接文本，root用户登录，输入密码。
在新建的text新建数据库text01。


第二步
创建数据表
实例：
CREATE TABLE IF NOT EXISTS `runoob_tbl`(
   `runoob_id` INT UNSIGNED AUTO_INCREMENT,
   `runoob_title` VARCHAR(100) NOT NULL,
   `runoob_author` VARCHAR(40) NOT NULL,
   `submission_date` DATE,
   PRIMARY KEY ( `runoob_id` )
)ENGINE=InnoDB DEFAULT CHARSET=utf8;
