## 简介

配置规则文件

macOS：[Surge](https://nssurge.com/) | [ClashX](https://github.com/yichengchen/clashX)

Windows：[Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg)

iOS：[Surge](https://itunes.apple.com/app/apple-store/id1329879957?mt=8) | [Quantumult](https://itunes.apple.com/app/apple-store/id1252015438?mt=8) | [Kitsunebi](https://itunes.apple.com/app/apple-store/id1446584073?mt=8) | [Shadowrocket](https://itunes.apple.com/app/apple-store/id932747118?mt=8) | [Pepi(ShadowRay)](https://itunes.apple.com/app/apple-store/id1283082051?mt=8) 

Android：[Kitsunebi](https://play.google.com/store/apps/details?id=fun.kitsunebi.kitsunebi4android&hl=zh)

## 规则

[Telegram 频道](https://t.me/DivineEngine_Profiles)

规则分为**标准版**、**专业版**和**回国版**

### 标准版

- 使用公共 DNS 达到快速、准确、稳定及安全的解析
- 国内直连、海外加速
- Apple 服务加速
- 海外媒体（部分）服务指定节点

### 专业版

在标准版的基础上加入：

- 拦截运营商劫持
- 拦截臭名昭著的欺诈网站（如**思杰马克丁**伪造的一系列软件官网、MacKeeper等）
- 拦截应用广告
  ⚠️ 网页广告请使用 Safari 内容拦截器如 [ADGuard](https://itunes.apple.com/app/apple-store/id1047223162?mt=8) 或集成去广告功能浏览器

### 回国版

- 国内媒体服务解锁
- 拦截应用广告
  ⚠️ 网页广告请使用 Safari 内容拦截器如 [ADGuard](https://itunes.apple.com/app/apple-store/id1047223162?mt=8) 或集成去广告功能浏览器

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

## 说明

### 导入配置教程

- [Surge 导入配置及安装证书](https://medium.com/circumvention-technology/import-profile-on-surge-2d4119822302)
-  [Quantumult 导入配置及安装证书](https://medium.com/circumvention-technology/import-profile-on-quantumult-2e5cef9cb0c5)（订阅时注意带有⚠️的策略）
- [Kitsunebi(iOS) 导入配置](https://medium.com/circumvention-technology/import-profile-on-kitsunebi-6befa3db03db)
- [Shadowrocket 导入配置及安装证书](https://medium.com/circumvention-technology/import-profile-on-shadowrocket-f183cd4e95ae)
- [Kitsunebi(Android) 导入配置](https://medium.com/circumvention-technology/import-profile-on-kitsunebi-android-3089026a037a)

------



### DNS 设置

- 运营商 DNS 及公共 DNS 共存设置为：`119.29.29.29,223.5.5.5,system`
- 若是运营商存在 DNS 污染则仅使用运营商 DNS 设置为：`system`
- 若是运营商存在 DNS 劫持则仅使用公共 DNS 设置为：`119.29.29.29,223.5.5.5`

#### 为什么没有海外 DNS

首先目前海外 DNS 基本在国内没有节点会导致 CDN **解析不准确**如解析到香港节点（包括腾讯的 119.28.28.28因运营商没有对路由进行更新所导致）

其次很多人觉得海外公共 DNS 干净，而实际情况是被污染的域名仍旧污染部分重灾区运营商还对海外 DNS 请求完全进行抢答，所以没有意义。

------



### 常见问题

> 1.遇到连接公共场所 Wi-Fi 时验证页面无法显示？

暂时关闭待验证成功后再开启，或者如校园网运营商客户端的可将相关域名或 IP 地址加入到「skip-proxy」中（主要是 Surge、Shadowrocket、Pepi(ShadowRay) 支持）。

> 2.iOS 12 上 Siri 无法正常使用

[#55](https://github.com/ConnersHua/Profiles/issues/55) 暂可判定为 Bug，多次重启可解决。

> 3.关于知乎避免强制「App 内打开」

此功能目前仅 Surge 用户可用，若想使用桌面版网页的知乎（但会影响 App）可以在「Header Rewrite」加入以下

```
^https?://www\.zhihu\.com header-replace User-Agent Mozilla/5.0  (Macintosh; Intel Mac OS X 10_13_6) AppleWebKit/605.1.15 (KHTML, like  Gecko) Version/12.0.2 Safari/605.1.15
```

> 4.SpeedTest 为什么没有做 DIRECT 规则？

因为众口难调，做 PROXY 有人需要国内测速，做 DIRECT 有人需要国外测速，所以现在是交由 GeoIP  处理，国外的测速服务器都是代理，国内的测速服务器都是直连，默认打开时是自动选择的国外服务器（代理节点的最优选择），此时可以手动修改到国内你所在省（区）的省会测速服务器即可。

> 5.如何解锁 TikTok？

（仅支持 Surge 和 Quantumult）规则中已带有相关复写规则，但是据反馈可能会导致抖音播放卡顿，如仍需此功能，在「HTTPS 解密」的域名列表中加入以下两项即可：

```
api*.tiktokv.com,*.musical.ly
```

*并且注意：Quantumult 用户需在「更多」里「高级」下的「模块」中选择「TUN + HTTP(Loopback)」*

> 6.Apple News 具体怎么使用

副作用为 macOS 及 iOS 12 以前的系统地图会变成海外 TOMTOM 版。

[关于解锁 Apple News 区域限制](https://chua.pro/unlock-apple-news-regional-restrictions/)

------



### 关于去广告

#### ⚠️ 为什么 Youtube、知乎、微博等应用（存在于 MitM 域名列表）无法使用？

⚠️ 如使用去广告规则并且开启了「HTTPS 解密(MitM)」功能

⚠️ 不仅需要安装证书

⚠️ 还要到系统「设置」>「通用」>「关于本机」中底部的「证书信任设置」中信任所安装的证书！！！

#### 为什么某应用还是有广告

**1.缓存**

有些应用会**将广告缓存**，如果在使用规则前应用就已经缓存了广告，所以你需要：

1. 应用内设置里清除缓存。
2. 但有的应用并不会清除广告的缓存，所以需要将应用删除重装。

⚠️ 广告加载是实时的，这就意味着：

- 需要实时开着类 Surge 应用托管网络
- 即便一直开着，但在遇到信号断开重连、蜂窝数据和 Wi-Fi 网络切换时会有一些网络请求先于类 Surge 应用加载导致广告出现，怎么办？看上面两步。

**2.功能**

广告阻止不仅于使用 [Rule] 规则，有的广告需要 [URL Rewrite] 和 [MITM]，这就意味着：

- Surfboard 仅支持 [URL Rewrite] 且仅支持 302 没有阻止功能
- Kitsunebi 不支持 [URL Rewrite] 和 [MITM]
- Surge 虽然支持 [URL Rewrite] 和 [MITM]，但对于个别应用如优酷、腾讯视频（部分）的请求（TUN）无法处理。
- Quantumult 虽然支持 [URL Rewrite] 和 [MITM]，但需要在「更多 > 附加功能」中开启「激进阻止」以开启更全面的支持否则同 Surge 效果一样，另外 Quantumult 对于 IP 的 Server Name 不会进行 MitM，所以对于个别应用如瑞幸咖啡也无效。

**3.其他**

> Youtube 去广告会造成以下问题

- 网页版可能无法正常播放
- YouTube Premium 用户无法正常播放

所以默认并没有启用，如果确定启用需在 [MITM] 的「hostname」列表中添加：

```
*.googlevideo.com
```

------



## 感谢

[lhie1](https://github.com/lhie1) – 2017 ~ 2018.5 特别版去广告相关规则基于其规则

Lison Bin – 完善 Apple、WhatsApp、Line 相关规则

[linjiacheng](https://github.com/linjiacheng) – 解决盯盯拍无法使用的问题

Booui、liceva – 完善 Google Play IP 段

[JO2EY](https://github.com/JO2EY) - 完善 Media 策略组

[Choler](https://github.com/Choler) - Tiktok封区解锁

## 许可

转载需注明作者及项目地址
