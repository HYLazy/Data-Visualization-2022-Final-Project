## 一、项目描述
### 1 后端项目
#### 1.1 项目简介
项目使用SpringBoot、Redis、Jieba，为项目提供数据接口
- 一个基于 SrpingBoot、Redis、Jieba 框架的数据可视化项目
- 项目使用定时器，定期从数据库执行n个统计SQL，将统计结果存放Redis中，前端定时刷新请求数据都从redis中取，减轻数据库压力

### 2 前端项目

一个基于 vue、datav、Echart 框架的数据可视化项目，通过 vue 组件实现数据动态刷新渲染，内部图表可实现自由替换。

## 二、项目地址
* http://47.94.232.64:5000/

## 三、参考网站
* https://blog.csdn.net/Mrkaizi/article/details/112240996?spm=1001.2101.3001.6650.5&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-5-112240996-blog-127618104.pc_relevant_multi_platform_whitelistv4&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-5-112240996-blog-127618104.pc_relevant_multi_platform_whitelistv4&utm_relevant_index=6
* ![图片](https://img-blog.csdnimg.cn/20210105164158463.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01ya2Fpemk=,size_16,color_FFFFFF,t_70)
* 借鉴了文章中的UI和表格使用技巧。
* 重构了界面格式，加入了自己爬取的数据和统计信息。
