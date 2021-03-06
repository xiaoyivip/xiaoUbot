# 骁幽bot v1.0
> 需求源于自己的一个推理爱好者Q群,没有时间发推理题目的情况下，在某宝买了很多机器人，发现娱乐功能一堆，却没有发题这一核心(不能自定义)。于是花了两天时间自己现学现卖随便写了一个，核心功能基本实现，题库需要自己录入数据库(目前题库题量很少)。

> 不管怎么说，起码暂时解放了双手，关于其他功能的开发与题库数据的录入工作看时间安排了！
## 技术说明
  - 后端:SpringBoot
  - 数据库:MySQL+MyBatis
  - 框架:Simple-robot
  - 管理:Maven
## 需要做的
### fork/clone
fork或者clone此项目到你的本地，并使用IDE工具打开并构建它。

### 修改配置文件
1. 打开文件 [xiaou.bot](src/main/resources/simbot-bots) 并修改其中的 `xiaou.bot` 项为你测试用的QQ账号，例如：
```yaml
simbot: 
  core:
    bots: 123456789:password
```
2. 打开文件 [BotConstant.java](src/main/Java/simbot.xiaoU.utils) 并修改其中的 `BotConstant.java`,配置需要使用的QQ群号。 
3. 数据库配置在文件[application.yml],另外，项目支持开发/生产环境的切换。
### 保证安静
将你的bot放在一些测试用的群而不是一些大型群。


### 运行
执行[SimbotExampleApplication](src/main/java/simbot/xiaoU/SimbotExampleApplication.java) 中的main方法。

### 验证
如果你是第一次使用此框架，且出现了诸如需要“滑动验证”等相关错误，你可以尝试先使用一次 [simbot-mirai-login-solver-selenium-helperPack](https://github.com/simple-robot/simbot-mirai-login-solver-selenium-helperPack) 来使腾讯记住你的设备信息。

以及，记得关闭账号中与“设备锁”、“安全保护”等相关内容。

### 测试
 > 测试QQ群：917125728。

### 关于部署
> 本项目使用maven进行管理，部署的话，直接打jar包丢进服务器即可。
### 致谢
- [simple-robot](https://github.com/ForteScarlet/simpler-robot) 

<p align="center">
    <a href="#投稿"><img src="https://img.shields.io/badge/开源-精神-blue.svg" alt="投稿"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-代码不良人-lightgrey.svg" alt="公众号"></a>
  <a href="#公众号"><img src="https://img.shields.io/badge/语言-Java-important.svg" alt="公众号"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/support-持续更新-green.svg" alt="投稿"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/框架-SpringBoot-orange.svg" alt="投稿"></a>
    <a href="#投稿"><img src="https://img.shields.io/badge/MyBatis-orange.svg" alt="投稿"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/QQ群-机器人-yellow.svg" alt="投稿"></a>
  <a href="#投稿"><img src="https://img.shields.io/badge/数据库-MySql-red.svg" alt="投稿"></a>
</p>
