# 🧸 百度贴吧签到

## 前言

百度贴吧多账户自动签到，支持青龙面板。


## 配置

### Surge

使用模块

```ini
https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/tieba_signin.sgmodule
```

### Quantumult X

```ini
[rewrite_remote]
https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/tieba_signin.qxrewrite, tag=贴吧_获取Cookie, update-interval=86400, opt-parser=false, enabled=true

[task_local]
30 10 * * *  https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/tieba_signin.js, tag=贴吧_每日签到, enabled=true
```

### Loon

安装插件

```ini
https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/tieba_checkin.lnplugin
```

### 青龙面板

订阅单文件

```ini
https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/tieba_signin.js
```

## 获取Cookie

关闭贴吧后台，重新进入一次贴吧即可。

![](https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/images/03.jpg)

## 多账户

全新的百度贴吧签到脚本，原生提供了多账户签到的支持。

**获取多账户Cookies的办法**：

你需要做的仅仅是在百度贴吧客户端中，选择“我的”，点击右上角的设置图标，进入“我的账户”，切换不同的账号。

每切换一个账号，需要重启一次贴吧客户端，让脚本自动获取Cookie。

随着贴吧客户端更新，上述操作方式可能会有变化，但整体大同小异，跟日常切换多账户一样就可以了。

*理论上，你可以执行无限多的账号签到，只要签到脚本执行不会超时。*

## 签到

带有重试机制，解决need vcode失败问题，凌晨高峰期签到也可以保证成功率。

全部签到成功时：

![](https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/images/01.jpg)

部分贴吧签到失败时：

![](https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/tieba/images/02.jpg)

## 脚本变量

当前脚本使用的变量，你可以根据这些Key，在magic.json中配置数据。

| 名称                | 类型 | 作用                            |
| ------------------- | ---- | ------------------------------- |
| tieba_signin_cookie | json | 存储多账号的Cookies             |
| tieba_sync_qinglong | bool | 判断是否将Cookies同步到青龙面板 |


