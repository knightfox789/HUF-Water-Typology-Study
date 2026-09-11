# Project Index — HUF Water Typology Study

## Purpose
Create a recoverable, versioned research workspace for reviewing the Gujarat Water Typology Study and translating it into a transparent, reproducible analytical framework for current and future HUF/DSC water-security work.

## Core analytical lens
For every study parameter, document the chain:

**Parameter → sub-parameter → variable → data source → unit → processing → analytical method → comparison/relationship → result → interpretation → water-security implication → intervention.**

For every published result, additionally reconstruct:

**Report result → source file → sheet/layer → source fields → cleaning → transformation → formula/GIS/statistical method → intermediate output → final result → validation.**

## Current workstreams

### A. Reverse-engineer the research report
- Identify all major parameters and sub-parameters.
- Reconstruct formulas, normalisation, classification and comparison logic.
- Separate secondary-data analysis from primary-data validation.
- Capture state-level and region-level findings.
- Flag numerical, methodological or reporting inconsistencies without silently correcting the source.

### B. Build a Research Analysis Chain Matrix
Working file:
- `05_RESEARCH_ANALYSIS_CHAIN_MATRIX.md`

Fields:
- Parameter
- Sub-parameter
- Indicator
- Variable
- Unit
- Data source
- Spatial scale
- Time period
- Formula / transformation
- Analytical method
- Cross-parameter relationship
- Result
- Interpretation
- Limitation
- Proposed current-use adaptation

Current status: **v0.1 created from the recovered executive summary and earlier project record.** Fields not yet verified from the detailed report remain explicitly unresolved rather than inferred.

### C. Historical result-to-data reverse engineering
Master plan:
- `06_MASTER_PLAN_REVERSE_ENGINEERING_AND_REUSABLE_RESEARCH_ENGINE.md`

Primary objective:
- map every important report output to the exact original Excel/GIS/Word/source database, fields, processing, formulas and analytical methods;
- reproduce the published result;
- record the result-data lineage and validation status.

### D. Reusable research framework and engine
After historical reproduction:
- abstract the methodology from the historical Gujarat data;
- classify methods as retain/update/replace/optional/new;
- build data-independent analytical modules;
- support temporal refreshes for Gujarat;
- support adaptation to other states.

### E. Interactive dashboard
Dashboard development follows validated reverse engineering and engine design. It will expose results, maps, trends, comparisons and a visible `How was this calculated?` provenance/methodology layer.

## Canonical files
- `01_CHAT_LOG.md` — chronological record of important sessions and decisions.
- `02_RESEARCH_ANALYSIS_CHAIN.md` — technical study breakdown.
- `03_IDEAS_BACKLOG.md` — future ideas and unresolved questions.
- `04_CONTINUATION_AND_RECOVERY.md` — latest state, next actions, recovery instructions.
- `05_RESEARCH_ANALYSIS_CHAIN_MATRIX.md` — source-grounded parameter matrix under active development.
- `06_MASTER_PLAN_REVERSE_ENGINEERING_AND_REUSABLE_RESEARCH_ENGINE.md` — approved project roadmap from source data to reusable research engine/dashboard.
- `../sources/SOURCE_REGISTER.md` — source provenance and known source inconsistencies.

## Status
**Master Plan v1.0 established. Historical reverse-engineering execution is ready to begin.**

### Immediate next sprint
1. Build the **Report Result Register** from the complete 555-page report.
2. Receive/inventory the user's original study database (Excel, Word, GIS, survey and other files) without altering originals.
3. Create the first end-to-end lineage pilot using **Rainfall 1995–2020 → regional trend → rainfall-groundwater relationship**.
