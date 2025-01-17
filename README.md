# Mirai-PHP
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FKawaiiZapic%2FMirai-PHP.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FKawaiiZapic%2FMirai-PHP?ref=badge_shield)

A PHP SDK for Mirai based on Swoole &amp; PHP8.  
**目前项目正在使用PHP 8完全重写,新的SDK将使用go-cqhttp作为接口,如果需要使用旧版或者需要使用Mirai-APIHTTP请切换分支到PHP_7**

## Progress  
* [ ] 主体
  * [ ] 机器人实例
  * [ ] 事件实例
  * [ ] 消息与消息链实例
  * [ ] 异常与错误  
  

* [ ] 检查API是否可以正常调用
  * [ ] 登录
  * [ ] 图片上传 
  * [ ] 接收事件
    * [ ] 好友消息事件
    * [ ] 群消息事件
    * [ ] 临时消息事件
    * [ ] ...
  * [ ] 发送消息
    * [ ] 好友消息
    * [ ] 群消息
    * [ ] 临时会话消息 
  * [ ] 禁言与解禁
  * [ ] 移除成员
  * [ ] 退群
  * [ ] 撤回消息
  * [ ] 好友列表与群(员)列表
  * [ ] 群(员)设置
  * [ ] 机器人管理员列表
  * [ ] 命令注册与监听
  * [ ] ...
  
* [ ] Docs
  * [ ] 主体
  * [ ] 事件
  * [ ] 消息与消息链

## 何时完成?  
等死吧,这辈子都写不完的.

## 需要一个像Mirai-Console的插件框架?
Potabot是一个基于Swoole和本SDK的协程机器人框架,提供完整的插件管理/事件分发/数据存储.  
**但是她还在开发,需要等待本SDK不再快速迭代之后才能确保稳定**

## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FKawaiiZapic%2FMirai-PHP.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FKawaiiZapic%2FMirai-PHP?ref=badge_large)