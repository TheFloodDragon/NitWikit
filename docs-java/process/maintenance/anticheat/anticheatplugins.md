---
title: 反作弊插件
sidebar_position: 1
---

# 反作弊

:::tip[写在最前]

混合端**不要**用下面所列的反作弊插件，建议使用 [次元反作弊](https://www.mcmod.cn/class/6578.html)，[SkAc 反作弊](https://www.mcmod.cn/class/18057.html) 或 [猫反作弊](https://www.wxmwl.com/?p=95)

次元反作弊的交流群：327175980

SkAc 反作弊的交流群：672827899

:::

## 选择反作弊插件

好的反作弊插件通过对玩家行为进行分析从而找出违规者可能的违规行为，从而限制甚至封禁。

市面上的反作弊很多，常常让人难以选择。为了让新手入门反作弊，我们写了一部分常见的反作弊插件。

虽然这些插件均存在绕过，但是仍然能检测或削弱 **大部分** 的作弊玩家，希望能帮到你。

:::warning[警告]

不要使用任何已经停止更新的反作弊插件，因为他们并不能支持最新版本且缺少对其他插件的兼容性，除非你有能力自己解决这些问题，不然就尽量不去使用已经停止更新的反作弊。而大多数反作弊插件对混合端和 Geyser 的支持有限甚至没有，可能需要其他方式解决。

没有任何一个反作弊是无法被绕过的，且所以反作弊都会有误判。反作弊该做的应是限制玩家的作弊行为并帮助管理员辨别作弊者，不要过度依赖或期望反作弊自动识别作弊者并将其封禁或踢出。

:::

### 主流反作弊插件

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

<Tabs queryString="anticheat">
<TabItem value="matrix" label="Matrix(推荐)">

Matrix 是由国人 RE 编写的一款反作弊插件，当年诞生是用于取代 AAC 这款反作弊插件，

而如今经过不断改良也拥有了不错的检测性能和质量，足以对抗部分脑溢血参数。

！试用版只拥有少部分检测且只支持一台机器
！7 天使用权到期后可继续订阅试用版使用

付费版 - 99 RMB

- 拥有 95% 的检测
- 可同时给 3 台机器使用

企业版 - 499 RMB

- 拥有所有检测 (虽然多的检测误判挺多的)
- 可同时给 40 台机器使用
- 可对你的服务器进行深度定制

如果你是生存服，可以先使用试用版进行测试，如何再进行付费版本的购买

如果你是大型小游戏/大型群组服，可以购买企业版，这能让 Matrix 对你的服务器进行更深度的定制

> 官网：matrix.rip

</TabItem>
<TabItem value="ncp" label="NoCheatPlus-Update">

非常经典的老牌反作弊，拥有悠久历史且和作弊者们对抗许久，但目前并不积极的进行更新，

且由于远古代码遗留导致部分检测较为低下，但这并不影响它是个不错的反作弊。

！只推荐影响原版插件较少的生存服务器使用。

！由于配置文件过于复杂，需要花费一段时间来理解和调整配置文件。

！不建议在不接触配置文件的情况下直接使用该插件。

> GitHub: https://github.com/Updated-NoCheatPlus/NoCheatPlus
> 
> 下载镜像：https://dl.8aka.org/plugins/NoCheatPlus.jar

</TabItem>
<TabItem value="grim" label="GrimAC">

一个不错的实验性反作弊，支持避免检查来自 Geyser 的玩家，移动检测虽然强大但有很多误判。

！目前仍然有很多不稳定因素，但 Timer 和 Reach，BadPackets 检查都是较为稳定的。

！除了实验性检查，其余的检查是不可被关闭的。

！可能不适合部分生电服务器或声明允许使用辅助模组的插件。

> GitHub: https://github.com/GrimAnticheat/Grim
> 
> MineBBS: https://www.minebbs.com/threads/grimanticheat-1-8-x-1-21-x.29384/

</TabItem>
<TabItem value="vulcan" label="Vulcan">

老牌火神反作弊，虽然在几个版本存在十分严重的漏洞，但并不影响他一些检测强力的事实，尽管他的配置文件非常脑淤血，但还是深受多人喜爱。

！拥有中规中矩的检测，但由于拉回系统非常不稳定，建议慎用或与其它反作弊搭配使用。

> SpigotMC: https://www.spigotmc.org/resources/vulcan-anti-cheat-advanced-cheat-detection-1-7-1-20-4.83626/

</TabItem>
<TabItem value="spartan" label="Spartan(不推荐)">

老牌垃圾反作弊，性能拉胯误判多，有很多无用和多余的检测，不如其它开源或具有相同价格的反作弊。

对于 Geyser 的基岩版支持也是如此，并且从一开始的同时检查基岩版玩家和 Java 版玩家被拆分成了 Spartan: Java 和 Spartan: Bedrock 两个不同的版本。

被 md_5 警告后在 SpigotMC 上 捆绑销售。就算你需要退款，先请在 SpigotMC 上撤回你的负面言论后才可进行 Spartan 的退款服务，

由于购买后 6 个月需要重新支付才能继续使用且包含额外的需要付费的功能导致被 md_5 警告的传奇反作弊，这就是 Spartan-AntiCheat。

> SpigotMC: https://www.spigotmc.org/resources/spartan-anti-cheat-advanced-cheat-hack-detection-1-7-1-20-4-33-off.25638/

</TabItem>
</Tabs>

### 扩展反作弊插件

一些扩展的反作弊插件，通常不提供直接的防作弊功能，而是扩展

<Tabs queryString="ext">
<TabItem value="aca" label="AntiCheatAddition">

添加了其他反作弊不会反的部分，目前添加了以下：

- 一键整理
- 自动钓鱼
- 自动进食
- 自动药水
- 自动工具
- 分析不可能发送的数据包
- (以及更多)

> 购买地址：https://www.spigotmc.org/resources/anticheataddition.33590/

</TabItem>
</Tabs>

### 扩展工具

这些插件自身不提供反作弊功能,但是可用于反作弊,推荐全部看一遍

<Tabs>
<TabItem value="aco" label="AntiCheatObfuscator">

此插件会 "混淆 你的服务器上的反作弊，可以避免作弊者发现你的反作弊组合而针对性绕过

> 下载地址：https://www.minebbs.com/resources/anticheatobfuscator-1-8-1-20.9251/
>
> Modrinth: https://modrinth.com/plugin/anticheatobfuscator

</TabItem>
<TabItem value="cdp" label="ClientDetectorPlus">

一个可以用来查端的插件，可以检测客户端是什么类型的客户端，可以检测到部分模组。

> 下载地址：https://www.spigotmc.org/resources/clientdetectorplus-now-in-alpha-testing.90375/
>
> 开发版本 (推荐): http://patreon.com/CraptiCraftDevelopment

</TabItem>
<TabItem value="iseeyou" label="ISeeYou">

ISeeYou 是一个免费的录制插件，可以录制玩家的一举一动

:::warning

仅支持 Leaf 和 Leaves

:::

> 下载地址：https://github.com/MC-XiaoHei/ISeeYou/releases

</TabItem>
<TabItem value="coordinateoffset" label="CoordinateOffset">

CoordinateOffset 是一个坐标混淆插件，可以防止玩家通过 F3 调试界面或客户端模组获取真实坐标。

**支持版本：** 1.17.x - 1.21.7 (Spigot/Paper)

> GitHub: https://github.com/joshuaprince/CoordinateOffset
>
> Modrinth: https://modrinth.com/plugin/coordinateoffset
>
> Spigot: https://www.spigotmc.org/resources/coordinateoffset.111292/

需要安装前置 PacketEvent

![](_images/img.png)

</TabItem>
<TabItem value="synsniff" label="syn-sniff">

syn-sniff 是一个被动 TCP/IP 协议栈指纹识别插件，通过分析网络数据包来获取玩家连接的深层信息。

**主要功能：**
- 被动嗅探 TCP/IP SYN 数据包进行指纹识别
- 检测玩家的操作系统类型

**系统要求：**
- pcap 原生库 (libpcap, WinPcap, Npcap)
- 管理员权限或 Linux Capabilities

**命令：**
- `/fingerprint <player>` - 查看原始 TCP/IP 指纹信息
- `/predictos <player>` - 显示预测的操作系统

:::warning[注意]

此插件需要管理员权限和特定的网络库支持，安装前请确保满足系统要求。

:::

![](_images/img_1.png)

> GitHub: https://github.com/Duckulus/syn-sniff

</TabItem>

</Tabs>

---

## 只有这几个？

你难道想让我把 Intave Karhu Polar 那些什么全部都列出来吗，

要求不高这几个主流就差不多够用了，毕竟是面向小白的开服教程，

后面想试试非主流反作弊请自己去官网购买就好了捏。

## 反作弊配置

![](./_images/anticheat/talentsaclogo.png)

🛡人才反作弊配置🛡

> “别人在倚老卖老但我在以老带新，只为了给名利场刮点清风。”

一款面向萌新的主流反作弊配置，对配置有任何问题骚扰 Talents 先生项目的 Issues 即可解决！

GitHub: https://github.com/8aka-Team/Talents-AntiCheat-Config

### ViaBackwards

如果你在你的服务器使用了跨版本插件 (ViaVersion)，你需要开启这个选项以增加反作弊对其他版本的兼容性。

打开 `ViaBackwards/config.yml` ，找到 `handle-pings-as-inv-acknowledgements` 配置项，把它改成 `true` 就可以增加对反作弊的兼容性

## 笨蛋脚本

自动为你配置反作弊，[下载！](https://script.8aka.org/config-anticheat)

## 组合反作弊

一般个人建议是一个服务器的反作弊两个足够，一个的话容易被绕，

太多又会严重影响服务器性能，并产生大量误判，一般装两个足够了。

:::warning

杂交可能会出现大量误判回弹

:::

高版本组合参考：

- Matrix + GrimAC
- NoCheatPlus + GrimAC
- Vulcan + Matrix
