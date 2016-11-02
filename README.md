# Three-linkage
Province urban linkage

Meteor官方推荐的组件包
每个Meteor开发者遇到的第一个问题可能就是组件包的选择，Meteor平台上有大量的组件包，但都需要每个开发者自己去分辨和试验，这篇文章是Meteor社区和官方共同选出优秀的组件包列表，熟练的掌握了这些组件包，基本可以解决在Meteor中遇到的大部分问题。

Meteor社区针对不同的功能需求，分别推荐一些组件包或者文章或者资源。

我会逐渐将这篇文章中推荐的组件都一一翻译成中文。通过阅读这个推荐资源基本可以晋级Meteor的高级开发者了。

:heart:️加心的重点推荐:heart:️

入门指南
从这开始学习Meteor

官方 Meteor 教程2
中文的Meteor电子书5 - 初学者必备:heart:️:heart:️:heart:️:heart:️:heart:️
官方技术指南
为什么选择 Meteor2 和 Meteor vs. the MEAN stack - 两篇博客文章
Collections 数据集合
数据集合的扩展工具

aldeed:collection2 - 支持客户端和服务器端的数据集合的自动验证工具 :heart:️:heart:️:heart:️:heart:️:heart:️
dburles:collection-helpers – 数据集合助手，可以组合多个字段或者
matb33:collection-hooks - 数据集合扩展，在 insert/update/remove/find/findOne 方法上增加了多个事件 before/after。
reywood:publish-composite - 允许订阅数据时联合查询多个数据集发布到一个订阅方法里。:heart:️:heart:️:heart:️:heart:️
REST 服务
REST服务支持

simple:rest - 全自动构建Meteor应用方便访问的HTTP和DDP的REST接口。
nimble:restivus - 方便简单的创建Meteor的REST接口。
表单和模板
表单和模板工具

aldeed:autoform - 配合collection2实现自动生成表单，支持自动验证、支持插入事件、更新事件。:heart:️:heart:️:heart:️:heart:️
dispatch:scrollview - 速度奇快的滚动组件
themeteorites:blaze-magic-events - 一套新的基于Blaze模板的绑定事件和增强工具
manuel:viewmodel - MVVM模型的meteor支持
webix:webix - Meteor.js - Webix界面集成
用户和认证
用户和认证的工具

alanning:roles - 基于accounts组件包的权限组支持.:heart:️:heart:️:heart:️
部署
Meteor项目的部署和管理工具

Meteorup1 - 最简单好用，支持中文环境的Meteor部署工具。:heart:️:heart:️:heart:️:heart:️:heart:️
When a Meteor finally hits production - 一篇博客文章，介绍如果部署Meteor项目
BulletProof Meteor - Meteor性能优化工具:heart:️:heart:️:heart:️
meteorhacks:kadira1 - 性能监听分析工具.:heart:️:heart:️:heart:️
meteor-up – 部署工具.
davidyaha:collection2-migrations - 自动迁移其他数据库到Meteor（使用 collection2 和 simple schema这两个组件）
percolate:migrations - 将系统迁移到Meteor的工具
meteorhacks:fast-render - 快速渲染界面，边加载数据变渲染界面:heart:️:heart:️:heart:️:heart:️:heart:️
meteorhacks:cluster - 基于负载均衡和服务接口的集群工具
yogiben:admin - 一个完整管理后台界面UI
demeteorizer - 转换Meteor app成为一个标准的NodeJS应用
Amazon auto scaling and Meteor - 一篇博客文章，教你如何部署、更新Meteor项目到Amazon的高可用性服务器上。
路由
基于Blaze模板的路由组件

iron:router - 支持客户端和服务器端的路由.
meteorhacks:flow-router - 纯客户端路由.（主流路由）:heart:️:heart:️:heart:️:heart:️:heart:️
离线工具
让Meteor项目可以离线使用的工具

ground:db - GroundDB是一个轻量级的离线数据库
测试工具
测试工具

Meteor 测试手册
Velocity - 一个响应式测试工具.
mike:mocha – 集成测试框架 Mocha 到 Meteor 中.
sanjo:jasmine - 集成测试框架 Jasmine 到 Meteor 中.
xolvio:cucumber - 使用 Cucumber.js 和 Velocity 做响应式数据驱动测试.
velocity:html-reporter - 集成 velocity 测试框架输入HTML报表.
文件管理
访问文件的工具

Meteor-CollectionFS - 基于WEB的文件管理工具，支持文件的上传下载。（作者已不维护）:heart:️:heart:️:heart:️
netanelgilad:excel - 分析生成excel文件(xlsx,xls)
搜索分页排序
搜索分页排序的相关工具

