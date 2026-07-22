# 更新记录

本文件记录产品范围、字段、价格、来源和结论的实质变化。日期采用 `YYYY-MM-DD`。

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
