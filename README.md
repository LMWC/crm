# crm
![](https://pip.itcast.cn/uploads/5e0583b1d715498c9ea637fe5ed94697.png)  
**沉浸式项目实战-CRM:汇客CRM(客达管家)-基于SSM传统行业单体架构及技术演进的初级项目课程**
=========================
[**产品原型线上地址(选择汇客CRM实战版)**](https://app.mockplus.cn/s/hvKXEoWW3g2l)  
[**项目基板**](https://github.com/LMWC/JavaProject02_huike-crm-backend/tree/master)  
[**前端文件**](https://github.com/LMWC/JavaProject02_huike-crm-web)  
[**day52_初出茅庐**](https://github.com/LMWC/JavaProject02_huike-crm-backend/tree/day52_%E5%88%9D%E5%87%BA%E8%8C%85%E5%BA%90)  
-利用系统的三层架构mybatis_review完成最简单的增删改查  
[**day53_牛刀小试**](https://github.com/LMWC/JavaProject02_huike-crm-backend/tree/day53_%E7%89%9B%E5%88%80%E5%B0%8F%E8%AF%95)  
-商机管理-公海池-商机捞取-提示信息异常：捞取失败！最大保有量(10)，剩余可以捞取-5条线索  
-权限管理-用户管理-高级搜索-手机号搜索不可用  
-公海池-创建时间搜索 -没有效果  
-商机管理-商机状态搜索框不可用  
-线索管理- 线索ID和手机号应该支持模糊搜索  
-线索管理-添加线索-活动信息-应该只展示 正在活动时间内的活动  
-使用商机专员账号--公海池捞取数据时-提示没有操作权限  
-当线索转商机时，使用规则来进行自动分配,没有按照规则来进行自动分配  
-预加载活动编号  
[**day54_熟能生巧**](https://github.com/LMWC/JavaProject02_huike-crm-backend/tree/day54_%E7%86%9F%E8%83%BD%E7%94%9F%E5%B7%A7)  
-今日简报接  
-首页--今日待办数据展示  
-统计分析--线索统计--新增线索数量折线图  
-统计分析--学科客户分布饼图  
-统计分析--线索统计--线索转化率漏斗图  
-首页数据--商机转化龙虎榜    
-首页数据--线索转化龙虎榜  
-首页基本数据展示使用并发编程  
[**day55_并肩作战**](https://github.com/LMWC/JavaProject02_huike-crm-backend/tree/day55_%E5%B9%B6%E8%82%A9%E4%BD%9C%E6%88%98)  
-查询线索跟进记录列表  
-添加线索根进记录  
-查询商机跟进记录列表  
-新增商机跟进记录  
[**day56_勇于突破**](https://github.com/LMWC/JavaProject02_huike-crm-backend/tree/day56_%E5%8B%87%E4%BA%8E%E7%AA%81%E7%A0%B4)  
-线索批量导入  
-合同上传  
-紧急修复  




**运行方式**
=========================
- 打开并运行本地redis-server.exe
- 启动运行crm\huike-admin\src\main\java\com\huike\HuiKeApplication.java
- 启动运行huike-crm-web前端程序
- 在浏览器中输入网址进入汇客CRM管理系统http://localhost/



**参考环境**
=========================
- IntelliJ IDEA 2020.1.3 (Ultimate Edition)  
  Non-Bundled Plugins: JBLJavaToWeb, Lombook Plugin, mobi.hsz.idea.gitignore, MavenRunHelper,        com.baomidou.plugin.idea.mybatisx
- node-v14.18.3-x64
- maven-3.5.3
- jdk 1.8.0_162
- mysql-5.7.29-winx64
- redis-x64-3.2.100
