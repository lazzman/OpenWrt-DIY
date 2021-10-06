<a href="#readme">
    <img src="https://avatars.githubusercontent.com/u/31687149?v=4" alt="图裂了😂" title="OpenWrt-DIY" align="right" height="180" />
</a>

[![](https://img.shields.io/github/last-commit/coolsnowwolf/lede/master?color=FFFFFF&label=%E6%BA%90%E7%A0%81%E6%9B%B4%E6%96%B0)](https://github.com/coolsnowwolf/lede) [![](https://img.shields.io/github/release-date/lazzman/OpenWrt-DIY?color=FFFFFF&label=%E5%9B%BA%E4%BB%B6%E6%9B%B4%E6%96%B0)](https://github.com/lazzman/OpenWrt-DIY/actions) 
<br/>
[![](https://img.shields.io/badge/-主要功能:-696969.svg)](https://github.com/lazzman/OpenWrt-DIY/wiki/OpenWrt-DIY%E6%8F%92%E4%BB%B6%E9%A2%84%E8%A7%88) ![](https://img.shields.io/badge/-SSR_Plus+-FFFFFF.svg) ![](https://img.shields.io/badge/-PassWall-FFFFFF.svg) ![](https://img.shields.io/badge/-广告屏蔽大师_Plus+-FFFFFF.svg) ![](https://img.shields.io/badge/-解锁网易云灰色歌曲-FFFFFF.svg) ![](https://img.shields.io/badge/-UPnP-FFFFFF.svg) ![](https://img.shields.io/badge/-京东签到服务-FFFFFF.svg) ![](https://img.shields.io/badge/-IPv6_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-BBR_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-FullCone_NAT_加速-FFFFFF.svg) ![](https://img.shields.io/badge/-SFE_加速-FFFFFF.svg)![](https://img.shields.io/badge/-桥接加速-FFFFFF.svg) ![](https://img.shields.io/badge/-DDNS-FFFFFF.svg) ![](https://img.shields.io/badge/-ARP_绑定-FFFFFF.svg) ![](https://img.shields.io/badge/-网络唤醒-FFFFFF.svg) 


OpenWrt DIY — 多设备固件云编译
==============================================================================================================

[![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) [![](https://img.shields.io/badge/-固件下载-FFFFFF.svg)](#固件下载-) [![](https://img.shields.io/badge/-基本介绍-FFFFFF.svg)](#基本介绍-)

请 `耐心认真阅读完毕` 本页面，本页面包含如何提升固件下载及使用体验的内容。

如果您未阅读完本页面，可能会遇到 `固件下载问题` ，若遇到问题，请 `返回此页面，认真完整阅读一遍`~

## 固件下载 [![](https://img.shields.io/badge/-支持设备、编译状态及固件下载-FFFFFF.svg)](#固件下载-)
<details>
 <summary><b>&nbsp;&nbsp;&nbsp; X86  设备编译状态及固件下载</b></summary>
    
<br/>
 
点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|   序号    |     X86设备  |   X86设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |   [![](https://img.shields.io/badge/OpenWrt-x86_(64位)-FFFFFF.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/.github/workflows/x86_64.yml)    | [![](https://github.com/lazzman/OpenWrt-DIY/workflows/Build%20X86(64bit)%20OpenWrt/badge.svg)](https://github.com/lazzman/OpenWrt-DIY/actions/workflows/x86_64.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/config/X86/x86-extra.config) |  |  
| 2 |    [![](https://img.shields.io/badge/OpenWrt-x86_(32位)-FFFFFF.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/.github/workflows/x86.yml)     |[![](https://github.com/lazzman/OpenWrt-DIY/workflows/Build%20X86(32bit)%20OpenWrt/badge.svg)](https://github.com/lazzman/OpenWrt-DIY/actions/workflows/x86.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/config/X86/x86-extra.config) | | 

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 到 **Actions** 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; ARM 设备编译状态及固件下载</b></summary>
    
<br/>
 
点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 即可跳转到该设备固件下载页面
|    序号   |     ARM设备    |   ARM设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
|1|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R2S-FFFFFF.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/.github/workflows/r2s.yml)     |  [![](https://github.com/lazzman/OpenWrt-DIY/workflows/Build%20NanoPi%20R2S%20OpenWrt/badge.svg)](https://github.com/lazzman/OpenWrt-DIY/actions/workflows/r2s.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |
|2|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R4S-FFFFFF.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/.github/workflows/r4s.yml)|  [![](https://github.com/lazzman/OpenWrt-DIY/workflows/Build%20NanoPi%20R4S%20OpenWrt/badge.svg)](https://github.com/lazzman/OpenWrt-DIY/actions/workflows/r4s.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/lazzman/OpenWrt-DIY/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/lazzman/OpenWrt-DIY/actions) 到 Actions 进一步查看。

</details>

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 基本介绍 [![](https://img.shields.io/badge/-项目基本介绍-FFFFFF.svg)](#基本介绍-)

1. 默认引用[ Lean 的 OpenWrt 库](https://github.com/coolsnowwolf/lede)（部分设备整合[ Lienol 的 Packages 库](https://github.com/Lienol/openwrt-packages)），因为他的 [README](https://github.com/coolsnowwolf/lede/blob/master/README.md) 影响了我开始学习编译；Github Actions 自动云编译代码采用 [P3TERX 的 Actions-OpenWrt 库 ](https://github.com/P3TERX/Actions-OpenWrt)。

2. [插件及功能预览 请点击查看](https://github.com/lazzman/OpenWrt-DIY/wiki/OpenWrt-DIY%E6%8F%92%E4%BB%B6%E9%A2%84%E8%A7%88)

3. `每周五查询大雕源码是否有更新`，如有更新自动拉取最新源码和第三方软件包项目自动编译（根据设备不同编译时间在1~5个小时），`固件包含必要驱动及常用插件`（各设备的 config 借鉴大雕设置及根据网友需求调整），未逐一经过实机测试，故 `不保证 100% 可靠性`；

4. 默认固件账号`root`密码`password`，IP地址`192.168.1.2`

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

