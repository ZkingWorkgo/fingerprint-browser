# 指纹浏览器（防关联浏览器）中文指南、产品对比与公开证据库

**指纹浏览器**是一类把 Cookie、本地存储、代理连接和网站可读取的浏览器/设备信号，按多个独立浏览器环境（Profile）分别管理的工具。它也常被称为**防关联浏览器、反检测浏览器或多环境浏览器**，但这些名称没有统一的行业定义。

指纹浏览器可以帮助用户隔离浏览器环境、管理经授权的多个账号或开展网站测试，但它**不能保证匿名、账号不被关联、规避平台风控或长期不封号**。网站仍可能结合账号行为、网络、支付信息、设备信号和平台规则作出判断。

本仓库不是一份只给出“最好用”“第一名”的排行榜，而是一个可复查的中文指南与公开证据库。目前使用同一套字段整理 AdsPower、Dolphin Anty、GoLogin、MoreLogin、Multilogin 和 Web4 Browser 的系统、内核、免费额度、价格、存储、团队与自动化资料。

🌐 **阅读完整指南：** [指纹浏览器是什么？原理、用途、风险与产品选择](https://fingerprint-browser-guide.github.io/fingerprint-browser/)

![指纹浏览器选择指南，涵盖系统、浏览器内核、数据存储、自动化、团队与价格六个选型维度](assets/fingerprint-browser-guide-2026-cover.png)

> **资料状态**
>
> - 产品事实最后核查：**2026-07-17**
> - 项目元数据最后更新：**2026-07-23**
> - 当前覆盖：**6 个产品、49 个公开来源、31 条价格记录**
> - 证据范围：厂商官网、帮助中心、价格页和开发文档
> - 统一横向实测：**尚未进行**

## 快速导航

| 你想解决的问题 | 建议入口 |
|---|---|
| 指纹浏览器是什么，与无痕模式、代理和 VPN 有什么区别 | [基础定义与技术边界](docs/what-is-a-fingerprint-browser.md) |
| 六款产品的系统、内核、自动化、存储和免费额度 | [完整产品对比](docs/comparison.md) |
| 直接查看可下载、可分析的数据 | [产品事实 CSV](data/products.csv) · [价格记录 CSV](data/pricing.csv) |
| 核对表格结论来自哪个官方页面 | [来源账本](SOURCES.md) |
| 了解纳入规则、证据等级和冲突处理 | [评估方法](METHODOLOGY.md) |
| 查看项目发生过哪些实质变化 | [更新记录](CHANGELOG.md) |
| 了解时效性、合法使用和结论边界 | [免责声明](DISCLAIMER.md) |

## 指纹浏览器解决什么问题

[MDN 对浏览器指纹的定义](https://developer.mozilla.org/en-US/docs/Glossary/Fingerprinting)是：网站可以组合浏览器版本、操作系统、时区、语言、字体、编解码器和屏幕尺寸等特征，用来识别某个浏览器，进而可能识别用户。

普通浏览器可以创建多个账号或用户目录，但指纹浏览器通常进一步提供环境级代理、浏览器信号配置、团队权限、环境分享以及 API/RPA 等批量管理能力。不同产品实现差异很大，“能修改参数”也不等于这些参数在目标网站看来一定合理。

| 工具 | 主要作用 | 不能单独解决的问题 |
|---|---|---|
| 无痕/隐私窗口 | 减少历史记录和会话数据留在本机 | 不自动更换 IP，也不创建长期保存的独立环境 |
| 代理 | 改变请求经过的网络出口 | 不自动隔离 Cookie，也不协调时区、字体、Canvas 等浏览器信号 |
| VPN | 在设备或系统层建立网络隧道 | 不自动建立和管理多个浏览器 Profile |
| 虚拟机 | 隔离操作系统和应用 | 成本较高；浏览器与网络信号是否合理仍需单独处理 |
| 指纹浏览器 | 分别管理多套浏览器状态、代理和环境信号 | 不保证匿名、合规、账号安全或零封禁 |

更完整的原理、合法用途和风险说明见[《什么是指纹浏览器》](docs/what-is-a-fingerprint-browser.md)。

## 2026 年六款指纹浏览器公开事实对比

下面的产品按英文名排序，**不是排名**。表格描述的是截至 2026-07-17 可以从公开页面核对的能力，不代表本项目已经验证运行稳定性或账号效果。

| 产品 | 客户端系统 | 浏览器环境 | 免费额度 | 自动化与公开差异 |
|---|---|---|---:|---|
| [AdsPower](https://www.adspower.com/) | Windows、macOS、Ubuntu | SunBrowser（Chromium）、FlowerBrowser（Firefox） | 2 个环境 | Local API、内置 RPA |
| [Dolphin Anty](https://dolphin-anty.com/) | Windows、macOS、Linux | Anty（官方设置文档指向 Chromium） | 5 个环境 | API、CDP、Selenium、Puppeteer、Playwright |
| [GoLogin](https://gologin.com/) | Windows、macOS、Ubuntu/Mint、Android | Orbita（Chromium） | 3 个环境 | REST API、Android 客户端、云端浏览器 |
| [MoreLogin](https://www.morelogin.com/) | Windows、macOS | Chrome、Firefox | 2 个环境、2 个成员 | Local API、免费团队成员 |
| [Multilogin](https://multilogin.com/) | Windows、macOS、Ubuntu | Mimic；Stealthfox 已标为 legacy | 5 个环境 | API、Selenium、Puppeteer、Playwright |
| [Web4 Browser](https://web4browser.io/cn/) | Windows、macOS | Fingerprint Chromium、Fingerprint Firefox | 3 个环境 | CDP、Headless、Selenium、Puppeteer、Playwright、MCP |

![AdsPower、Dolphin Anty、GoLogin、MoreLogin、Multilogin与Web4 Browser六款指纹浏览器公开差异对比](assets/fingerprint-browser-differences-2026.png)

*图片用于快速理解公开差异，不代表实测排名。完整限制、价格与来源以数据文件和来源账本为准。*

### 这张表的来源

- **AdsPower：** [系统要求](https://help.adspower.com/docs/system_requirements)、[浏览器环境](https://help.adspower.com/docs/creating_browser_profiles)、[API](https://help.adspower.com/docs/api)、[RPA](https://help.adspower.com/docs/rpa)
- **Dolphin Anty：** [价格与免费额度](https://dolphin-anty.com/tarifs/)、[环境设置](https://docs.dolphin-anty.com/en/getting-started/guidelines-for-setting-up-a-profile-dolphin-anty)、[自动化](https://docs.dolphin-anty.com/en/api/basic-automation-dolphin-anty)
- **GoLogin：** [支持平台](https://support.gologin.com/en/articles/3452486-supported-platforms-installation)、[Orbita](https://support.gologin.com/en/articles/14853789-orbita-browser)、[API](https://support.gologin.com/en/articles/5461004-api-gologin)
- **MoreLogin：** [使用与系统要求](https://support.morelogin.com/en/articles/10183527-how-to-use-morelogin)、[套餐](https://support.morelogin.com/en/articles/10137594-subscription-packages)、[环境 API](https://support.morelogin.com/en/articles/10204806-browser-profile)
- **Multilogin：** [系统要求](https://multilogin.com/help/en_US/minimum-system-requirements)、[浏览器环境](https://multilogin.com/help/en_US/quick-browser-profiles)、[自动化](https://multilogin.com/help/puppeteer-selenium-and-playwright)
- **Web4 Browser：** [功能](https://web4browser.io/cn/features.html)、[下载与系统要求](https://web4browser.io/cn/download.html)、[价格与免费额度](https://web4browser.io/cn/pricing.html)

更详细的逐项解释见[六个平台完整对比](docs/comparison.md)，结构化原始记录见[`products.csv`](data/products.csv)和[`pricing.csv`](data/pricing.csv)。

## 不先看总榜，先按硬条件筛选

产品是否适合，首先取决于无法妥协的条件，而不是一个没有公开权重的综合分数。

| 首要条件 | 当前可以先核对的产品 | 必须继续确认的限制 |
|---|---|---|
| 需要 Linux 客户端 | AdsPower、Dolphin Anty、GoLogin、Multilogin | 发行版、最低版本和硬件要求不同 |
| 需要 Android 原生客户端 | GoLogin | 模拟 Android 参数不等于 Android 客户端 |
| 需要 Chromium 与 Firefox 两类环境 | AdsPower、MoreLogin、Web4 Browser；谨慎核对 Multilogin | Multilogin 的 Stealthfox 已被标为 legacy |
| 需要内置 RPA | AdsPower | 需要核对套餐权限与任务限制 |
| 需要常见代码自动化框架 | 六款均公开了不同形式的自动化入口 | 接口、并发、套餐和客户端在线要求不同 |
| 需要 MCP 工作流 | Web4 Browser | 公开支持不等于本项目已经验证稳定性 |
| 想先检查两人团队流程 | MoreLogin | 免费档的分享、权限和长期限制仍需实际确认 |
| 更关注默认本地数据 | Web4 Browser | “默认本地”不自动等于更安全或已有备份 |

建议按以下顺序完成第一轮选择：

1. 用操作系统、浏览器内核和原生移动端要求排除不符合条件的产品。
2. 再比较本地/云端存储、团队权限、API、RPA、MCP 与自动化框架。
3. 用实际环境数、成员数、额外席位和计费周期计算总成本，不只看广告起价。
4. 使用免费版或试用版检查自己的合法工作流，但不要把一次成功外推为长期保证。

## 本项目记录了哪些公开资料冲突

公开证据库的价值不只是汇总厂商功能，还包括保留无法被安全简化的矛盾和缺口：

- **AdsPower：** 价格页金额由动态选择器生成，本次没有获得稳定、可引用的静态付费起价，因此没有使用第三方文章补数。
- **Dolphin Anty：** 设置文档明确说明基于 Chromium，但价格页抓取文本出现“Chrome or Firefox engine”；在进一步澄清前，不把 Firefox 支持写成确定事实。
- **GoLogin：** 同一官方价格帮助页对 Professional 年付月均价出现不同数字，相关年付记录标为 `unverified`。
- **Multilogin：** 官方帮助页仍列出 Stealthfox，但同时将其标记为 legacy，并说明不再获得内核更新。
- **Web4 Browser：** “AI 原生”和“真机级环境”属于产品定位；本项目目前只能核对其公开列出的双内核、MCP、自动化入口和默认本地数据，不能据此推导账号成功率。

这些冲突的来源、处理方式和字段影响保存在[来源账本](SOURCES.md)与[更新记录](CHANGELOG.md)中。

## 证据标签如何理解

| 标签 | 含义 |
|---|---|
| `official` | 来自厂商官网、帮助中心、价格页或开发文档 |
| `cross_checked` | 至少两个相关公开来源的核心口径一致 |
| `editorial_analysis` | 基于已列证据作出的比较或解释，不是厂商原话 |
| `tested` | 已公开测试环境、版本、步骤、样本与原始结果 |
| `unverified` | 页面冲突、信息缺失或暂时无法稳定核对 |

当前首版没有 `tested` 数据。未经记录环境与原始证据的“独立测试”、营销演示和单次成功不会被改写为实测结论。具体规则见[评估方法](METHODOLOGY.md)。

## 这个仓库能回答什么

目前可以回答：

- 六款产品公开列出的客户端系统、浏览器内核和免费额度；
- API、RPA、MCP 与常见自动化框架的公开支持情况；
- 团队成员、数据存储和代表性价格口径；
- 官方页面之间已经发现的冲突、缺失和限制；
- 每条结构化记录的来源与核查日期。

目前不能回答：

- 哪个平台账号存活率最高或最不容易被封；
- 哪个平台一定能通过某个指纹检测网站；
- 大规模并发、资源占用、崩溃率和升级兼容性；
- 客服、退款、云同步恢复和数据迁移的真实执行质量；
- 厂商安全宣传是否经过统一的独立审计。

这些问题需要统一版本、设备、代理、目标网站、样本量和原始日志。没有这些条件时，本项目不会生成看似精确的评分。

## 常见问题

### 指纹浏览器能防止账号关联吗？

不能保证。浏览器环境只是网站判断的一部分，账号行为、IP 与 ASN、登录时间、支付信息、历史记录和平台规则都可能影响结果。

### 指纹浏览器和代理 IP 是一回事吗？

不是。代理主要改变网络请求经过的出口；指纹浏览器主要管理 Cookie、存储、浏览器信号和多套环境。实际工作流可能同时使用两者，但它们解决的是不同层面的问题。

### 哪个是最好的指纹浏览器？

没有脱离条件的统一第一名。需要先明确操作系统、内核、环境数、团队成员、存储方式、自动化接口和预算，再用自己的合法工作流验证候选产品。

### 为什么目前只比较六款？

首版只纳入存在可访问的官方站点或帮助中心、并且公开资料足以填写核心字段的产品。六款并不代表全部市场，也不代表未纳入产品一定更差。后续扩展应先进入产品目录和来源核验，再进入完整对比。

### Web4 Browser 的“AI 原生”经过实测了吗？

“AI 原生”和“真机级环境”是产品定位。公开页面可以核对 MCP、Headless、CDP、Selenium、Puppeteer、Playwright、双内核和默认本地数据等具体能力；本项目尚未测试这些能力的稳定性，也不据此承诺账号效果。

## 数据、复核与贡献

本项目优先保存可机器读取的数据，而不是只在文章中保留一张无法追踪的表格：

- [`data/products.csv`](data/products.csv)：系统、内核、自动化、团队、代理、存储和免费额度；
- [`data/pricing.csv`](data/pricing.csv)：套餐、周期、金额、币种、环境数、成员数、来源和核查日期；
- [`SOURCES.md`](SOURCES.md)：实际使用的 49 个公开来源及其支持结论；
- [`METHODOLOGY.md`](METHODOLOGY.md)：纳入规则、证据等级、价格标准化和冲突处理；
- [`CHANGELOG.md`](CHANGELOG.md)：产品事实、字段、来源与项目元数据的实质变化。

发现价格变化、失效链接或事实错误时，可以提交 Issue。请尽量提供产品名称、字段、当前记录、官方 URL、访问日期和页面位置。厂商口头说明、无法公开核查的聊天记录或没有环境信息的截图，不会直接替换现有事实。

本仓库原创文字、表格结构、数据汇编、评估方法与原创示意图采用 [CC BY 4.0](LICENSE.md)；第三方商标、网页内容和外部资料仍归各自权利人所有。

## 合法使用边界

本项目面向合法的隐私保护、网站兼容性测试、广告验证、经授权的账号管理、跨境业务和浏览器自动化研究。

本项目不提供欺诈、撞库、虚假身份、身份验证规避、账号交易、未经授权访问或违反第三方平台规则的操作指导。完整说明见[免责声明](DISCLAIMER.md)。

## 相关研究

- [浏览器指纹检测工具对比](https://github.com/fingerprint-browser-guide/browser-fingerprint-checkers)：BrowserLeaks、CreepJS、Cover Your Tracks、AmIUnique、FingerprintJS、BrowserScan、Pixelscan 与 IPhey。
- [SMS 接码与虚拟号码平台对比](https://github.com/fingerprint-browser-guide/sms-verification-platforms)：号码类型、价格、退款、保留时间、API/MCP 与公开成功率证据。
- [代理 IP 服务](https://github.com/fingerprint-browser-guide/proxy-ip-services)：住宅、ISP、移动和机房代理的公开资料框架。
- [云手机平台](https://github.com/fingerprint-browser-guide/cloud-phone-platforms)：安卓云设备、网络、数据保留、批量管理与自动化。
- [浏览器自动化工具](https://github.com/fingerprint-browser-guide/browser-automation-tools)：Playwright、Puppeteer、Selenium、RPA、API 与 MCP。

全部专题和发布状态见[指纹浏览器生态指南](https://fingerprint-browser-guide.github.io/)。
