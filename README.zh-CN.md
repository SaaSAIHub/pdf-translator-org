[English](README.md) · [简体中文](README.zh-CN.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md)

<img src="assets/pdftranslator-logo.png" alt="PDFTranslator.org logo" width="64" height="64">

# PDFTranslator.org — 免费在线 PDF 翻译器，AI 驱动保留排版

[PDFTranslator.org](https://pdftranslator.org/zh) 支持将整份 PDF 翻译为 100 多种语言，并尽可能保留文字布局、表格和图片。阅读译文可下载纯译文 PDF，需要逐页对照时可下载双语 PDF。

**游客每自然月可免费翻译 50 页普通 PDF。注册账户每月有 600 页普通 PDF 免费额度，首次注册另赠 1,000 积分。需要 OCR 的扫描件按整份文件使用积分。**

[开始在线翻译 PDF](https://pdftranslator.org/zh) · [额度与价格](https://pdftranslator.org/zh/pricing) · [产品反馈与功能建议](https://pdftranslator-org.feedlog.ai/)

这是由 [SaaSAIHub](https://github.com/SaaSAIHub) 维护的官方产品文档仓库，提供在线服务的使用指南与翻译效果展示，不包含网站应用源码或翻译引擎。

![游客上传表单显示剩余 50 页免费额度、最多 2 个任务](assets/pdf-translator-online-homepage.jpg)

*英文官网首页的游客视图。*

## 免费 AI PDF 翻译：功能与使用范围

PDFTranslator 适合学生、研究人员及职场用户阅读外语 PDF，减少逐段复制、粘贴翻译的工作。

| 功能 | 当前说明 |
| --- | --- |
| PDF 下载 | 纯译文 PDF、含原文和译文的双语 PDF。 |
| 100 多种语言 | 自行选择文档源语言和目标语言。 |
| 保留排版 | 尽可能保留布局、表格、图片及页面结构；复杂文档需检查。 |
| 翻译风格 | 通用领域、学术论文、法律法规、商务文件。 |

| 使用身份 | 每月普通 PDF 免费页数 | 单文件上限 | 排队与处理中的任务数合计 |
| --- | ---: | --- | ---: |
| 游客 | 50 | 20 MiB / 200 页 | 2 |
| 免费账户 | 600 | 20 MiB / 200 页 | 2 |
| 有效月卡会员 | 600 | 50 MiB / 800 页 | 5 |

月卡为一次性购买，有效期 30 天，期内新任务优先处理，到期不会自动续费。

## 如何在线翻译 PDF

1. 打开 [PDFTranslator.org 中文首页](https://pdftranslator.org/zh)，选择或拖入 PDF。
2. 选择文档源语言和目标语言。
3. 选择通用领域，或按内容选择学术论文、法律法规、商务文件。
4. 点击“开始翻译”，在上传和文件检查期间保持页面打开。只用免费页且符合条件的任务会直接排队；需要积分时，先核对费用再确认提交。
5. 在首页“最近翻译”中查看进度。
6. 完成后可预览结果，也可下载纯译文 PDF 或双语 PDF。

保留原文件，及时下载译文。文件准备、任务限制及排错方法见[使用指南（英文）](docs/usage-guide.md)。

## PDF 翻译效果示例

以下页面对照均来自官网已发布的示例。前三组为论文、手册和教材的英译中页面，第四组为日文竖排文本的中文译页。

### 论文 PDF 翻译

对照阅读研究摘要，保留段落与关键词的上下文。

<table>
<tr><th>英文原文：摘要与关键词</th><th>中文译文：摘要与关键词</th></tr>
<tr><td width="50%"><img src="assets/research-paper-english.webp" alt="论文 PDF 翻译 — 英文原文：摘要与关键词" width="100%"></td><td width="50%"><img src="assets/research-paper-chinese.webp" alt="论文 PDF 翻译 — 中文译文：摘要与关键词" width="100%"></td></tr>
</table>

### 手册 PDF 翻译

阅读手册时，将章节标题、步骤编号和列表放在一起查看。

<table>
<tr><th>英文原文：员工手册</th><th>中文译文：员工手册</th></tr>
<tr><td width="50%"><img src="assets/handbook-english.webp" alt="手册 PDF 翻译 — 英文原文：员工手册" width="100%"></td><td width="50%"><img src="assets/handbook-chinese.webp" alt="手册 PDF 翻译 — 中文译文：员工手册" width="100%"></td></tr>
</table>

### 教材与课程资料 PDF 翻译

结合正文、列表和图示对照学习教材内容。

<table>
<tr><th>英文原文：教材</th><th>中文译文：教材</th></tr>
<tr><td width="50%"><img src="assets/textbook-english.webp" alt="教材与课程资料 PDF 翻译 — 英文原文：教材" width="100%"></td><td width="50%"><img src="assets/textbook-chinese.webp" alt="教材与课程资料 PDF 翻译 — 中文译文：教材" width="100%"></td></tr>
</table>

### 日文竖排 PDF 翻译

从右往左逐列对照，留意对话的起止位置、标点和阅读顺序。

<table>
<tr><th>日文竖排原文</th><th>中文竖排译文</th></tr>
<tr><td width="50%"><img src="assets/vertical-japanese.webp" alt="日文竖排 PDF 翻译 — 日文竖排原文" width="100%"></td><td width="50%"><img src="assets/vertical-chinese.webp" alt="日文竖排 PDF 翻译 — 中文竖排译文" width="100%"></td></tr>
</table>

术语、表格、图示及阅读顺序的检查方法见[翻译与排版检查指南（英文）](docs/translation-review.md)。

## 支持的语言与适用场景

PDFTranslator.org 支持 100 多种翻译语言，包括英语、中文、西班牙语、法语、德语、葡萄牙语、日语和韩语。网站界面语言与文档翻译语言可分别选择。

| 翻译需求 | 选择方式 |
| --- | --- |
| PDF 英语翻译成西班牙语 | 源语言选择英语，目标语言选择西班牙语。 |
| 将 PDF 文档翻译成英语 | 选择文档实际源语言，目标语言选择英语。 |
| PDF 翻译成德语 | 选择源语言，目标语言选择德语。 |
| 英语 PDF 翻译成中文或葡萄牙语 | 源语言选择英语，选择对应的目标语言选项。 |

论文、研究报告和课程资料可选择“学术论文”；商务报告可选择“商务文件”；日常文档和手册可选择“通用领域”。涉及法律术语时可选“法律法规”，重要用途仍应复核措辞。

官网界面：[English](https://pdftranslator.org/) · [中文](https://pdftranslator.org/zh) · [Español](https://pdftranslator.org/es) · [Português (Brasil)](https://pdftranslator.org/pt-BR)。

## PDF 翻译常见问题

### PDFTranslator.org 免费且无需注册吗？

可以。游客每自然月可免费翻译 50 页普通 PDF。登录后先使用账户每月 600 页免费额度，超出部分每页 10 积分。未用完的免费页不结转。

### 翻译 PDF 能保留原格式吗？

工具尽可能保留布局、表格、图片和页面结构。译文长度可能变化，复杂表格、公式、字体与分页仍需检查，不保证完全一致。

### 可以翻译长篇 PDF 吗？

游客和免费账户每个文件最多 200 页、20 MiB；月卡有效期内，每个文件最多 800 页、50 MiB。只需部分章节时可以拆分，按实际提交的页数使用额度。

### 扫描 PDF 可以直接翻译吗？

可直接上传扫描件。若检查提示需要 OCR，请登录并核对报价。按整份文件每页 20 积分计费，即使只有部分页面需要识别；普通免费页不能抵扣，注册赠送的积分可用。

### 翻译结果是 Word 文档吗？

主翻译流程输入 PDF，输出翻译后的 PDF。本仓库不将其描述为 PDF 转 Word 工具，也不承诺可编辑 DOCX 输出。

### 译文可以下载多久？

任务完成、失败或取消后，历史记录可见 24 小时。成功结果可自完成起预览和下载 24 小时，月卡不会延长这一时限。请以任务卡显示的到期时间为准。

### PDF 文件只在本地处理吗？

翻译需要上传文件，由服务端处理。游客历史保存在当前浏览器，登录用户的历史由服务端按账户管理。访问到期后，存储副本和必要业务记录仍可能保留。详见[文件处理指南（英文）](docs/privacy.md)。

### 翻译失败或取消后，页数和积分怎么处理？

排队中的任务可以取消，进入处理后无法取消。任务失败或成功取消后，已使用的免费页和积分按规则返还，免费页返还到原月份。

### 这是可自行部署的开源翻译器吗？

不是。此仓库提供 PDFTranslator.org 在线服务的官方文档，不包含可自行部署的应用、翻译引擎或公共 API 软件包。

## 指南、PDF 工具与反馈

- [PDF 翻译使用与排错指南（英文）](docs/usage-guide.md)
- [翻译质量与排版检查指南（英文）](docs/translation-review.md)
- [文件上传、保留期限与隐私（英文）](docs/privacy.md)
- [拆分 PDF](https://pdftranslator.org/tools/split-pdf) · [合并 PDF](https://pdftranslator.org/tools/merge-pdf) · [更多 PDF 工具](https://pdftranslator.org/tools)
- [通过 FeedLog 提交问题与功能建议](https://pdftranslator-org.feedlog.ai/)
- [文档纠错与贡献方式（英文）](CONTRIBUTING.md)

公开反馈请使用无敏感内容的材料，不要上传私人文档、任务标识符或带签名的上传／下载链接。

**产品资料核对日期：2026 年 11 月 2 日。** 功能与限制可能变化，以[官网](https://pdftranslator.org/zh)、[隐私政策](https://pdftranslator.org/privacy-policy)和[服务条款](https://pdftranslator.org/terms-of-service)为准。
