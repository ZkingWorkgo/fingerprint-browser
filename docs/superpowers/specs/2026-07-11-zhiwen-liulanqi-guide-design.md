# 指纹浏览器评测指南：项目设计规范

- 项目名称：zhiwen-liulanqi-guide
- 仓库所有者：ZkingWorkgo
- 设计版本：1.0
- 制定日期：2026-07-11
- 项目状态：首轮建设中

## 1. 项目定位

本项目是一个独立、公开、可复现的中文指纹浏览器评测与对比项目。

项目通过统一的评分标准，对主流指纹浏览器、反检测浏览器和防关联浏览器进行长期跟踪，公开产品信息来源、测试方法、原始证据、价格变化、版本变化和评分依据。

项目不以文章数量为核心目标，而以信息准确性、测试可复现性、更新及时性和商业透明度为核心竞争力。

## 2. 项目目标

### 2.1 用户目标

帮助中文用户回答以下问题：

1. 指纹浏览器是什么？
2. 指纹浏览器与无痕模式、代理和虚拟机有什么区别？
3. 不同指纹浏览器的核心功能有什么差异？
4. 哪些产品适合个人、团队、自动化或隐私研究？
5. 产品价格、环境数量和团队成员费用如何比较？
6. 产品有哪些优点、限制和潜在风险？
7. 评测结论是否有证据支持？

### 2.2 搜索目标

首批重点覆盖以下中文搜索主题：

- 指纹浏览器
- 指纹浏览器推荐
- 指纹浏览器排名
- 指纹浏览器哪个好
- 2026 指纹浏览器
- 防关联浏览器
- 反检测浏览器
- 免费指纹浏览器
- 指纹浏览器价格
- 指纹浏览器对比

搜索排名是结果指标，不以复制、关键词堆砌、伪造测试、大规模低价值内容或购买垃圾外链的方式实现。

### 2.3 仓库目标

仓库同时承担四种作用：

1. GitHub README 主题入口；
2. 产品结构化数据仓库；
3. 测试证据与变更历史仓库；
4. GitHub Pages 网站的数据源。

## 3. 非目标

首轮建设不包含：

- 复制其他仓库的文章；
- 未经测试就发布产品排名；
- 使用“最安全”“绝对防关联”“全网第一”等无证据结论；
- 大量生成只有关键词不同的重复页面；
- 隐藏推广链接或商业关系；
- 提供规避平台规则、欺诈或账号滥用指导；
- 开发或分发反检测浏览器软件本身。

## 4. 目标读者

主要读者包括：

- 正在选择指纹浏览器的个人用户；
- 需要团队权限和环境管理的企业用户；
- 研究浏览器指纹与隐私保护的技术人员；
- 需要浏览器自动化能力的开发者；
- 希望比较产品价格和功能的采购人员。

## 5. 内容架构

计划采用以下目录结构：

```text
README.md

docs/
  index.md
  ranking.md
  methodology.md
  disclosure.md
  changelog.md

  reviews/
    adspower.md
    multilogin.md
    gologin.md
    dolphin-anty.md

  comparisons/
    adspower-vs-multilogin.md
    free-fingerprint-browsers.md
    fingerprint-browser-pricing.md

  guides/
    what-is-a-fingerprint-browser.md
    fingerprint-browser-vs-incognito.md
    browser-fingerprinting-basics.md

data/
  browsers.yml
  pricing-history.csv
  versions.csv
  test-results.json

evidence/
  screenshots/
  test-logs/
  source-snapshots/

scripts/
  validate-data.py
  generate-tables.py
  check-expiry.py

assets/
  images/
  charts/
  social-preview.png
