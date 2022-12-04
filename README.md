## 一、项目描述
### 1 后端项目
#### 1.1 项目简介
项目使用SpringBoot-Redis-Jieba，为项目提供数据接口
- 一个基于 SrpingBoot、Redis、Jieba 框架的数据可视化项目
- 项目使用定时器，定期从数据库执行n个统计SQL，将统计结果存放Redis中，前端定时刷新请求数据都从redis中取，减轻数据库压力

### 2 前端项目

一个基于 vue、datav、Echart 框架的数据可视化项目，通过 vue 组件实现数据动态刷新渲染，内部图表可实现自由替换。
