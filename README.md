# dmit 搬瓦工 对比：价格差在哪、晚高峰谁更稳、IP 被墙了怎么办？（附全套餐价格表与年付总成本）

DMIT 洛杉矶 Premium 的入门款是 $88.88/年，搬瓦工香港 CN2 GIA 年付 $899.99，两家都标着 CN2 GIA，价格能差出四倍多。差价来自三件事：线路分了几档、机房放在哪、机器是哪一代硬件。

选择逻辑可以先定下来：固定一台机器长期用，在意晚高峰掉不掉速、IP 被墙之后怎么换，选 DMIT；需要在一堆机房之间来回切换试线路、看重面板成熟度和更低的入门门槛，选搬瓦工。

下面把套餐、价格、年付总成本、退款和换 IP 的具体数字都摆出来，看完能直接下单。

> **大多数人对号入座**
> - 电信用户建站、要三网 CN2 GIA 回程：洛杉矶 Premium TINY（AN4），1 核 2GB / 20GB / 1000GB，$88.88/年
> - 联通、移动为主，预算一样：洛杉矶 Eyeball TINY（AN4），同样 $88.88/年，流量给到 1500GB、带宽 2Gbps，回程走 CMIN2
> - 服务国内访客、要 50ms 以内的延迟：香港 Premium TINY，$39.90/月；嫌贵看东京 Pro，$21.90/月起
> - 只要一台便宜的国际线路机器做落地或中转：三地同价的 Tier 1 WEE，$36.90/年，但没有大陆优化
>
> 👉 [查看 DMIT 全部套餐与当前价格](https://www.dmit.io/aff.php?aff=9081)

## 同样是 CN2 GIA，钱差在哪

DMIT 把产品线分成三档，价格差主要在这里，不在品牌溢价。

Premium（Pro）是三网 CN2 GIA 回程，电信走 GIA、联通走 AS9929、移动走 CMI/CMIN2；Eyeball（EB）联通 9929 加移动 CMIN2，比 Pro 便宜一档；Tier 1（T1）是纯国际线路，官网写明不含中国大陆优化，也不保证 IP 在所有国家可用。搬瓦工这边的线路更杂：洛杉矶分 CN2 GIA（DC6/DC9）、CN2 GT 和普通线路三档，另外还有香港 CN2 GIA、东京 CN2 GIA、大阪软银、荷兰联通 AS9929 可选。

线路相同的时候，两家的延迟几乎没有差别。第三方测速数据里，DMIT 洛杉矶 Premium 全国平均约 158ms，搬瓦工洛杉矶 DC9 约 159ms。

硬件上的差距更明显。sysbench CPU 测试里，DMIT（AMD EPYC）约 4228 events/s、平均延迟 0.24ms，搬瓦工旧款 Intel E5 机器约 641 events/s、1.56ms，差 6.6 倍；磁盘 IO 是 839 MB/s 对 427 MB/s。不过搬瓦工已经在 DC9、温哥华等部分机房把宿主机从 E5 迁到 EPYC，已迁移机房的性能基本能追平，升级是分批做的，下单前要看清楚目标机房迁完没有。

圈内一直有“搬瓦工洛杉矶 DC9 的 CN2 GIA 带宽来自 DMIT，DMIT 是上游、搬瓦工是零售”的说法。这个关系两家都没有官方确认过，当参考就行，别当成定价依据。

## DMIT 全部套餐与价格

价格整理自 DMIT 官网套餐页，其中香港 Pro、香港 T1 和东京 Pro 的入门价在 2026 年 11 月初复核过，其余套餐未逐项复核，下单前以结算页显示为准。

**洛杉矶**

| 产品线 · 套餐 | 配置 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| Premium TINY (AN4) | 1核 2GB / 20GB | 1000GB / 1Gbps | $88.88/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium Pocket (AN4) | 2核 2GB / 40GB | 1500GB / 4Gbps | $159.98/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium TINY (AN5) | 1核 2GB / 20GB | 1000GB / 1Gbps | $119.99/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium STARTER | 2核 2GB / 80GB | 3000GB / 10Gbps | $29.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium MINI | 4核 4GB / 80GB | 5000GB / 10Gbps | $76.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball TINY (AN4) | 1核 2GB / 20GB | 1500GB / 2Gbps | $88.88/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball Pocket (AN4) | 2核 2GB / 40GB | 3000GB / 4Gbps | $159.98/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball TINY (AN5) | 1核 2GB / 20GB | 1500GB / 2Gbps | $119.99/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball STARTER (AN5) | 2核 2GB / 80GB | 5000GB / 10Gbps | $38.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 WEE | 1核 1GB / 20GB | 1000GB | $36.90/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 TINY | 1核 1GB / 20GB | 2000GB | $6.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 STARTER | 2核 2GB / 40GB | 4000GB | $12.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |

**香港**

| 产品线 · 套餐 | 配置 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| Premium TINY | 1核 1GB / 20GB | 500GB / 1Gbps | $39.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium STARTER | 1核 2GB / 40GB | 1000GB / 1Gbps | $79.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium MINI | 2核 2GB / 60GB | 1500GB / 1Gbps | $119.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball TINYv2 | 1核 1GB / 20GB | 1000GB / 1Gbps | $29.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball STARTERv2 | 1核 2GB / 40GB | 2000GB / 2Gbps | $59.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 WEE | 1核 1GB / 20GB | 1000GB | $36.90/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 TINY | 1核 1GB / 20GB | 2000GB | $6.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 STARTER | 1核 2GB / 40GB | 4000GB | $12.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |

**东京**

| 产品线 · 套餐 | 配置 | 月流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| Premium TINY | 1核 1GB / 20GB | 500GB / 1Gbps | $21.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium STARTER | 1核 2GB / 40GB | 1000GB / 1Gbps | $39.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Premium MINI | 2核 2GB / 60GB | 2000GB / 1Gbps | $79.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball TINY | 1核 1GB / 20GB | 1000GB / 1Gbps | $25.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Eyeball STARTER | 1核 2GB / 40GB | 2000GB / 2Gbps | $55.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 WEE | 1核 1GB / 20GB | 1000GB | $36.90/年 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 TINY | 1核 1GB / 20GB | 2000GB | $6.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |
| Tier 1 STARTER | 1核 2GB / 40GB | 4000GB | $12.90/月 | [ 查看](https://www.dmit.io/aff.php?aff=9081) |

表格里有两点值得单独拎出来。

一是洛杉矶 Premium 和 Eyeball 的 TINY（AN4）同价，都是 $88.88/年。很多人以为 EB 是缩水版，实际 EB 的流量给到 1500GB、带宽 2Gbps，比 Pro 的 1000GB / 1Gbps 还宽。差别只在回程线路：Pro 是三网 CN2 GIA，EB 走 CMIN2。哪个划算取决于你的宽带，电信用户买 Pro，联通移动用户买 EB 更值。

二是同一个 TINY 分 AN4 和 AN5 两个平台，价格差 $31.11/年，约 35%。配置看上去一样，买的其实是不同代际的宿主机，下单页会标出来。

👉 [按机房查看 DMIT 洛杉矶 Premium 套餐](https://www.dmit.io/aff.php?aff=9081)

## 什么情况下搬瓦工更合适

搬瓦工有两个 DMIT 短期追不上的点：一是 KiwiVM 面板能一键把机器切到 15 个以上机房，重装系统、看实时流量、免费快照、紧急控制台、IP 信誉查询都在一个后台里；二是入门门槛低，CN2 GIA-E 季付 $49.99，配置 2 核 / 2GB 内存 / 40GB SSD / 1TB 流量，可以免费切到洛杉矶 DC6/DC9、加拿大温哥华、日本软银、荷兰联通这些机房。买一台机器试多条线路，这种玩法 DMIT 做不到，买了哪个机房就固定在哪个机房。

价格上搬瓦工也不是全贵。香港 HK2 的 CN2 GIA 是 2 核 2GB / 40GB / 500GB 月流量 / 1Gbps，$89.99/月、年付 $899.99（2026 年 11 月初核对）；大阪、新加坡的 CN2 GIA 月付 $49.99 起。

退款政策搬瓦工更宽松，30 天内可申请，条件是流量使用不超过 10%。换 IP 要付费，论坛用户说在 8 美元左右一次，官方页面没有统一标价。

有用户提到瓦工的优点是流量给得大方、DNS 方式解锁 ChatGPT 客户端好用，缺点是“稳定但性能差”。这条评价来自 2024 年底的论坛帖，机型已经换过几代，只当参考。

## 把年付总价算出来

香港 CN2 GIA 是最能看出差价的一档。DMIT 香港 Premium TINY 是 $39.90/月，按年算 $478.8；搬瓦工香港 HK2 年付 $899.99。同为香港 CN2 GIA，一年差约 $421。DMIT 这边还是月付，用两个月不合适可以停，搬瓦工那个价格是一次付一年。

洛杉矶这边要看平台代际。同一个 LAX.Pro TINY，AN4 平台 $88.88/年，AN5 平台 $119.99/年，配置写的都是 1 核 2GB / 20GB / 1000GB / 1Gbps。差 $31.11 买的是更新一代的宿主机，值不值看你跑什么，纯建站和小流量代理感知不出来。

续费上两家的规则不一样。DMIT 的续费价和首购价一致，测评资料里多次提到这一点；搬瓦工部分套餐存在活动价与续费价的差异，长期用要按续费价算预算。

👉 [以 $39.90/月 开通 DMIT 香港 Premium CN2 GIA](https://www.dmit.io/aff.php?aff=9081)

## 买之前最该确认的四件事

**香港 T1 不等于低延迟。** T1 是国际线路，不做中国大陆优化，官网也写明 IP 不保证在所有国家可用。有人看到“香港节点”就默认延迟低，实际路由可能绕到日本，延迟比洛杉矶 Pro 还高。T1 的正确用途是国际业务、落地中转、需要香港或东京 IP 但不在乎回国速度的场景。

**Pro 和 EB 经常缺货。** 促销期尤其明显，T1 系列一般有货。补货信息会发在官方 Telegram 频道 @dmit_com。

**部分套餐默认 SSH 密钥登录。** 不习惯的话第一次连不上，得先按官方文档配置密钥。

**流媒体解锁官方不做保证。** DMIT 全系原生 IP，实测普遍能解锁 Netflix、TikTok，但官方不拿这个当卖点。买之前建议先用测试 IP 154.17.12.22 验证你要的服务。

## 退款和换 IP 决定试错成本

DMIT 的退款分两档：购买后 3 天内且流量不超过 30GB，可以全额退，扣支付网关手续费；30 天内按剩余价值部分退。3 天够跑一遍 ping、路由追踪和下载测速，线路合不合适基本能判断出来。

换 IP 对做代理类用途的人是长期成本。DMIT 的 Premium 和 Eyeball 系列在 IP 被墙的情况下每 15 天可以免费换一次，其他情况 $5 一次，2026 年起支持自助操作，不用提工单。T1 系列只有付费换 IP。搬瓦工那边按论坛用户口径是 8 美元左右一次，且不免。

如果一台机器打算用两三年，被墙三五次，这笔差价能抵掉小半年的套餐钱。

👉 [查看 DMIT 当前库存与换 IP 政策](https://www.dmit.io/aff.php?aff=9081)

## 几个常被问到的问题

**两家的 CN2 GIA 是同一条线吗？**

圈内一直有 DMIT 是搬瓦工 DC9 上游的说法，两家都没官方确认。能确认的是延迟数据几乎一样，158ms 对 159ms。线路体验接近，差别在超售策略和硬件上。

**DMIT 续费会涨价吗？**

按现有资料，DMIT 续费价与首购价一致。搬瓦工部分套餐的活动价和续费价不同，买之前看清楚续费栏的数字。

**流量超了会怎样？**

T1 系列流量超出后按限速处理，不会直接断网。Pro 和 EB 的具体处理方式下单页有写，买大流量套餐前确认一下。

**促销码还能用吗？**

DMIT 结算页有 Promo Code 输入框，填进去点 Validate Code 就知道有没有效。网上流传的那批码名字里带 2025、202510 字样，整理时间已经过去大半年，别把折扣当成现价去算预算。

## 最后的选购规则

- 只要一台便宜的国际线路机器，做落地、中转或面向海外：三地 T1 WEE，$36.90/年
- 电信用户建站、要三网 CN2 GIA 回程：洛杉矶 Premium TINY（AN4），$88.88/年
- 联通、移动为主，想同样的钱拿更多流量：洛杉矶 Eyeball TINY（AN4），同价 $88.88/年，1500GB / 2Gbps
- 要极低延迟、访客都在国内：香港 Premium TINY $39.90/月，预算紧就看东京 Pro TINY $21.90/月
- 不确定自己要什么：先买 T1 TINY $6.90/月 试一个月，测完路由再决定升不升

下单前确认两件事：套餐页标的是 AN4 还是 AN5 平台，以及目标机房当前有没有货。

👉 [前往 DMIT 选择适合你的机房与套餐](https://www.dmit.io/aff.php?aff=9081)
