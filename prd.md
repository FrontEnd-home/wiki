##需求文档

鉴于网络上优秀的资源已经足够多，而搜索引擎无法突破的种种困境，难免要让大家经历痛苦的筛选，好的东西，排名不一定靠前，于是乎，大家见到好的东西，就会收藏起来，久而久之，收藏夹也混乱了。。。

而收藏夹也有一个弊端，难以共享交流，于是网络收藏夹应运而生。。。

###简单描述

此需求，旨在为大家推荐优秀的网站链接，将优秀的东西，按分类集中的展现到大家面前，初步实现即开发者指南，也就是开发者摘这里将都是有营养的游历

###初步实现

1、实现网络收藏夹功能，共享优秀的网站
2、初步实现，只时间基本功能：分类、筛选以及简单排序
3、目标：简约布局，清晰明了，操作便捷，质量上乘
4、第一准则：快、精准、傻瓜化
5、其他：浏览器标签，方便提交优秀的网站

###项目规划

- 单页面应用实现，力求速度
- 所有的操作（关注的类目）都是本地操作，速度极致
- 路由控制，支持分享与直接访问筛选类目
- 操作简单便捷，配置完备的搜索框功能,支持快捷键
- 简单记录访问次数，热门程度，用户可以提交优秀网址
- 分类优秀网站，常用工具等

#### 相关技术实现

- 使用 nodejs 配合 nginx 做服务
- 使用 ejs 模板，入门简单
- 使用 mangoDB，对后期发展支持明显
- 路由控制，单页应用
- 简单的后台，编辑数据
- 配置快速精准的搜索框
- icon的自动整合处理
- 打包处理，模块划分
- 用户意见及建议反馈等
- 快捷键支持，符合常用操作习惯
- 离线存储，本地访问，间隔性同步更新
- 增加手势，更大程度的便捷操作

###后期规划（暂不分先后）

- 增加注册用户功能，可进行关注订阅等操作
- 支持订阅/关注类目的离线访问
- 操作访问统计，优化排序算法
- 关注的类目有更新会推送，另外有类似每日福利的推送
- 多维化分类方式（按编程语言以及功用性等）
- 系列类目，教程类，方便系列式学习
- 增加难度等级，入门，中级，进阶，练习
- 可自定义便捷访问，支持搜索直达，如 **** 官网
- 增加趣味性，惊喜不断，冒出个笑话，哲理？
- [第二阶段]制作浏览器插件扩展，方便与浏览器收藏夹交互
- [第二阶段]增加内容爬取，这里有几个需要攻克的问题，自动匹配，自动排版，自动分类？
- [第二阶段]解决内容跟踪，更新后会发出提醒等