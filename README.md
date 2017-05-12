## 简单概述
这是一个简单的记账用App,使用mui框架，vue.js进行数据双向绑定，h5+api调用原生接口
## 核心功能
1. 启动App后校验登录状态，若已登录，直接跳转应用首页；否则，显示登录页面；
2. 支持本地注册（账号信息使用localStorage保存在本机）；
3. 支持设置手势密码，登录时可使用手势密码代替账号、密码；
4. 记账数据使用了websql保存在本机数据库中；