# ShadowRule

分流规则、复写规则与自动化脚本合集，覆盖 Shadowrocket、Surge、Quantumult X、Loon、Stash、Clash 与 AdGuard。

本仓库克隆自 [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)，在原项目基础上整理与维护。规则与脚本的著作权归原作者及各位贡献者所有。

## 分流规则

分流规则按平台分目录存放于 [rule](https://github.com/LOWERTOP/ShadowRule/tree/master/rule)，共 5320 个规则文件；每个规则目录下均有 README，内含该规则的订阅链接。

| 平台 | 规则文件数 | 格式 |
| --- | --- | --- |
| Shadowrocket | 807 | .list |
| Surge | 861 | .list |
| Quantumult X | 689 | .list |
| Loon | 815 | .list |
| Clash | 2142 | .list、.yaml |
| AdGuard | 6 | .txt |

其中 .list 文件合计约 1050 万行（含文件头与注释）。

订阅地址格式如下（以 Shadowrocket 的去广告规则为例）：

```
https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/rule/Shadowrocket/Advertising/Advertising.list
```

也可使用 jsDelivr 镜像：

```
https://cdn.jsdelivr.net/gh/LOWERTOP/ShadowRule@master/rule/Shadowrocket/Advertising/Advertising.list
```

规则数据来源于互联网公开的规则项目，仓库仅做整理与备份。

## 复写规则

复写规则存放于 [rewrite](https://github.com/LOWERTOP/ShadowRule/tree/master/rewrite)，共 111 个文件，覆盖 Loon、Quantumult X、Shadowrocket、Stash 与 Surge。主要类别包括去广告、AllInOne、拦截 HTTP DNS、获取 Cookie、重定向、升级与知乎助手等，各目录下均有 README 与订阅链接。

## 脚本

脚本存放于 [script](https://github.com/LOWERTOP/ShadowRule/tree/master/script)，基于 MagicJS 框架编写（MagicJS 2 已停止维护）。目前保留以下脚本，其余已移至 [script/archive](https://github.com/LOWERTOP/ShadowRule/tree/master/script/archive)：

- [开屏去广告](https://github.com/LOWERTOP/ShadowRule/tree/master/script/startup)：去除缓存到本地的 APP 开屏广告
- [百度贴吧签到](https://github.com/LOWERTOP/ShadowRule/tree/master/script/tieba)：多账户自动签到，支持青龙面板
- [Luka](https://github.com/LOWERTOP/ShadowRule/tree/master/script/luka)：每日自动签到
- [哲也同学](https://github.com/LOWERTOP/ShadowRule/tree/master/script/zheye)：模块与脚本，详见目录 README
- [Quora](https://github.com/LOWERTOP/ShadowRule/tree/master/script/quora)：模块与脚本，详见目录 README
- [AppleStore 库存监控](https://github.com/LOWERTOP/ShadowRule/tree/master/script/applestore)：监控线下 Apple Store 指定商品库存（目前已暂停）

脚本的具体配置方法见各目录 README 与 [script/README.md](https://github.com/LOWERTOP/ShadowRule/blob/master/script/README.md)。Quantumult X Gallery 订阅地址：https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/gallery.json；BoxJS 订阅地址：https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/script/boxjs.json。

## 外部资源

[external](https://github.com/LOWERTOP/ShadowRule/tree/master/external) 目录收录互联网上其他开源项目的资源（按 Loon、Quantumult X、Shadowrocket、Stash、Surge 分类，包括 TestFlight 与 TikTok 解锁相关），仓库仅做整合与备份，相关问题请联系原作者。

## 说明

- 本仓库内容仅供学习与研究使用。
- 规则与脚本数据来源于互联网，仓库无法保证其合法性、准确性、完整性与有效性；使用本仓库内容所造成的后果由使用者自行承担。
- 第三方硬件、软件与本仓库没有直接或间接的关系。

## 感谢

本仓库源自 [blackmatrix7](https://github.com/blackmatrix7) 的 [ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) 项目，衷心感谢原作者 blackmatrix7 多年来对开源规则生态的持续付出，以及所有为该项目贡献过力量的朋友。

以下排名不分先后

[@blackmatrix7](https://github.com/blackmatrix7)  [@BaileyZyp](https://github.com/BaileyZyp)  [@Mazeorz](https://github.com/Mazeorz)  [@LuzMasonj](https://github.com/LuzMasonj)  [@chouchoui](https://github.com/chouchoui)  [@ypannnn](https://github.com/ypannnn)  [@echizenryoma](https://github.com/echizenryoma)  [@zirawell](https://github.com/zirawell)  [@urzz](https://github.com/urzz)  [@ASD-max](https://github.com/ASD-max)
