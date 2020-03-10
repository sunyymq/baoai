功能特点：

- 超10万行代码

平台包含多个模块，并且模块数量仍不断的增加中。可用于各行业的前端和后端系统软件开发，已包含有CMS、人工智能、图像识别、人脸识别、大数据和量化投资领域等常用模块供开发人员直接使用。

- 平台模块化，易于开发扩展

BaiAI平台设计思路是将大型企业应用项目分解成很多小模块，每个模块分为前端模块和后端模块，前端模块使用后端模块提供的API服务。前后模块由脚本语言构成，无需编译，独立运行，独立部署。让企业应用、人工智能和量化系统开发更迅速、更简单

- 前端兼容多种浏览器

支持包括IE8以上、safari、firefox、chrome、360浏览器，腾讯浏览器、Android和IOS等多种PC和移动浏览器，原生支持ES5，代码无需编译即可直接运行。

- 兼容性好，跨平台，响应式设计

前端管理界面和扩展的内容管理系统基于Bootstrap响应式设计，能够兼容多个终端，无需为每个终端做一个特定的版本。支持PC、平板、手机、微信等各种设备的无缝显示。
后端采用Python开发，可运行于windows、linux、unix和macos多个操作系统平台。

- 平台二次开发学习曲线低，易上手

前端和后端都使用Visual Studio Code做为开发和调试IDE，前端构建工具使用易于学习和功能强大的gulp。前端开发只要集中于控制器、模板和服务调用三个方面的开发。

后端使用易学习、易使用和应用广泛的python语言，基于flask的Restful服务框架，提供了强大基于角色的权限管理服务、内容管理服务等，集成了numpy、pandas、scikit-learn、tensorflow、keras等常用人工智能框架，提供人工智能快速开发API。基于celery，提供的强大的队列消息服务和定时任务服务。基于backtrader和talib，提供了强大的金融量化服务。基于scapy提供了网络爬虫和股票金融数据采集服务。可安装在嵌入式系统中，为智能设备提供网络数据服务。

- 国际化

数据库默认生成的表包含语言字段，从数据核心层上支持国际化，用户可以快速的增加各种语言。平台默认自带了英语版本和中文简体版本，需要扩展其他语言的，可以通过配置模块等快速实现。

- 前后端代码分离

前后端可独立进行开发进行，前端工程师可专注写前端的代码，后端工程师专注写后端的代码，后端基于Restful提供相应的数据接口服务。

- 基于H5的单页面应用（SPA）

前端基于HTML5的WEB应用，所有资源动态加载，用户的操作集中在一个主页面中调度，获取内容无需页面重新加载或跳转，从而实现像手机应用一样的UI和用户交互体验。

- 自动代码产生器

通过自动代码产生器模块，可视化设置就可快速分别产生前端模块代码和后端模块代码，自动产生基于角色的资源、管理菜单和访问路由等。简单项目甚至可以实现零代码编写。

- 支持多数据库和数据迁移

数据库转换无需修改代码，仅修改config.py中的SQLALCHEMY_DATABASE_URI。基于ORM框架SQLAlchemy ，支持多数据库（如 SQLite、MySQL、Postgres、Oracle、MS-SQL、SQLServer 和 Firebird），通过数据迁移模块，使用Web界面就可以快速实现数据模型迁移和数据库表更新操作。

- 强大的富文本编辑

基于CKEditor和AngularJS相关指令，文章内容编辑和修改实现了跨平台操作，即可使用PC机还可以使用移动设备。编辑功能强大并可动态扩展。

实现图片和附件的拖放上传。实现从附件模块中选择分类图片或附件上传至CKEditor文本中编辑。

实现本地图片及从网站中复制的页网内容图片自动保存至本地服务器。使用简单，增加指令ng-ckeditor即可实现表单文本控件转化为CKEditor富文本编辑器。

- 人工智能

平台包含人工智能学习模块及应用模块。提供了机器学习常用接口，及深度学习接口。包括各种常见的人工智能学习模块及图像识别、人脸识别，智能量化等应用。

- 大数据

基于Scapy爬虫采集模块、消息队列和任务模块、自动代码产生模块、数据迁移模块实现了各种类型网站的数据快速采集。

- 金融数据采集模块

每天定时自动采集股票、指数、基本面、财务等多种金融数据，为证券投资者提供可靠的数据基础。

- 量化分析

智能股票选择及交易策略，根据交易策略产生相关的回测报告及分析数据，为证券投资者提供强大的技术保障。

- 完善的开发和部署工具和方案

前后端开发和调试工具都使用功能强大和免费的Visual Studio Code。前端构建工具使用gulp。

前端部署使用nginx服务器，简单的设置nginx配置文件即可实现多服务器负载均衡，反向代理使用户无需关心后端服务地址，仅需暴露前端80端口提供给用户，增加了系统的安全性。

后端使用高效和稳定gunicon做为wsgi服务器，supervisor做为后端应用的守护程序，管理应用进程方便高效，并能随时自动监护应用。

- 前端和后端框架选型，深思熟虑

前端和后端实现目的：建立一个简洁、直观、强大和易于掌握的前端和后端SPA开发框架，支持国际化，以模块为基础，让WEB应用、人工智能、大数据和量化系统开发更迅速、更简单。实现大型企业项目的模块化开发，快速部署，无需编译，快速运行。