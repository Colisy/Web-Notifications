## Web Notifications 简单demo
#### H5新出来的新特性，通知消息
##### 接下来简单描述一下
 - new Notification 创建一个通知信息，出现消息框
 - onshow 消息框出来的时候发生的函数
 - close 消息框被点击时被调用
 - onclick 点击消息框
 - onerror 发生错误时调用的函数
 - Notification.permission 判断浏览器是否允许消息出现
  - default 用户没有接收或拒绝授权 不能显示通知
  - granted 用户接受授权 允许显示通知
  - denied  用户拒绝授权 不允许显示通知
