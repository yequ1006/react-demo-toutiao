# react 仿今日头条webapp
## 为什么要做这个
  * 平时比较喜欢折腾，所以才入了前端这个坑，它满足了我最大化的求知欲
  * 目前公司的前端技术栈还是停留在jq的时代，前后端看似分离，其实还是jsp的后端返回页面的技术，对于前端的个人发展，有着不小的瓶颈，所以如果生活局限了你，那自己也不能局限了自己，如果平时的业务满足不了自己的发展，那就利用空闲时间，自己折腾寻求突破
  * 去年夏天，接触了vue全家桶，并仿写了cnode论坛，小试牛刀，带领自己进入了全新的前端世界，学习不该停止，相比较vue的快速上手，react吸引我的是js is all的语法，所有的一切都是在写Js，函数式，高级组件，等等，结构化上面的统一，让我对它有着持续不断的了解，但理论总归是单薄的，实践出真知，所以才会想着，使用它做点什么东西出来，这样才能掌握的更深刻一些
## 一、技术栈
* react + react-redux + react-router + webpack

## 二、结构
* build webpack配置
* config 项目配置参数
* src  
    actions:存放action方法  
    assets:静态资源文件，存放图片等等  
    components:常用组件  
    reducers:存放reducer  
    router:路由管理  
    store:状态管理 redux  
    styles:样式文件  
    utils:常用的工具封装  
    views:视图页面  
* static 静态文件

# 目前进度
* 2018.5.7  完成项目结构的搭建，webpack与react开发环境与生产环境的配置 
            项目框架试运行  
            1、将项目文件clone到本地  
            2、npm install 安装项目所依赖的包  
            3、npm run dev 运行开发环境

* 2018.5.8  
    1、完成路由的相关配置  
    2、一些公用组件的开发，公用的弹窗组件  
    3、路由跳转错误的404页面开发  
    4、初始化action 以及 reducer  
    5、common模块的action和reducer编写

* 2018.5.9  
    1、异步加载组件的工具函数asyncComponent编写  
    2、components模块中，Header和Footer组件的编写  
    3、views视图模块中，个人中心Account view的编写  
    4、user模块的action和reducer编写

* 2018.5.10  
    1、Login登录页的组件编写  
    2、个人中心页相关交互的完善  
    3、公用弹窗Alert组件的引入  
    4、loading效果组件的编写   
    5、TitleBar公用组件编写      
    6、开关按钮Switch组件编写

* 2018.5.11  
    1、我的商城页面编写  
    2、系统设置页面编写以及交互完善   
    3、暂无数据模块的编写  
    4、消息通知页面编写  
    5、用户反馈页面编写  
    6、京东特供页面编写  
    7、微头条headline相关数据处理  

* 2018.5.14  
    1、headline相关数据整合  
    2、headline页面结构搭建  
    3、headline页面topbar组件编写  
    4、headline页面text组件编写  

* 2018.5.15  
    1、headline组件相关样式编写和调整   
    2、上拉下滑组件PullLoad编写  

* 2018.5.16  
    1、PullLoad样式编写  
    2、headline组件数据加载相关bug以及样式处理   
    3、文章详情页article编写    
    4、circleLoading加载组件编写  
    5、文章详情页article 相关action reducer编写  
    6、我的收藏record页面编写   

* 2018.5.17   
    1、我的收藏record样式编写    
    2、search页面action和reducer编写  
    3、search页面head和body组件编写  
    4、search页面样式表编写  
    5、home页面actions和reducer编写    

* 2018.5.18  
    1、新闻分类数据data.js编写   
    2、新闻分类弹出栏组件编写    
    3、home页topbar组件编写    
    4、home页content组件编写  
    5、home页样式以及结构编写 

* 2018.5.23  
    1、视频模块的编写   
    2、视频模块actions和reducers编写  
    3、组件和样式编写  

* 2018.6.20  


相关效果图的展示： 
 
![](https://github.com/bettermu/blog-picture-store/blob/master/toutiao/%E6%95%88%E6%9E%9C%E5%9B%BE1.gif?raw=true) ![](https://github.com/bettermu/blog-picture-store/blob/master/toutiao/%E6%95%88%E6%9E%9C%E5%9B%BE2.gif?raw=true) 

  
* 先完成基本结构框架的搭建，项目运行起来，后续的开发工作，将利用空闲时间慢慢完成。
* 于5.23日完成，差不多用了2周时间，后续会给出该项目的相关经验总结

