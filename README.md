# Wehhit
淮海工学院 微信小程序

### 目录结构
```
wehhit
  ├─ app.json       // 全局配置文件，决定页面文件的路径、窗口表现、设置网络超时时间、设置多tab等     
  ├─ app.js         // 全局js，如执行App()函数来初始化注册小程序
  ├─ app.wxss       // 全局样式
  ├─ utils          // 模块化文件夹，利用module.exports暴露接口，通过require(path)使用模块接口
  │    └─ util.js   // 模块化例子
  ├─ images         // 图片文件夹
  └─ pages          // 页面文件夹
       ├─ index     // 主页
       │    ├─ index.wxml
       │    ├─ index.wxss
       │    └─ index.js
       ├─ order     // 订单
       │    ├─ order.wxml
       │    ├─ order.wxss
       │    └─ order.js    
       
       ├─ evaluate      // 评价
       │    ├─ news.wxml    // 列表
       │    ├─ news.wxss
       │    ├─ news.js
       │    ├─ detail.wxml   // 详情
       │    ├─ detail.wxss
       │    └─ detail.js
       │
       └─ core      // 主页功能文件夹
            ├─ kb       // 课表
            │    ├─ kb.wxml
            │    ├─ kb.wxss
            │    └─ kb.js
            └─ other    // 其他
                 └─ ..
```
