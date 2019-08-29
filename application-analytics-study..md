## 技术选型预研：
### 国内：
  [TalkingData](#TalkingData)    
  [友盟+](#友盟)  
  [Cobub Razor](#CobubRazor)  
  [百度统计](#百度统计)  

### 国外：
  [Google Analytics](#GoogleAnalytics)
  
## 具体选型调研
### TalkingData
  - [官网](https://www.talkingdata.com/products.jsp?languagetype=zh_cn)
  / [demo](https://www.talkingdata.com/spa/app-analytics/)
  - 开源/收费：  不开源，第三方平台，免费(应用统计分析服务)
  - 平台支持： 跨平台，支持HTML5，单独集成HTML5文档
    ![TalkingData平台支持](https://www.z4a.net/images/2019/08/28/talkingData-.png)
  - 使用/文档：
    [HTML5](http://doc.talkingdata.com/posts/36)
    [微信小程序](http://doc.talkingdata.com/posts/484)
  
  - 客户行为分析
    页面访问、事件分析、转化漏斗、用户趋势、渠道分析、卸载分析、留存分析
  - 特点：  
    - 优点
      1. 文档详细
      2. 支持原始日志导出：  
        客户除了通过报表和OpenAPI获取统计数据外，还能导出原始日志数据，对您的产品进行跟详细的分析
      3. 支持自定义事件
    - 不足
      1. HTML5平台暂未支持获取联网方式、运营商、机型信息功能
    
  - [隐私政策](https://www.talkingdata.com/privacy.jsp?languagetype=zh_cn)
  
### 友盟+
  - [官网](https://web.umeng.com/main.php?spm=a211g2.181323.0.0.3cb275efYxY3Dv&c=user&a=index)
  / [demo](https://web.umeng.com/demo.php?spm=a211g2.11755511.1387249.2.7d2519e9xhKuKZ)
  - 开源/收费：  不开源，第三方平台，免费
  - 平台支持：  
    U-App 移动统计  
        产品介绍: 实时多维数据，全景展现移动应用表现力，分析用户属性和行为，服务产品优化与运营推广。  
    U-Web 网站统计  
        产品介绍: 同时适用于pc页面和移动端页面，为保证统计数据的准确性，请将cnzz的统计代码放置在其他统计代码的前面，加载此代码不会影响您网页的正常显示和加载速度。
  - 使用/文档：  
    [事件统计文档](https://open.cnzz.com/a/new/trackevent/)
  
  - 特点：  
    - 优点
      1. 稳定性：实时
      2. 文档详细
      3. [支持异步载入](https://developer.umeng.com/docs/67963/detail/68646)
      4. 功能支持页面统计（pv,uv），还有事件统计
      5. 使用自己的umid策略，可以过滤刷量数据(准确性不错)
      6. 报表相对固定，基本都是单维的，无法做更深入的多维分析(据说)
    - 不足
  
  - [隐私政策](https://www.umeng.com/policy?spm=a211g2.11755511.0.0.148319e9pQ0r2r)

### 百度统计
  - [官网](https://tongji.baidu.com/web/welcome/login)
  / [demo](https://tongji.baidu.com/web/demo/overview/index?siteId=5503017)
  - 开源/收费：  不开源，提供免费版本(站长版)
  - 平台支持：
    网站统计
    移动统计：安卓、IOS、小程序 
  - 使用/文档：  
    [使用指南](https://tongji.baidu.com/web/help/article?id=170&type=0)
    
  - 客户行为分析报告
    流量分析、来源分析、访客分析、转化分析、优化分析
  - 特点：  
    - 优点
      1. 集成百度推广数据
      2. 单页应用(SPA)跟踪
    - 不足
      1. 自定义性较差

  - [隐私政策](https://tongji.baidu.com/web/help/article?id=330&type=0)
    
  ### CobubRazor
  - [官网](http://www.cobub.com/cobub-razor/)
  / [demo(web版、微信小程序、IOS、Android)](https://c4j.cn/demo/)
  - 开源/收费：  开源的移动应用统计分析系统
  - 平台支持：支持iOS / Android / Windows Phone / 混合型应用
  - 使用/文档：http://docs.cobub.com/pages/viewpage.action?pageId=884751
  
  - 分析数据（WEB应用）：  
    流量数量指标：今日流量、趋势分析、实时访客、浏览量、访客数、访问次数、新访客数、IP数
    流量质量指标：跳出率、平均访问时长、地域分布、TOP10(入口页面、来源网站、受访页面）、事件统计、系统环境
    流量转化指标：事件转化、目标达成、页面上下游
  
  - 特点：  
    - 优点
      1. 可把平台搭在自己的服务器上
      2. 提供移动端报表展现，随时获取APP报告
    - 不足
      1. 支持平台有限,web端和小程序版没有详细文档
  
  - 各版本比较(开源版、商业版、大数据版)  
    ![Cobub Razor各版本比较](https://www.z4a.net/images/2019/08/29/_20190829154528.png)
  
  - [开源协议](http://docs.cobub.com/pages/viewpage.action?pageId=1638542)
    
  ### GoogleAnalytics
  - [官网](https://developers.google.com/analytics/?hl=zh-cn)
  - 开源/收费：  不开源，有免费版
  - 平台支持： 支持WEB端
  - 使用/文档：
  - 特点：  
    - 优点
      1. GA支持异步载入，google有异步加载代码，速度快，损耗更小
      2. 集成了Google推广的数据(对网站排名有影响？)
    - 不足
      1. 服务器不在国内，有丢包，20%以内(据说)
      2. 尽管异步载入代码，但网络出现问题是会导致页面一直在加载中(据说)
      3. 免费版一旦请求数据过大，GA会进行采样
      4. 高级功能使用门槛较高,要求运营人员掌握正则表达式等技能

  - [隐私政策]()

### 参考资料
  [用户行为统计分析工具比较](https://blog.csdn.net/marlene0312/article/details/17009909)
