# 微信小程序商城

## 服务器端
框架：ThinkPHP5.1
数据库：MySQL5.6
技术：
1. 以ORM的方式查询数据库
2. 验证器 Validate 构建整个验证层
3. 开发环境和生产环境下不同的全局异常处理机制
4. 缓存的使用
5. 使用数据库事务

## 小程序端
技术：
1. 微信小程序登录状态维护
2. 微信支付接入（暂无、但已经实现了微信支付的封装）
3. Class 和 Module 面向对象的思维构建前端代码
4. 前端如何管理用户令牌

## API
1. RESTFul API风格
2. 回码、URL语义、HTTP动词、错误码、异常返回
3. Token令牌来构建用户授权体系