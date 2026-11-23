# Publication verification

Date: 23 November 2026. Package: CbCR v3, 2025 fictional simulation.

## Selected files

The template matches the v3 delivery. The completed example uses the newer saved v3 copy from 9 November 2026. Comparison against the 6 November delivery found identical sheet names, cell values and formula text, with the same counts of conditional-format ranges. Differences are in saved workbook representation, formatting/printing and metadata; they are not presented as a new functional version.

Only the local absolute-directory metadata element was removed from each public workbook. No worksheet XML or formula was changed by that privacy operation. The hidden calculation sheet is intentionally retained.

## Checks performed

- Both workbooks contain 17 worksheets. Read-only scans found no cached formula-error cells, external relationships, macros, suspicious external-call formulas or remaining local path metadata.
- Both final clean workbooks opened in the local desktop Microsoft Excel without a repair prompt. Recalculation was invoked. The template input page and the completed English tax-report page were visually inspected.
- The saved package was retained without saving these inspection sessions. This preserves the reviewed files and avoids reintroducing local path metadata. A fresh save-close-reopen cycle and input-perturbation test of conditional formatting were **not** completed for this publication package.
- All bundled source statements and reports carry simulation/fictional labels. PDF text was checked for local file paths. Report PDFs remain the original static exports, not newly printed reports.
- The supplemental-response PDF and Chinese operating-guide PDF are excluded from the public edition at the maintainer's request. The completed workbook remains included; the supporting-document pack is partial. See the README for the English guide's original folder references.

## Remaining checks and use

Press F9 to recalculate before reviewing/exporting a report if Excel is in manual calculation mode. Check source periods, pending items, highlighting and print coverage in your Excel version. Reading cached values is not proof of fresh calculation, and a successful open is not proof that all conditional formatting works. Dynamic print ranges may not be interpreted by other spreadsheet libraries; use desktop Excel for the intended print workflow.

The fictional example does not determine a real group's obligations or replace professional review. When reporting a problem, include the file/version, sheet/cell, fictional inputs, Excel/OS version and expected result.
