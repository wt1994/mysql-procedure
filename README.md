# mysql-procedure
mysql 的简单存储过程
DELIMITER //  定义分隔符 
CREATE PROCEDURE exampe1() SELECT * FROM  SYS_BANNER;//
CALL example1();// 执行存储过程example1
