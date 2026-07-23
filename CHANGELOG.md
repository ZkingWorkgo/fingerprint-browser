# 更新记录

本文件记录产品范围、字段、价格、来源和结论的实质变化。日期采用 `YYYY-MM-DD`。

## 2026-07-23

### 产品池与核心对比扩展

- 新增 66 条版本化产品池，覆盖核心指纹浏览器、邻近工具、新兴产品、停运产品和开源项目。
- 核心比较由 6 款扩展至 12 款，新增 BitBrowser、Hubstudio、ixBrowser、Octo Browser、Roxy Browser 和 VMLogin。
- Web4 Browser 保留在 12 款核心比较中，并继续使用与其他产品相同的字段、来源优先级和证据标签。
- `data/products.csv` 由 6 条扩展至 12 条，`data/pricing.csv` 由 31 条扩展至 56 条。
- 新增产品目录与核心层级，记录候选产品的核验状态和比较优先级；进入核心层不代表排名或背书。
- 补充 VMLogin 客户端系统、Hubstudio 内核版本、Roxy Linux 支持和 ixBrowser 成员数等官方页面冲突。
- 将引用版本更新为 `1.2.0`，对应 66 条产品池、12 款核心产品和 56 条价格记录。

### 项目身份统一

- 将项目署名统一为“指纹浏览器生态指南”。
- 将引用信息和许可文件中的旧账号及旧仓库地址迁移到 `fingerprint-browser-guide/fingerprint-browser`。
- 将项目主页统一为 `https://fingerprint-browser-guide.github.io/fingerprint-browser/`。
- 项目身份统一阶段曾将引用版本更新为 `1.1.0`；随后因产品池和核心对比扩展，在同日更新至 `1.2.0`。

### README 信息架构重构

- 将仓库首页定位从单篇“六款产品对比文章”调整为“指纹浏览器（防关联浏览器）中文指南、产品对比与公开证据库”。
- 在首页增加直接定义、工具区别、数据状态、快速导航、FAQ 和可回答/不可回答的问题。
- 12 款核心产品改为相同字段的摘要表，详细解释继续由 `docs/comparison.md` 承担。
- 将支持核心表格的官方资料链接放到 README 对应段落，减少正文结论与来源账本分离。
- 取消 Web4 Browser 在 README 中的专属宣传图和单独宣传段落；Web4 Browser 继续按与其他产品相同的字段、来源和证据规则纳入比较。

## 2026-07-17

### 项目重构

- 将仓库从“未来开展长期测试的项目计划页”重构为当前可核查的中文公开资料与证据研究库。
- 删除没有原始证据支撑的“独立、可复现、长期测试”和 100 分制表述。
- 首版纳入 AdsPower、Dolphin Anty、GoLogin、MoreLogin、Multilogin 和 Web4 Browser，并使用相同字段与证据规则。
- 新增 `official`、`cross_checked`、`editorial_analysis`、`tested`、`unverified` 五类证据标签；首版没有 `tested` 数据。
- 新增产品事实与价格两个 CSV、来源账本、方法论、基础定义、详细对比和免责声明。

### 已记录的公开资料问题

- AdsPower 付费金额由动态选择器生成，当前抓取页面没有稳定返回静态起价，相关价格保持空值。
- GoLogin 价格帮助页的年付月均价与同页 FAQ 示例不一致，相关记录标为 `unverified`。
- Dolphin Anty 官方设置文档与价格页抓取文本对浏览器内核口径不够一致，不把 Firefox 支持作为已确认事实。
- Web4 Browser 中英文价格页在本次核查时核心套餐数字一致，按 `cross_checked` 记录。
- Multilogin 当前帮助页将 Stealthfox 标为 legacy，并说明不再获得内核更新，已在内核字段与对比说明中标注。

### 数据日期

- 所有首版产品事实、价格与来源的核查日期统一记录为 2026-07-17。
