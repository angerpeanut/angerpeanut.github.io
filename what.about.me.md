
---
|姓名：符新 | 电话：17682303793 |
|---|---|
|出生：19910908 |籍贯：海南|
|学校：2011级湖南大学 |专业：智能科学与技术|
|邮箱：<2290791526@qq.com> |网站：[http://angerpeanut.github.io/](http://angerpeanut.github.io/)|


### 技能
```php``` ```java``` ```golang``` ```mysql``` ```mogondb``` ```redis``` ```memcached``` ```nginx```
```thinkphp``` ```yii```
```springboot```  ```hibernate```
```vue``` ```react``` ```nodejs```
```Docker``` ```kubernetes```
```rocketmq``` ```storm``` ```Spark```

### 经历

- **职责**:后端架构、开发
- **公司**:客官到家、网站：[http://keguanchina.com/](http://keguanchina.com/)
- **业务**:末端配送集成
- **时间**:2016/8-2017/10
- **工作内容**:
```
1、收派模块开发
2、快递系统对接
3、统计系统设计、开发
4、API接口开发
5、带领5-7个人的技术团队
```


- **职责**:后端架构、开发
- **公司**:宝贝码头
- **业务**:母婴海淘toB
- **时间**:2015/11-2016/7
- **工作内容**:
```
1、交易、订单、商品系统设计
2、后台管理开发
3、统计系统设计、开发
4、API接口开发
5、带领4-5个人的后端技术团队
```

- **职责**：技术主管
- **公司**：大象洗车
- **业务**:上门洗车
- **时间**：2014/12-2015/10
- **工作内容**：
```
1、系统架构、api接口、pc管理后台、公众号开发；
2、mysql && nginx运维管理
3、带领7-10个人的前后端团队
```
---
- **职责**：android工程师
- **公司**：大象洗车
- **时间**：2014/11-2015/5
- **工作内容**：android app开发、pc管理台开发


### 项目

----
#### 客官到家：收派系统实现
  - **主要承担工作**：团队管理、系统设计、编码实现
  - **详情**:
  1、收派实现
  2、网点管理实现
  3、业绩统计系统


----
#### 宝贝码头：BD业绩统计系统
  - **主要承担工作**：BD团队管理、业绩统计功能实现
  - **详情**:
  1、BD团队无限制任意层级嵌套新建、解散、人员转移、业绩转移
  2、BD业绩统计、BD团队业绩统计
  3、业绩统计系统数据库与用户数据库分离，使用redis的消息队列实现异步统计

----
#### 宝贝码头：微服务模块
  - **主要目的**：系统重构、增加系统可扩展性与可靠性
  - **主要承担工作**：模块架构设计、编码实现
  - **详情**：
  1、订单微服务
  2、商品微服务
  3、店铺微服务
  4、用户微服务

----
#### 宝贝码头：后台管理
  - **主要承担工作**：管理模块功能实现
  - **详情**:
  1、订单管理
  2、商品管理
  3、门店管理
  4、BD管理
  5、类目管理
  6、广告、活动管理
  7、基于ace模板实现

----
#### 宝贝码头：b端pc版功能实现
  - **主要承担工作**：订单、商品模块设计，b端页面渲染，业务逻辑实现
  - **主要承担工作**：订单、商品模块设计，b端页面渲染，业务逻辑实现
  - **详情**:
  1、商品分类、商品详情功能
  2、订单流程管理

----
#### 大象洗车：用户轨迹模块
  - **主要目的**：给大象洗车app导入流量，增加app活跃度
  - **主要承担工作**：原型设计、数据库设计、api实现
  - **详情**：

  1、项目用php thinkphp框架开发，nginx做web服务器，mysql做数据持久存储，redis做前端数据缓存。<br>
  2、本功能模块主要功能有：用户轨迹记录、用户轨迹详情、用户里程排行榜。<br>
  3、本人主要负责原型设计、数据库设计、api实现。用墨刀做原型设计，用MySQL Workbench做数据库设计。

----
#### 大象洗车：后端服务功能开发
  - **主要目的**：增加新功能
  - **主要承担工作**：用php新功能开发、DB设计
  - **详情**：

    1、本人主要开发以下功能：定时取消订单、定时调整洗车预约时间、增加活动功能模块。<br>
    2、当用户下单30分钟后，未能付款，需要定时取消订单。在centos开启一个crotab定时器，1分钟运行一次取消订单程序，把未付款订单取消。<br>
    3、根据洗车工空闲时间、空闲数量调整洗车预约时间。在centos开启crotab定时器，5分钟运行一次预约程序。提供手动调整洗车预约时间功能。<br>
    4、在节假日等时间给用户显示相关活动信息。信息显示形式有app主页弹窗、微信公众号主页轮播图、微信公众号弹窗。

----
#### 大象洗车：后端代码重构
  - **主要目的**：提高可靠性、增强扩展性
  - **主要承担工作**：代码重构
  - **详情**：

      1、后端代码第一版本是外包demo版本，面条式代码，mvc未分离。代码耦合度高不可复用，功能不稳定，代码逻辑繁杂。<br>
      2、本人主要承担mvc分离重构主要工作。<br>
      3、分离mvc，重model轻controller；抽象基本服务，把支付功能、活动功能、短信功能、消息推送功能模块化。


#### 大象洗车：android app页面、功能重构
  - **主要目的**：提高可靠性、增强扩展性
  - **主要承担工作**：app主要功能代码重构
  - **详情**：

    1、android第一版本是外包demo版本，代码耦合度非常高，功能不稳定。并且用java写的view，可读性非常差。<br>
    2、本人主要工作：调整主页面架构；把controller、model、view分离；支付模块分离、增加分享模块；统一管理dimen、string、color资源。

----
#### 大象洗车：android app开发
  - **主要目的**：保持周期迭代、增加新功能、及时修复已知bug
  - **主要承担工作**：app主要功能开发
  - **详情**：

    1、本人主要开发如下功能：增加业务动态调整功能、分离订单创建与支付、增加vip充值功能<br>
    2、优化定位精确度、优化页面显示



### 兴趣
```人工智能``` ```读书``` ```滑冰``` ```音乐``` ```足球``` ```排球``` ……

### 书籍
```《设计模式》``` ```《人月神话》``` ```《黑客与画家》```……

```《失控》``` ```《奇点临近》```……

```《自私的基因》``` ```《裸猿》```……
### 音乐
```李建``` ```李宗盛``` ```笛子``` ……
### 影视
```《神秘博士》``` ```《武林外传》``` ```《黑客帝国》``` ```《救赎》``` ……
