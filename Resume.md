### 联系方式

- 手机：13761223471
- Email：shannonchenchn@foxmail.com

---

### 个人信息

 - 陈祥龙 / 男 / 1992.10 / 湖南 
 - 本科 / 中北大学 / 飞行器制造工程专业 
 - 工作年限：3 年（2014 年 06 月毕业）    

 - 个人博客：[http://www.jianshu.com/u/4ef5e287fc91](http://www.jianshu.com/u/4ef5e287fc91)
 - Github：[https://github.com/ShannonChenCHN](https://github.com/ShannonChenCHN)
 
 - 应聘职位：iOS 开发工程师

---

### 工作经历


#### 上海悦会信息科技有限公司 （ 2016年08月 ~ 2017年03月 ）
###### 职位：iOS 开发工程师

**项目：OnlyU （单人开发、视频聊天+IM+社区）**

- **创新优化点**：
  - 采用 URLRoutes 的方式来处理页面跳转（推送跳转、轮播图动态配置跳转）
  - 借助并改进 In-App 调试工具，方便 UI 设计师和服务端开发人员
  - 运用 runtime 和分类的结合来实现灵活的、低耦合的埋点需求
  - 借助本地化的方式来集中管理文案，既方便修改，又有利于后期文案本地化的快速开展
  - 数据持久化的集中管理，防止后期业务增多后的失控
  - 优雅地使用 WebViewJavascriptBridge 来处理 webView 中 Objective-C 和 JavaScript 交互，使得 WebViewController 中的代码由原来的 200 多行减少到了 140 多行
  
- **问题和挑战**：
  - 架构选型
  - 网络层的设计
  - 首页交互动画
  - 第三方服务的选择（IM 和视频通话）
  - 通过上传日志来监控视频聊天时出现的问题，视频聊天匹配逻辑的 bug 调试
  - 美颜、贴纸
- **Get 到的新技能**：
  - 单元测试
  - 借助 QuartzCore 框架和 coreAnimation 框架，实现了视频聊天匹配页面的水波动画
  - 借助 QuartzCore 框架，实现了视频聊天倒计时的方形进度条
  - 通过实现 UIViewControllerTransitioningDelegate 和 UIViewControllerAnimatedTransitioning 协议，来实现聊天大厅的转场动画
  - 通过处理 cookie 来管理用户的登录，并实现原生和 webView 的 cookie 互通
  - 不同环境下的 xcode-configurations 配置

 
#### 宝宝树的电商-美囤妈妈 （ 2015年10月 ~ 2016年07月 ）
###### 职位：iOS 开发工程师

**项目：宝宝树孕育、美囤妈妈 （5人团队、电商）**   
 
- **创新优化点**：
  - 自定义 UICollectionViewFlowLayout， 实现一个首页列表，使得每个 cell 都有一个 header，且每个 cell header 都能像 UITableView 的 section header 一样可以吸顶，并且对 UICollectionView 的代理方法调用进行封装，在实现功能的同时还保证了代码的可维护性，并将成果（SCStickyCellHeaderCollectionView）开源到了 Github 上
  - 三级分类列表的低耦合设计
  - 通过 分类 + runtime 的形式优雅地实现了自定义 UITabBarButton 上的小红点
- **问题和挑战**：
  - 让 UIWebview 支持 WebP 格式图片的加载，以及性能优化
  - 实现多 APP 间共享同一个设备唯一标识
  - 与前端同学一起解决 webView 中加载 h5 页面时崩溃的问题，
  - 通过 Instrument 工具找出了机身发热的元凶 —— 导航栏中跑马灯的 bug 导致 CPU 消耗过高

- **Get 到的新技能**：
  - 阅读了 MJRefresh 和 SVPullRefresh 源码，尝试自己实现了一个 下拉刷新控件 MTRefresh
  - webView 中 Objective-C 和 JavaScript 之间的交互的几种不同方式
  - 编写 shell 脚本，使用 xcodebuild 实现自动化打包
  - 自定义  UICollectionViewFlowLayout 来实现 item 间距固定的 collectionView


#### 中航工业江西洪都航空工业集团有限责任公司 （ 2014年07月 ~ 2015年09月 ）

######职位：飞机装配工艺工程师
---

### 开源项目和作品


#### 开源项目

 - [SCStickyCellHeaderCollectionView](https://github.com/ShannonChenCHN/SCStickyCellHeaderCollectionView)：A custom UICollectionView wrapper with sticky "cell" header effect, and it has UICollectionView-like API.

 ```更多项目见个人 Github```

#### 技术文章

- [如何获取设备唯一标识？以及多个App间如何共享同一个设备唯一标识？](http://www.jianshu.com/p/25eb5fd24c59)
- [如何处理 iOS 原生网络请求中的 cookie ？](http://www.jianshu.com/p/d144bd7226b7)

```更多文章见个人博客（简书）```

#### 演讲和讲义

  - In-App Puchase 技术调研成果分享：[InAppPurchaseGuide](https://github.com/ShannonChenCHN/InAppPurchaseGuide)

```详见个人 Github```

### 技能清单

- 语言：
  - C（熟练）
  - Objective-C（熟练）
  - Swift（入门）
  - JavaScript/HTML/CSS(了解)
- 版本管理：SVN、Git