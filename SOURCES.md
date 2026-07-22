# 来源账本

最后核查：2026-07-17

本页记录首版数据实际使用的公开来源。`有效` 表示本次访问时页面可用；`待复核` 表示页面内部或与其他官方页面存在需要继续确认的口径。来源状态不代表对厂商全部宣传主张的认可。

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

## 通用技术资料

| 来源页面 | 类型 | 支持结论 | 状态 |
|---|---|---|---|
| [MDN: Fingerprinting](https://developer.mozilla.org/en-US/docs/Glossary/Fingerprinting) | 权威技术文档 | 浏览器指纹的定义和常见组成信号 | 有效 |
| [MDN: privacy.websites](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/privacy/websites) | 浏览器开发文档 | 网站通过 Web API 收集配置数据形成指纹 | 有效 |
| [Mozilla: Private Browsing](https://support.mozilla.org/en-US/kb/private-browsing-use-firefox-without-history) | 浏览器官方帮助 | 隐私浏览减少本地记录，但不会让用户在互联网上匿名 | 有效 |
| [MDN: Proxy Server](https://developer.mozilla.org/en-US/docs/Glossary/Proxy_server) | 权威技术文档 | 代理服务器是用户与目标之间的中间程序或计算机 | 有效 |

## 如何提交更新

提交 issue 时请提供：产品、字段、当前记录、官方 URL、访问日期、页面原文所在位置，以及该变更应当标为 `official`、`cross_checked` 还是 `unverified`。只有无法公开核查的聊天记录或内部口头说明，不会直接替换现有事实。
