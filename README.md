## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

---

# 基于SpringBoot+Vue的博物馆管理系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

本系统是一款面向公众参观服务与馆内运营协同的数字化博物馆管理平台，针对线下排队购票与纸质导览并存、馆藏档案、特展排期、研学名额与文创销售分散在多套台账、游客难以及时获知展讯与余票、馆方难以对客流核销与互动评论统一监管等问题，把数字化馆藏鉴赏、陈列特展专栏、分时门票预约与入馆核销、研学社教报名、文创订购、修缮纪实与资讯发布，以及 AI 文博导览问答整合到同一套前后端分离工程中。

系统采用 SpringBoot + Vue 架构，区分普通游客与系统管理员：游客端完成馆藏浏览、预约核销、研学报名、文创下单与个人行程管理；管理端维护藏品门类与展厅、特展与票务核销、研学与文创订单、评论审核与 AI 审计，并在 ECharts 数据大屏查看馆藏分布、预约趋势与热销情况。预约从下单、生成核销码到一次核销可追溯，文创库存随订单扣减，适合作为毕设、课设与智慧文博学习参考。

## 主要功能模块

- **用户认证与角色分流**：游客与管理员统一登录注册，JWT 鉴权；登录后按角色进入公众门户或管理中台，/admin 路由与接口双重隔离
- **文博门户首页**：特展轮播、镇馆之宝推荐、研学预告与参观指南，一站式导流至馆藏、预约与活动
- **馆藏鉴赏**：按门类筛选藏品，详情展示图文档案、点赞与评论互动，支撑数字化浏览
- **陈列特展专栏**：浏览临展档期、封面与导览说明，关联展厅与票价信息
- **门票分时预约**：选择日期时段与人数下单，生成核销码/二维码；管理端支持入馆核销，保证一次有效
- **研学社教报名**：浏览活动名额并提交报名，个人中心跟踪报名状态
- **文创商城与订单**：浏览文创商品、下单支付与收货信息维护，库存随订购扣减
- **修缮纪实与资讯**：查阅文物修缮公示与文博资讯公告
- **AI 文博馆长**：围绕开馆信息、展讯与参观建议进行导览问答，管理端可审计问答记录
- **个人中心**：资料与密码维护，我的预约、研学与文创订单集中查看
- **经营数据大屏**：馆藏分布、预约趋势、文创热销等 KPI 与 ECharts 图表
- **档案与履约中台**：藏品/门类/展厅、特展发布、门票核销、研学与文创订单、评论审核、用户启停
- **论文与 UML 概览**：配套论文设计实现页拼图与 UML 图列表，便于答辩材料对照

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT + Lombok
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E9%A6%86%E8%97%8F%E9%89%B4%E8%B5%8F.png" alt="馆藏鉴赏" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E9%97%A8%E7%A5%A8%E9%A2%84%E7%BA%A6.png" alt="门票预约" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E6%96%87%E5%88%9B%E5%95%86%E5%9F%8E.png" alt="文创商城" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E9%97%A8%E7%A5%A8%E6%A0%B8%E9%94%80.png" alt="门票核销" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E7%AE%A1%E7%90%86%E5%91%98%E4%BB%AA%E8%A1%A8%E7%9B%98.png" alt="管理员仪表盘" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E8%97%8F%E5%93%81%E7%AE%A1%E7%90%86.png" alt="藏品管理" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/museummanage/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->
