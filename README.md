# Excel Quality Operations Toolkit
### Built from 5 years of quality auditing experience at Accenture

Three Advanced Excel tools for operations quality management
in digital lending, BFSI, and e-commerce environments.
All tools built using dummy data for portfolio demonstration.

---

## Tool 1 — Quality Reporting Workbook

**Business problem solved:**
The audit team spent 45 minutes every morning manually
cleaning exported data, applying formulas, and calculating
quality scores. The process was error-prone and produced
no new analysis — only formatted numbers.

**What the tool does:**
Analysts paste the raw audit export once.
VLOOKUP, pivot tables, and slicers automatically display
accuracy scores, SLA status, and error trends across
13 reviewer sheets feeding a master dashboard.
Zero manual work after the paste.

**Excel skills:** COUNTIF · AVERAGEIF · VLOOKUP · Pivot Tables ·
Named Ranges · Slicers · Report Connections ·
GETPIVOTDATA · Cross-sheet formulas · IFERROR

**File:** `Quality_Reporting_Workbook_v1.xlsx`

---

## Tool 2 — 5-Why RCA Automation Tool

**Business problem solved:**
Root cause analysis sessions took 15–20 minutes per case
because analysts manually cross-referenced a 40-page
taxonomy document. Different analysts reached different
root causes for identical errors — making trends
impossible to track.

**What the tool does:**
Analyst selects Error Category from a dropdown.
A dependent dropdown shows only the relevant sub-types.
VLOOKUP auto-fills all 5 Whys, the root cause statement,
and the recommended resolution from the taxonomy.
Session time: under 2 minutes. Consistency: guaranteed.

**Excel skills:** VLOOKUP · INDIRECT · SUBSTITUTE ·
Data Validation · Dependent Dropdowns · Named Ranges ·
Absolute References · Staging Row Log Design

**File:** `5Why_RCA_Automation_Tool_v1.xlsx`

---

## Tool 3 — Real-time Production Tracker

**Business problem solved:**
Errors were only visible the next day after the audit
export arrived. By then the same error had already
occurred multiple times. Same-day intervention was
impossible with a 24-hour data lag.

**What the tool does:**
5 analysts log cases in their own dedicated sheets.
A MASTER_VIEW sheet consolidates all five using SUMIF
and AVERAGEIF filtered by TODAY(). A dashboard shows
live KPI tiles, per-analyst status, and a same-day
alert section that surfaces which analysts need
immediate coaching — updated the moment a case is logged.

**Excel skills:** SUMIF · COUNTIFS · AVERAGEIF ·
Cross-sheet references · Multi-sheet architecture ·
TODAY() dynamic filter · Weighted average ·
Nested IF · AND/OR logic · Conditional formatting

**File:** `Production_Tracker_v1.xlsx`

---

## Skills Demonstrated Across All Three Tools

| Skill | Tool |
|---|---|
| VLOOKUP (exact match) | Tool 2, Tool 1 |
| SUMIF / AVERAGEIF / COUNTIFS | Tool 1, Tool 3 |
| INDIRECT + SUBSTITUTE (dependent dropdown) | Tool 2 |
| Named ranges as abstraction layer | All three |
| Multi-sheet architecture | Tool 3 |
| Cross-sheet formula referencing | Tool 1, Tool 3 |
| TODAY() as a dynamic live filter | Tool 3 |
| Weighted average calculation | Tool 3 |
| Pivot tables with slicers | Tool 1 |
| Data validation (input control) | All three |
| IFERROR (blank row guards) | All three |
| Conditional formatting | All three |

---

## Context

These tools were built using dummy data to replicate
real quality reporting workflows in operations environments.
The architecture, formula logic, and design decisions
are based on actual quality auditing work.

**Author:** Kalpesh Hule | Process Excellence Professional
**LinkedIn:** linkedin.com/in/kalpesh-hule
