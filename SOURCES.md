# 来源账本

最后核查：2026-07-23

本页记录核心对比数据实际使用的公开来源。`有效` 表示本次访问时页面可用；`待复核` 表示页面内部或与其他官方页面存在需要继续确认的口径。来源状态不代表对厂商全部宣传主张的认可。

## AdsPower

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [Pricing](https://www.adspower.com/pricing) | 官方价格页 | 免费版 2 个环境、0 个普通成员、1 个超级管理员；付费档环境范围；Enterprise 询价 | 有效 |
| [System Requirements](https://help.adspower.com/docs/system_requirements) | 官方帮助中心 | Windows、macOS、Ubuntu 客户端要求 | 有效 |
| [Creating Browser Profiles](https://help.adspower.com/docs/creating_browser_profiles) | 官方帮助中心 | SunBrowser 与 FlowerBrowser；环境级代理配置 | 有效 |
| [API](https://help.adspower.com/docs/api) | 官方开发文档 | Local API、API Key 与无头模式说明 | 有效 |
| [RPA](https://help.adspower.com/docs/rpa) | 官方帮助中心 | 内置 RPA、计划任务与日志 | 有效 |
| [Members](https://help.adspower.com/docs/members) | 官方帮助中心 | 成员角色、权限与团队管理 | 有效 |
| [Global Settings](https://help.adspower.com/docs/global_settings) | 官方帮助中心 | 云同步相关设置 | 有效 |
| [Cache Data](https://help.adspower.com/docs/Cache-Data) | 官方帮助中心 | 本地缓存与云缓存的差异 | 有效 |

核查说明：付费套餐金额由动态选择器生成，本次公开页面没有稳定返回可引用的静态起价，因此 `pricing.csv` 不补写第三方文章中的数字。

## Multilogin

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [Pricing](https://multilogin.com/pricing/) | 官方价格页 | 免费 5 个环境；Pro 与 Business 的年费、环境数、团队席位和附加流量 | 有效 |
| [Minimum System Requirements](https://multilogin.com/help/en_US/minimum-system-requirements) | 官方帮助中心 | Windows 10+、macOS 14+、Ubuntu 22+、仅 64 位 | 有效 |
| [Quick Browser Profiles](https://multilogin.com/help/en_US/quick-browser-profiles) | 官方帮助中心 | Mimic 与 Stealthfox 浏览器类型；Stealthfox 被标记为 legacy 且不再获得内核更新 | 有效 |
| [Puppeteer, Selenium and Playwright](https://multilogin.com/help/puppeteer-selenium-and-playwright) | 官方开发文档 | API 与三种自动化框架支持 | 有效 |
| [Workspace Roles and Permissions](https://multilogin.com/help/en_US/workspace-roles-and-permissions) | 官方帮助中心 | Owner、Manager、Operator、Starter 等工作区权限 | 有效 |
| [Profile Settings: Proxy](https://multilogin.com/help/profile-settings-proxy-section) | 官方帮助中心 | 内置代理和自定义代理 | 有效 |
| [Cloud and Local Storage](https://multilogin.com/help/en_US/profile-management/cloud-and-local-storage) | 官方帮助中心 | 云端与本地存储；移动环境的存储限制 | 有效 |

核查说明：当前价格页同时销售浏览器环境和云手机能力。本项目只引用能明确对应浏览器环境或共享套餐容量的字段。

## GoLogin

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [Pricing](https://support.gologin.com/en/articles/14617029-pricing) | 官方帮助中心 / 价格 | 免费版、各付费档起价、环境数、API 限额、团队成员和代理流量 | 待复核 |
| [Supported Platforms & Installation](https://support.gologin.com/en/articles/3452486-supported-platforms-installation) | 官方帮助中心 | Windows、macOS、Linux、Android 与不支持系统 | 有效 |
| [Orbita Browser](https://support.gologin.com/en/articles/14853789-orbita-browser) | 官方帮助中心 | Orbita 基于与 Chrome 相同的开源基础 | 有效 |
| [API GoLogin](https://support.gologin.com/en/articles/5461004-api-gologin) | 官方开发文档 | API、Puppeteer 与 Selenium 接入 | 有效 |
| [Cloud Browser](https://gologin.com/docs/api-reference/cloud-browser/what-is-gologin-cloud-browser) | 官方开发文档 | Puppeteer、Playwright、持久环境与代理路由 | 有效 |
| [How to Share Profiles](https://support.gologin.com/en/articles/14810554-how-to-share-profiles) | 官方帮助中心 | 环境分享权限 | 有效 |
| [Team Members](https://support.gologin.com/en/articles/3452652-team-members) | 官方帮助中心 | 团队成员与工作区协作 | 有效 |
| [Built-in Proxy Manager](https://support.gologin.com/en/articles/14442381-built-in-proxy-manager) | 官方帮助中心 | 内置代理管理 | 有效 |
| [FAQ: Proxies](https://support.gologin.com/en/articles/14839275-faq-proxies) | 官方帮助中心 | 内置与第三方代理 | 有效 |
| [Profile Synchronization](https://support.gologin.com/en/articles/14404855-profile-synchronization) | 官方帮助中心 | 指纹、Cookie、本地存储和扩展云同步 | 有效 |
| [Storage & Cache Management](https://support.gologin.com/en/articles/15451173-storage-cache-management) | 官方帮助中心 | 运行时本地临时数据与浏览器二进制文件 | 有效 |

核查说明：价格页计划表写 Professional 年付月均 4.5 美元起，但同页 FAQ 的示例句重复写为 9 美元/月。该年付记录保留为 `unverified`；月付起价仍按计划表记录。

## Dolphin Anty

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [Plans & Pricing](https://dolphin-anty.com/tarifs/) | 官方价格页 | Free、Starter、Base、Team、Enterprise 的月价、环境数与额外用户价格 | 有效 |
| [Quick Start](https://docs.dolphin-anty.com/en/getting-started/quick-start-in-dolphin-anty) | 官方帮助中心 | Windows、macOS、Linux；代理与团队角色入门 | 有效 |
| [Guidelines for Setting Up a Profile](https://docs.dolphin-anty.com/en/getting-started/guidelines-for-setting-up-a-profile-dolphin-anty) | 官方帮助中心 | Dolphin Anty 基于 Chromium；代理与指纹配置边界 | 有效 |
| [Basic Automation](https://docs.dolphin-anty.com/en/api/basic-automation-dolphin-anty) | 官方开发文档 | API、DevTools Protocol、Puppeteer、Playwright 与 Selenium | 有效 |
| [Transfer and Share a Browser Profile](https://docs.dolphin-anty.com/en/teamwork/how-to-transfer-and-share-a-browser-profile-in-dolphin-anty) | 官方帮助中心 | 环境分享、转移与权限条件 | 有效 |
| [Profile Cloud Sync](https://docs.dolphin-anty.com/en/working-with-profiles/profile-cloud-sync) | 官方帮助中心 | 本地存储、可选云同步及关闭同步后的限制 | 有效 |
| [Application Interface](https://docs.dolphin-anty.com/en/interface-dolphin-anty/application-interface-dolphin-anty) | 官方帮助中心 | 代理的添加、检查、分享和批量操作 | 有效 |

核查说明：设置文档明确写 Dolphin Anty 基于 Chromium；价格页的功能表抓取文本同时出现“Chrome or Firefox engine”。由于两者口径不够清晰，本项目不把 Firefox 支持写成确定事实。

## MoreLogin

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [Subscription Packages](https://support.morelogin.com/en/articles/10137594-subscription-packages) | 官方帮助中心 / 价格 | 30/60/180/360 天价格矩阵、环境数与额外成员价格 | 有效 |
| [How to Use MoreLogin](https://support.morelogin.com/en/articles/10183527-how-to-use-morelogin) | 官方帮助中心 | 客户端系统、Chrome/Firefox、免费环境与成员数 | 有效 |
| [MoreLogin Overview](https://support.morelogin.com/en/articles/10137340-morelogin-overview) | 官方帮助中心 | 自动化、团队与代理能力；硬件和系统要求 | 有效 |
| [Browser Profile API](https://support.morelogin.com/en/articles/10204806-browser-profile) | 官方开发文档 | Local API、Chrome/Firefox 环境与自动化参数 | 有效 |
| [Team Management](https://support.morelogin.com/en/articles/10137638-team-management) | 官方帮助中心 | 超级管理员、管理员、经理和成员权限 | 有效 |
| [Setting Center](https://support.morelogin.com/en/articles/10198603-setting-center) | 官方帮助中心 | Cookie、扩展、本地存储和 IndexedDB 云同步；本地缓存位置 | 有效 |

核查说明：帮助中心把客户端支持系统和环境模拟系统分别描述。本项目只把 Windows 10 64 位+、macOS 12.6.1+ 写入 `supported_os`，不把可模拟的 Android/iOS 误写成客户端系统。

## Web4 Browser

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [中文官网](https://web4browser.io/cn/) | 官方产品页 | 产品定位、环境、代理、Cookie、本地数据与 AI 工作流入口 | 有效 |
| [功能页](https://web4browser.io/cn/features.html) | 官方产品文档 | Fingerprint Chromium/Firefox、HTTP/HTTPS/SOCKS5、CDP、Selenium/Puppeteer/Playwright、默认本地存储 | 有效 |
| [下载页](https://web4browser.io/cn/download.html) | 官方下载页 | Windows 10/11 x64、macOS 12+、Intel 与 Apple Silicon | 有效 |
| [帮助中心](https://web4browser.io/cn/help.html) | 官方帮助页 | 代理类型与指纹字段说明 | 有效 |
| [中文价格页](https://web4browser.io/cn/pricing.html) | 官方价格页 | Free、Starter、Small Team、Popular、Scale Team、Custom 的价格、环境和成员数 | 有效 |
| [English Pricing](https://web4browser.io/pricing.html) | 官方价格页 | 与中文价格页交叉确认套餐数字 | 有效 |

核查说明：Web4 Browser 与其他产品使用完全相同的字段、来源优先级和证据标签。只使用公开页面，没有用内部资料补全字段。本次核查时中英文价格页的核心数字一致。

## BitBrowser / 比特浏览器

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [中文官网](https://www.bitbrowser.cn/) | 官方产品页 | Google、Firefox 内核系；Local API、RPA、团队协作与指纹字段 | 有效 |
| [下载页](https://www.bitbrowser.cn/download) | 官方下载页 | Windows 10+ x64、macOS 12+ Intel/Apple Silicon | 有效 |
| [价格方案](https://www.bitbrowser.cn/price) | 官方价格页 | 免费 10 个环境、1 名成员、每日打开和新建限制；代表性团队套餐 | 有效 |
| [API 接口文档](https://doc2.bitbrowser.cn/jiekou.html) | 官方开发文档 | Local API 入口 | 有效 |

核查说明：官网把指纹浏览器、Android 云手机和 iOS 真机集群放在同一产品导航中。本项目的核心对比只记录桌面指纹浏览器字段，不把云手机或 iOS 真机能力算作浏览器客户端能力。

## VMLogin

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [系统要求](https://www.vmlogin.com.cn/help/get-started/system-requirements.html) | 官方帮助中心 | 客户端只支持 Windows；模拟系统不等于客户端系统 | 有效 |
| [VMLogin 介绍](https://www.vmlogin.com.cn/help/introduction.html) | 官方帮助中心 | 本地与云同步、团队分享、代理和自动化能力 | 有效 |
| [自动化接口](https://www.vmlogin.com.cn/help/api/automation-interfaces.html) | 官方开发文档 | REST API、Selenium 与 Puppeteer | 有效 |
| [试用套餐功能](https://www.vmlogin.com.cn/help/get-started/trial.html) | 官方帮助中心 | 3 天试用、5 个环境及团队能力限制 | 有效 |
| [价格方案](https://www.vmlogin.com.cn/pricing.html) | 官方价格页 | Personal、Solo、Team、Scale 的月价、环境和子账号数 | 待复核 |

核查说明：价格页的 FREE 卡片把添加子账号、分享和转移列为可用，具体的试用说明页却明确写为不可用。试用团队能力因此采用更具体页面的说明，并保留冲突。旧内核更新页仍展示 Chromium 79/86，本项目不把这些数字写成当前内核版本。

## Hubstudio

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [价格](https://www.hubstudio.cn/pricing/index.html) | 官方价格页 | 免费、VIP、SVIP 的起价、每日打开次数、环境与云存储口径 | 有效 |
| [开始使用](https://support-orig.hubstudio.cn/373a/0bfa) | 官方帮助中心 | Windows 7+ 客户端及基础配置要求 | 有效 |
| [新建环境](https://support-orig.hubstudio.cn/645e/2879) | 官方帮助中心 | ChroBrowser、FireBrowser 和环境模拟系统 | 待复核 |
| [API 文档](https://api-docs.hubstudio.cn/) | 官方开发文档 | Local API、Selenium、Puppeteer、Playwright 和请求频率 | 有效 |
| [为什么要设置代理](https://support-orig.hubstudio.cn/7794/e409) | 官方帮助中心 | 官方不直接提供代理，需使用第三方代理 | 有效 |

核查说明：API 页面和环境文档对 ChroBrowser 版本出现 100 与 109 以上等不同口径，FireBrowser 也有单独限制。核心数据只记录浏览器名称，不写统一内核版本。

## Roxy Browser

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [软件安装与系统要求](https://roxybrowser.cn/docs/quick/System-requirements.html) | 官方帮助中心 | Windows 10+、Windows Server 2016+、macOS 10.12+ | 有效 |
| [入门常见问题](https://roxybrowser.cn/docs/faqs/problem.html) | 官方帮助中心 | Chromium/Firefox；FAQ 另列 Linux 客户端 | 待复核 |
| [API 说明](https://roxybrowser.cn/docs/api-documentation/api-reference.html) | 官方开发文档 | Local API、Selenium、Puppeteer、Playwright | 有效 |
| [窗口配置](https://roxybrowser.cn/docs/features/profile-configuration.html) | 官方帮助中心 | 本地优先、可选云同步与缓存设置 | 有效 |
| [价格方案](https://roxybrowser.cn/pricing) | 官方价格页 | 免费 5 个环境、项目数、API 频率、一次性试用与阶梯范围 | 有效 |
| [购买订阅](https://roxybrowser.cn/docs/pricing/subscription.html) | 官方帮助中心 / 价格 | 环境单位价格、团队和成员附加费用 | 有效 |

核查说明：下载与系统要求页没有列出 Linux，FAQ 却写支持 Windows、Mac 和 Linux，因此 Linux 保留为冲突项。官网的用户数、检测通过、安全认证和成功率主张不直接写入产品事实表。

## ixBrowser

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [产品首页](https://www.ixbrowser.com/en) | 官方产品页 | 免费额度、团队、云端存储、API 和付费套餐金额 | 待复核 |
| [下载中心](https://www.ixbrowser.com/en/download-page) | 官方下载页 | Windows 10+、macOS Intel/Apple Silicon 与当前版本记录 | 有效 |
| [Pricing](https://www.ixbrowser.com/pricing) | 官方价格页 | 免费及付费档的环境、团队席位、每日新建和打开次数 | 待复核 |

核查说明：首页写免费版“Unlimited sub-accounts”，价格表写 2 个团队席位，成员数因此不填确定值。当前可访问的官方技术页面也没有明确说明具体浏览器内核，本项目不根据界面、扩展兼容或第三方文章推断。

## Octo Browser

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [System Requirements](https://docs.octobrowser.net/en/start/system-requirements/) | 官方帮助中心 | Windows、macOS、Linux 的具体支持版本及仅 x64 | 有效 |
| [Browser Profile Settings](https://docs.octobrowser.net/en/profiles/browser-profile-settings/) | 官方帮助中心 | Octium 基于 Chromium；桌面和移动环境字段 | 有效 |
| [Working with API](https://docs.octobrowser.net/en/api/start-api/) | 官方开发文档 | API、Playwright、Puppeteer、Selenium、CDP 及套餐限额 | 有效 |
| [Types of Proxies](https://docs.octobrowser.net/en/proxy/proxy-types/) | 官方帮助中心 | HTTP、HTTPS、SOCKS5、SSH 和 IPv6 | 有效 |
| [Account Settings](https://docs.octobrowser.net/en/start/account-settings/) | 官方帮助中心 | 设备本地缓存与客户端设置 | 有效 |
| [Choosing a Subscription](https://docs.octobrowser.net/en/payments/subscriptions/) | 官方帮助中心 / 价格 | Base、Team、Advanced 的环境、成员和 API 容量 | 有效 |
| [中文价格页](https://octobrowser.net/zh/pricing/) | 官方价格页 | Lite、Starter、Base、Team、Advanced 月价 | 有效 |

核查说明：Octo Browser 另有 iOS 产品与免费促销环境，但不与桌面订阅混为一谈。指纹质量、接近 100% 正常运行时间和未发生数据泄漏等厂商声明不作为本项目测试结论。

## 通用技术资料

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [MDN: Fingerprinting](https://developer.mozilla.org/en-US/docs/Glossary/Fingerprinting) | 权威技术文档 | 浏览器指纹的定义和常见组成信号 | 有效 |
| [MDN: privacy.websites](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/privacy/websites) | 浏览器开发文档 | 网站通过 Web API 收集配置数据形成指纹 | 有效 |
| [Mozilla: Private Browsing](https://support.mozilla.org/en-US/kb/private-browsing-use-firefox-without-history) | 浏览器官方帮助 | 隐私浏览减少本地记录，但不会让用户在互联网上匿名 | 有效 |
| [MDN: Proxy Server](https://developer.mozilla.org/en-US/docs/Glossary/Proxy_server) | 权威技术文档 | 代理服务器是用户与目标之间的中间程序或计算机 | 有效 |

## 如何提交更新

提交 issue 时请提供：产品、字段、当前记录、官方 URL、访问日期、页面原文所在位置，以及该变更应当标为 `official`、`cross_checked` 还是 `unverified`。只有无法公开核查的聊天记录或内部口头说明，不会直接替换现有事实。
