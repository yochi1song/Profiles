## 简介

配置规则文件

macOS：[Surge](https://nssurge.com/) | [ClashX](https://github.com/yichengchen/clashX)

Windows：[Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg)

iOS：[Surge](https://itunes.apple.com/app/apple-store/id1329879957?mt=8) | [Quantumult](https://itunes.apple.com/app/apple-store/id1252015438?mt=8) | [Kitsunebi](https://itunes.apple.com/app/apple-store/id1446584073?mt=8) | [Shadowrocket](https://itunes.apple.com/app/apple-store/id932747118?mt=8) | [Pepi(ShadowRay)](https://itunes.apple.com/app/apple-store/id1283082051?mt=8) 

Android：[Kitsunebi](https://play.google.com/store/apps/details?id=fun.kitsunebi.kitsunebi4android&hl=zh)

## 说明

[使用说明 & 常见问题](https://github.com/ConnersHua/Profiles/wiki) | [导入教程](https://github.com/ConnersHua/Profiles/wiki/%E8%A7%84%E5%88%99%E6%80%8E%E4%B9%88%E5%AF%BC%E5%85%A5%E5%92%8C%E6%9B%B4%E6%96%B0%EF%BC%9F%E6%8D%B7%E5%BE%84%E5%92%8C%E8%87%AA%E5%AE%9A%E4%B9%89%E8%A7%84%E5%88%99%E6%80%8E%E4%B9%88%E7%94%A8%EF%BC%9F) | [Telegram 频道](https://t.me/DivineEngine_Profiles)

## 规则

规则分为**标准版**、**专业版**和**回国版**

### 标准版

- 使用公共 DNS 达到快速、准确、稳定及安全的解析
- 国内应用及网站直连
- 海外应用及网站加速
- Apple 服务加速（具体看底部说明）
- 海外媒体部分服务可指定节点（具体看底部说明）

### 专业版

- 标准版所有功能
- 拦截应用及网站的行为分析、数据统计、隐私跟踪
- 拦截运营商劫持
- 拦截应用的广告（网页广告请使用 Safari 内容拦截器如 [ADGuard](https://itunes.apple.com/app/apple-store/id1047223162?mt=8) (在「过滤器」中添加「EasyList China」) 或自带去广告功能的浏览器。）
- 拦截臭名昭著的诈骗网站（如**思杰马克丁**伪造的一系列软件官网、MacKeeper等）

### 回国版

- 国内应用及网站加速

**下载**

- 移动设备长按版本名即可「拷贝」链接进行导入
- 有自定义规则需求方才使用「快捷指令」

|                             应用                             |                            标准版                            |                            专业版                            |                            回国版                            |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|                            Clash                             |                              无                              | [Pro](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Clash/Pro.yaml) | [BacktoCN](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Clash/BacktoCN.yaml) |
|                          Kitsunebi                           | [Basic](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Kitsunebi/Basic.conf) | [Pro](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Kitsunebi/Pro.conf) | [BacktoCN](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Kitsunebi/BacktoCN.conf) |
| Quantumult \| [快捷指令](https://www.icloud.com/shortcuts/44f0cffd3ddf422ea28fb94380cec417) | [Basic](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/Basic.conf) | [Pro](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/Pro.conf) \| [Rejection](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/Rejection.conf) | [BacktoCN](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/BacktoCN.conf) \| [Rejection](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Quantumult/Rejection.conf) |
|                         Quantumult X                         |                              无                              | [Pro](https://github.com/ConnersHua/Profiles/raw/master/Quantumult/X/Pro.conf) \| [Rewrite](https://github.com/ConnersHua/Profiles/raw/master/Quantumult/X/Rewrite.conf)<br />[Filter Remote](https://github.com/ConnersHua/Profiles/tree/master/Quantumult/X/Filter) |                              无                              |
| Shadowrocket \| Pepi \| [快捷指令](https://www.icloud.com/shortcuts/b50d84fb063e469891f8600ab089a684) | [Basic](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Shadow/Basic.conf) | [Pro](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Shadow/Pro.conf) | [BacktoCN](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Shadow/BacktoCN.conf) |
| Surge 2 \| [快捷指令](https://www.icloud.com/shortcuts/244585386fef4058abc9ac4b2f47ca56) | [Basic](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Basic.conf) | [Pro](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Pro.conf) | [BacktoCN](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/BacktoCN.conf) |
| Surge 3+ \| [快捷指令](https://www.icloud.com/shortcuts/5e2e1a366a5e457ca60170925736ba68) |                              无                              | [Surge3](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Surge3.conf) |                              无                              |

## 感谢

[lhie1](https://github.com/lhie1) – 2017 ~ 2018.5 特别版去广告相关规则基于其规则

Lison Bin – 完善 Apple、WhatsApp、Line 相关规则

[linjiacheng](https://github.com/linjiacheng) – 解决盯盯拍无法使用的问题

Booui、liceva – 完善 Google Play IP 段

[JO2EY](https://github.com/JO2EY) - 完善 Media 策略组

[Choler](https://github.com/Choler) - Tiktok封区解锁

## 许可

转载需注明作者及项目地址
