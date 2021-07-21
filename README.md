# 2021年最新整理，5000道校招常用面试题，包含leetcode，校招笔试题，面试题，算法题，语法题。每天(周日休息)持续更新中。。。
* :dart: [mysql（已更新100道）](#4)
* :crystal_ball: [redis（已更新50道）](#5)
* :airplane: [nginx（已更新32道）](#6)
* :loudspeaker: [语法语言（已更新87道）](#7)
* :hourglass: [网络原理（已更新36道）](#8)
* :sparkles: [网络编程（已更新25道）](#9)
* :desktop_computer: [操作系统（已更新18道）](#10)
* :floppy_disk: [编译原理（已更新5道）](#11)
* [并发](#14)
* [堆与栈](#15)
* [树](#16)
* [图](#17)
* [排序](#18)
* [字符串](#19)
* [作者福利](#22)

<h3 id="4">:dart: mysql</h3> 

---
##### [1. MySQL 索引使用有哪些注意事项呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#1-mysql-%E7%B4%A2%E5%BC%95%E4%BD%BF%E7%94%A8%E6%9C%89%E5%93%AA%E4%BA%9B%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9%E5%91%A2)
##### [2. MySQL 遇到过死锁问题吗，你是如何解决的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#2-mysql-%E9%81%87%E5%88%B0%E8%BF%87%E6%AD%BB%E9%94%81%E9%97%AE%E9%A2%98%E5%90%97%E4%BD%A0%E6%98%AF%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3%E7%9A%84)
##### [3. 日常工作中你是怎么优化SQL的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#3-%E6%97%A5%E5%B8%B8%E5%B7%A5%E4%BD%9C%E4%B8%AD%E4%BD%A0%E6%98%AF%E6%80%8E%E4%B9%88%E4%BC%98%E5%8C%96sql%E7%9A%84)
##### [4. 说说分库与分表的设计](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#4-%E8%AF%B4%E8%AF%B4%E5%88%86%E5%BA%93%E4%B8%8E%E5%88%86%E8%A1%A8%E7%9A%84%E8%AE%BE%E8%AE%A1)
##### [5. InnoDB与MyISAM的区](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#5-innodb%E4%B8%8Emyisam%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [6. 数据库索引的原理，为什么要用 B+树，为什么不用二叉树？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#6-%E6%95%B0%E6%8D%AE%E5%BA%93%E7%B4%A2%E5%BC%95%E7%9A%84%E5%8E%9F%E7%90%86%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E7%94%A8-b%E6%A0%91%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E7%94%A8%E4%BA%8C%E5%8F%89%E6%A0%91)
##### [7. 聚集索引与非聚集索引的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#7-%E8%81%9A%E9%9B%86%E7%B4%A2%E5%BC%95%E4%B8%8E%E9%9D%9E%E8%81%9A%E9%9B%86%E7%B4%A2%E5%BC%95%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [8. limit 1000000 加载很慢的话，你是怎么解决的呢?](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#8-limit-1000000-%E5%8A%A0%E8%BD%BD%E5%BE%88%E6%85%A2%E7%9A%84%E8%AF%9D%E4%BD%A0%E6%98%AF%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3%E7%9A%84%E5%91%A2)
##### [9. 如何选择合适的分布式主键方案呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#9-%E5%A6%82%E4%BD%95%E9%80%89%E6%8B%A9%E5%90%88%E9%80%82%E7%9A%84%E5%88%86%E5%B8%83%E5%BC%8F%E4%B8%BB%E9%94%AE%E6%96%B9%E6%A1%88%E5%91%A2)
##### [10. 事务的隔离级别有哪些？MySQL的默认隔离级别是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#10-%E4%BA%8B%E5%8A%A1%E7%9A%84%E9%9A%94%E7%A6%BB%E7%BA%A7%E5%88%AB%E6%9C%89%E5%93%AA%E4%BA%9Bmysql%E7%9A%84%E9%BB%98%E8%AE%A4%E9%9A%94%E7%A6%BB%E7%BA%A7%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88)
##### [11. 什么是幻读，脏读，不可重复读呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#11-%E4%BB%80%E4%B9%88%E6%98%AF%E5%B9%BB%E8%AF%BB%E8%84%8F%E8%AF%BB%E4%B8%8D%E5%8F%AF%E9%87%8D%E5%A4%8D%E8%AF%BB%E5%91%A2)
##### [12. 在高并发情况下，如何做到安全的修改同一行数据？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#12-%E5%9C%A8%E9%AB%98%E5%B9%B6%E5%8F%91%E6%83%85%E5%86%B5%E4%B8%8B%E5%A6%82%E4%BD%95%E5%81%9A%E5%88%B0%E5%AE%89%E5%85%A8%E7%9A%84%E4%BF%AE%E6%94%B9%E5%90%8C%E4%B8%80%E8%A1%8C%E6%95%B0%E6%8D%AE)	
##### [13. 数据库的乐观锁和悲观锁。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#13-%E6%95%B0%E6%8D%AE%E5%BA%93%E7%9A%84%E4%B9%90%E8%A7%82%E9%94%81%E5%92%8C%E6%82%B2%E8%A7%82%E9%94%81)
##### [14. SQL优化的一般步骤是什么，怎么看执行计划（explain），如何理解其中各个字段的含义。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#14-sql%E4%BC%98%E5%8C%96%E7%9A%84%E4%B8%80%E8%88%AC%E6%AD%A5%E9%AA%A4%E6%98%AF%E4%BB%80%E4%B9%88%E6%80%8E%E4%B9%88%E7%9C%8B%E6%89%A7%E8%A1%8C%E8%AE%A1%E5%88%92explain%E5%A6%82%E4%BD%95%E7%90%86%E8%A7%A3%E5%85%B6%E4%B8%AD%E5%90%84%E4%B8%AA%E5%AD%97%E6%AE%B5%E7%9A%84%E5%90%AB%E4%B9%89)	
##### [15. select for update有什么含义，会锁表还是锁行还是其他。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#15-select-for-update%E6%9C%89%E4%BB%80%E4%B9%88%E5%90%AB%E4%B9%89%E4%BC%9A%E9%94%81%E8%A1%A8%E8%BF%98%E6%98%AF%E9%94%81%E8%A1%8C%E8%BF%98%E6%98%AF%E5%85%B6%E4%BB%96)	
##### [16. MySQL事务得四大特性以及实现原理](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#16-mysql%E4%BA%8B%E5%8A%A1%E5%BE%97%E5%9B%9B%E5%A4%A7%E7%89%B9%E6%80%A7%E4%BB%A5%E5%8F%8A%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)	
##### [17. 如果某个表有近千万数据，CRUD比较慢，如何优化。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#17-%E5%A6%82%E6%9E%9C%E6%9F%90%E4%B8%AA%E8%A1%A8%E6%9C%89%E8%BF%91%E5%8D%83%E4%B8%87%E6%95%B0%E6%8D%AEcrud%E6%AF%94%E8%BE%83%E6%85%A2%E5%A6%82%E4%BD%95%E4%BC%98%E5%8C%96)
##### [18. 如何写sql能够有效的使用到复合索引。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#18-%E5%A6%82%E4%BD%95%E5%86%99sql%E8%83%BD%E5%A4%9F%E6%9C%89%E6%95%88%E7%9A%84%E4%BD%BF%E7%94%A8%E5%88%B0%E5%A4%8D%E5%90%88%E7%B4%A2%E5%BC%95)
##### [19. mysql中in 和exists的区别。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#19-mysql%E4%B8%ADin-%E5%92%8Cexists%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [20. 数据库自增主键可能遇到什么问题。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#20-%E6%95%B0%E6%8D%AE%E5%BA%93%E8%87%AA%E5%A2%9E%E4%B8%BB%E9%94%AE%E5%8F%AF%E8%83%BD%E9%81%87%E5%88%B0%E4%BB%80%E4%B9%88%E9%97%AE%E9%A2%98)	
##### [21. MVCC熟悉吗，它的底层原理？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#21-mvcc%E7%86%9F%E6%82%89%E5%90%97%E5%AE%83%E7%9A%84%E5%BA%95%E5%B1%82%E5%8E%9F%E7%90%86)	
##### [22. 数据库中间件了解过吗，sharding jdbc，mycat？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#22-%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%AD%E9%97%B4%E4%BB%B6%E4%BA%86%E8%A7%A3%E8%BF%87%E5%90%97sharding-jdbcmycat)
##### [23. MYSQL的主从延迟，你怎么解决？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#23-mysql%E7%9A%84%E4%B8%BB%E4%BB%8E%E5%BB%B6%E8%BF%9F%E4%BD%A0%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3)	
##### [24. 说一下大表查询的优化方案](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#24-%E8%AF%B4%E4%B8%80%E4%B8%8B%E5%A4%A7%E8%A1%A8%E6%9F%A5%E8%AF%A2%E7%9A%84%E4%BC%98%E5%8C%96%E6%96%B9%E6%A1%88)	
##### [25. 什么是数据库连接池?为什么需要数据库连接池呢?	](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#25-%E4%BB%80%E4%B9%88%E6%98%AF%E6%95%B0%E6%8D%AE%E5%BA%93%E8%BF%9E%E6%8E%A5%E6%B1%A0%E4%B8%BA%E4%BB%80%E4%B9%88%E9%9C%80%E8%A6%81%E6%95%B0%E6%8D%AE%E5%BA%93%E8%BF%9E%E6%8E%A5%E6%B1%A0%E5%91%A2)
##### [26. 一条SQL语句在MySQL中如何执行的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#26-%E4%B8%80%E6%9D%A1sql%E8%AF%AD%E5%8F%A5%E5%9C%A8mysql%E4%B8%AD%E5%A6%82%E4%BD%95%E6%89%A7%E8%A1%8C%E7%9A%84)	
##### [27. InnoDB引擎中的索引策略，了解过吗？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#27-innodb%E5%BC%95%E6%93%8E%E4%B8%AD%E7%9A%84%E7%B4%A2%E5%BC%95%E7%AD%96%E7%95%A5%E4%BA%86%E8%A7%A3%E8%BF%87%E5%90%97)	
##### [28. 数据库存储日期格式时，如何考虑时区转换问题？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#28-%E6%95%B0%E6%8D%AE%E5%BA%93%E5%AD%98%E5%82%A8%E6%97%A5%E6%9C%9F%E6%A0%BC%E5%BC%8F%E6%97%B6%E5%A6%82%E4%BD%95%E8%80%83%E8%99%91%E6%97%B6%E5%8C%BA%E8%BD%AC%E6%8D%A2%E9%97%AE%E9%A2%98)	
##### [29. 一条sql执行过长的时间，你如何优化，从哪些方面入手？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#29-%E4%B8%80%E6%9D%A1sql%E6%89%A7%E8%A1%8C%E8%BF%87%E9%95%BF%E7%9A%84%E6%97%B6%E9%97%B4%E4%BD%A0%E5%A6%82%E4%BD%95%E4%BC%98%E5%8C%96%E4%BB%8E%E5%93%AA%E4%BA%9B%E6%96%B9%E9%9D%A2%E5%85%A5%E6%89%8B)	
##### [30. MYSQL数据库服务器性能分析的方法命令有哪些?](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#30-mysql%E6%95%B0%E6%8D%AE%E5%BA%93%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%80%A7%E8%83%BD%E5%88%86%E6%9E%90%E7%9A%84%E6%96%B9%E6%B3%95%E5%91%BD%E4%BB%A4%E6%9C%89%E5%93%AA%E4%BA%9B)	
##### [31. Blob和text有什么区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#31-blob%E5%92%8Ctext%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)	
##### [32. mysql里记录货币用什么字段类型比较好？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#32-mysql%E9%87%8C%E8%AE%B0%E5%BD%95%E8%B4%A7%E5%B8%81%E7%94%A8%E4%BB%80%E4%B9%88%E5%AD%97%E6%AE%B5%E7%B1%BB%E5%9E%8B%E6%AF%94%E8%BE%83%E5%A5%BD)	
##### [33. Mysql中有哪几种锁，列举一下？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#33-mysql%E4%B8%AD%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E9%94%81%E5%88%97%E4%B8%BE%E4%B8%80%E4%B8%8B)	
##### [34. Hash索引和B+树区别是什么？你在设计索引是怎么抉择的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#34-hash%E7%B4%A2%E5%BC%95%E5%92%8Cb%E6%A0%91%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88%E4%BD%A0%E5%9C%A8%E8%AE%BE%E8%AE%A1%E7%B4%A2%E5%BC%95%E6%98%AF%E6%80%8E%E4%B9%88%E6%8A%89%E6%8B%A9%E7%9A%84)	
##### [35. mysql 的内连接、左连接、右连接有什么区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#35-mysql-%E7%9A%84%E5%86%85%E8%BF%9E%E6%8E%A5%E5%B7%A6%E8%BF%9E%E6%8E%A5%E5%8F%B3%E8%BF%9E%E6%8E%A5%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)	
##### [36. 说说MySQL 的基础架构图](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#36-%E8%AF%B4%E8%AF%B4mysql-%E7%9A%84%E5%9F%BA%E7%A1%80%E6%9E%B6%E6%9E%84%E5%9B%BE)	
##### [37. 什么是内连接、外连接、交叉连接、笛卡尔积呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#37-%E4%BB%80%E4%B9%88%E6%98%AF%E5%86%85%E8%BF%9E%E6%8E%A5%E5%A4%96%E8%BF%9E%E6%8E%A5%E4%BA%A4%E5%8F%89%E8%BF%9E%E6%8E%A5%E7%AC%9B%E5%8D%A1%E5%B0%94%E7%A7%AF%E5%91%A2)	
##### [38. 说一下数据库的三大范式](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#38-%E8%AF%B4%E4%B8%80%E4%B8%8B%E6%95%B0%E6%8D%AE%E5%BA%93%E7%9A%84%E4%B8%89%E5%A4%A7%E8%8C%83%E5%BC%8F)
##### [39. mysql有关权限的表有哪几个呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#39-mysql%E6%9C%89%E5%85%B3%E6%9D%83%E9%99%90%E7%9A%84%E8%A1%A8%E6%9C%89%E5%93%AA%E5%87%A0%E4%B8%AA%E5%91%A2)	
##### [40. Mysql的binlog有几种录入格式？分别有什么区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#40-mysql%E7%9A%84binlog%E6%9C%89%E5%87%A0%E7%A7%8D%E5%BD%95%E5%85%A5%E6%A0%BC%E5%BC%8F%E5%88%86%E5%88%AB%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)	
##### [41. InnoDB引擎的4大特性，了解过吗](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#41-innodb%E5%BC%95%E6%93%8E%E7%9A%844%E5%A4%A7%E7%89%B9%E6%80%A7%E4%BA%86%E8%A7%A3%E8%BF%87%E5%90%97)	
##### [42. 索引有哪些优缺点？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#42-%E7%B4%A2%E5%BC%95%E6%9C%89%E5%93%AA%E4%BA%9B%E4%BC%98%E7%BC%BA%E7%82%B9)	
##### [43. 索引有哪几种类型？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#43-%E7%B4%A2%E5%BC%95%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E7%B1%BB%E5%9E%8B)	
##### [44. 创建索引有什么原则呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#44-%E5%88%9B%E5%BB%BA%E7%B4%A2%E5%BC%95%E6%9C%89%E4%BB%80%E4%B9%88%E5%8E%9F%E5%88%99%E5%91%A2)	
##### [45. 创建索引的三种方式](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#45-%E5%88%9B%E5%BB%BA%E7%B4%A2%E5%BC%95%E7%9A%84%E4%B8%89%E7%A7%8D%E6%96%B9%E5%BC%8F)	
##### [46. 百万级别或以上的数据，你是如何删除的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#46-%E7%99%BE%E4%B8%87%E7%BA%A7%E5%88%AB%E6%88%96%E4%BB%A5%E4%B8%8A%E7%9A%84%E6%95%B0%E6%8D%AE%E4%BD%A0%E6%98%AF%E5%A6%82%E4%BD%95%E5%88%A0%E9%99%A4%E7%9A%84)
##### [47. 什么是最左前缀原则？什么是最左匹配原则？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#47-%E4%BB%80%E4%B9%88%E6%98%AF%E6%9C%80%E5%B7%A6%E5%89%8D%E7%BC%80%E5%8E%9F%E5%88%99%E4%BB%80%E4%B9%88%E6%98%AF%E6%9C%80%E5%B7%A6%E5%8C%B9%E9%85%8D%E5%8E%9F%E5%88%99)
##### [48. B树和B+树的区别，数据库为什么使用B+树而不是B树？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#48-b%E6%A0%91%E5%92%8Cb%E6%A0%91%E7%9A%84%E5%8C%BA%E5%88%AB%E6%95%B0%E6%8D%AE%E5%BA%93%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BD%BF%E7%94%A8b%E6%A0%91%E8%80%8C%E4%B8%8D%E6%98%AFb%E6%A0%91)
##### [49. 覆盖索引、回表等这些，了解过吗？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#49-%E8%A6%86%E7%9B%96%E7%B4%A2%E5%BC%95%E5%9B%9E%E8%A1%A8%E7%AD%89%E8%BF%99%E4%BA%9B%E4%BA%86%E8%A7%A3%E8%BF%87%E5%90%97)
##### [50. B+树在满足聚簇索引和覆盖索引的时候不需要回表查询数据？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#50-b%E6%A0%91%E5%9C%A8%E6%BB%A1%E8%B6%B3%E8%81%9A%E7%B0%87%E7%B4%A2%E5%BC%95%E5%92%8C%E8%A6%86%E7%9B%96%E7%B4%A2%E5%BC%95%E7%9A%84%E6%97%B6%E5%80%99%E4%B8%8D%E9%9C%80%E8%A6%81%E5%9B%9E%E8%A1%A8%E6%9F%A5%E8%AF%A2%E6%95%B0%E6%8D%AE)
##### [51. 何时使用聚簇索引与非聚簇索引](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#51-%E4%BD%95%E6%97%B6%E4%BD%BF%E7%94%A8%E8%81%9A%E7%B0%87%E7%B4%A2%E5%BC%95%E4%B8%8E%E9%9D%9E%E8%81%9A%E7%B0%87%E7%B4%A2%E5%BC%95)	
##### [52. 非聚簇索引一定会回表查询吗？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#52-%E9%9D%9E%E8%81%9A%E7%B0%87%E7%B4%A2%E5%BC%95%E4%B8%80%E5%AE%9A%E4%BC%9A%E5%9B%9E%E8%A1%A8%E6%9F%A5%E8%AF%A2%E5%90%97)
##### [53. 组合索引是什么？为什么需要注意组合索引中的顺序？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#53-%E7%BB%84%E5%90%88%E7%B4%A2%E5%BC%95%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%BA%E4%BB%80%E4%B9%88%E9%9C%80%E8%A6%81%E6%B3%A8%E6%84%8F%E7%BB%84%E5%90%88%E7%B4%A2%E5%BC%95%E4%B8%AD%E7%9A%84%E9%A1%BA%E5%BA%8F)
##### [54. 什么是数据库事务？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#54-%E4%BB%80%E4%B9%88%E6%98%AF%E6%95%B0%E6%8D%AE%E5%BA%93%E4%BA%8B%E5%8A%A1)	
##### [55. 隔离级别与锁的关系](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#55-%E9%9A%94%E7%A6%BB%E7%BA%A7%E5%88%AB%E4%B8%8E%E9%94%81%E7%9A%84%E5%85%B3%E7%B3%BB)	
##### [56. 按照锁的粒度分，数据库锁有哪些呢？锁机制与InnoDB锁算法](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#56-%E6%8C%89%E7%85%A7%E9%94%81%E7%9A%84%E7%B2%92%E5%BA%A6%E5%88%86%E6%95%B0%E6%8D%AE%E5%BA%93%E9%94%81%E6%9C%89%E5%93%AA%E4%BA%9B%E5%91%A2%E9%94%81%E6%9C%BA%E5%88%B6%E4%B8%8Einnodb%E9%94%81%E7%AE%97%E6%B3%95)	
##### [57. 从锁的类别角度讲，MySQL都有哪些锁呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#57-%E4%BB%8E%E9%94%81%E7%9A%84%E7%B1%BB%E5%88%AB%E8%A7%92%E5%BA%A6%E8%AE%B2mysql%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E9%94%81%E5%91%A2)	
##### [58. MySQL中InnoDB引擎的行锁是怎么实现的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#58-mysql%E4%B8%ADinnodb%E5%BC%95%E6%93%8E%E7%9A%84%E8%A1%8C%E9%94%81%E6%98%AF%E6%80%8E%E4%B9%88%E5%AE%9E%E7%8E%B0%E7%9A%84)	
##### [59. 什么是死锁？怎么解决？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#59-%E4%BB%80%E4%B9%88%E6%98%AF%E6%AD%BB%E9%94%81%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3)	
##### [60. 为什么要使用视图？什么是视图？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#60-%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E4%BD%BF%E7%94%A8%E8%A7%86%E5%9B%BE%E4%BB%80%E4%B9%88%E6%98%AF%E8%A7%86%E5%9B%BE)	
##### [61. 视图有哪些特点？哪些使用场景？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#61-%E8%A7%86%E5%9B%BE%E6%9C%89%E5%93%AA%E4%BA%9B%E7%89%B9%E7%82%B9%E5%93%AA%E4%BA%9B%E4%BD%BF%E7%94%A8%E5%9C%BA%E6%99%AF)	
##### [62. 视图的优点，缺点，讲一下？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#62-%E8%A7%86%E5%9B%BE%E7%9A%84%E4%BC%98%E7%82%B9%E7%BC%BA%E7%82%B9%E8%AE%B2%E4%B8%80%E4%B8%8B)	
##### [63. count(1)、count(*) 与 count(列名) 的区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#63-count1count-%E4%B8%8E-count%E5%88%97%E5%90%8D-%E7%9A%84%E5%8C%BA%E5%88%AB)	
##### [64. 什么是游标？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#64-%E4%BB%80%E4%B9%88%E6%98%AF%E6%B8%B8%E6%A0%87)	
##### [65. 什么是存储过程？有哪些优缺点？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#65-%E4%BB%80%E4%B9%88%E6%98%AF%E5%AD%98%E5%82%A8%E8%BF%87%E7%A8%8B%E6%9C%89%E5%93%AA%E4%BA%9B%E4%BC%98%E7%BC%BA%E7%82%B9)	
##### [66. 什么是触发器？触发器的使用场景有哪些？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#66-%E4%BB%80%E4%B9%88%E6%98%AF%E8%A7%A6%E5%8F%91%E5%99%A8%E8%A7%A6%E5%8F%91%E5%99%A8%E7%9A%84%E4%BD%BF%E7%94%A8%E5%9C%BA%E6%99%AF%E6%9C%89%E5%93%AA%E4%BA%9B)	
##### [67. MySQL中都有哪些触发器？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#67-mysql%E4%B8%AD%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E8%A7%A6%E5%8F%91%E5%99%A8)	
##### [68. 超键、候选键、主键、外键分别是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#68-%E8%B6%85%E9%94%AE%E5%80%99%E9%80%89%E9%94%AE%E4%B8%BB%E9%94%AE%E5%A4%96%E9%94%AE%E5%88%86%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88)	
##### [69. SQL 约束有哪几种呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#69-sql-%E7%BA%A6%E6%9D%9F%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E5%91%A2)	
##### [70. 谈谈六种关联查询，使用场景。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#70-%E8%B0%88%E8%B0%88%E5%85%AD%E7%A7%8D%E5%85%B3%E8%81%94%E6%9F%A5%E8%AF%A2%E4%BD%BF%E7%94%A8%E5%9C%BA%E6%99%AF)
##### [71. varchar(50)中50的涵义](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#71-varchar50%E4%B8%AD50%E7%9A%84%E6%B6%B5%E4%B9%89)	
##### [72. mysql中int(20)和char(20)以及varchar(20)的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#72-mysql%E4%B8%ADint20%E5%92%8Cchar20%E4%BB%A5%E5%8F%8Avarchar20%E7%9A%84%E5%8C%BA%E5%88%AB)	
##### [73. drop、delete与truncate的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#73-dropdelete%E4%B8%8Etruncate%E7%9A%84%E5%8C%BA%E5%88%AB)	
##### [74. UNION与UNION ALL的区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#74-union%E4%B8%8Eunion-all%E7%9A%84%E5%8C%BA%E5%88%AB)	
##### [75. SQL的生命周期？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#75-sql%E7%9A%84%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F)	
##### [76. 一条Sql的执行顺序？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#76-%E4%B8%80%E6%9D%A1sql%E7%9A%84%E6%89%A7%E8%A1%8C%E9%A1%BA%E5%BA%8F)	
##### [77. 列值为NULL时，查询是否会用到索引？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#77-%E5%88%97%E5%80%BC%E4%B8%BAnull%E6%97%B6%E6%9F%A5%E8%AF%A2%E6%98%AF%E5%90%A6%E4%BC%9A%E7%94%A8%E5%88%B0%E7%B4%A2%E5%BC%95)	
##### [78. 关心过业务系统里面的sql耗时吗？统计过慢查询吗？对慢查询都怎么优化过？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#78-%E5%85%B3%E5%BF%83%E8%BF%87%E4%B8%9A%E5%8A%A1%E7%B3%BB%E7%BB%9F%E9%87%8C%E9%9D%A2%E7%9A%84sql%E8%80%97%E6%97%B6%E5%90%97%E7%BB%9F%E8%AE%A1%E8%BF%87%E6%85%A2%E6%9F%A5%E8%AF%A2%E5%90%97%E5%AF%B9%E6%85%A2%E6%9F%A5%E8%AF%A2%E9%83%BD%E6%80%8E%E4%B9%88%E4%BC%98%E5%8C%96%E8%BF%87)	
##### [79. 主键使用自增ID还是UUID，为什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#79-%E4%B8%BB%E9%94%AE%E4%BD%BF%E7%94%A8%E8%87%AA%E5%A2%9Eid%E8%BF%98%E6%98%AFuuid%E4%B8%BA%E4%BB%80%E4%B9%88)	
##### [80. mysql自增主键用完了怎么办？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#80-mysql%E8%87%AA%E5%A2%9E%E4%B8%BB%E9%94%AE%E7%94%A8%E5%AE%8C%E4%BA%86%E6%80%8E%E4%B9%88%E5%8A%9E)	
##### [81. 字段为什么要求定义为not null？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#81-%E5%AD%97%E6%AE%B5%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E6%B1%82%E5%AE%9A%E4%B9%89%E4%B8%BAnot-null)	
##### [82. 如果要存储用户的密码散列，应该使用什么字段进行存储？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#82-%E5%A6%82%E6%9E%9C%E8%A6%81%E5%AD%98%E5%82%A8%E7%94%A8%E6%88%B7%E7%9A%84%E5%AF%86%E7%A0%81%E6%95%A3%E5%88%97%E5%BA%94%E8%AF%A5%E4%BD%BF%E7%94%A8%E4%BB%80%E4%B9%88%E5%AD%97%E6%AE%B5%E8%BF%9B%E8%A1%8C%E5%AD%98%E5%82%A8)
##### [83. Mysql驱动程序是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#83-mysql%E9%A9%B1%E5%8A%A8%E7%A8%8B%E5%BA%8F%E6%98%AF%E4%BB%80%E4%B9%88)
##### [84. 如何优化长难的查询语句？有实战过吗？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#84-%E5%A6%82%E4%BD%95%E4%BC%98%E5%8C%96%E9%95%BF%E9%9A%BE%E7%9A%84%E6%9F%A5%E8%AF%A2%E8%AF%AD%E5%8F%A5%E6%9C%89%E5%AE%9E%E6%88%98%E8%BF%87%E5%90%97)
##### [85. 优化特定类型的查询语句](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#85-%E4%BC%98%E5%8C%96%E7%89%B9%E5%AE%9A%E7%B1%BB%E5%9E%8B%E7%9A%84%E6%9F%A5%E8%AF%A2%E8%AF%AD%E5%8F%A5)
##### [86. MySQL数据库cpu飙升的话，要怎么处理呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#86-mysql%E6%95%B0%E6%8D%AE%E5%BA%93cpu%E9%A3%99%E5%8D%87%E7%9A%84%E8%AF%9D%E8%A6%81%E6%80%8E%E4%B9%88%E5%A4%84%E7%90%86%E5%91%A2)
##### [87. 读写分离常见方案？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#87-%E8%AF%BB%E5%86%99%E5%88%86%E7%A6%BB%E5%B8%B8%E8%A7%81%E6%96%B9%E6%A1%88)
##### [88. MySQL的复制原理以及流程	](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#88-mysql%E7%9A%84%E5%A4%8D%E5%88%B6%E5%8E%9F%E7%90%86%E4%BB%A5%E5%8F%8A%E6%B5%81%E7%A8%8B)
##### [89. MySQL中DATETIME和TIMESTAMP的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#89-mysql%E4%B8%ADdatetime%E5%92%8Ctimestamp%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [90. Innodb的事务实现原理？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#90-innodb%E7%9A%84%E4%BA%8B%E5%8A%A1%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
##### [91. 谈谈MySQL的Explain](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#91-%E8%B0%88%E8%B0%88mysql%E7%9A%84explain)	
##### [92. Innodb的事务与日志的实现方式](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#92-innodb%E7%9A%84%E4%BA%8B%E5%8A%A1%E4%B8%8E%E6%97%A5%E5%BF%97%E7%9A%84%E5%AE%9E%E7%8E%B0%E6%96%B9%E5%BC%8F)	
##### [93. MySQL中TEXT数据类型的最大长度](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#93-mysql%E4%B8%ADtext%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B%E7%9A%84%E6%9C%80%E5%A4%A7%E9%95%BF%E5%BA%A6)	
##### [94. 500台db，在最快时间之内重启。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#94-500%E5%8F%B0db%E5%9C%A8%E6%9C%80%E5%BF%AB%E6%97%B6%E9%97%B4%E4%B9%8B%E5%86%85%E9%87%8D%E5%90%AF)	
##### [95. 你是如何监控你们的数据库的？你们的慢日志都是怎么查询的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#95-%E4%BD%A0%E6%98%AF%E5%A6%82%E4%BD%95%E7%9B%91%E6%8E%A7%E4%BD%A0%E4%BB%AC%E7%9A%84%E6%95%B0%E6%8D%AE%E5%BA%93%E7%9A%84%E4%BD%A0%E4%BB%AC%E7%9A%84%E6%85%A2%E6%97%A5%E5%BF%97%E9%83%BD%E6%98%AF%E6%80%8E%E4%B9%88%E6%9F%A5%E8%AF%A2%E7%9A%84)
##### [96. 你是否做过主从一致性校验，如果有，怎么做的，如果没有，你打算怎么做？	](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#96-%E4%BD%A0%E6%98%AF%E5%90%A6%E5%81%9A%E8%BF%87%E4%B8%BB%E4%BB%8E%E4%B8%80%E8%87%B4%E6%80%A7%E6%A0%A1%E9%AA%8C%E5%A6%82%E6%9E%9C%E6%9C%89%E6%80%8E%E4%B9%88%E5%81%9A%E7%9A%84%E5%A6%82%E6%9E%9C%E6%B2%A1%E6%9C%89%E4%BD%A0%E6%89%93%E7%AE%97%E6%80%8E%E4%B9%88%E5%81%9A)
##### [97. 你们数据库是否支持emoji表情存储，如果不支持，如何操作？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#97-%E4%BD%A0%E4%BB%AC%E6%95%B0%E6%8D%AE%E5%BA%93%E6%98%AF%E5%90%A6%E6%94%AF%E6%8C%81emoji%E8%A1%A8%E6%83%85%E5%AD%98%E5%82%A8%E5%A6%82%E6%9E%9C%E4%B8%8D%E6%94%AF%E6%8C%81%E5%A6%82%E4%BD%95%E6%93%8D%E4%BD%9C)	
##### [98. MySQL如何获取当前日期？](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#98-mysql%E5%A6%82%E4%BD%95%E8%8E%B7%E5%8F%96%E5%BD%93%E5%89%8D%E6%97%A5%E6%9C%9F)
##### [99. 一个6亿的表a，一个3亿的表b，通过外间tid关联，你如何最快的查询出满足条件的第50000到第50200中的这200条数据记录。](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#99-%E4%B8%80%E4%B8%AA6%E4%BA%BF%E7%9A%84%E8%A1%A8a%E4%B8%80%E4%B8%AA3%E4%BA%BF%E7%9A%84%E8%A1%A8b%E9%80%9A%E8%BF%87%E5%A4%96%E9%97%B4tid%E5%85%B3%E8%81%94%E4%BD%A0%E5%A6%82%E4%BD%95%E6%9C%80%E5%BF%AB%E7%9A%84%E6%9F%A5%E8%AF%A2%E5%87%BA%E6%BB%A1%E8%B6%B3%E6%9D%A1%E4%BB%B6%E7%9A%84%E7%AC%AC50000%E5%88%B0%E7%AC%AC50200%E4%B8%AD%E7%9A%84%E8%BF%99200%E6%9D%A1%E6%95%B0%E6%8D%AE%E8%AE%B0%E5%BD%95)	
##### [100. Mysql一条SQL加锁分析](https://github.com/0voice/campus_recruitmen_questions/blob/main/mysql/1~100mysql%E7%9A%84%E9%9D%A2%E8%AF%95%E9%A2%98.md#100-mysql%E4%B8%80%E6%9D%A1sql%E5%8A%A0%E9%94%81%E5%88%86%E6%9E%90)	

<br>

<h3 id="5">:crystal_ball:	redis</h3> 

---
##### [1、什么是 Redis?简述它的优缺点?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#1%E4%BB%80%E4%B9%88%E6%98%AF-redis)
##### [2、Redis相比memcached有哪些优势?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#2redis-%E7%9B%B8%E6%AF%94-memcached-%E6%9C%89%E5%93%AA%E4%BA%9B%E4%BC%98%E5%8A%BF)
##### [3、Redis支持哪几种数据类型?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#3redis-%E6%94%AF%E6%8C%81%E5%93%AA%E5%87%A0%E7%A7%8D%E6%95%B0%E6%8D%AE%E7%B1%BB%E5%9E%8B)
##### [4、Redis主要消耗什么物理资源?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#4redis-%E4%B8%BB%E8%A6%81%E6%B6%88%E8%80%97%E4%BB%80%E4%B9%88%E7%89%A9%E7%90%86%E8%B5%84%E6%BA%90)
##### [5、Redis 的全称是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#5redis-%E7%9A%84%E5%85%A8%E7%A7%B0%E6%98%AF%E4%BB%80%E4%B9%88)
##### [6、Redis有哪几种数据淘汰策略?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#6redis-%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E6%95%B0%E6%8D%AE%E6%B7%98%E6%B1%B0%E7%AD%96%E7%95%A5)
##### [7、Redis官方为什么不提供Windows版本?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#7redis-%E5%AE%98%E6%96%B9%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E6%8F%90%E4%BE%9B-windows-%E7%89%88%E6%9C%AC)
##### [8、一个字符串类型的值能存储最大容量是多少?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#8%E4%B8%80%E4%B8%AA%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%B1%BB%E5%9E%8B%E7%9A%84%E5%80%BC%E8%83%BD%E5%AD%98%E5%82%A8%E6%9C%80%E5%A4%A7%E5%AE%B9%E9%87%8F%E6%98%AF%E5%A4%9A%E5%B0%91)
##### [9、为什么Redis需要把所有数据放到内存中?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#9%E4%B8%BA%E4%BB%80%E4%B9%88-redis-%E9%9C%80%E8%A6%81%E6%8A%8A%E6%89%80%E6%9C%89%E6%95%B0%E6%8D%AE%E6%94%BE%E5%88%B0%E5%86%85%E5%AD%98%E4%B8%AD)
##### [10、Redis 集群方案应该怎么做?都有哪些方案?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#10redis-%E9%9B%86%E7%BE%A4%E6%96%B9%E6%A1%88%E5%BA%94%E8%AF%A5%E6%80%8E%E4%B9%88%E5%81%9A%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E6%96%B9%E6%A1%88)
##### [11、Redis 集群方案什么情况下会导致整个集群不可用?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#11redis-%E9%9B%86%E7%BE%A4%E6%96%B9%E6%A1%88%E4%BB%80%E4%B9%88%E6%83%85%E5%86%B5%E4%B8%8B%E4%BC%9A%E5%AF%BC%E8%87%B4%E6%95%B4%E4%B8%AA%E9%9B%86%E7%BE%A4%E4%B8%8D%E5%8F%AF%E7%94%A8)
##### [12、MySQL 里有 2000w 数据，redis 中只存 20w 的数据，如何保证 redis中的数据都是热点数据？](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#12mysql-%E9%87%8C%E6%9C%89-2000w-%E6%95%B0%E6%8D%AEredis-%E4%B8%AD%E5%8F%AA%E5%AD%98-20w-%E7%9A%84%E6%95%B0%E6%8D%AE%E5%A6%82%E4%BD%95%E4%BF%9D%E8%AF%81-redis-%E4%B8%AD%E7%9A%84%E6%95%B0%E6%8D%AE%E9%83%BD%E6%98%AF%E7%83%AD%E7%82%B9%E6%95%B0%E6%8D%AE)
##### [13、Redis有哪些适合的场景?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#13redis-%E6%9C%89%E5%93%AA%E4%BA%9B%E9%80%82%E5%90%88%E7%9A%84%E5%9C%BA%E6%99%AF)
##### [14、Redis.支持的Java客户端都有哪些?官方推荐用哪个?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#14redis-%E6%94%AF%E6%8C%81%E7%9A%84-java-%E5%AE%A2%E6%88%B7%E7%AB%AF%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E5%AE%98%E6%96%B9%E6%8E%A8%E8%8D%90%E7%94%A8%E5%93%AA%E4%B8%AA)
##### [15、Redis 和Redisson有什么关系?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#15redis-%E5%92%8C-redisson-%E6%9C%89%E4%BB%80%E4%B9%88%E5%85%B3%E7%B3%BB)
##### [16、Jedis与 Redisson对比有什么优缺点?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#16jedis-%E4%B8%8E-redisson-%E5%AF%B9%E6%AF%94%E6%9C%89%E4%BB%80%E4%B9%88%E4%BC%98%E7%BC%BA%E7%82%B9)
##### [17、Redis如何设置密码及验证密码?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#17redis-%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E5%AF%86%E7%A0%81%E5%8F%8A%E9%AA%8C%E8%AF%81%E5%AF%86%E7%A0%81)
##### [18、说说 Redis 哈希槽的概念?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#18%E8%AF%B4%E8%AF%B4-redis-%E5%93%88%E5%B8%8C%E6%A7%BD%E7%9A%84%E6%A6%82%E5%BF%B5)
##### [19、Redis 集群的主从复制模型是怎样的?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#19redis-%E9%9B%86%E7%BE%A4%E7%9A%84%E4%B8%BB%E4%BB%8E%E5%A4%8D%E5%88%B6%E6%A8%A1%E5%9E%8B%E6%98%AF%E6%80%8E%E6%A0%B7%E7%9A%84)
##### [20、Redis集群会有写操作丢失吗?为什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#20redis-%E9%9B%86%E7%BE%A4%E4%BC%9A%E6%9C%89%E5%86%99%E6%93%8D%E4%BD%9C%E4%B8%A2%E5%A4%B1%E5%90%97%E4%B8%BA%E4%BB%80%E4%B9%88)
##### [21、Redis 集群之间是如何复制的?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#21redis-%E9%9B%86%E7%BE%A4%E4%B9%8B%E9%97%B4%E6%98%AF%E5%A6%82%E4%BD%95%E5%A4%8D%E5%88%B6%E7%9A%84)
##### [22、Redis 集群最大节点个数是多少?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#22redis-%E9%9B%86%E7%BE%A4%E6%9C%80%E5%A4%A7%E8%8A%82%E7%82%B9%E4%B8%AA%E6%95%B0%E6%98%AF%E5%A4%9A%E5%B0%91)
##### [23、Redis 集群如何选择数据库?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#23redis-%E9%9B%86%E7%BE%A4%E5%A6%82%E4%BD%95%E9%80%89%E6%8B%A9%E6%95%B0%E6%8D%AE%E5%BA%93)
##### [24、怎么测试Redis的连通性?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#24%E6%80%8E%E4%B9%88%E6%B5%8B%E8%AF%95-redis-%E7%9A%84%E8%BF%9E%E9%80%9A%E6%80%A7)
##### [25、Redis 中的管道有什么用?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#25redis-%E4%B8%AD%E7%9A%84%E7%AE%A1%E9%81%93%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8)
##### [26、怎么理解 Redis 事务?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#26%E6%80%8E%E4%B9%88%E7%90%86%E8%A7%A3-redis-%E4%BA%8B%E5%8A%A1)
##### [27、Redis事务相关的命令有哪几个?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#27redis-%E4%BA%8B%E5%8A%A1%E7%9B%B8%E5%85%B3%E7%9A%84%E5%91%BD%E4%BB%A4%E6%9C%89%E5%93%AA%E5%87%A0%E4%B8%AA)
##### [28、Redis key的过期时间和永久有效分别怎么设置?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#28redis-key-%E7%9A%84%E8%BF%87%E6%9C%9F%E6%97%B6%E9%97%B4%E5%92%8C%E6%B0%B8%E4%B9%85%E6%9C%89%E6%95%88%E5%88%86%E5%88%AB%E6%80%8E%E4%B9%88%E8%AE%BE%E7%BD%AE)
##### [29、Redis 如何做内存优化?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#29redis-%E5%A6%82%E4%BD%95%E5%81%9A%E5%86%85%E5%AD%98%E4%BC%98%E5%8C%96)
##### [30、Redis回收进程如何工作的?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#30redis-%E5%9B%9E%E6%94%B6%E8%BF%9B%E7%A8%8B%E5%A6%82%E4%BD%95%E5%B7%A5%E4%BD%9C%E7%9A%84%E4%B8%80%E4%B8%AA%E5%AE%A2%E6%88%B7%E7%AB%AF%E8%BF%90%E8%A1%8C%E4%BA%86%E6%96%B0%E7%9A%84%E5%91%BD%E4%BB%A4%E6%B7%BB%E5%8A%A0%E4%BA%86%E6%96%B0%E7%9A%84%E6%95%B0%E6%8D%AE)
##### [31、Redis回收使用的是什么算法?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#31redis-%E5%9B%9E%E6%94%B6%E4%BD%BF%E7%94%A8%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E7%AE%97%E6%B3%95)
##### [32、Redis 如何做大量数据插入?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#32redis-%E5%A6%82%E4%BD%95%E5%81%9A%E5%A4%A7%E9%87%8F%E6%95%B0%E6%8D%AE%E6%8F%92%E5%85%A5)
##### [33、为什么要做Redis分区?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#33%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E5%81%9A-redis-%E5%88%86%E5%8C%BA)
##### [34、有哪些Redis分区实现方案?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#34%E6%9C%89%E5%93%AA%E4%BA%9B-redis-%E5%88%86%E5%8C%BA%E5%AE%9E%E7%8E%B0%E6%96%B9%E6%A1%88)
##### [35、Redis分区有什么缺点?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#35redis-%E5%88%86%E5%8C%BA%E6%9C%89%E4%BB%80%E4%B9%88%E7%BC%BA%E7%82%B9)
##### [36、Redis 持久化数据和缓存怎么做扩容？如果 Redis 被当做缓存使用，使用一致性哈希实现动态扩容缩容](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#36redis-%E6%8C%81%E4%B9%85%E5%8C%96%E6%95%B0%E6%8D%AE%E5%92%8C%E7%BC%93%E5%AD%98%E6%80%8E%E4%B9%88%E5%81%9A%E6%89%A9%E5%AE%B9%E5%A6%82%E6%9E%9C-redis-%E8%A2%AB%E5%BD%93%E5%81%9A%E7%BC%93%E5%AD%98%E4%BD%BF%E7%94%A8%E4%BD%BF%E7%94%A8%E4%B8%80%E8%87%B4%E6%80%A7%E5%93%88%E5%B8%8C%E5%AE%9E%E7%8E%B0%E5%8A%A8%E6%80%81%E6%89%A9%E5%AE%B9%E7%BC%A9%E5%AE%B9)
##### [37、分布式Redis.是前期做还是后期规模上来了再做好?为什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#37%E5%88%86%E5%B8%83%E5%BC%8F-redis-%E6%98%AF%E5%89%8D%E6%9C%9F%E5%81%9A%E8%BF%98%E6%98%AF%E5%90%8E%E6%9C%9F%E8%A7%84%E6%A8%A1%E4%B8%8A%E6%9D%A5%E4%BA%86%E5%86%8D%E5%81%9A%E5%A5%BD%E4%B8%BA%E4%BB%80%E4%B9%88)
##### [38、Twemproxy是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#38twemproxy-%E6%98%AF%E4%BB%80%E4%B9%88)
##### [39、支持一致性哈希的客户端有哪些?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#39%E6%94%AF%E6%8C%81%E4%B8%80%E8%87%B4%E6%80%A7%E5%93%88%E5%B8%8C%E7%9A%84%E5%AE%A2%E6%88%B7%E7%AB%AF%E6%9C%89%E5%93%AA%E4%BA%9B)
##### [40、Redis与其他 key-value存储有什么不同?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#40redis-%E4%B8%8E%E5%85%B6%E4%BB%96-key-value-%E5%AD%98%E5%82%A8%E6%9C%89%E4%BB%80%E4%B9%88%E4%B8%8D%E5%90%8C)
##### [41、Redis的内存占用情况怎么样?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#41redis-%E7%9A%84%E5%86%85%E5%AD%98%E5%8D%A0%E7%94%A8%E6%83%85%E5%86%B5%E6%80%8E%E4%B9%88%E6%A0%B7)
##### [42、都有哪些办法可以降低Redis的内存使用情况呢?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#42%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8A%9E%E6%B3%95%E5%8F%AF%E4%BB%A5%E9%99%8D%E4%BD%8E-redis-%E7%9A%84%E5%86%85%E5%AD%98%E4%BD%BF%E7%94%A8%E6%83%85%E5%86%B5%E5%91%A2)
##### [43、查看Redis使用情况及状态信息用什么命令?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#43%E6%9F%A5%E7%9C%8B-redis-%E4%BD%BF%E7%94%A8%E6%83%85%E5%86%B5%E5%8F%8A%E7%8A%B6%E6%80%81%E4%BF%A1%E6%81%AF%E7%94%A8%E4%BB%80%E4%B9%88%E5%91%BD%E4%BB%A4)
##### [44、Redis 的内存用完了会发生什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#44redis-%E7%9A%84%E5%86%85%E5%AD%98%E7%94%A8%E5%AE%8C%E4%BA%86%E4%BC%9A%E5%8F%91%E7%94%9F%E4%BB%80%E4%B9%88)
##### [45、Redis是单线程的，如何提高多核CPU的利用率?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#45redis-%E6%98%AF%E5%8D%95%E7%BA%BF%E7%A8%8B%E7%9A%84%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E5%A4%9A%E6%A0%B8-cpu-%E7%9A%84%E5%88%A9%E7%94%A8%E7%8E%87)
##### [46、一个 Redis 实例最多能存放多少的keys？List、Set、Sorted Set 他们最多能存放多少元素？](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#46%E4%B8%80%E4%B8%AA-redis-%E5%AE%9E%E4%BE%8B%E6%9C%80%E5%A4%9A%E8%83%BD%E5%AD%98%E6%94%BE%E5%A4%9A%E5%B0%91%E7%9A%84keyslistsetsorted-set-%E4%BB%96%E4%BB%AC%E6%9C%80%E5%A4%9A%E8%83%BD%E5%AD%98%E6%94%BE%E5%A4%9A%E5%B0%91%E5%85%83%E7%B4%A0)
##### [47、Redis 常见性能问题和解决方案?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#47redis-%E5%B8%B8%E8%A7%81%E6%80%A7%E8%83%BD%E9%97%AE%E9%A2%98%E5%92%8C%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88)
##### [48、Redis提供了哪几种持久化方式?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#48redis-%E6%8F%90%E4%BE%9B%E4%BA%86%E5%93%AA%E5%87%A0%E7%A7%8D%E6%8C%81%E4%B9%85%E5%8C%96%E6%96%B9%E5%BC%8F)
##### [49、如何选择合适的持久化方式?](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#49%E5%A6%82%E4%BD%95%E9%80%89%E6%8B%A9%E5%90%88%E9%80%82%E7%9A%84%E6%8C%81%E4%B9%85%E5%8C%96%E6%96%B9%E5%BC%8F)
##### [50、修改配置不重启 Redis 会实时生效吗？](https://github.com/0voice/campus_recruitmen_questions/blob/main/redis/1~50Redis%E9%9D%A2%E8%AF%95%E9%A2%98.md#50%E4%BF%AE%E6%94%B9%E9%85%8D%E7%BD%AE%E4%B8%8D%E9%87%8D%E5%90%AF-redis-%E4%BC%9A%E5%AE%9E%E6%97%B6%E7%94%9F%E6%95%88%E5%90%97)

<br>

<h3 id="6">:airplane: nginx</h3> 

---
##### [1、请解释一下什么是Nginx?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#1%E8%AF%B7%E8%A7%A3%E9%87%8A%E4%B8%80%E4%B8%8B%E4%BB%80%E4%B9%88%E6%98%AFnginx)
##### [2、请列举Nginx的一些特性。](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#2%E8%AF%B7%E5%88%97%E4%B8%BEnginx%E7%9A%84%E4%B8%80%E4%BA%9B%E7%89%B9%E6%80%A7)
##### [3、请列举Nginx和Apache之间的不同点。](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#3%E8%AF%B7%E5%88%97%E4%B8%BEnginx%E5%92%8Capache%E4%B9%8B%E9%97%B4%E7%9A%84%E4%B8%8D%E5%90%8C%E7%82%B9)
##### [4、请解释Nginx如何处理HTTP请求。](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#4%E8%AF%B7%E8%A7%A3%E9%87%8Anginx%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86http%E8%AF%B7%E6%B1%82)
##### [5、在Nginx中，如何使用未定义的服务器名称来阻止处理请求?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#5%E5%9C%A8nginx%E4%B8%AD%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8%E6%9C%AA%E5%AE%9A%E4%B9%89%E7%9A%84%E6%9C%8D%E5%8A%A1%E5%99%A8%E5%90%8D%E7%A7%B0%E6%9D%A5%E9%98%BB%E6%AD%A2%E5%A4%84%E7%90%86%E8%AF%B7%E6%B1%82)
##### [6、使用“反向代理服务器”的优点是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#6-%E4%BD%BF%E7%94%A8%E5%8F%8D%E5%90%91%E4%BB%A3%E7%90%86%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%9A%84%E4%BC%98%E7%82%B9%E6%98%AF%E4%BB%80%E4%B9%88)
##### [7、请列举Nginx服务器的最佳用途。](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#7%E8%AF%B7%E5%88%97%E4%B8%BEnginx%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E7%94%A8%E9%80%94)
##### [8、请解释Nginx服务器上的Master和Worker进程分别是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#8%E8%AF%B7%E8%A7%A3%E9%87%8Anginx%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E7%9A%84master%E5%92%8Cworker%E8%BF%9B%E7%A8%8B%E5%88%86%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88)
##### [9、请解释你如何通过不同于80的端口开启Nginx?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#9%E8%AF%B7%E8%A7%A3%E9%87%8A%E4%BD%A0%E5%A6%82%E4%BD%95%E9%80%9A%E8%BF%87%E4%B8%8D%E5%90%8C%E4%BA%8E80%E7%9A%84%E7%AB%AF%E5%8F%A3%E5%BC%80%E5%90%AFnginx)
##### [10、请解释是否有可能将Nginx的错误替换为502错误、503?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#10%E8%AF%B7%E8%A7%A3%E9%87%8A%E6%98%AF%E5%90%A6%E6%9C%89%E5%8F%AF%E8%83%BD%E5%B0%86nginx%E7%9A%84%E9%94%99%E8%AF%AF%E6%9B%BF%E6%8D%A2%E4%B8%BA502%E9%94%99%E8%AF%AF503)
##### [11、在Nginx中，解释如何在URL中保留双斜线?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#11%E5%9C%A8nginx%E4%B8%AD%E8%A7%A3%E9%87%8A%E5%A6%82%E4%BD%95%E5%9C%A8url%E4%B8%AD%E4%BF%9D%E7%95%99%E5%8F%8C%E6%96%9C%E7%BA%BF)
##### [12、请解释ngx_http_upstream_module的作用是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#12%E8%AF%B7%E8%A7%A3%E9%87%8Angx_http_upstream_module%E7%9A%84%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)
##### [13、请解释什么是C10K问题?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#13%E8%AF%B7%E8%A7%A3%E9%87%8A%E4%BB%80%E4%B9%88%E6%98%AFc10k%E9%97%AE%E9%A2%98)
##### [14、请陈述stub_status和sub_filter指令的作用是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#14%E8%AF%B7%E9%99%88%E8%BF%B0stub_status%E5%92%8Csub_filter%E6%8C%87%E4%BB%A4%E7%9A%84%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)
##### [15、解释Nginx是否支持将请求压缩到上游?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#15%E8%A7%A3%E9%87%8Anginx%E6%98%AF%E5%90%A6%E6%94%AF%E6%8C%81%E5%B0%86%E8%AF%B7%E6%B1%82%E5%8E%8B%E7%BC%A9%E5%88%B0%E4%B8%8A%E6%B8%B8)
##### [16、解释如何在Nginx中获得当前的时间?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#16%E8%A7%A3%E9%87%8A%E5%A6%82%E4%BD%95%E5%9C%A8nginx%E4%B8%AD%E8%8E%B7%E5%BE%97%E5%BD%93%E5%89%8D%E7%9A%84%E6%97%B6%E9%97%B4)
##### [17、用Nginx服务器解释-s的目的是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#17%E7%94%A8nginx%E6%9C%8D%E5%8A%A1%E5%99%A8%E8%A7%A3%E9%87%8A-s%E7%9A%84%E7%9B%AE%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88)
##### [18、解释如何在Nginx服务器上添加模块?](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#18%E8%A7%A3%E9%87%8A%E5%A6%82%E4%BD%95%E5%9C%A8nginx%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E6%B7%BB%E5%8A%A0%E6%A8%A1%E5%9D%97)
##### [19、什么是Nginx？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#19%E4%BB%80%E4%B9%88%E6%98%AFnginx)
##### [20、为什么使用nginx](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#20%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BD%BF%E7%94%A8nginx)
##### [21、为什么nginx性能这么高](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#21%E4%B8%BA%E4%BB%80%E4%B9%88nginx%E6%80%A7%E8%83%BD%E8%BF%99%E4%B9%88%E9%AB%98)
##### [22、nginx的负载均衡算法都要哪些？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#22nginx%E7%9A%84%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E7%AE%97%E6%B3%95%E9%83%BD%E8%A6%81%E5%93%AA%E4%BA%9B)
##### [23、nginx的upstream中的ip_hash和url_hash的区别和特点。](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#23nginx%E7%9A%84upstream%E4%B8%AD%E7%9A%84ip_hash%E5%92%8Curl_hash%E7%9A%84%E5%8C%BA%E5%88%AB%E5%92%8C%E7%89%B9%E7%82%B9)
##### [24、什么是正向代理和反向代理](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#24%E4%BB%80%E4%B9%88%E6%98%AF%E6%AD%A3%E5%90%91%E4%BB%A3%E7%90%86%E5%92%8C%E5%8F%8D%E5%90%91%E4%BB%A3%E7%90%86)
##### [25、动态资源，静态资源分离？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#25%E5%8A%A8%E6%80%81%E8%B5%84%E6%BA%90%E9%9D%99%E6%80%81%E8%B5%84%E6%BA%90%E5%88%86%E7%A6%BB)
##### [26、为什么要做动静分离？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#26%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E5%81%9A%E5%8A%A8%E9%9D%99%E5%88%86%E7%A6%BB)
##### [27、生产中如何设置worker进程的数量呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#27%E7%94%9F%E4%BA%A7%E4%B8%AD%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AEworker%E8%BF%9B%E7%A8%8B%E7%9A%84%E6%95%B0%E9%87%8F%E5%91%A2)
##### [28、Last-Modified,Expires,Max-age,Etag他们的含义，作用于浏览器端的是那些？作用于服务端的是那些？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#28last-modifiedexpiresmax-ageetag%E4%BB%96%E4%BB%AC%E7%9A%84%E5%90%AB%E4%B9%89%E4%BD%9C%E7%94%A8%E4%BA%8E%E6%B5%8F%E8%A7%88%E5%99%A8%E7%AB%AF%E7%9A%84%E6%98%AF%E9%82%A3%E4%BA%9B%E4%BD%9C%E7%94%A8%E4%BA%8E%E6%9C%8D%E5%8A%A1%E7%AB%AF%E7%9A%84%E6%98%AF%E9%82%A3%E4%BA%9B)
##### [29、为什么nginx不使用多线程？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#29%E4%B8%BA%E4%BB%80%E4%B9%88nginx%E4%B8%8D%E4%BD%BF%E7%94%A8%E5%A4%9A%E7%BA%BF%E7%A8%8B)
##### [30、nginx常见的优化配置有哪些？](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#30nginx%E5%B8%B8%E8%A7%81%E7%9A%84%E4%BC%98%E5%8C%96%E9%85%8D%E7%BD%AE%E6%9C%89%E5%93%AA%E4%BA%9B)
##### [31、nginx常用模块](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#31nginx%E5%B8%B8%E7%94%A8%E6%A8%A1%E5%9D%97)
##### [32、location匹配的优先级别](https://github.com/0voice/campus_recruitmen_questions/blob/main/nginx/1~32%20Nginx%E9%9D%A2%E8%AF%95%E9%A2%98.md#32location%E5%8C%B9%E9%85%8D%E7%9A%84%E4%BC%98%E5%85%88%E7%BA%A7%E5%88%AB)

<br>

<h3 id="7">:loudspeaker: 语言语法</h3> 

---
##### [1、new、delete、malloc、free关系](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#1newdeletemallocfree%E5%85%B3%E7%B3%BB)
##### [2、delete与 delete()区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#2delete%E4%B8%8E-delete-%E5%8C%BA%E5%88%AB)
##### [3、C和C++的共同点？不同之处？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#3c%E5%92%8Cc%E7%9A%84%E5%85%B1%E5%90%8C%E7%82%B9%E4%B8%8D%E5%90%8C%E4%B9%8B%E5%A4%84)
##### [4、继承的优缺点](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#4%E7%BB%A7%E6%89%BF%E7%9A%84%E4%BC%98%E7%BC%BA%E7%82%B9)
##### [5、C++有哪些性质（面向对象特点）](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#5c%E6%9C%89%E5%93%AA%E4%BA%9B%E6%80%A7%E8%B4%A8%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%89%B9%E7%82%B9)
##### [6、子类析构时要调用父类的析构函数吗？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#6%E5%AD%90%E7%B1%BB%E6%9E%90%E6%9E%84%E6%97%B6%E8%A6%81%E8%B0%83%E7%94%A8%E7%88%B6%E7%B1%BB%E7%9A%84%E6%9E%90%E6%9E%84%E5%87%BD%E6%95%B0%E5%90%97)
##### [7、多态，虚函数，纯虚函数](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#7%E5%A4%9A%E6%80%81%E8%99%9A%E5%87%BD%E6%95%B0%E7%BA%AF%E8%99%9A%E5%87%BD%E6%95%B0)
##### [8、什么是“引用”？申明和使用“引用”要注意哪些问题？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#8%E4%BB%80%E4%B9%88%E6%98%AF%E5%BC%95%E7%94%A8%E7%94%B3%E6%98%8E%E5%92%8C%E4%BD%BF%E7%94%A8%E5%BC%95%E7%94%A8%E8%A6%81%E6%B3%A8%E6%84%8F%E5%93%AA%E4%BA%9B%E9%97%AE%E9%A2%98)
##### [9、将“引用”作为函数参数有哪些特点？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#9%E5%B0%86%E5%BC%95%E7%94%A8%E4%BD%9C%E4%B8%BA%E5%87%BD%E6%95%B0%E5%8F%82%E6%95%B0%E6%9C%89%E5%93%AA%E4%BA%9B%E7%89%B9%E7%82%B9)
##### [10、在什么时候需要使用“常引用”？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#10%E5%9C%A8%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%9C%80%E8%A6%81%E4%BD%BF%E7%94%A8%E5%B8%B8%E5%BC%95%E7%94%A8)
##### [11、将“引用”作为函数返回值类型的格式的好处和需要遵守的规则?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#11%E5%B0%86%E5%BC%95%E7%94%A8%E4%BD%9C%E4%B8%BA%E5%87%BD%E6%95%B0%E8%BF%94%E5%9B%9E%E5%80%BC%E7%B1%BB%E5%9E%8B%E7%9A%84%E6%A0%BC%E5%BC%8F%E7%9A%84%E5%A5%BD%E5%A4%84%E5%92%8C%E9%9C%80%E8%A6%81%E9%81%B5%E5%AE%88%E7%9A%84%E8%A7%84%E5%88%99)
##### [12、“引用”与多态的关系？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#12%E5%BC%95%E7%94%A8%E4%B8%8E%E5%A4%9A%E6%80%81%E7%9A%84%E5%85%B3%E7%B3%BB)
##### [13、“引用”与指针的区别是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#13%E5%BC%95%E7%94%A8%E4%B8%8E%E6%8C%87%E9%92%88%E7%9A%84%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88)
##### [14、什么时候需要“引用”？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#14%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E9%9C%80%E8%A6%81%E5%BC%95%E7%94%A8)
##### [15、结构与联合有和区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#15%E7%BB%93%E6%9E%84%E4%B8%8E%E8%81%94%E5%90%88%E6%9C%89%E5%92%8C%E5%8C%BA%E5%88%AB)
##### [16、关联、聚合(Aggregation)以及组合(Composition)的区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#16%E5%85%B3%E8%81%94%E8%81%9A%E5%90%88aggregation%E4%BB%A5%E5%8F%8A%E7%BB%84%E5%90%88composition%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [17、面向对象的三个基本特征，并简单叙述之？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#17%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%9A%84%E4%B8%89%E4%B8%AA%E5%9F%BA%E6%9C%AC%E7%89%B9%E5%BE%81%E5%B9%B6%E7%AE%80%E5%8D%95%E5%8F%99%E8%BF%B0%E4%B9%8B)
##### [18、重载（overload)和重写(overried，有的书也叫做“覆盖”）的区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#18%E9%87%8D%E8%BD%BDoverload%E5%92%8C%E9%87%8D%E5%86%99overried%E6%9C%89%E7%9A%84%E4%B9%A6%E4%B9%9F%E5%8F%AB%E5%81%9A%E8%A6%86%E7%9B%96%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [19、多态的作用？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#19%E5%A4%9A%E6%80%81%E7%9A%84%E4%BD%9C%E7%94%A8)
##### [20、Ado与Ado.net的相同与不同？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#20ado%E4%B8%8Eadonet%E7%9A%84%E7%9B%B8%E5%90%8C%E4%B8%8E%E4%B8%8D%E5%90%8C)
##### [21、New delete 与malloc free 的联系与区别?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#21new-delete-%E4%B8%8Emalloc-free-%E7%9A%84%E8%81%94%E7%B3%BB%E4%B8%8E%E5%8C%BA%E5%88%AB)
##### [22、#define DOUBLE(x) x+x ，i = 5*DOUBLE(5)； i 是多少？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#22define-doublex-xx-i--5double5-i-%E6%98%AF%E5%A4%9A%E5%B0%91)
##### [23、有哪几种情况只能用intialization list 而不能用assignment?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#23%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E6%83%85%E5%86%B5%E5%8F%AA%E8%83%BD%E7%94%A8intialization-list-%E8%80%8C%E4%B8%8D%E8%83%BD%E7%94%A8assignment)
##### [24、C++是不是类型安全的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#24c%E6%98%AF%E4%B8%8D%E6%98%AF%E7%B1%BB%E5%9E%8B%E5%AE%89%E5%85%A8%E7%9A%84)
##### [25、main 函数执行以前，还会执行什么代码？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#25main-%E5%87%BD%E6%95%B0%E6%89%A7%E8%A1%8C%E4%BB%A5%E5%89%8D%E8%BF%98%E4%BC%9A%E6%89%A7%E8%A1%8C%E4%BB%80%E4%B9%88%E4%BB%A3%E7%A0%81)
##### [26、描述内存分配方式以及它们的区别?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#26%E6%8F%8F%E8%BF%B0%E5%86%85%E5%AD%98%E5%88%86%E9%85%8D%E6%96%B9%E5%BC%8F%E4%BB%A5%E5%8F%8A%E5%AE%83%E4%BB%AC%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [27、struct 和 class 的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#27struct-%E5%92%8C-class-%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [28、当一个类A 中没有任何成员变量与成员函数,这时sizeof(A)的值是多少？如果不是零，请解释一下编译器为什么没有让它为零。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#28%E5%BD%93%E4%B8%80%E4%B8%AA%E7%B1%BBa-%E4%B8%AD%E6%B2%A1%E6%9C%89%E4%BB%BB%E4%BD%95%E6%88%90%E5%91%98%E5%8F%98%E9%87%8F%E4%B8%8E%E6%88%90%E5%91%98%E5%87%BD%E6%95%B0%E8%BF%99%E6%97%B6sizeofa%E7%9A%84%E5%80%BC%E6%98%AF%E5%A4%9A%E5%B0%91%E5%A6%82%E6%9E%9C%E4%B8%8D%E6%98%AF%E9%9B%B6%E8%AF%B7%E8%A7%A3%E9%87%8A%E4%B8%80%E4%B8%8B%E7%BC%96%E8%AF%91%E5%99%A8%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E6%9C%89%E8%AE%A9%E5%AE%83%E4%B8%BA%E9%9B%B6)
##### [29、在8086 汇编下，逻辑地址和物理地址是怎样转换的？（Intel）](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#29%E5%9C%A88086-%E6%B1%87%E7%BC%96%E4%B8%8B%E9%80%BB%E8%BE%91%E5%9C%B0%E5%9D%80%E5%92%8C%E7%89%A9%E7%90%86%E5%9C%B0%E5%9D%80%E6%98%AF%E6%80%8E%E6%A0%B7%E8%BD%AC%E6%8D%A2%E7%9A%84intel)
##### [30、比较C++中的4种类型转换方式？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#30%E6%AF%94%E8%BE%83c%E4%B8%AD%E7%9A%844%E7%A7%8D%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2%E6%96%B9%E5%BC%8F)
##### [31、分别写出BOOL,int,float,指针类型的变量a 与“零”的比较语句。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#31%E5%88%86%E5%88%AB%E5%86%99%E5%87%BAboolintfloat%E6%8C%87%E9%92%88%E7%B1%BB%E5%9E%8B%E7%9A%84%E5%8F%98%E9%87%8Fa-%E4%B8%8E%E9%9B%B6%E7%9A%84%E6%AF%94%E8%BE%83%E8%AF%AD%E5%8F%A5)
##### [32、请说出const与#define 相比，有何优点？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#32%E8%AF%B7%E8%AF%B4%E5%87%BAconst%E4%B8%8Edefine-%E7%9B%B8%E6%AF%94%E6%9C%89%E4%BD%95%E4%BC%98%E7%82%B9)
##### [33、简述数组与指针的区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#33%E7%AE%80%E8%BF%B0%E6%95%B0%E7%BB%84%E4%B8%8E%E6%8C%87%E9%92%88%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [34、类成员函数的重载、覆盖和隐藏区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#34%E7%B1%BB%E6%88%90%E5%91%98%E5%87%BD%E6%95%B0%E7%9A%84%E9%87%8D%E8%BD%BD%E8%A6%86%E7%9B%96%E5%92%8C%E9%9A%90%E8%97%8F%E5%8C%BA%E5%88%AB)
##### [35、求出两个数中的较大者](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#35%E6%B1%82%E5%87%BA%E4%B8%A4%E4%B8%AA%E6%95%B0%E4%B8%AD%E7%9A%84%E8%BE%83%E5%A4%A7%E8%80%85)
##### [36、如何打印出当前源文件的文件名以及源文件的当前行号？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#36%E5%A6%82%E4%BD%95%E6%89%93%E5%8D%B0%E5%87%BA%E5%BD%93%E5%89%8D%E6%BA%90%E6%96%87%E4%BB%B6%E7%9A%84%E6%96%87%E4%BB%B6%E5%90%8D%E4%BB%A5%E5%8F%8A%E6%BA%90%E6%96%87%E4%BB%B6%E7%9A%84%E5%BD%93%E5%89%8D%E8%A1%8C%E5%8F%B7)
##### [37、main主函数执行完毕后，是否可能会再执行一段代码，给出说明？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#37main%E4%B8%BB%E5%87%BD%E6%95%B0%E6%89%A7%E8%A1%8C%E5%AE%8C%E6%AF%95%E5%90%8E%E6%98%AF%E5%90%A6%E5%8F%AF%E8%83%BD%E4%BC%9A%E5%86%8D%E6%89%A7%E8%A1%8C%E4%B8%80%E6%AE%B5%E4%BB%A3%E7%A0%81%E7%BB%99%E5%87%BA%E8%AF%B4%E6%98%8E)
##### [38、如何判断一段程序是由C 编译程序还是由C++编译程序编译的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#38%E5%A6%82%E4%BD%95%E5%88%A4%E6%96%AD%E4%B8%80%E6%AE%B5%E7%A8%8B%E5%BA%8F%E6%98%AF%E7%94%B1c-%E7%BC%96%E8%AF%91%E7%A8%8B%E5%BA%8F%E8%BF%98%E6%98%AF%E7%94%B1c%E7%BC%96%E8%AF%91%E7%A8%8B%E5%BA%8F%E7%BC%96%E8%AF%91%E7%9A%84)
##### [39、文件中有一组整数，要求排序后输出到另一个文件中](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#39%E6%96%87%E4%BB%B6%E4%B8%AD%E6%9C%89%E4%B8%80%E7%BB%84%E6%95%B4%E6%95%B0%E8%A6%81%E6%B1%82%E6%8E%92%E5%BA%8F%E5%90%8E%E8%BE%93%E5%87%BA%E5%88%B0%E5%8F%A6%E4%B8%80%E4%B8%AA%E6%96%87%E4%BB%B6%E4%B8%AD)
##### [40、请你详细地解释一下IP协议的定义，在哪个层上面？主要有什么作用？TCP与UDP呢 ？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#40%E8%AF%B7%E4%BD%A0%E8%AF%A6%E7%BB%86%E5%9C%B0%E8%A7%A3%E9%87%8A%E4%B8%80%E4%B8%8Bip%E5%8D%8F%E8%AE%AE%E7%9A%84%E5%AE%9A%E4%B9%89%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B1%82%E4%B8%8A%E9%9D%A2%E4%B8%BB%E8%A6%81%E6%9C%89%E4%BB%80%E4%B9%88%E4%BD%9C%E7%94%A8tcp%E4%B8%8Eudp%E5%91%A2-)
##### [41、请问交换机和路由器各自的实现原理是什么？分别在哪个层次上面实现的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#41%E8%AF%B7%E9%97%AE%E4%BA%A4%E6%8D%A2%E6%9C%BA%E5%92%8C%E8%B7%AF%E7%94%B1%E5%99%A8%E5%90%84%E8%87%AA%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86%E6%98%AF%E4%BB%80%E4%B9%88%E5%88%86%E5%88%AB%E5%9C%A8%E5%93%AA%E4%B8%AA%E5%B1%82%E6%AC%A1%E4%B8%8A%E9%9D%A2%E5%AE%9E%E7%8E%B0%E7%9A%84)
##### [42、全局变量和局部变量有什么区别？是怎么实现的？操作系统和编译器是怎么知道的 ？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#42%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E5%92%8C%E5%B1%80%E9%83%A8%E5%8F%98%E9%87%8F%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%E6%98%AF%E6%80%8E%E4%B9%88%E5%AE%9E%E7%8E%B0%E7%9A%84%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E5%92%8C%E7%BC%96%E8%AF%91%E5%99%A8%E6%98%AF%E6%80%8E%E4%B9%88%E7%9F%A5%E9%81%93%E7%9A%84-)
##### [43、8086是多少位的系统？在数据总线上是怎么实现的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#438086%E6%98%AF%E5%A4%9A%E5%B0%91%E4%BD%8D%E7%9A%84%E7%B3%BB%E7%BB%9F%E5%9C%A8%E6%95%B0%E6%8D%AE%E6%80%BB%E7%BA%BF%E4%B8%8A%E6%98%AF%E6%80%8E%E4%B9%88%E5%AE%9E%E7%8E%B0%E7%9A%84)
##### [44、解释局部变量、全局变量和静态变量的含义。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#44%E8%A7%A3%E9%87%8A%E5%B1%80%E9%83%A8%E5%8F%98%E9%87%8F%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E5%92%8C%E9%9D%99%E6%80%81%E5%8F%98%E9%87%8F%E7%9A%84%E5%90%AB%E4%B9%89)
##### [45、论述含参数的宏与函数的优缺点。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#45%E8%AE%BA%E8%BF%B0%E5%90%AB%E5%8F%82%E6%95%B0%E7%9A%84%E5%AE%8F%E4%B8%8E%E5%87%BD%E6%95%B0%E7%9A%84%E4%BC%98%E7%BC%BA%E7%82%B9)
##### [46、C++里面是不是所有的动作都是main()引起的？如果不是，请举例。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#46c%E9%87%8C%E9%9D%A2%E6%98%AF%E4%B8%8D%E6%98%AF%E6%89%80%E6%9C%89%E7%9A%84%E5%8A%A8%E4%BD%9C%E9%83%BD%E6%98%AFmain%E5%BC%95%E8%B5%B7%E7%9A%84%E5%A6%82%E6%9E%9C%E4%B8%8D%E6%98%AF%E8%AF%B7%E4%B8%BE%E4%BE%8B)
##### [47、如何定义和实现一个类的成员函数为回调函数？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#47%E5%A6%82%E4%BD%95%E5%AE%9A%E4%B9%89%E5%92%8C%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E7%B1%BB%E7%9A%84%E6%88%90%E5%91%98%E5%87%BD%E6%95%B0%E4%B8%BA%E5%9B%9E%E8%B0%83%E5%87%BD%E6%95%B0)
##### [48、解释堆和栈的区别。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#48%E8%A7%A3%E9%87%8A%E5%A0%86%E5%92%8C%E6%A0%88%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [49、C++里面如何声明const void f(void)函数为C程序中的库函数？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#49c%E9%87%8C%E9%9D%A2%E5%A6%82%E4%BD%95%E5%A3%B0%E6%98%8Econst-void-fvoid%E5%87%BD%E6%95%B0%E4%B8%BAc%E7%A8%8B%E5%BA%8F%E4%B8%AD%E7%9A%84%E5%BA%93%E5%87%BD%E6%95%B0)
##### [50、内联函数在编译时是否做参数类型检查？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#50%E5%86%85%E8%81%94%E5%87%BD%E6%95%B0%E5%9C%A8%E7%BC%96%E8%AF%91%E6%97%B6%E6%98%AF%E5%90%A6%E5%81%9A%E5%8F%82%E6%95%B0%E7%B1%BB%E5%9E%8B%E6%A3%80%E6%9F%A5)
##### [51、static有什么用途？（请至少说明两种）](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#51static%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8%E9%80%94%E8%AF%B7%E8%87%B3%E5%B0%91%E8%AF%B4%E6%98%8E%E4%B8%A4%E7%A7%8D)
##### [52、引用与指针有什么区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#52%E5%BC%95%E7%94%A8%E4%B8%8E%E6%8C%87%E9%92%88%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
##### [53、描述实时系统的基本特性](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#53%E6%8F%8F%E8%BF%B0%E5%AE%9E%E6%97%B6%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%9F%BA%E6%9C%AC%E7%89%B9%E6%80%A7)
##### [54、全局变量和局部变量在内存中是否有区别？如果有，是什么区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#54%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E5%92%8C%E5%B1%80%E9%83%A8%E5%8F%98%E9%87%8F%E5%9C%A8%E5%86%85%E5%AD%98%E4%B8%AD%E6%98%AF%E5%90%A6%E6%9C%89%E5%8C%BA%E5%88%AB%E5%A6%82%E6%9E%9C%E6%9C%89%E6%98%AF%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
##### [55、什么是平衡二叉树？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#55%E4%BB%80%E4%B9%88%E6%98%AF%E5%B9%B3%E8%A1%A1%E4%BA%8C%E5%8F%89%E6%A0%91)
##### [56、堆栈溢出一般是由什么原因导致的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#56%E5%A0%86%E6%A0%88%E6%BA%A2%E5%87%BA%E4%B8%80%E8%88%AC%E6%98%AF%E7%94%B1%E4%BB%80%E4%B9%88%E5%8E%9F%E5%9B%A0%E5%AF%BC%E8%87%B4%E7%9A%84)
##### [57、什么函数不能声明为虚函数？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#57%E4%BB%80%E4%B9%88%E5%87%BD%E6%95%B0%E4%B8%8D%E8%83%BD%E5%A3%B0%E6%98%8E%E4%B8%BA%E8%99%9A%E5%87%BD%E6%95%B0)
##### [58、冒泡排序算法的时间复杂度是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#58%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F%E7%AE%97%E6%B3%95%E7%9A%84%E6%97%B6%E9%97%B4%E5%A4%8D%E6%9D%82%E5%BA%A6%E6%98%AF%E4%BB%80%E4%B9%88)
##### [59、Internet采用哪种网络协议？该协议的主要层次结构？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#59internet%E9%87%87%E7%94%A8%E5%93%AA%E7%A7%8D%E7%BD%91%E7%BB%9C%E5%8D%8F%E8%AE%AE%E8%AF%A5%E5%8D%8F%E8%AE%AE%E7%9A%84%E4%B8%BB%E8%A6%81%E5%B1%82%E6%AC%A1%E7%BB%93%E6%9E%84)
##### [60、Internet物理地址和IP地址转换采用什么协议？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#60internet%E7%89%A9%E7%90%86%E5%9C%B0%E5%9D%80%E5%92%8Cip%E5%9C%B0%E5%9D%80%E8%BD%AC%E6%8D%A2%E9%87%87%E7%94%A8%E4%BB%80%E4%B9%88%E5%8D%8F%E8%AE%AE)
##### [61、IP地址的编码分为哪俩部分？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#61ip%E5%9C%B0%E5%9D%80%E7%9A%84%E7%BC%96%E7%A0%81%E5%88%86%E4%B8%BA%E5%93%AA%E4%BF%A9%E9%83%A8%E5%88%86)
##### [62、不能做switch()的参数类型是？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#62%E4%B8%8D%E8%83%BD%E5%81%9Aswitch%E7%9A%84%E5%8F%82%E6%95%B0%E7%B1%BB%E5%9E%8B%E6%98%AF)
##### [63、局部变量能否和全局变量重名？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#63%E5%B1%80%E9%83%A8%E5%8F%98%E9%87%8F%E8%83%BD%E5%90%A6%E5%92%8C%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E9%87%8D%E5%90%8D)
##### [64、如何引用一个已经定义过的全局变量？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#64%E5%A6%82%E4%BD%95%E5%BC%95%E7%94%A8%E4%B8%80%E4%B8%AA%E5%B7%B2%E7%BB%8F%E5%AE%9A%E4%B9%89%E8%BF%87%E7%9A%84%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F)
##### [65、全局变量可不可以定义在可被多个.C文件包含的头文件中？为什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#65%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E5%8F%AF%E4%B8%8D%E5%8F%AF%E4%BB%A5%E5%AE%9A%E4%B9%89%E5%9C%A8%E5%8F%AF%E8%A2%AB%E5%A4%9A%E4%B8%AAc%E6%96%87%E4%BB%B6%E5%8C%85%E5%90%AB%E7%9A%84%E5%A4%B4%E6%96%87%E4%BB%B6%E4%B8%AD%E4%B8%BA%E4%BB%80%E4%B9%88)
##### [66、语句for( ；1 ；)有什么问题？它是什么意思？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#66%E8%AF%AD%E5%8F%A5for-1-%E6%9C%89%E4%BB%80%E4%B9%88%E9%97%AE%E9%A2%98%E5%AE%83%E6%98%AF%E4%BB%80%E4%B9%88%E6%84%8F%E6%80%9D)
##### [67、do……while和while……do有什么区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#67dowhile%E5%92%8Cwhiledo%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
##### [68、static 全局变量、局部变量、函数与普通全局变量、局部变量、函数区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#68static-%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E5%B1%80%E9%83%A8%E5%8F%98%E9%87%8F%E5%87%BD%E6%95%B0%E4%B8%8E%E6%99%AE%E9%80%9A%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E5%B1%80%E9%83%A8%E5%8F%98%E9%87%8F%E5%87%BD%E6%95%B0%E5%8C%BA%E5%88%AB)
##### [69、-1,2,7,28,126请问28和126中间那个数是什么？为什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#69-12728126%E8%AF%B7%E9%97%AE28%E5%92%8C126%E4%B8%AD%E9%97%B4%E9%82%A3%E4%B8%AA%E6%95%B0%E6%98%AF%E4%BB%80%E4%B9%88%E4%B8%BA%E4%BB%80%E4%B9%88)
##### [70、用两个栈实现一个队列的功能？要求给出算法和思路！](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#70%E7%94%A8%E4%B8%A4%E4%B8%AA%E6%A0%88%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E9%98%9F%E5%88%97%E7%9A%84%E5%8A%9F%E8%83%BD%E8%A6%81%E6%B1%82%E7%BB%99%E5%87%BA%E7%AE%97%E6%B3%95%E5%92%8C%E6%80%9D%E8%B7%AF)
##### [71、在c语言库函数中将一个字符转换成整型的函数是atool()吗，这个函数的原型是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#71%E5%9C%A8c%E8%AF%AD%E8%A8%80%E5%BA%93%E5%87%BD%E6%95%B0%E4%B8%AD%E5%B0%86%E4%B8%80%E4%B8%AA%E5%AD%97%E7%AC%A6%E8%BD%AC%E6%8D%A2%E6%88%90%E6%95%B4%E5%9E%8B%E7%9A%84%E5%87%BD%E6%95%B0%E6%98%AFatool%E5%90%97%E8%BF%99%E4%B8%AA%E5%87%BD%E6%95%B0%E7%9A%84%E5%8E%9F%E5%9E%8B%E6%98%AF%E4%BB%80%E4%B9%88)
##### [72、对于一个频繁使用的短小函数,在C语言中应用什么实现,在C++中应用什么实现?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#72%E5%AF%B9%E4%BA%8E%E4%B8%80%E4%B8%AA%E9%A2%91%E7%B9%81%E4%BD%BF%E7%94%A8%E7%9A%84%E7%9F%AD%E5%B0%8F%E5%87%BD%E6%95%B0%E5%9C%A8c%E8%AF%AD%E8%A8%80%E4%B8%AD%E5%BA%94%E7%94%A8%E4%BB%80%E4%B9%88%E5%AE%9E%E7%8E%B0%E5%9C%A8c%E4%B8%AD%E5%BA%94%E7%94%A8%E4%BB%80%E4%B9%88%E5%AE%9E%E7%8E%B0)
##### [73、用预处理指令#define 声明一个常数，用以表明1年中有多少秒（忽略闰年问题）](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#73%E7%94%A8%E9%A2%84%E5%A4%84%E7%90%86%E6%8C%87%E4%BB%A4define-%E5%A3%B0%E6%98%8E%E4%B8%80%E4%B8%AA%E5%B8%B8%E6%95%B0%E7%94%A8%E4%BB%A5%E8%A1%A8%E6%98%8E1%E5%B9%B4%E4%B8%AD%E6%9C%89%E5%A4%9A%E5%B0%91%E7%A7%92%E5%BF%BD%E7%95%A5%E9%97%B0%E5%B9%B4%E9%97%AE%E9%A2%98)
##### [74、写一个“标准”宏MIN，这个宏输入两个参数并返回较小的一个。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#74%E5%86%99%E4%B8%80%E4%B8%AA%E6%A0%87%E5%87%86%E5%AE%8Fmin%E8%BF%99%E4%B8%AA%E5%AE%8F%E8%BE%93%E5%85%A5%E4%B8%A4%E4%B8%AA%E5%8F%82%E6%95%B0%E5%B9%B6%E8%BF%94%E5%9B%9E%E8%BE%83%E5%B0%8F%E7%9A%84%E4%B8%80%E4%B8%AA)
##### [75、预处理器标识#error的目的是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#75%E9%A2%84%E5%A4%84%E7%90%86%E5%99%A8%E6%A0%87%E8%AF%86error%E7%9A%84%E7%9B%AE%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88)
##### [76、嵌入式系统中经常要用到无限循环，你怎么样用C编写死循环呢？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#76%E5%B5%8C%E5%85%A5%E5%BC%8F%E7%B3%BB%E7%BB%9F%E4%B8%AD%E7%BB%8F%E5%B8%B8%E8%A6%81%E7%94%A8%E5%88%B0%E6%97%A0%E9%99%90%E5%BE%AA%E7%8E%AF%E4%BD%A0%E6%80%8E%E4%B9%88%E6%A0%B7%E7%94%A8c%E7%BC%96%E5%86%99%E6%AD%BB%E5%BE%AA%E7%8E%AF%E5%91%A2)
##### [77、关键字static的作用是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#77%E5%85%B3%E9%94%AE%E5%AD%97static%E7%9A%84%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88)
##### [78、关键字const是什么含意？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#78%E5%85%B3%E9%94%AE%E5%AD%97const%E6%98%AF%E4%BB%80%E4%B9%88%E5%90%AB%E6%84%8F)
##### [79、关键字volatile有什么含意 并给出三个不同的例子。](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#79%E5%85%B3%E9%94%AE%E5%AD%97volatile%E6%9C%89%E4%BB%80%E4%B9%88%E5%90%AB%E6%84%8F-%E5%B9%B6%E7%BB%99%E5%87%BA%E4%B8%89%E4%B8%AA%E4%B8%8D%E5%90%8C%E7%9A%84%E4%BE%8B%E5%AD%90)
##### [80、ASDL使用的是什么协议？并进行简单描述？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#80asdl%E4%BD%BF%E7%94%A8%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%E5%8D%8F%E8%AE%AE%E5%B9%B6%E8%BF%9B%E8%A1%8C%E7%AE%80%E5%8D%95%E6%8F%8F%E8%BF%B0)
##### [81、什么是预编译,何时需要预编译?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#81%E4%BB%80%E4%B9%88%E6%98%AF%E9%A2%84%E7%BC%96%E8%AF%91%E4%BD%95%E6%97%B6%E9%9C%80%E8%A6%81%E9%A2%84%E7%BC%96%E8%AF%91)
##### [82、Itearator各指针的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#82itearator%E5%90%84%E6%8C%87%E9%92%88%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [83、C++中的class和struct的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#83c%E4%B8%AD%E7%9A%84class%E5%92%8Cstruct%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [84、关系模型的基本概念](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#84%E5%85%B3%E7%B3%BB%E6%A8%A1%E5%9E%8B%E7%9A%84%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5)
##### [85、C语言中结构化程序设计的三种基本控制结构](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#85c%E8%AF%AD%E8%A8%80%E4%B8%AD%E7%BB%93%E6%9E%84%E5%8C%96%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1%E7%9A%84%E4%B8%89%E7%A7%8D%E5%9F%BA%E6%9C%AC%E6%8E%A7%E5%88%B6%E7%BB%93%E6%9E%84)
##### [86、三种基本的数据模型](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#86%E4%B8%89%E7%A7%8D%E5%9F%BA%E6%9C%AC%E7%9A%84%E6%95%B0%E6%8D%AE%E6%A8%A1%E5%9E%8B)
##### [87、设计模式：工厂模式 和 单例模式 介绍一下？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95/1~103%20%E8%AF%AD%E8%A8%80%E8%AF%AD%E6%B3%95%E9%9D%A2%E8%AF%95%E9%A2%98.md#87%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F%E5%B7%A5%E5%8E%82%E6%A8%A1%E5%BC%8F-%E5%92%8C-%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F-%E4%BB%8B%E7%BB%8D%E4%B8%80%E4%B8%8B)
##### 88、const的作用有哪些，谈一谈你对const的理解？
##### 89、描述char*、const char*、char* const、const char* const的区别？
##### 90、指针常量和常量指针有什么区别？
##### 91、static的作用是什么，什么情况下用到static？
##### 92、全局变量与局部变量的区别？
##### 93、宏定义的作用是什么？
##### 94、内存对齐的概念？为什么会有内存对齐？
##### 95、inline 内联函数的特点有哪些？它的优缺点是什么？
##### 96、如何避免野指针？
##### 97、如何计算结构体长度？
##### 98、sizeof和strlen有什么区别？
##### 99、知道条件变量吗？条件变量为什么要和锁配合使用？
##### 100、如何用C 实现 C++ 的面向对象特性（封装、继承、多态）
##### 101、memcpy怎么实现让它效率更高？
##### 102、typedef和define有什么区别？
##### 103、extern有什么作用，extern C有什么作用？

<br>

<h3 id="8">:hourglass: 网络原理</h3> 

---
##### [1.如何理解 URI？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#1%E5%A6%82%E4%BD%95%E7%90%86%E8%A7%A3-uri)
##### [2.解释一下HTTP的超文本传输协议](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#2%E8%A7%A3%E9%87%8A%E4%B8%80%E4%B8%8Bhttp%E7%9A%84%E8%B6%85%E6%96%87%E6%9C%AC%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE)
##### [3.HTTP 的特点？HTTP 有哪些缺点？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#3http-%E7%9A%84%E7%89%B9%E7%82%B9http-%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BC%BA%E7%82%B9)
##### [4.HTTP 报文结构是怎样的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#4http-%E6%8A%A5%E6%96%87%E7%BB%93%E6%9E%84%E6%98%AF%E6%80%8E%E6%A0%B7%E7%9A%84)
##### [5.如何理解 HTTP 的请求方法？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#5%E5%A6%82%E4%BD%95%E7%90%86%E8%A7%A3-http-%E7%9A%84%E8%AF%B7%E6%B1%82%E6%96%B9%E6%B3%95)
##### [6.http 常见字段有哪些？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#6http-%E5%B8%B8%E8%A7%81%E5%AD%97%E6%AE%B5%E6%9C%89%E5%93%AA%E4%BA%9B)
##### [7.对于定长和不定长的数据，HTTP 是怎么传输的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#7%E5%AF%B9%E4%BA%8E%E5%AE%9A%E9%95%BF%E5%92%8C%E4%B8%8D%E5%AE%9A%E9%95%BF%E7%9A%84%E6%95%B0%E6%8D%AEhttp-%E6%98%AF%E6%80%8E%E4%B9%88%E4%BC%A0%E8%BE%93%E7%9A%84)
##### [8.HTTP 如何处理大文件的传输？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#8http-%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86%E5%A4%A7%E6%96%87%E4%BB%B6%E7%9A%84%E4%BC%A0%E8%BE%93)
##### [9.HTTP 中如何处理表单数据的提交？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#9http-%E4%B8%AD%E5%A6%82%E4%BD%95%E5%A4%84%E7%90%86%E8%A1%A8%E5%8D%95%E6%95%B0%E6%8D%AE%E7%9A%84%E6%8F%90%E4%BA%A4)
##### [10.如何理解 HTTP 代理？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#10%E5%A6%82%E4%BD%95%E7%90%86%E8%A7%A3-http-%E4%BB%A3%E7%90%86)
##### [11.说说 HTTP1.1 相比 HTTP1.0 提高了什么性能？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#11%E8%AF%B4%E8%AF%B4-http11-%E7%9B%B8%E6%AF%94-http10-%E6%8F%90%E9%AB%98%E4%BA%86%E4%BB%80%E4%B9%88%E6%80%A7%E8%83%BD)
##### [12.那上面的 HTTP1.1 的性能瓶颈，HTTP2 做了什么优化？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#12%E9%82%A3%E4%B8%8A%E9%9D%A2%E7%9A%84-http11-%E7%9A%84%E6%80%A7%E8%83%BD%E7%93%B6%E9%A2%88http2-%E5%81%9A%E4%BA%86%E4%BB%80%E4%B9%88%E4%BC%98%E5%8C%96)
##### [13.HTTP2 有哪些缺陷？HTTP3 做了哪些优化？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#13http2-%E6%9C%89%E5%93%AA%E4%BA%9B%E7%BC%BA%E9%99%B7http3-%E5%81%9A%E4%BA%86%E5%93%AA%E4%BA%9B%E4%BC%98%E5%8C%96)
##### [14.HTTP 与 HTTPS 有哪些区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#14http-%E4%B8%8E-https-%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8C%BA%E5%88%AB)
##### [15.HTTPS 解决了 HTTP 的哪些问题？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#15https-%E8%A7%A3%E5%86%B3%E4%BA%86-http-%E7%9A%84%E5%93%AA%E4%BA%9B%E9%97%AE%E9%A2%98)
##### [16.HTTPS 是如何解决上面的三个风险的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#16https-%E6%98%AF%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3%E4%B8%8A%E9%9D%A2%E7%9A%84%E4%B8%89%E4%B8%AA%E9%A3%8E%E9%99%A9%E7%9A%84)
##### [17.HTTPS 是如何建立连接的？其间交互了什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#17https-%E6%98%AF%E5%A6%82%E4%BD%95%E5%BB%BA%E7%AB%8B%E8%BF%9E%E6%8E%A5%E7%9A%84%E5%85%B6%E9%97%B4%E4%BA%A4%E4%BA%92%E4%BA%86%E4%BB%80%E4%B9%88)
##### [18.UDP 和 TCP 的区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#18udp-%E5%92%8C-tcp-%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [19.TCP 三次握手和四次挥手](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#19tcp-%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%92%8C%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B)
##### [20.说说TCP传输的三次握手四次挥手策略](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#20%E8%AF%B4%E8%AF%B4tcp%E4%BC%A0%E8%BE%93%E7%9A%84%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%9B%9B%E6%AC%A1%E6%8C%A5%E6%89%8B%E7%AD%96%E7%95%A5)
##### [21.什么是无状态协议，HTTP 是无状态协议吗，怎么解决](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#21%E4%BB%80%E4%B9%88%E6%98%AF%E6%97%A0%E7%8A%B6%E6%80%81%E5%8D%8F%E8%AE%AEhttp-%E6%98%AF%E6%97%A0%E7%8A%B6%E6%80%81%E5%8D%8F%E8%AE%AE%E5%90%97%E6%80%8E%E4%B9%88%E8%A7%A3%E5%86%B3)
##### [22.OSI与TCP/IP各层的结构与功能,都有哪些协议?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#22osi%E4%B8%8Etcpip%E5%90%84%E5%B1%82%E7%9A%84%E7%BB%93%E6%9E%84%E4%B8%8E%E5%8A%9F%E8%83%BD%E9%83%BD%E6%9C%89%E5%93%AA%E4%BA%9B%E5%8D%8F%E8%AE%AE)
##### [23.TCP协议如何保证可靠传输](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#23tcp%E5%8D%8F%E8%AE%AE%E5%A6%82%E4%BD%95%E4%BF%9D%E8%AF%81%E5%8F%AF%E9%9D%A0%E4%BC%A0%E8%BE%93)
##### [24.说说ARQ协议](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#24%E8%AF%B4%E8%AF%B4arq%E5%8D%8F%E8%AE%AE)
##### [25.什么是滑动窗口和流量控制](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#25%E4%BB%80%E4%B9%88%E6%98%AF%E6%BB%91%E5%8A%A8%E7%AA%97%E5%8F%A3%E5%92%8C%E6%B5%81%E9%87%8F%E6%8E%A7%E5%88%B6)
##### [26.什么是拥塞控制](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#26%E4%BB%80%E4%B9%88%E6%98%AF%E6%8B%A5%E5%A1%9E%E6%8E%A7%E5%88%B6)
##### [27.在浏览器中输入url地址 ->> 显示主页的过程？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#27%E5%9C%A8%E6%B5%8F%E8%A7%88%E5%99%A8%E4%B8%AD%E8%BE%93%E5%85%A5url%E5%9C%B0%E5%9D%80---%E6%98%BE%E7%A4%BA%E4%B8%BB%E9%A1%B5%E7%9A%84%E8%BF%87%E7%A8%8B)
##### [28.HTTP长连接,短连接](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#28http%E9%95%BF%E8%BF%9E%E6%8E%A5%E7%9F%AD%E8%BF%9E%E6%8E%A5)
##### [29.Cookie的作用是什么?和Session有什么区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#29cookie%E7%9A%84%E4%BD%9C%E7%94%A8%E6%98%AF%E4%BB%80%E4%B9%88%E5%92%8Csession%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
##### [30.URI和URL的区别是什么?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#30uri%E5%92%8Curl%E7%9A%84%E5%8C%BA%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88)
##### [31.HTTP常见的状态码有哪些？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#31http%E5%B8%B8%E8%A7%81%E7%9A%84%E7%8A%B6%E6%80%81%E7%A0%81%E6%9C%89%E5%93%AA%E4%BA%9B)
##### [32.说说常见的常见HTTP首部字段？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#32%E8%AF%B4%E8%AF%B4%E5%B8%B8%E8%A7%81%E7%9A%84%E5%B8%B8%E8%A7%81http%E9%A6%96%E9%83%A8%E5%AD%97%E6%AE%B5)
##### [33.HTTPS方式与web服务器通信的步骤？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#33https%E6%96%B9%E5%BC%8F%E4%B8%8Eweb%E6%9C%8D%E5%8A%A1%E5%99%A8%E9%80%9A%E4%BF%A1%E7%9A%84%E6%AD%A5%E9%AA%A4)
##### [34.HTTP请求报文与响应报文格式？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#34http%E8%AF%B7%E6%B1%82%E6%8A%A5%E6%96%87%E4%B8%8E%E5%93%8D%E5%BA%94%E6%8A%A5%E6%96%87%E6%A0%BC%E5%BC%8F)
##### [35.地址栏输入 URL 发生了什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#35%E5%9C%B0%E5%9D%80%E6%A0%8F%E8%BE%93%E5%85%A5-url-%E5%8F%91%E7%94%9F%E4%BA%86%E4%BB%80%E4%B9%88)
##### [36.HTTPS的工作原理](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86/1~36%20%E7%BD%91%E7%BB%9C%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#36https%E7%9A%84%E5%B7%A5%E4%BD%9C%E5%8E%9F%E7%90%86)

<br>

<h3 id="9">:sparkles: 网络编程</h3> 

---
##### [1、什么是IO多路复用](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#1%E4%BB%80%E4%B9%88%E6%98%AFio%E5%A4%9A%E8%B7%AF%E5%A4%8D%E7%94%A8)
##### [2、epool中et和lt的区别与实现原理](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#2epool%E4%B8%ADet%E5%92%8Clt%E7%9A%84%E5%8C%BA%E5%88%AB%E4%B8%8E%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86)
##### [3、tcp连接建立的时候3次握手，断开连接的4次握手的具体过程](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#3tcp%E8%BF%9E%E6%8E%A5%E5%BB%BA%E7%AB%8B%E7%9A%84%E6%97%B6%E5%80%993%E6%AC%A1%E6%8F%A1%E6%89%8B%E6%96%AD%E5%BC%80%E8%BF%9E%E6%8E%A5%E7%9A%844%E6%AC%A1%E6%8F%A1%E6%89%8B%E7%9A%84%E5%85%B7%E4%BD%93%E8%BF%87%E7%A8%8B)
##### [4、connect方法会阻塞，请问有什么方法可以避免其长时间阻塞？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#4connect%E6%96%B9%E6%B3%95%E4%BC%9A%E9%98%BB%E5%A1%9E%E8%AF%B7%E9%97%AE%E6%9C%89%E4%BB%80%E4%B9%88%E6%96%B9%E6%B3%95%E5%8F%AF%E4%BB%A5%E9%81%BF%E5%85%8D%E5%85%B6%E9%95%BF%E6%97%B6%E9%97%B4%E9%98%BB%E5%A1%9E)
##### [5、网络中，如果客户端突然掉线或者重启，服务器端怎么样才能立刻知道？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#5%E7%BD%91%E7%BB%9C%E4%B8%AD%E5%A6%82%E6%9E%9C%E5%AE%A2%E6%88%B7%E7%AB%AF%E7%AA%81%E7%84%B6%E6%8E%89%E7%BA%BF%E6%88%96%E8%80%85%E9%87%8D%E5%90%AF%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AB%AF%E6%80%8E%E4%B9%88%E6%A0%B7%E6%89%8D%E8%83%BD%E7%AB%8B%E5%88%BB%E7%9F%A5%E9%81%93)
##### [6、在子网210.27.48.21/30种有多少个可用地址？分别是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#6%E5%9C%A8%E5%AD%90%E7%BD%9121027482130%E7%A7%8D%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E5%8F%AF%E7%94%A8%E5%9C%B0%E5%9D%80%E5%88%86%E5%88%AB%E6%98%AF%E4%BB%80%E4%B9%88)
##### [7、TTL是什么？有什么用处，通常那些工具会用到它？（ping? traceroute? ifconfig? netstat?）](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#7ttl%E6%98%AF%E4%BB%80%E4%B9%88%E6%9C%89%E4%BB%80%E4%B9%88%E7%94%A8%E5%A4%84%E9%80%9A%E5%B8%B8%E9%82%A3%E4%BA%9B%E5%B7%A5%E5%85%B7%E4%BC%9A%E7%94%A8%E5%88%B0%E5%AE%83ping-traceroute-ifconfig-netstat)
##### [8、路由表示做什么用的？在linux环境中怎么来配置一条默认路由？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#8%E8%B7%AF%E7%94%B1%E8%A1%A8%E7%A4%BA%E5%81%9A%E4%BB%80%E4%B9%88%E7%94%A8%E7%9A%84%E5%9C%A8linux%E7%8E%AF%E5%A2%83%E4%B8%AD%E6%80%8E%E4%B9%88%E6%9D%A5%E9%85%8D%E7%BD%AE%E4%B8%80%E6%9D%A1%E9%BB%98%E8%AE%A4%E8%B7%AF%E7%94%B1)
##### [9、在网络中有两台主机A和B，并通过路由器和其他交换设备连接起来，已经确认物理连接正确无误，怎么来测试这两台机器是否连通？如果不通，怎么来判断故障点？怎么排除故障？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#9%E5%9C%A8%E7%BD%91%E7%BB%9C%E4%B8%AD%E6%9C%89%E4%B8%A4%E5%8F%B0%E4%B8%BB%E6%9C%BAa%E5%92%8Cb%E5%B9%B6%E9%80%9A%E8%BF%87%E8%B7%AF%E7%94%B1%E5%99%A8%E5%92%8C%E5%85%B6%E4%BB%96%E4%BA%A4%E6%8D%A2%E8%AE%BE%E5%A4%87%E8%BF%9E%E6%8E%A5%E8%B5%B7%E6%9D%A5%E5%B7%B2%E7%BB%8F%E7%A1%AE%E8%AE%A4%E7%89%A9%E7%90%86%E8%BF%9E%E6%8E%A5%E6%AD%A3%E7%A1%AE%E6%97%A0%E8%AF%AF%E6%80%8E%E4%B9%88%E6%9D%A5%E6%B5%8B%E8%AF%95%E8%BF%99%E4%B8%A4%E5%8F%B0%E6%9C%BA%E5%99%A8%E6%98%AF%E5%90%A6%E8%BF%9E%E9%80%9A%E5%A6%82%E6%9E%9C%E4%B8%8D%E9%80%9A%E6%80%8E%E4%B9%88%E6%9D%A5%E5%88%A4%E6%96%AD%E6%95%85%E9%9A%9C%E7%82%B9%E6%80%8E%E4%B9%88%E6%8E%92%E9%99%A4%E6%95%85%E9%9A%9C)
##### [10、网络编程中设计并发服务器，使用多进程 与 多线程 ，请问有什么区别？ ](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#10%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E4%B8%AD%E8%AE%BE%E8%AE%A1%E5%B9%B6%E5%8F%91%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%BD%BF%E7%94%A8%E5%A4%9A%E8%BF%9B%E7%A8%8B-%E4%B8%8E-%E5%A4%9A%E7%BA%BF%E7%A8%8B-%E8%AF%B7%E9%97%AE%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB)
##### [11、网络编程的一般步骤](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#11%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E7%9A%84%E4%B8%80%E8%88%AC%E6%AD%A5%E9%AA%A4)
##### [12、TCP的重发机制是怎么实现的？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#12tcp%E7%9A%84%E9%87%8D%E5%8F%91%E6%9C%BA%E5%88%B6%E6%98%AF%E6%80%8E%E4%B9%88%E5%AE%9E%E7%8E%B0%E7%9A%84)
##### [13、TCP为什么不是两次连接？而是三次握手？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#13tcp%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E6%98%AF%E4%B8%A4%E6%AC%A1%E8%BF%9E%E6%8E%A5%E8%80%8C%E6%98%AF%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B)
##### [14、socket编程，如果client断电了，服务器如何快速知道？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#14socket%E7%BC%96%E7%A8%8B%E5%A6%82%E6%9E%9Cclient%E6%96%AD%E7%94%B5%E4%BA%86%E6%9C%8D%E5%8A%A1%E5%99%A8%E5%A6%82%E4%BD%95%E5%BF%AB%E9%80%9F%E7%9F%A5%E9%81%93)
##### [15、fork()一子进程程后 父进程癿全局变量能不能使用？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#15fork%E4%B8%80%E5%AD%90%E8%BF%9B%E7%A8%8B%E7%A8%8B%E5%90%8E-%E7%88%B6%E8%BF%9B%E7%A8%8B%E7%99%BF%E5%85%A8%E5%B1%80%E5%8F%98%E9%87%8F%E8%83%BD%E4%B8%8D%E8%83%BD%E4%BD%BF%E7%94%A8)
##### [16、4G的long型整数中找到一个最大的，如何做？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#164g%E7%9A%84long%E5%9E%8B%E6%95%B4%E6%95%B0%E4%B8%AD%E6%89%BE%E5%88%B0%E4%B8%80%E4%B8%AA%E6%9C%80%E5%A4%A7%E7%9A%84%E5%A6%82%E4%BD%95%E5%81%9A)
##### [17、tcp三次握手的过程，accept发生在三次握手哪个阶段？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#17tcp%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E7%9A%84%E8%BF%87%E7%A8%8Baccept%E5%8F%91%E7%94%9F%E5%9C%A8%E4%B8%89%E6%AC%A1%E6%8F%A1%E6%89%8B%E5%93%AA%E4%B8%AA%E9%98%B6%E6%AE%B5)
##### [18、tcp流， udp的数据报，之间有什么区别，为什么TCP要叫做数据流？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#18tcp%E6%B5%81-udp%E7%9A%84%E6%95%B0%E6%8D%AE%E6%8A%A5%E4%B9%8B%E9%97%B4%E6%9C%89%E4%BB%80%E4%B9%88%E5%8C%BA%E5%88%AB%E4%B8%BA%E4%BB%80%E4%B9%88tcp%E8%A6%81%E5%8F%AB%E5%81%9A%E6%95%B0%E6%8D%AE%E6%B5%81)
##### [19、socket在什么情况下可读?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#19socket%E5%9C%A8%E4%BB%80%E4%B9%88%E6%83%85%E5%86%B5%E4%B8%8B%E5%8F%AF%E8%AF%BB)
##### [20、TCP通讯中，select到读事件，但是读到的数据量是0，为什么，如何解决?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#20tcp%E9%80%9A%E8%AE%AF%E4%B8%ADselect%E5%88%B0%E8%AF%BB%E4%BA%8B%E4%BB%B6%E4%BD%86%E6%98%AF%E8%AF%BB%E5%88%B0%E7%9A%84%E6%95%B0%E6%8D%AE%E9%87%8F%E6%98%AF0%E4%B8%BA%E4%BB%80%E4%B9%88%E5%A6%82%E4%BD%95%E8%A7%A3%E5%86%B3)
##### [21、说说IO多路复用优缺点？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#21%E8%AF%B4%E8%AF%B4io%E5%A4%9A%E8%B7%AF%E5%A4%8D%E7%94%A8%E4%BC%98%E7%BC%BA%E7%82%B9)
##### [22、说说select机制的缺点](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#22%E8%AF%B4%E8%AF%B4select%E6%9C%BA%E5%88%B6%E7%9A%84%E7%BC%BA%E7%82%B9)
##### [23、说一下epoll的好处](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#23%E8%AF%B4%E4%B8%80%E4%B8%8Bepoll%E7%9A%84%E5%A5%BD%E5%A4%84)
##### [24、epoll需要在用户态和内核态拷贝数据么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#24epoll%E9%9C%80%E8%A6%81%E5%9C%A8%E7%94%A8%E6%88%B7%E6%80%81%E5%92%8C%E5%86%85%E6%A0%B8%E6%80%81%E6%8B%B7%E8%B4%9D%E6%95%B0%E6%8D%AE%E4%B9%88)
##### [25、epoll的实现知道么？在内核当中是什么样的数据结构进行存储，每个操作的时间复杂度是多少？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B/1~25%20%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B%E9%9D%A2%E8%AF%95%E9%A2%98.md#25epoll%E7%9A%84%E5%AE%9E%E7%8E%B0%E7%9F%A5%E9%81%93%E4%B9%88%E5%9C%A8%E5%86%85%E6%A0%B8%E5%BD%93%E4%B8%AD%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E8%BF%9B%E8%A1%8C%E5%AD%98%E5%82%A8%E6%AF%8F%E4%B8%AA%E6%93%8D%E4%BD%9C%E7%9A%84%E6%97%B6%E9%97%B4%E5%A4%8D%E6%9D%82%E5%BA%A6%E6%98%AF%E5%A4%9A%E5%B0%91)

<br>

<h3 id="10">:desktop_computer: 操作系统</h3> 

---
##### [1、什么是操作系统？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#1%E4%BB%80%E4%B9%88%E6%98%AF%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F)
##### [2、什么是系统调用？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#2%E4%BB%80%E4%B9%88%E6%98%AF%E7%B3%BB%E7%BB%9F%E8%B0%83%E7%94%A8)
##### [3、进程和线程的区别？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#3%E8%BF%9B%E7%A8%8B%E5%92%8C%E7%BA%BF%E7%A8%8B%E7%9A%84%E5%8C%BA%E5%88%AB)
##### [4、进程有哪几种状态?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#4%E8%BF%9B%E7%A8%8B%E6%9C%89%E5%93%AA%E5%87%A0%E7%A7%8D%E7%8A%B6%E6%80%81)
##### [5、进程间的通信方式](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#5%E8%BF%9B%E7%A8%8B%E9%97%B4%E7%9A%84%E9%80%9A%E4%BF%A1%E6%96%B9%E5%BC%8F)
##### [6、线程间的同步的方式](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#6%E7%BA%BF%E7%A8%8B%E9%97%B4%E7%9A%84%E5%90%8C%E6%AD%A5%E7%9A%84%E6%96%B9%E5%BC%8F)
##### [7、进程的调度算法](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#7%E8%BF%9B%E7%A8%8B%E7%9A%84%E8%B0%83%E5%BA%A6%E7%AE%97%E6%B3%95)
##### [8、操作系统的内存管理主要是做什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#8%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E7%9A%84%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86%E4%B8%BB%E8%A6%81%E6%98%AF%E5%81%9A%E4%BB%80%E4%B9%88)
##### [9、常见的几种内存管理机制](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#9%E5%B8%B8%E8%A7%81%E7%9A%84%E5%87%A0%E7%A7%8D%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86%E6%9C%BA%E5%88%B6)
##### [10、快表和多级页表](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#10%E5%BF%AB%E8%A1%A8%E5%92%8C%E5%A4%9A%E7%BA%A7%E9%A1%B5%E8%A1%A8)
##### [11、分页机制和分段机制的共同点和区别](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#11%E5%88%86%E9%A1%B5%E6%9C%BA%E5%88%B6%E5%92%8C%E5%88%86%E6%AE%B5%E6%9C%BA%E5%88%B6%E7%9A%84%E5%85%B1%E5%90%8C%E7%82%B9%E5%92%8C%E5%8C%BA%E5%88%AB)
##### [12、逻辑(虚拟)地址和物理地址](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#12%E9%80%BB%E8%BE%91%E8%99%9A%E6%8B%9F%E5%9C%B0%E5%9D%80%E5%92%8C%E7%89%A9%E7%90%86%E5%9C%B0%E5%9D%80)
##### [13、CPU 寻址了解吗?为什么需要虚拟地址空间?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#13cpu-%E5%AF%BB%E5%9D%80%E4%BA%86%E8%A7%A3%E5%90%97%E4%B8%BA%E4%BB%80%E4%B9%88%E9%9C%80%E8%A6%81%E8%99%9A%E6%8B%9F%E5%9C%B0%E5%9D%80%E7%A9%BA%E9%97%B4)
##### [14、什么是虚拟内存(Virtual Memory)?](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#14%E4%BB%80%E4%B9%88%E6%98%AF%E8%99%9A%E6%8B%9F%E5%86%85%E5%AD%98virtual-memory)
##### [15、局部性原理](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#15%E5%B1%80%E9%83%A8%E6%80%A7%E5%8E%9F%E7%90%86)
##### [16、虚拟存储器](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#16%E8%99%9A%E6%8B%9F%E5%AD%98%E5%82%A8%E5%99%A8)
##### [17、虚拟内存的技术实现](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#17%E8%99%9A%E6%8B%9F%E5%86%85%E5%AD%98%E7%9A%84%E6%8A%80%E6%9C%AF%E5%AE%9E%E7%8E%B0)
##### [18、页面置换算法](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F/1~18%20%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E9%9D%A2%E8%AF%95%E9%A2%98.md#18%E9%A1%B5%E9%9D%A2%E7%BD%AE%E6%8D%A2%E7%AE%97%E6%B3%95)
##### 19、操作系统是怎么进行进程管理的？
##### 20、操作系统是如何做到进程阻塞的？
##### 21、线程是如何实现的？
##### 22、线程之间私有和共享的资源有哪些？
##### 23、一般应用程序内存空间的堆和栈的区别是什么？
##### 24、进程虚拟空间是怎么布局的？
##### 25、虚拟内存是如何映射到物理内存的？了解分页内存管理吗？
##### 26、什么是上下文切换，操作系统是怎么做的上下文切换？
##### 27、什么是大端字节，什么是小端字节？如何转换字节序？
##### 28、产生死锁的必要条件有哪些？如何避免死锁？
##### 29、信号和信号量的区别是什么？
##### 30、锁的性能开销，锁的实现原理？

<br>

<h3 id="11">:floppy_disk: 编译原理</h3> 

---
##### [1、什么是语法分析？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86/1~9%20%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#1%E4%BB%80%E4%B9%88%E6%98%AF%E8%AF%AD%E6%B3%95%E5%88%86%E6%9E%90)
##### [2、什么是自顶向下分析法？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86/1~9%20%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#2%E4%BB%80%E4%B9%88%E6%98%AF%E8%87%AA%E9%A1%B6%E5%90%91%E4%B8%8B%E5%88%86%E6%9E%90%E6%B3%95)
##### [3、在自顶向下的分析过程中，存在的问题是什么？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86/1~9%20%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#3%E5%9C%A8%E8%87%AA%E9%A1%B6%E5%90%91%E4%B8%8B%E7%9A%84%E5%88%86%E6%9E%90%E8%BF%87%E7%A8%8B%E4%B8%AD%E5%AD%98%E5%9C%A8%E7%9A%84%E9%97%AE%E9%A2%98%E6%98%AF%E4%BB%80%E4%B9%88)
##### [4、什么是确定的自顶向下分析法？](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86/1~9%20%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#4%E4%BB%80%E4%B9%88%E6%98%AF%E7%A1%AE%E5%AE%9A%E7%9A%84%E8%87%AA%E9%A1%B6%E5%90%91%E4%B8%8B%E5%88%86%E6%9E%90%E6%B3%95)
##### [5、存在的问题](https://github.com/0voice/campus_recruitmen_questions/blob/main/%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86/1~9%20%E7%BC%96%E8%AF%91%E5%8E%9F%E7%90%86%E9%9D%A2%E8%AF%95%E9%A2%98.md#5%E5%AD%98%E5%9C%A8%E7%9A%84%E9%97%AE%E9%A2%98)
##### 6、gcc hello.c 这行命令具体的执行过程，内部究竟做了什么？
##### 7、程序一定会从main函数开始运行吗？
##### 8、如何确定某个函数有被编译输出？
##### 9、动态链接库和静态链接库的区别是什么？

<br>

<h3 id="14">并发</h3> 

---
##### 1.线程和进程区别
##### 2.创建线程的四种方式
##### 3.as-if-serial规则和happens-before规则的区别
##### 4.多线程如何使用？
##### 5.启动多线程调用使用什么方法？
##### 6.并发容器之CopyOnWriteArrayList详解
##### 7.并发容器之ThreadLocal详解
##### 8.并发容器之ConcurrentHashMap详解(JDK1.8版本)与源码分析
##### 9.并发容器之BlockingQueue详解
##### 10.ThreadLocal内存泄漏分析与解决方案

<br>

<h3 id="15">堆与栈</h3> 

---
##### 1、什么时候可能发生栈溢出
##### 2、堆和栈的区别
##### 3、什么是小根堆和大根堆？
##### 4、栈溢出的原因
##### 5、栈的效率高的原因
##### 6、请你说一说小根堆特点
##### 7、请你解释一下，内存中的栈(stack)、堆(heap) 和静态区(static area) 的用法。并且说明heap和stack有什么区别
##### 8、大顶堆怎么插入删除
##### 9、请你讲一下动态链表和静态链表的区别

<br>

<h3 id="16">树</h3> 

---
##### 1、 树的定义
##### 2、（144） Binary Tree Preorder Traversal
##### 3、（589） N-ary Tree Preorder Traversal
##### 4、（94） Binary Tree Inorder Traversal
##### 5、（145） Binary Tree Postorder Traversal
##### 6、（590） N-ary Tree Postorder Traversal
##### 7、（100） Same Tree
##### 8、（101） Symmetric Tree
##### 9、（104） Maximum Depth of Binary Tree
##### 10、（559） Maximum Depth of N-ary Tree
##### 11、（111） Minimum Depth of Binary Tree
##### 12、（105） Construct Binary Tree from Preorder and Inorder Traversal
##### 13、（106） Construct Binary Tree from Inorder and Postorder Traversal
##### 14、（889） Construct Binary Tree from Preorder and Postorder Traversal
##### 15、（572） Subtree of Another Tree
##### 16、（102） Binary Tree Level Order Traversal
##### 17、（103） Binary Tree Zigzag Level Order Traversal
##### 18、（107） Binary Tree Level Order Traversal II
##### 19、（429） N-ary Tree Level Order Traversal
##### 20、（637） Average of Levels in Binary Tree
##### 21、（515） Find Largest Value in Each Tree Row
##### 22、（987） Vertical Order Traversal of a Binary Tree
##### 23、（257） Binary Tree Paths
##### 24、（988） Smallest String Starting From Leaf
##### 25、（112） Path Sum
##### 26、（113） Path Sum II
##### 27、（297） Serialize and Deserialize Binary Tree
##### 28、（110） Balanced Binary Tree
##### 29、（108） Convert Sorted Array to Binary Search Tree
##### 30、（235） Lowest Common Ancestor of a Binary Search Tree
##### 31、（404） Sum of Left Leaves
##### 32、（938） Range Sum of BST
##### 33、（530） Minimum Absolute Difference in BST
##### 34、（783） Minimum Distance Between BST Nodes
##### 35、（538） Convert BST to Greater Tree
##### 36、（958） Check Completeness of a Binary Tree
##### 37、（543） Diameter of Binary Tree
##### 38、（965） Univalued Binary Tree
##### 39、（563） Binary Tree Tilt
##### 40、（606） Construct String from Binary Tree
##### 41、（617） Merge Two Binary Trees
##### 42、（653） Two Sum IV - Input is a BST
##### 43、（669） Trim a Binary Search Tree
##### 44、（671） Second Minimum Node In a Binary Tree
##### 45、（687） Longest Univalue Path
##### 46、（700） Search in a Binary Search Tree
##### 47、（872） Leaf-Similar Trees
##### 48、（897） Increasing Order Search Tree
##### 49、（993） Cousins in Binary Tree
##### 50、（230） Kth Smallest Element in a BST
##### 51、（98） Validate Binary Search Tree
##### 52、（109） Convert Sorted List to Binary Search Tree
##### 53、（1008） Construct Binary Search Tree from Preorder Traversal
##### 54、（236） Lowest Common Ancestor of a Binary Tree
##### 55、（654） Maximum Binary Tree
##### 56、（513） Find Bottom Left Tree Value
##### 57、（814） Binary Tree Pruning
##### 58、（199） Binary Tree Right Side View
##### 59、（662） Maximum Width of Binary Tree
##### 60、（222） Count Complete Tree Nodes
##### 61、（1022） Sum of Root To Leaf Binary Numbers
##### 62、（1026） Maximum Difference Between Node and Ancestor
##### 63、（1038） Binary Search Tree to Greater Sum Tree
##### 64、（1080） Insufficient Nodes in Root to Leaf Paths
##### 65、（1161） Maximum Level Sum of a Binary Tree
##### 66、（1104） Path In Zigzag Labelled Binary Tree
##### 67、（1110） Delete Nodes And Return Forest
##### 68、（1123） Lowest Common Ancestor of Deepest Leaves
##### 69、（1382） Balance a Binary Search Tree
##### 70、（1372） Longest ZigZag Path in a Binary Tree
##### 71、（1367） Linked List in Binary Tree
##### 72、（124） Binary Tree Maximum Path Sum
##### 73、（1443） Minimum Time to Collect All Apples in a Tree
##### 74、（1339） Maximum Product of Splitted Binary Tree
##### 75、（1315） Sum of Nodes with Even-Valued Grandparent
##### 76、（1457） Pseudo-Palindromic Paths in a Binary Tree
##### 77、（129） Sum Root to Leaf Numbers
##### 78、（114） Flatten Binary Tree to Linked List
##### 79、（450） Delete Node in a BST
##### 80、（971） Flip Binary Tree To Match Preorder Traversal
##### 81、（951） Flip Equivalent Binary Trees
##### 82、（863） All Nodes Distance K in Binary Tree
##### 83、（865） Smallest Subtree with all the Deepest Nodes
##### 84、（1373） Maximum Sum BST in Binary Tree
##### 85、（501） Find Mode in Binary Search Tree
##### 86、（968） Binary Tree Cameras
##### 87、（116） Populating Next Right Pointers in Each Node
##### 88、（117） 填充每个节点的下一个右侧节点指针 II
##### 89、（834） Sum of Distances in Tree]
##### 90、（655） Print Binary Tree
##### 91、（307） Range Sum Query - Mutable
##### 92、（652） Find Duplicate Subtrees
##### 93、（1028） Recover a Tree From Preorder Traversal
##### 94、（NC45） 实现二叉树先序，中序和后序遍历
##### 95、（NC15） 求二叉树的层序遍历
##### 96、（NC14） 二叉树的之字形层序遍历
##### 97、（NC102） 在二叉树中找到两个节点的最近公共祖先
##### 98、（NC12） 重建二叉树
##### 99、（NC136） 输出二叉树的右视图
##### 100、（NC13） 二叉树的最大深度
##### 101、（NC62） 平衡二叉树
##### 102、（NC60） 判断一棵二叉树是否为搜索二叉树和完全二叉树
##### 103、（NC5） 二叉树的所有路径和
##### 104、（NC8） 二叉树和为指定值的路径
##### 105、（NC6） 二叉树的最大路径和
##### 106、（NC16） 判断二叉树是否对称
##### 107、（NC9）   二叉树中是否存在节点和为指定值的路径
##### 108、（NC99） 树的直径
##### 109、（NC123） 序列化二叉树
##### 110、（NC81） 二叉搜索树的第k个结点
##### 111、（NC124） 字典树的实现
##### 112、（NC80） 把二叉树打印成多行
##### 113、（NC98） 判断t1树中是否有与t2树拓扑结构完全相同的子树
##### 114、（NC117） 合并二叉树
##### 115、（NC72） 二叉树的镜像
##### 116、（NC58） 找到搜索二叉树中两个错误的节点
##### 117、（NC64） 二叉搜索树与双向链表
##### 118、（NC84） 完全二叉树结点数
##### 119、（NC11） 有序数组转化为二叉平衡树
##### 120、（NC159） 最小生成树
##### 121、（NC687） 牛牛浇
##### 122、（NC530） 线段树编号问题
##### 123、（NC582） 苹果树
##### 124、（NC587） 树与序列问题
##### 125、（NC150） 二叉树的个数
##### 126、（NC597） 两棵树的问题
##### 127、（NC161） 二叉树的中序遍历

<br>

<h3 id="17">图</h3> 

---
##### 1、（990） Satisfiability of Equality Equations
##### 2、（997） Find the Town Judge
##### 3、（133） Clone Graph
##### 4、（1334） Find the City With the Smallest Number of Neighbors at a Threshold Distance
##### 5、（1267） Count Servers that Communicate
##### 6、（886） Possible Bipartition
##### 7、（207） Course Schedule
##### 8、（1462） Course Schedule IV
##### 9、（1466） Reorder Routes to Make All Paths Lead to the City Zero
##### 10、（1210） Minimum Moves to Reach Target with Rotations
##### 11、（1202） Smallest String With Swaps
##### 12、（787） Cheapest Flights Within K Stops
##### 13、（332） Reconstruct Itinerary
##### 14、（1519） Number of Nodes in the Sub-Tree With the Same Label
##### 15、（478） Generate Random Point in a Circle
##### 16、（1559） Detect Cycles in 2D Grid
##### 17、（310） Minimum Height Trees
##### 18、（127） Word Ladder
##### 19、（547） Friend Circles
##### 20、（1584） Min Cost to Connect All Points
##### 21、（684） Redundant Connection
##### 22、（685） Redundant Connection II
##### 23、（743） Network Delay Time
##### 24、（721） Accounts Merge
##### 25、（851） Loud and Rich
##### 26、（399） Evaluate Division
##### 27、（1617） Count Subtrees With Max Distance Between Cities
##### 28、（1284） Minimum Number of Flips to Convert Binary Matrix to Zero Matrix
##### 29、（1293） Shortest Path in a Grid with Obstacles Elimination
##### 30、（1298） Maximum Candies You Can Get from Boxes
##### 31、（1345） Jump Game IV
##### 32、（1391） Check if There is a Valid Path in a Grid
##### 33、（1162） As Far from Land as Possible
##### 34、（1091） Shortest Path in Binary Matrix
##### 35、（1034） Coloring A Border
##### 36、（1031） Number of Enclaves
##### 37、（695） Max Area of Island
##### 38、（994） Rotting Oranges
##### 39、（733） Flood Fill
##### 40、（1625） Lexicographically Smallest String After Applying Operations
##### 41、（1627） Graph Connectivity With Threshold
##### 42、（947） Most Stones Removed with Same Row or Column
##### 43、（1654） Minimum Jumps to Reach Home
##### 44、（1203） Sort Items by Groups Respecting Dependencies
##### 45、（803） Bricks Falling When Hit
##### 46、（1766） Tree of Coprimes
##### 46-1、 找到每个节点的最小祖先，并且祖先节点和其节点值互质。
##### 47、 （1368） Minimum Cost to Make at Least One Valid Path in a Grid
##### 47-1、 修改箭头方向最少次数能够到达右下角的点。
##### 48、（1786） Number of Restricted Paths From First to Last Node
##### 48-1、 从头节点到尾节点的限制路径是多少个，限制路径指每次节点到尾节点的最短路径要递减。
##### 49、（331） Verify Preorder Serialization of a Binary Tree
##### 49-1、 判断一个字符串序列是否是前序遍历。

<br>

<h3 id="18">排序</h3> 

---
##### 1、请你来手写一下快排的代码，并说明其最优情况
##### 2、请问求第k大的数的方法以及各自的复杂度是怎样的，另外追问一下，当有相同元素时，还可以使用什么不同的方法求第k大的元素
##### 3、请你来介绍一下各种排序算法及时间复杂度
##### 4、请问海量数据如何去取最大的k个
##### 5、介绍一下，归并排序的原理是什么？
##### 6、谈一谈，如何得到一个数据流中的中位数？
##### 7、对一千万个整数排序,整数范围在[-1000,1000]间,用什么排序最快?
##### 8、堆排序的思想
##### 9、topK给出3种解法
##### 10、常见排序算法

<br>

<h3 id="19">字符串</h3> 

---
##### 1、(14) Longest Common Prefix
##### 2、(20) Valid Parentheses
##### 3、(921) Minimum Add to Make Parentheses Valid
##### 4、(28) Implement strStr()
##### 5、(38) Count and Say
##### 6、(443) String Compression
##### 7、(125) Valid Palindrome
##### 8、(680) Valid Palindrome II
##### 9、(151) Reverse Words in a String
##### 10、(344) Reverse String
##### 11、(242) Valid Anagram
##### 12、(438) Find All Anagrams in a String
##### 13、(3) Longest Substring Without Repeating Characters
##### 14、(387) First Unique Character in a String
##### 15、(58) Length of Last Word
##### 16、(205) Isomorphic Strings
##### 17、(290) Word Pattern
##### 18、(890) Find and Replace Pattern
##### 19、(917) Reverse Only Letters
##### 20、(345)Reverse Vowels of a String
##### 21、(383) Ransom Note
##### 22、(925) Long Pressed Name
##### 23、(929) Unique Email Addresses
##### 24、(409) Longest Palindrome
##### 25、(434) Number of Segments in a String
##### 26、(500) Keyboard Row
##### 27、(520) Detect Capital
##### 28、(541) Reverse String II
##### 29、(551) Student Attendance Record I
##### 30、(557) Reverse Words in a String III
##### 31、(657) Robot Return to Origin
##### 32、(696) Count Binary Substrings
##### 33、(709) To Lower Case
##### 34、(771) Jewels and Stones
##### 35、(784) Letter Case Permutation
##### 36、(788) Rotated Digits
##### 37、(796) Rotate String
##### 38、(804) Unique Morse Code Words
##### 39、(806) Number of Lines To Write String
##### 40、(819) Most Common Word
##### 41、(821) Shortest Distance to a Character
##### 42、(824) Goat Latin
##### 43、(844) Backspace String Compare
##### 44、(859) Buddy Strings
##### 45、(893) Groups of Special-Equivalent Strings
##### 46、(1003) Check If Word Is Valid After Substitutions
##### 47、(17) Letter Combinations of a Phone Number
##### 48、(1023) Binary String With Substrings Representing 1 To N
##### 49、(482) License Key Formatting
##### 50、(1071) Greatest Common Divisor of Strings
##### 51、(1156) Swap For Longest Repeated Character Substring
##### 52、(1106) Parsing A Boolean Expression
##### 53、(1408) String Matching in an Array
##### 54、(791) Custom Sort String
##### 55、(678) Valid Parenthesis String
##### 56、(1419) Minimum Number of Frogs Croaking
##### 57、(1358) Number of Substrings Containing All Three Characters
##### 58、(1309) Decrypt String from Alphabet to Integer Mapping
##### 59、(1545) Find Kth Bit in Nth Binary String
##### 60、(777) Swap Adjacent in LR String
##### 61、(539) Minimum Time Difference
##### 62、(459) Repeated Substring Pattern
##### 63、(165) Compare Version Numbers
##### 64、(1371) Find the Longest Substring Containing Vowels in Even Counts
##### 65、(443) String Compression
##### 66、(809) Expressive Words
##### 67、(833) Find And Replace in String
##### 68、最长单词
##### 69、模式匹配
##### 70、(1638)Count Substrings That Differ by One Character

<br>


<h3 id="22">作者福利</h3> 

---
#### 零声教育，专注于c/c++Linux后台服务器开发架构技术提升。<br>
[分享Linux，Nginx，ZeroMQ，MySQL，Redis，fastdfs，MongoDB，ZK，流媒体，CDN，P2P，K8S，Docker，TCP/IP，协程，DPDK等技术内容，立即学习。](https://ke.qq.com/course/417774?flowToken=1037711)

福利资料获取：
#### 1、十份大厂面经视频分享

  ① 秋招如何斩获字节&快手offer<br>
  
  ② 小厂到腾讯60Woffer的逆袭<br>
  
  ③ 如何一次跳槽涨薪12W<br>
  
  ④ 清华毕业生跨专业如何拿到美团&字节offer<br>
  
  ⑤ 普通二本应届生的B站之路<br>
  
  ⑥ 非科班毕业如何进京东，拿到28W岗位offer<br>
  
  ⑦ 外包裸辞6个月，成功入职金山实现薪资翻倍<br>
  
  ⑧ 三年社招如何能够拿到35K&360offer<br>
  
  ⑨ 毕业半年，离职挑战华为offer<br>
  
  ⑩ 30天突击学习，拿下高薪offer涨薪10W
  
#### 2、对标腾讯T9职级技术要求的后台开发学习图谱

![大纲部分图.png](https://img11.360buyimg.com/ddimg/jfs/t1/37229/14/15620/149708/60e6a78eE5241eec1/d0f0c9d9aa1e4d99.png)

#### 扫码联系橙子，免费领取干货资料【备注：GitHub面试题】<br>
![barcode](https://www.0voice.com/uiwebsite/img/barcode/cz.jpg)







