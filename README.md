##项目名称
唐诗分析
##项目描述
抓取古诗文网上的唐诗三百首，进行数据的清洗，存储，数据分析，将诗人的创作数量、创作用词进行可视化。
##涉及技术
+ 编程语言：Java
+ 数据库: JDBC编程、MySQL数据库
+ 前端：HTML、JavaScript、jQuery、echarts
+ 第三方：htmlunit、Ansj、Sparkjava、Druid
##实现功能
+ 爬取古诗文网
+ 对爬取的信息进行解析、清洗
+ 诗人创作数量、创作用词的可视化
##项目效果
! [poetry](../images/poetryCount.png)

! [word](../images/word.png)
##项目测试
+ 输入正确url进入页面，点击按钮，图表可以成功显示
+ 通过数据库查询检查爬取的数据，无乱码；并对诗文进行抽查，检查数据正确性
+ Lenovo S41设备，Windows10操作系统，MySQL数据库的环境下使用6个线程爬取：

  爬取30首诗，用时2.79s
  
  爬取160首诗，用时15.96s
  
  爬取319首诗，用时31.93s
+ 兼容性测试：在Chrome、Firefox、IE浏览器中分别进行测试
##待优化
+ 重复爬取时没有去重机制
