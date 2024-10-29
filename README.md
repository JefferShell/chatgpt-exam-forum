## 项目简介

这是一个完整的推荐系统，自带菜谱数据，初始化在sqlite数据库一份，在neo4j中一份。系统可以通过用户浏览记录做推荐。


## 主要功能

**用户端：**

- 完善的用户系统，登录注册退出登录无问题。
- 主页可查看菜谱列表，并可翻页。
- 可以收藏菜谱，点赞菜谱。
- 主页可模糊搜索菜谱。
- 点击菜谱可进入菜谱详情页，并可评论菜谱或回复他人评论。
- 点击推荐tab可以进入推荐菜谱页面，推荐根据浏览的菜谱数据，从neo4j查询推荐数据。


**管理员端：**

- 管理菜谱和评论数据，增删改查。


## 技术架构

- 基底层架构：Django
- 数据库：SQLite、Neo4j
- 推荐：关系图谱的相邻节点近似属性


## 使用说明

1. 下载项目源代码。
2. 在项目根目录下安装依赖项。
3. 初始化neo4j数据库，并将其与项目中配置。
4. 运行项目，并登录系统。


## 联系方式

微信号：zt745324325