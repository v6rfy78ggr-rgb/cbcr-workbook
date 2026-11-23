# CbCR Workbook v3 — 2025 Simulation

[English](README.md) · [Deutsch](README.de.md) · [简体中文](README.zh-CN.md)

[Project hub](https://v6rfy78ggr-rgb.github.io/v6rfy78ggr-rgb/) · [One-minute first look](TRY_IT.md) · [Version downloads](https://github.com/v6rfy78ggr-rgb/cbcr-workbook/releases) · [Download Excel template](workbooks/CbCR_Template_v3.xlsx)

A bilingual Chinese/English Excel work package for organising country-by-country reporting inputs, review questions and report preparation. It includes a blank template and a complete fictional five-entity example. German documentation is provided; the workbook itself has not been translated into German.

## Start here

Download the repository with **Code → Download ZIP** and extract it. Open [`workbooks/CbCR_Template_v3.xlsx`](workbooks/CbCR_Template_v3.xlsx) for a new exercise, or [`examples/2025_CbCR_Completed_Example.xlsx`](examples/2025_CbCR_Completed_Example.xlsx) to follow the example. Use desktop Microsoft Excel. No macros or external workbook links are included. Other spreadsheet engines have not been accepted as equivalent.

Read the [English operating guide](guides/Project_Operating_and_Review_Guide_EN.pdf). The sequence is: setup, entities, original-currency figures, FX, adjustments, disclosures, information requests, confirmations, pending items, reports. Yellow cells are inputs. Enter 0 only for a known zero; leave unknowns blank. Capacity is 50 entities through the reserved rows and columns.

## Contents and method

- A formula-based template and completed 2025 example with separate source periods and reporting dates.
- Fictional financial statements and an input matrix in `examples/source-documents/`.
- Six Chinese/English report PDFs in `examples/reports/`, exported from Excel. These are static snapshots: re-export after workbook changes.
- FX source data and a reproducible method description in `examples/methodology/`. Average conversion uses the arithmetic mean of daily reciprocal ECB quotes, not the reciprocal of the annual mean quote.

## Status and limitations

This public edition omits `CLIENT_2025_Supplement_EN.pdf` and the Chinese operating-guide PDF at the maintainer's request. The English guide refers to the original full package; its supplemental-document references are not downloadable here. Its original folders map to `workbooks/`, `examples/`, `examples/source-documents/`, `examples/reports/` and `examples/methodology/` in this repository. The completed workbook is included, but its entire supporting-document pack is not.

v3 was prepared on **6 November 2026**. Publication review on **23 November 2026** found no cached formula-error cells, macros or external relationships in either workbook. Local folder-path metadata was removed without changing worksheet XML. The hidden calculations sheet is intentionally retained. Reading caches is not fresh Excel recalculation. Native Excel reopening and conditional-format behavior must be checked in the target environment; current evidence is recorded in [VALIDATION.md](VALIDATION.md).

All companies, identifiers, replies and approvals are fictional. The example does not determine statutory CbCR or Pillar Two obligations. Pillar Two sheets support data preparation; they do not calculate full GloBE/top-up tax or generate GIR. Public-report PDFs are not iXBRL filing files. Do not replace confirmed source periods merely by changing the reporting year.

## Feedback

Please report the Excel version and OS, sheet and cell, fictional inputs, expected versus actual result, and whether recalculation was performed. Particularly useful: missing-data handling, source-period changes, adding an entity and PDF print coverage. Workbook formulas are the editable implementation; platform-specific generation tooling is not bundled.

Original templates and documentation use MIT. ECB observations remain subject to the ECB terms and attribution in [NOTICE.md](NOTICE.md).

## Contribute

[Report an issue or suggest an improvement](https://github.com/v6rfy78ggr-rgb/cbcr-workbook/issues/new/choose). English, German and Chinese feedback is welcome. Use synthetic data only; public Issues are visible to everyone. See [CONTRIBUTING.md](CONTRIBUTING.md) for the review process and [LICENSE](LICENSE) for the MIT license.
