
# 扫码体验
<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wxmini.jpg" width="200" alt="小程序个性简历" />


# 前言

* 体验之前我们先来认识一下小程序，官方定义的微信小程序是一种新的开放能力，开发者可以快速地开发一个小程序。更是一种全新的连接用户与服务的方式，它可以在微信内被便捷地获取和传播，同时具有出色的使用体验。
* 如果感觉还不错的话，老铁们是不是赏个★Star鼓励一哈，后续会发布更多小程序DEMO源码，也期待大家的交流。

# 项目介绍/开发教程
[https://blog.csdn.net/qq_15041931/article/details/106178226](https://blog.csdn.net/qq_15041931/article/details/106178226)


# 效果截图

## 启动页(封面图)

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx1.jpg" width="200" alt="启动页" />

## 基本信息界面

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx2.jpg" width="200" alt="基本信息界面" />

## 工作经验界面

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx3.jpg" width="200" alt="工作经验界面" />

## 专业技能界面

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx4.jpg" width="200" alt="专业技能界面" />

## 技术博客界面

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx5.jpg" width="200" alt="技术博客界面" />

## 文章精选界面

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx8.jpg" width="200" alt="文章精选界面" />

## 文章详情界面

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx9.jpg" width="200" alt="文章详情界面" />



# 项目架构
```
│  app.js                  // 小程序逻辑    
│  app.json                // 小程序公共配置
│  app.wxss                // 小程序公共样式表
│  project.config.json     // 项目配置文件
│  sitemap.json            // 页面收录配置文件
├─images                   // 公共图片存放文件夹
├─pages                    // 注册页面文件夹
│  ├─about                 // 基本信息页面
│  │      about.js         // 页面逻辑
│  │      about.json       // 页面配置
│  │      about.wxml       // 页面结构
│  │      about.wxss       // 页面样式表
│  │      
│  ├─article               // 文章详情页面
│  │      article.js       // 页面逻辑
│  │      article.json     // 页面配置
│  │      article.wxml     // 页面结构
│  │      article.wxss     // 页面样式表
│  │      
│  ├─articles              // 文章精选页面
│  │      articles.js      // 页面逻辑
│  │      articles.json    // 页面配置
│  │      articles.wxml    // 页面结构
│  │      articles.wxss    // 页面样式表
│  │      
│  ├─blog                  // 技术博客页面
│  │      blog.js          // 页面逻辑
│  │      blog.json        // 页面配置
│  │      blog.wxml        // 页面结构
│  │      blog.wxss        // 页面样式表
│  │      
│  ├─index                 // 工作经验页面
│  │      index.js         // 页面逻辑
│  │      index.json       // 页面配置
│  │      index.wxml       // 页面结构  
│  │      index.wxss       // 页面样式表  
│  │      
│  ├─skill                 // 专业技能页面
│  │      skill.js         // 页面逻辑
│  │      skill.json       // 页面配置
│  │      skill.wxml       // 页面结构
│  │      skill.wxss       // 页面样式表
│  │      
│  └─welcome               // 启动页
│          welcome.js      // 页面逻辑 
│          welcome.json    // 页面配置
│          welcome.wxml    // 页面结构
│          welcome.wxss    // 页面样式表
│          
└─utils                    // 全局工具类文件夹
        icon.wxss          // 公共图标样式表 
        main.wxss          // 公共组件样式表
        util.js            // 全局JS工具类

```


# 技术栈
* 小程序原生框架
* 小程序原生组件（常用组件）
* 小程序原生API
* ColorUI组件库
* 微信web开发者工具
 
# 功能模块
* 启动页（CSS3动画）
* 底部tabBar导航栏
* 引用ColorUI组件库样式表
* 弹出二维码图片
* 直接拨打电话
* 保存通讯录
* 工作经验时间轴
* 多彩进度条
* 数字滚动
* 复制链接
* 页面路由跳转
* 小程序跳转web-view


## 申请账号

小程序账号注册流程，请移步官方文档，有详细说明。
[https://developers.weixin.qq.com/miniprogram/dev/framework/quickstart/getstart.html#%E7%94%B3%E8%AF%B7%E5%B8%90%E5%8F%B7](https://developers.weixin.qq.com/miniprogram/dev/framework/quickstart/getstart.html#%E7%94%B3%E8%AF%B7%E5%B8%90%E5%8F%B7)

## 安装开发者工具

前往[开发者工具下载界面](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)，根据自己的操作系统下载对应的安装包进行安装，有关开发者工具更详细的介绍可以查看 [《开发者工具介绍》](https://developers.weixin.qq.com/miniprogram/dev/devtools/devtools.html) 。

## 你的第一个小程序

新建项目选择小程序项目，选择代码存放的硬盘路径，填入刚刚申请到的小程序的 AppID，给你的项目起一个好听的名字，勾选 "不使用云服务" （注意: 你要选择一个空的目录才可以创建项目），点击新建，你就得到了你的第一个小程序了，点击顶部菜单编译就可以在微信开发者工具中预览你的第一个小程序。


<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx2_1.jpg" width="200" alt="你的第一个小程序" />


## 导入项目

<img src="https://github.com/jackchen0120/wxResume/blob/master/images/wx2_2.jpg" width="200" alt="导入项目" />

