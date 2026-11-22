# 资料来源与核验记录 SOURCES

版本：V1.1 最新候选版（保留 V1.0 原始登记，补充 A09 复核；未发布）。首次登记：2026-11-20；各条复核日期见表。

## 资料等级与核验边界

- A：官方技术文档、源码、服务条款及官方资料。运营商或开发者的说明仅证明其公开声明，不代表独立实测。
- B：有完整记录的实际测试。本版本无具体机场实测记录。
- C：可核实第三方资料。本版本未采用第三方品牌评测作为确定结论。
- D：未经核实的信息，不作为确定事实发表。

“可读取”指本次网页检索获得了对应官方页面的文本或存档快照；不是实时 HTTP 可用性保证、软件测试或品牌核验。下列日期是本次检索日期，不是网页发布日期。文章中的虚构算例及模板均属教学内容，不列为 B 级。

## 正文引用登记

编号 01–12 对应 README 知识库的既定顺序。同一 URL 合并登记；正文原始链接仍保留。

| 编号 | 来源名称及原始地址 | 等级 | 复核日期 | 核验状态 | 对应文章 | 用途与限制 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A01 | [RFC Editor](https://www.rfc-editor.org/) | A | 2026-11-20 | 可读取公开页面或快照 | README | 标准文献检索入口，不单独证明技术结论 |
| A02 | [RFC 2681](https://www.rfc-editor.org/info/rfc2681/) | A | 2026-11-20 | 可读取公开页面或快照 | README、03、10、11 | IP 往返延迟测量；不等于客户端任意 Ping 算法 |
| A03 | [RFC 7680](https://www.rfc-editor.org/info/rfc7680/) | A | 2026-11-20 | 可读取公开页面或快照 | README、03、04、10、11 | IP 单向丢包定义；注意测量条件 |
| A04 | [RFC 5481](https://www.rfc-editor.org/info/rfc5481/) | A | 2026-11-20 | 可读取公开页面或快照 | 03、04、10 | 数据包时延变化；不同统计口径不可混用 |
| A05 | [RFC 6349](https://www.rfc-editor.org/info/rfc6349/) | A | 2026-11-20 | 可读取公开页面或快照 | 03、10 | TCP 吞吐量测试框架；不声称本项目完成标准测试 |
| A06 | [Project X：VLESS](https://xtls.github.io/en/config/inbounds/vless.html) | A | 2026-11-20 | 可读取公开页面或快照 | 05、06 | 轻量无状态结构、用户身份及 VLESS Encryption 功能；不构成配置指导或安全认证 |
| A07 | [Project X：VMess](https://xtls.github.io/en/development/protocols/vmess.html) | A | 2026-11-20 | 可读取公开页面或快照 | 05、06 | 协议认证及加密概念；注意版本差异 |
| A08 | [Project X：Trojan](https://xtls.github.io/en/config/inbounds/trojan.html) | A | 2026-11-20 | 可读取公开页面或快照 | 06 | 认证机制及相关传输保护概念 |
| A09 | [Project X：传输配置](https://xtls.github.io/en/config/transport.html) | A | 2026-11-21 | 本轮重新取得官方页面文本或快照 | 06 | 区分协议、传输、安全层；非实时 HTTP 检测 |
| A10 | [Shadowsocks：AEAD](https://shadowsocks.org/doc/aead) | A | 2026-11-20 | 可读取公开页面或快照 | 06 | 机密性与完整性；不概括所有历史版本 |
| A11 | [Mihomo：配置文档](https://wiki.metacubex.one/en/config/) | A | 2026-11-20 | 可读取公开页面或快照 | README | 配置对象和结构 |
| A12 | [Mihomo：代理集合](https://wiki.metacubex.one/en/config/proxy-providers/) | A | 2026-11-20 | 可读取公开页面或快照 | 05、07 | 配置集合和分发对象 |
| A13 | [Mihomo：代理集合内容](https://wiki.metacubex.one/en/config/proxy-providers/content/) | A | 2026-11-20 | 可读取公开页面或快照 | README | 配置内容形式；不是服务兼容认证 |
| A14 | [Mihomo：配置示例](https://wiki.metacubex.one/en/example/conf/) | A | 2026-11-20 | 可读取公开页面或快照 | 07 | 数据结构及 YAML 表达 |
| A15 | [Mihomo 历史 Wiki](https://github.com/MetaCubeX/mihomo/wiki) | A | 2026-11-20 | 可读取公开页面或快照 | 07 | 历史 Clash.Meta 命名；新功能以现行文档为准 |
| A16 | [Clash Verge Rev](https://github.com/clash-verge-rev/clash-verge-rev) | A | 2026-11-20 | 可读取公开页面或快照 | README、01、07、08、11 | 桌面系统及软件定位 |
| A17 | [v2rayN](https://github.com/2dust/v2rayN) | A | 2026-11-20 | 可读取公开页面或快照 | README、01、08 | Windows、Linux、macOS 及多内核定位 |
| A18 | [v2rayNG](https://github.com/2dust/v2rayNG) | A | 2026-11-20 | 可读取公开页面或快照 | README、01、08 | Android 客户端定位 |
| A19 | [Shadowrocket App Store（马来西亚区）](https://apps.apple.com/my/app/shadowrocket/id932747118) | A | 2026-11-20 | 可读取公开页面或快照 | README、01、08 | 开发者软件说明；非中国区可获得性或安全认证 |
| A20 | [Android Developers：VPN](https://developer.android.com/develop/connectivity/vpn) | A | 2026-11-20 | 可读取公开页面或快照 | 01 | 操作系统 VPN 接口概念 |
| A21 | [Android Developers：权限](https://developer.android.com/guide/topics/permissions/overview) | A | 2026-11-20 | 可读取公开页面或快照 | 12 | 权限范围及受限操作；非具体软件安全审计 |
| A22 | [FTC：网站与应用隐私](https://consumer.ftc.gov/articles/how-websites-and-apps-collect-and-use-your-information) | A | 2026-11-20 | 可读取公开页面或快照 | 01 | 一般隐私教育资料，不作为中国大陆法律依据 |
| A23 | [FTC：试用与自动续费](https://consumer.ftc.gov/articles/getting-and-out-free-trials-auto-renewals-and-negative-option-subscriptions) | A | 2026-11-20 | 可读取公开页面或快照 | 02、11、12 | 一般消费风险提醒，不推定本地退款权利 |
| A24 | [Airtel：国际专线](https://www.airtel.in/b2b/international-private-line) | A | 2026-11-20 | 可读取公开页面或快照 | README、09 | 企业专用连接的官方公示，非第三方机场线路证据 |
| A25 | [中国电信欧洲：IEPL](https://www.chinatelecomeurope.com/product/iepl/) | A | 2026-11-20 | 可读取公开页面或快照 | README、09 | 以太网专线产品概念，非实际第三方线路核验 |

## 本次移除及替换记录

- TIME 国际私有连接页面：本次获取超时，README 与文章09改用中国电信欧洲 IEPL 官方页面；不判定旧地址已失效。
- Android Help 应用权限页面：本次触发访问验证，文章12改用 Android Developers 权限概览。
- Project X 协议索引：取得公开搜索记录但正文读取失败，文章05改用可读取的 VLESS、VMess 具体官方文档。

## 编辑原则参考（不计入正文引用数）

[Bing Webmaster Guidelines](https://www.bing.com/webmasters/help/bing-webmaster-guidelines-30fba23a)（2026-11-20，官方搜索记录可确认）：遵循真实内容、自然链接、清晰导航。不承诺 GitHub 收录、排名或排名时间。

## 尚无证据的内容

具体机场名称、套餐实际报价、线路架构、实测指标及用户评价尚未收集为本项目可发布证据。关联博客具体页面未完成全文及商业披露核验，本版本不加入其链接。日后补充须记录原始来源、日期、适用范围及利益关系。

## 维护

每14天复查外链、价格与服务资料；每季度复核协议及软件。重大变化及时修订，保留 [更新记录](CHANGELOG.md)。请按 [贡献规则](CONTRIBUTING.md) 提交更正，并阅读 [商业披露](DISCLOSURE.md)。
