# ShadowRule

常规分流规则合集，覆盖 Shadowrocket、Surge、Quantumult X、Loon 与 Clash。

本仓库克隆自 [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script)，在原项目基础上整理与维护。规则的著作权归原作者及各位贡献者所有。

## 分流规则

分流规则按平台分目录存放于 [rule](https://github.com/LOWERTOP/ShadowRule/tree/master/rule)，共 5229 个规则文件；每个规则目录下均有 README，内含该规则的订阅链接。本仓库仅收录常规分流规则，不含需要 REJECT 动作的拦截类规则。

| 平台 | 规则文件数 | 格式 |
| --- | --- | --- |
| Shadowrocket | 790 | .list、.conf、.sgmodule |
| Surge | 830 | .list、.sgmodule |
| Quantumult X | 678 | .list |
| Loon | 796 | .list、.plugin |
| Clash | 2135 | .list、.yaml、.txt |

其中 .list 文件合计约 470 万行（含文件头与注释）。

订阅地址格式如下（以 Shadowrocket 的 Apple 规则为例）：

```
https://raw.githubusercontent.com/LOWERTOP/ShadowRule/master/rule/Shadowrocket/Apple/Apple.list
```

也可使用 jsDelivr 镜像：

```
https://cdn.jsdelivr.net/gh/LOWERTOP/ShadowRule@master/rule/Shadowrocket/Apple/Apple.list
```

规则数据来源于互联网公开的规则项目，仓库仅做整理与备份。

## 说明

- 本仓库内容仅供学习与研究使用。
- 规则数据来源于互联网，仓库无法保证其合法性、准确性、完整性与有效性；使用本仓库内容所造成的后果由使用者自行承担。
- 第三方硬件、软件与本仓库没有直接或间接的关系。

## 感谢

本仓库源自 [blackmatrix7](https://github.com/blackmatrix7) 的 [ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) 项目，衷心感谢原作者 blackmatrix7 多年来对开源规则生态的持续付出，以及所有为该项目贡献过力量的朋友。

以下排名不分先后

[@blackmatrix7](https://github.com/blackmatrix7)  [@BaileyZyp](https://github.com/BaileyZyp)  [@Mazeorz](https://github.com/Mazeorz)  [@LuzMasonj](https://github.com/LuzMasonj)  [@chouchoui](https://github.com/chouchoui)  [@ypannnn](https://github.com/ypannnn)  [@echizenryoma](https://github.com/echizenryoma)  [@zirawell](https://github.com/zirawell)  [@urzz](https://github.com/urzz)  [@ASD-max](https://github.com/ASD-max)
