# CbCR Workbook v3 — 2025 Simulation

[English](README.md) · [Deutsch](README.de.md) · [简体中文](README.zh-CN.md)

[项目入口](https://v6rfy78ggr-rgb.github.io/v6rfy78ggr-rgb/zh-CN.html) · [一分钟试用](TRY_IT.md) · [版本下载](https://github.com/v6rfy78ggr-rgb/cbcr-workbook/releases) · [下载 Excel 模板](workbooks/CbCR_Template_v3.xlsx)

用于组织国别报告数据、复核问题和报告准备的中英双语 Excel 工作包，包含空白模板和完整的五实体虚构示例。这里另提供德语 README，工作簿本身仍是中文/英语。

## 从哪里开始

通过 **Code → Download ZIP** 下载并解压。新练习打开 [`workbooks/CbCR_Template_v3.xlsx`](workbooks/CbCR_Template_v3.xlsx)，学习完整流程打开 [`examples/2025_CbCR_Completed_Example.xlsx`](examples/2025_CbCR_Completed_Example.xlsx)。使用桌面 Microsoft Excel；文件没有宏或外部工作簿链接，尚未将其他表格软件验收为等效环境。

可参考[英文操作指南](guides/Project_Operating_and_Review_Guide_EN.pdf)。顺序为参数、实体、原币数字、汇率、调整、披露、资料、确认、待办、报告。淡黄色为输入格；真实零填 0，未知留空。预留行列支持 50 家实体。

## 内容与方法

- 含公式的空白模板和 2025 年已填示例，分开记录来源期间与报告日期。
- `examples/source-documents/` 包含虚构财务报表和输入矩阵。
- `examples/reports/` 包含六份直接从 Excel 打印的中英文报告 PDF。它们是静态快照，工作簿变更后须重新导出。
- `examples/methodology/` 提供汇率来源和方法说明：年度转换汇率使用每日 ECB 报价倒数的算术平均，不是年度平均报价的倒数。

## 当前状态与限制

根据维护者的选择，公开版不包含 `CLIENT_2025_Supplement_EN.pdf` 和中文操作指南 PDF。英文指南描述原始完整包，其中提及的补充资料在本仓库不提供下载；原始文件夹在这里分别对应 `workbooks/`、`examples/`、`examples/source-documents/`、`examples/reports/` 和 `examples/methodology/`。已填工作簿保留，但配套来源文件并非全部公开。

v3 完成于 **2026年11月6日**。**11月23日**发布检查未发现缓存公式错误、宏或外部关系；只删除了本地文件夹路径元数据，工作表 XML 未改变。隐藏计算表有意保留。读取缓存不等于重新计算；目标 Excel 环境仍应检查重开和条件格式，当前证据见 [VALIDATION.md](VALIDATION.md)。

公司、税号、回复和审批全部为虚构。示例不判断法定 CbCR 或 Pillar Two 义务。Pillar Two 表仅用于数据准备，不计算完整 GloBE/补足税，不生成 GIR。公开报告 PDF 不是 iXBRL 申报文件。改变报告年份时，不应自动重标已确认的来源期间。

## 需要哪些反馈

请注明 Excel 版本、操作系统、工作表和单元格、虚构输入、预期与实际结果，以及是否重算。尤其欢迎缺失值处理、来源期间变化、新增实体和 PDF 打印覆盖方面的反馈。工作簿公式就是可编辑实现，未打包平台专用的生成工具。

自有模板和文档采用 MIT；ECB 数据继续适用原来源条件，见 [NOTICE.md](NOTICE.md)。

## 参与完善

[提交问题或建议](https://github.com/v6rfy78ggr-rgb/cbcr-workbook/issues/new/choose)，支持中文、德语和英语。请只使用虚构数据，公开 Issue 任何人都能看到。协作流程见 [CONTRIBUTING.md](CONTRIBUTING.md)，MIT 许可见 [LICENSE](LICENSE)。
