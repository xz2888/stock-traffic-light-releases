# 盯盘红绿灯 · Android

**不用反复打开行情页面，在手机桌面看市场、看观察股、看自己的持仓。**

用红绿圆点、指数方框和展开列表，快捷查看个股、持仓及国内外主要指数。原生 Android 应用，不是券商交易软件，不会代你下单。

## 下载与每日观察

| 入口 | 说明 |
| --- | --- |
| [Android 下载 / Releases](https://github.com/xz2888/stock-traffic-light-releases/releases) | 只从正式发布条目获取 APK，并核对版本与校验值；无 APK 附件时表示公开下载尚未开放。 |
| [每日推荐观察 PDF](https://github.com/xz2888/stock-traffic-light-releases/releases?q=daily-observation&expanded=true) | 每日资料发布入口；仅以实际 PDF 附件及其标注的数据日期为准。无附件时表示尚未开放，不代表当天没有观察标的。 |
| [安装与升级](docs/安装与下载.md) | Android 8.0 及以上；升级请覆盖安装，勿卸载或清除数据。 |
| [完整使用手册](docs/使用手册.md) | 浮窗、自选观察、交易记录、本金、收益及推荐名单操作。 |

文档建立时尚未上传公开 APK 或每日 PDF；两者须分别完成发布核验。每日 PDF 是研究观察资料，不是买入指令，不承诺每天必有结果或盈利。**App 内推荐观察与 PDF 是不同交付形式，不能将 PDF 已更新等同于手机已同步。**

## 能帮你做什么

- **桌面悬浮盯盘**：红涨、绿跌，圆点和方框点按展开，支持拖动、分组与显示开关；灰色提示行情不可用或过期。
- **自选与持仓分开**：零股观察卡不混入收益；A 股代码或名称查询后添加，显示、排序分别保存。
- **本地记录实际交易**：买卖需确认，按记录计算持股数量、平均成本和收益；不连接券商下单。
- **本金与收益看清楚**：明确转入/转出才改变本金；查看今日、周/月/年和累计收益，证据不足不当成零。
- **推荐观察独立管理**：手动同步、打开应用时后台补读及系统允许时的定时读取；失败保留上次成功名单，并显示数据日期。
- **急涨急跌声音提醒**：按设定阈值提示短时变化，受声音设置、行情质量及系统后台限制影响。

## 版本与使用边界

已核对的发行记录：**1.9 / versionCode 55（2026-10-27）**，详见 [版本记录](CHANGELOG.md)。此处记录产品版本，不等于 GitHub 已提供可安装附件；下载状态以 Releases 为准。

需要联网获取行情；更新、授权及推荐观察依赖作者维护的服务，其可用性并不由 GitHub 文档保证。首次安装无预置个人股票。当前添加个股面向 A 股，不宣传新增港美个股支持。Android 厂商省电策略可能中断浮窗或延迟同步，不保证锁屏显示、逐笔实时或准点推送。

源码继续保持私有，本仓库是**公开文档与成果发布入口**，不包含构建源码、签名材料或私人配置。

## 帮助、隐私与联系

- [隐私与权限](docs/隐私与权限.md) · [版权与使用说明](docs/版权与使用说明.md)
- [提交问题](https://github.com/xz2888/stock-traffic-light-releases/issues/new/choose)：请隐去持仓、账号、安装凭证和其他个人信息。
- [可复制的推广介绍](docs/推广介绍.md)
- 版权所有 © 摩犀 · xz2888@126.com

仅作快捷盯盘与记录工具，不构成投资建议。行情和统计可能延迟或不完整，请以交易所、券商和真实交易凭证为准；投资风险由使用者自行判断。本说明不排除法律规定的责任。

### English summary
Stock Traffic Light is an Android floating market-watch app with A-share watchlists, locally recorded positions and return summaries. It does not place trades or promise investment returns. This repository hosts public documentation and release materials; application source code remains private. APK and daily observation PDF availability must be checked on the Releases page.