tmeasday:publish-counts - 实施订阅数据总数的工具（用于分页）
percolate:find-from-publication - 查询并订阅所有数据的插件。
meteorhacks:search-source - 响应式的数据搜索
matteodem:easy-search - 简单易用的搜索组件（基于Blaze，支持Elastic搜索）
alethes:pages - 分页组件
Discover Meteor Blog 关于分页的文章
移动开发
支持手机移动开发的工具

meteoric:ionic - 用Blaze集成Ionic组件到Meteor中.
driftyco:ionic - 官方的Ionic支持（需要Angular）.
raix:push - 支持cordova（ios，android）和浏览器（Chrome, Safari, Firefox）的消息推送组件
martijnwalraven:meteor-ios - 通过DDP集成IOS原生开发。
delight-im/Android-DDP - DDP的andorid客户端
okland:accounts-phone - 基于手机号登陆注册的Accounts组件.
okland:camera-ui - 支持手机和浏览器的相机和照片组件。
percolatestudio/cordova-plugin-safe-reload - 基于cordova的热推送组件
分析
流量分析

okgrow:analytics - 集成谷歌分析、Mixpanel、KISSmetrics等（多种）平台的插件:heart:️:heart:️:heart:️
计划任务
计划任务系统

percolate:synced-cron1 - 异步、多进程的cron计划任务系统
调试工具
Debugging Tools

msavin:mongol - 方便的可视化的Minimongo显示工具（只支持客户端）:heart:️:heart:️:heart:️:heart:️:heart:️
msavin:jetsetter - Session变量的get、set可视化工具
meteorhacks:kadira-debug -全栈的调试解决方案
babrahams:constellation - console的扩展工具
Meteor DDP Monitor - 集成在chrome调试工具中的DDP流量监控工具
Dr. Mongo - 开源小巧的MongoDB客户端，可以集成在应用中。
组件包管理
管理组件包的工具

meteorhacks:npm - 方便使用和管理NPM包的工具.
cosmos:browserify - Browserify 是一个客户端的npm管理工具.
脚手架
脚手架

Meteor Kitchen - 代码生成工具
iron-cli - 基于命令行的代码生成工具
Differential - meteor-boilerplate
matteodem - meteor-boilerplate
meteoris2
Base
工具
ESLint-plugin-Meteor - ESLint plugin for Meteor JS代码语法规范检测工具ESLint
开源项目
Telescope - 开源的社交新闻平台
Microscope - The Discover Meteor book's example app
Wekan - Open source Trello-like kanban
Reaction Commerce - 开源的基于Meteor开发的电子商务平台
Crowducate Platform - 开源的教育平台
Orion CMS - 开源的CMS平台和组件集合
前端框架
可以替代Blaze的其他前端框架

Blaze
React - 集成React到Meteor​:heart:️:heart:️:heart:️:heart:️
Angular - 集成Angular
Angular 2 - 集成Angular2
Famo.us - 集成 Famo.us

frozeman:build-client - A tool to bundle the client part of a Meteor app.

Asteroid - An alternative client for a Meteor backend
ddp.js - 另一个DDP客户端
其他的数据库支持
除了MongoDB，Meteor对其他数据库的支持

numtel:pg - 响应式 PostgreSQL 支持
numtel:mysql - 响应式 MySQL 支持:heart:️:heart:️:heart:️
simple:rethink - RethinkDB 数据库集成
Resources
Meteor相关的图书
Meteor Explained
Meteor Tips
Meteor Cookbook
Meteor网络课程
EventedMind1
Udemy — Meteor: Build a real-time web app using only JavaScript
Udemy - A Beginner's Guide to the Meteor JavaScript Framework
tuts+ - Single Page Web Apps with Meteor
DevFreeCasts.org
MeteorTuts
Meteor教程
scotch.io - Building a Slack Clone in Meteor
Rocket-Chat Slack Clone
Meteor Learning - List of resources to learn
Learning Resources for Meteor
Phusion Passenger: Meteor tutorial
Meteor的优秀博客
Official Meteor blog
Meteor Hacks Blog
Meteor Create - Discover the Best Meteor Tutorials
The Meteor podcast
Meteor club podcast
Blog about Optimistic UIs With Meteor Latency Compensation
Meteor相关的网站
Official website
Official Documentation
Official Guide
Atmosphere - The catalog of Meteor packages, resources and tools.
BulletProof Meteor - Online course for Meteor performance in production, by Arunoda Susiripala
Meteorpedia (infrequently updated)
DiscoverMeteor Encyclopedia
Roadmap
Meetups
Reddit
YouTube videos from meetups around the world
Unofficial Meteor FAQ
The Meteor Chef
Meteor相关问答社区

Stack Overflow
Meteor forums
Gitter IM channel
The Meteor Chef Slack channel
IRC - #meteor on freenode
Weekly
Meteor-Blog
Meteor Weekly
Crater.io
This Week In Meteor
Twitter
Official Meteor
Job Boards
We Work Meteor
