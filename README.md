# vue2-manage
vue2.0 + elementUI 后台管理平台


# 概述
vue2.0 + element UI完成后台管理系统，主要实现用户信息管理。通过项目的架构分析，模块搭载，脚手架搭载配置，实现功能包括增删改查，所使用的技术有vue-router路由、vuex、二次封装axios接口请求、element ui组件库、mock后台数据模拟、echarts图表可视化。
# 依赖项版本
  
     更新：vue已升级至2.5.X，elementUI已升级至2.2，其他相关依赖也已升级，
     具体请参考https://github.com/chintl510/vue2-manage/blob/master/package.json
     
     
# 特别提醒
 为了便于项目在github pages直接在线预览，部分配置与本地运行配置不一样。目前有2处，代码中已有详细说明，遇到问题可自行修改：
 
 一是在`config/index.js`中的`assetsPublicPath: '/vue2-manage/'`,本地打包可改为`assetsPublicPath: '/'`
 
 二是在UE编辑器的配置`static/UE/ueditor.config.js`中，本地开发写`window.UEDITOR_HOME_URL = "/static/UE/"`即可。
# 更新
### 增加富文本编辑器(beta)

集成Ueditor富文本编辑器，作为公共组件,编辑器支持同页面多次调用,支持各式小功能。

效果如下：
![](http://images2015.cnblogs.com/blog/1023587/201707/1023587-20170711213454306-1844528970.png)
 
# 截图预览
![](http://images2015.cnblogs.com/blog/1023587/201704/1023587-20170417163412243-1686976549.png)
![](http://images2015.cnblogs.com/blog/1023587/201704/1023587-20170417163442727-1202100665.png)
![](http://images2015.cnblogs.com/blog/1023587/201704/1023587-20170417163508102-673769802.png)
![](http://images2015.cnblogs.com/blog/1023587/201704/1023587-20170424111627287-2091967244.gif)
## Build Setup

``` bash
#clone
git clone https://github.com/chintl510/vue2-manage.git

# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

