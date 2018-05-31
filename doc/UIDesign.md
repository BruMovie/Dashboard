# UI design
 ---
 ### 根据设计的用例及大致产品结构，简单的规划了主要的部分 UI 结构，页面之间的约定关系大概如下图：
 <center>
 <img src = "https://github.com/BruMovie/Dashboard/blob/gh-pages/doc/images/UI/UI_STRUCT.png?raw=true"> 
</center>


**①用例"电影" UI 设计**

#### 用户打开小程序，首先展示的主界面就应该是“电影”页面，页面设计如截图：
 
<center>
 <img width = "250px" src = "https://github.com/BruMovie/Dashboard/blob/gh-pages/doc/images/UI/film1.png?raw=true"> 
 <img width = "253px" src = "https://github.com/BruMovie/Dashboard/blob/gh-pages/doc/images/UI/film2.png?raw=true">
</center>
   
   - 在“电影”页面中，顶部从左至右，依次是定位键、热映、待映以及搜索图标，分别点击进入城市定位、热映电影展示页、待映电影展示页以及搜索界面
   
   - 往下便是电影展示的主区域，内容以小卡片的形式展示，卡片显示内容包括
    
       - 电影海报
       - 电影名称
       - 电影类型
       - 电影主演
       - 放映影院数量与场次
       - 评分或想看人次
      
**②用例"我的" UI 设计**

#### 用户打开应用，点击底部菜单栏"我的"，便可跳转到用户个人信息页面，页面设计如截图：
 
<center>
 <img width = "250px" src = "https://github.com/BruMovie/Dashboard/blob/gh-pages/doc/images/UI/mine1.png?raw=true"> 
 <img width = "253px" src = "https://github.com/BruMovie/Dashboard/blob/gh-pages/doc/images/UI/mine2.png?raw=true">
</center>
   
   - 在“我的”页面中，顶部蓝色区域，用于展示用户头像与用户名，作为一款小程序，自然是用于呈现所绑定的微信用户的头像与昵称
   
   - 随后区域第一部分是“我的订单”，在这里分别展示了用户的四类订单： 
     
     - 即将观影: 下单已支付或未支付，等待观影的订单
     - 观影足迹: 下单已支付且已观影的历史订单
     - 观影周边: 下单已支付的观影周边订单（如：观影时的零食饮料、观影前后产生的周边购买订单）
     - 观影评价: 下单已支付且观影后填写了影片评价的订单
     
   - 再往下便是常见的优惠券、会员卡、观影卡/票的入口热区；然后是用户想看的电影和看过的电影两个合集入口
   
**③用例"影院" UI 设计**

#### 点击底部菜单栏"影院"，便可跳转到用户个人信息页面，页面设计如截图：
 
<center>
 <img width = "250px" src = "https://github.com/BruMovie/Dashboard/blob/gh-pages/doc/images/UI/cinema1.png?raw=true"> 
 <img width = "253px" src = "https://github.com/BruMovie/Dashboard/blob/gh-pages/doc/images/UI/cinema2.png?raw=true">
</center>
   
   - 在“影院”页面中，顶部蓝色区域，用于展示用户头像与用户名，作为一款小程序，自然是用于呈现所绑定的微信用户的头像与昵称
   
   - 随后区域第一部分是“我的订单”，在这里分别展示了用户的四类订单： 
     
     - 即将观影: 下单已支付或未支付，等待观影的订单
     - 观影足迹: 下单已支付且已观影的历史订单
     - 观影周边: 下单已支付的观影周边订单（如：观影时的零食饮料、观影前后产生的周边购买订单）
     - 观影评价: 下单已支付且观影后填写了影片评价的订单
     
   - 再往下便是常见的优惠券、会员卡、观影卡/票的入口热区；然后是用户想看的电影和看过的电影两个合集入口
   
