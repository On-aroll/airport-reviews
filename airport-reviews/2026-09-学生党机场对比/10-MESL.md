# MESL 怎么选？官方客户端、OpenWrt 与多设备接入（2026 年 11 月）

> **一句话定位** · MESL 的特点是用同一账号登录电脑、手机、Apple TV 和 OpenWrt 路由器，官方 App 自动获取配置。官网公开档从 ¥50/月起，两档都有 5 个同时在线名额。[MESL 官网](https://mesl.cloud/)

**待实测** · 价格、客户端和条款核对于 2026-11-10。节点、出口 IP 与晚高峰表现待实测。

## 一、两档月付怎么选

| 档位 | 月付 | 月流量 | 标称单 GB | 同时在线上限 |
| --- | --- | --- | --- | --- |
| Premium 200G | ¥50 | 200 GB | ¥0.25 | 5 个公网 IP |
| Premium 300G | ¥70 | 300 GB | 约 ¥0.23 | 5 个公网 IP |

300G 档每月多 ¥20，增加 100 GB。两档公开的设备名额、客户端与工单支持相同，可用最近一个月的用量估算所需档位。表中单价按用满套餐额度计算，实际使用时上下行都计量，标有倍率的节点按倍率扣量。[官网套餐](https://mesl.cloud/#plans) · [流量计费条款](https://tos.meslcloud.com/terms?lang=zh)

## 二、它的特点是多端配置和路由器接入

- **官方 App 登录即取配置** · 官网列有 Windows、macOS、Linux、Android、iPhone、iPad 和 Apple TV 客户端。账户支持两步验证和通行密钥，电脑端可以导出诊断信息提交工单。[MESL 官网](https://mesl.cloud/)
- **OpenWrt 有专门的安装包** · 官网列出 OpenWrt 22.03 及以上，覆盖 x86_64、ARM64 和 ARMv7，可以通过路由器的网页界面安装和管理。无法安装客户端的电视或游戏机也可以经路由器接入。[OpenWrt 支持说明](https://mesl.cloud/#faq)
- **5 个名额按公网 IP 计** · 家里电脑和平板如果共用同一个公网 IP，可共用一个名额。手机切到另一个公网 IP 的移动网络时，会占用额外名额。个人套餐适用于本人和同住家人。[MESL 服务条款](https://tos.meslcloud.com/terms?lang=zh)

## 三、续费、第三方订阅和退款

1. **提前续费和重置流量分别处理。** 同档提前续费会延长有效期，当期已用流量保留。月度账单日重置额度，未用流量清零。流量提前用完时服务暂停，可在后台购买重置流量。[MESL 服务条款](https://tos.meslcloud.com/terms?lang=zh)
2. **第三方客户端要先开启订阅。** 订阅地址默认关闭，导入或更新前需要在网页临时打开。官方 App 登录后会自动处理。具体订阅格式、节点倍率和速率限制按账户页面确认。[MESL 服务条款](https://tos.meslcloud.com/terms?lang=zh)
3. **网站购买与 App Store 订阅各走各的退款规则。** 网站订单因个人网络不适配等原因一般不退款。因服务商原因长期无法使用时，条款列有补偿时长或退款的处理方式。App Store 订阅的取消及退款由 Apple 处理。[MESL 退款条款](https://tos.meslcloud.com/terms?lang=zh)

隐私政策说明，部分服务器会记录访问目标、来源 IP 和连接时间等信息，用于故障排查和处理滥用投诉。[MESL 隐私政策](https://tos.meslcloud.com/privacy?lang=zh)

## 四、适合谁，先测什么

- **电脑、手机和电视一起用** · 先核对各设备的 App 或路由器版本，再分别用家庭 Wi-Fi 和手机移动网络测试在线名额与连接。
- **在意特定出口或晚高峰表现** · 先用短周期在常用网络检查目标节点、实际扣量和出口 IP，再验证 GitHub、AI 或流媒体等自己的常用服务。现行公开套餐页未列逐节点的线路、协议和 IP 类型，具体表现以实测为准。[MESL 官网套餐](https://mesl.cloud/#plans)

---

[官方网址](https://getmesl.com/#/register?code=wCKFzQ5N)

[返回总览与横向对比](README.md)
