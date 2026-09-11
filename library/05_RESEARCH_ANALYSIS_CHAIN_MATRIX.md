# Research Analysis Chain Matrix — v0.1

## Status
Phase 1 working matrix created from the recovered project state plus the saved source file `Executive summary-HUF 18-02-23.pdf`.

This is **not yet the final reconstruction of the detailed report**. Where the executive summary does not name an underlying dataset, formula, year, or processing step, the field is marked **Detailed report confirmation required** rather than inferred.

## Layer rule
Every entry keeps three layers separate:

1. **Source-derived** — what the recovered source explicitly states.
2. **Recorded interpretation** — interpretation already preserved in the project files from the earlier detailed review.
3. **Proposed current HUF adaptation** — future methodology ideas only; not part of the original study unless explicitly stated.

---

# A. Study-wide methodological frame

| Field | Source-derived record |
|---|---|
| Study title | *Building Informed and Scalable Water Security Solutions for Gujarat* |
| Study period | June 2020–March 2022; publication February 2023 |
| Formal parameters | Rainfall; Surface Water; Irrigation Infrastructure; Ground Water and quality; Soil Type and quality; Agriculture; Animal Husbandry |
| Secondary-data preprocessing | Datasets were in different formats/units; standardized to a uniform district-level format |
| Statistical approach | Inter-parameter and inter-region comparison using statistical methods including normalization |
| Spatial approach | Advanced Remote Sensing and GIS for generation, visualization, analysis and interpretation of thematic parameters |
| Static regionalization | Rainfall + Soil Type + Geology used to categorize Gujarat into seven regions |
| Executive-summary primary sample | 12 representative watersheds; 108 sample villages; 877 households; soil and water testing with households |
| Important contradiction | Earlier detailed-methodology review recorded 10 watersheds / 838 households. Do not reconcile until the detailed report is reopened. |

### Approved analysis-chain structure
**Parameter → Sub-parameter → Variable → Data source → Unit → Spatial/temporal scale → Processing → Formula / analytical method → Cross-parameter comparison → Result → Interpretation → Water-security implication → Intervention.**

---

# 1. Rainfall

## 1.1 Historical rainfall and spatial variability

| Matrix field | Record |
|---|---|
| Parameter | Rainfall |
| Sub-parameter | Long-term rainfall amount and spatial distribution |
| Variables | Annual rainfall; regional/district rainfall; long-term average; temporal trend |
| Data source | **Detailed report confirmation required**; executive summary does not name the rainfall dataset |
| Unit | mm |
| Spatial scale | District → seven study regions → state |
| Time period | 1995–2020 |
| Preprocessing | District-level standardization; region-wise aggregation/comparison |
| GIS/statistical technique | Spatial comparison/mapping; temporal trend analysis; correlation with groundwater trend |
| Formula / method | State/region averages and trend comparison; exact statistical formula **not exposed in executive summary** |
| Primary validation | Not described specifically for rainfall in executive summary |
| State result | Average rainfall 1995–2020 = 821 mm; five-year alternating increase/decrease pattern reported |
| Regional result | Highest: South Gujarat, 1034–2358 mm; lowest range 456–634 mm in Kachchh and several western/northern districts |
| Cross-parameter relation | Rainfall trend compared with groundwater-level trend |
| Limitation | Source dataset and station/gridding method not named in recovered summary |

### Recorded interpretation
Increasing rainfall did not automatically produce groundwater recovery. North Gujarat and Central Gujarat showed increasing rainfall while groundwater levels declined.

### Water-security implication
Rainfall alone is not a sufficient water-security indicator; extraction pressure, aquifer behaviour, recharge pathways and cropping intensity must be analysed jointly.

---

# 2. Surface Water

## 2.1 Surface-water contribution to supply

| Matrix field | Record |
|---|---|
| Parameter | Surface Water |
| Sub-parameter | Surface-water availability / contribution to total supply |
| Variables | Surface-water availability (MCM); district/region share; canal access; local storage |
| Data source | **Detailed report confirmation required** for the main surface-water availability dataset |
| Unit | MCM; later normalized as MCM/ha |
| Spatial scale | District → region → state |
| Time period | Common water-balance reference year linked to 2017–18 demand; detailed source year requires confirmation |
| Processing | Standardization at district level; combined with groundwater as total Water Supply |
| GIS/statistical technique | District/regional mapping and comparison; later normalization by Gross Cropped Area |
| Formula | Total Water Supply = Surface Water + Groundwater |
| Primary validation | Field narratives and watershed-level surveys were used for selected water-resource variables; exact surface-water validation protocol requires detailed report |
| State/regional result | Combined supply is highest in South Gujarat (22%), Central Gujarat (19%), North Gujarat (18%); lowest ETB (6%) and Kachchh (5%) |
| Limitation | Executive summary reports combined supply more clearly than stand-alone surface-water calculation |

## 2.2 Water-harvesting structures

| Matrix field | Record |
|---|---|
| Sub-parameter | Water-harvesting structure inventory and functionality |
| Variables | Number/type of structures; region; functionality; maintenance condition |
| Data source | Water Resources Department (WRD) secondary inventory; primary structure survey |
| Unit | Number; % functional/non-functional |
| Spatial/temporal scale | State/region inventory to March 2018; primary survey in 12 watersheds |
| Processing | Regional distribution + primary functionality assessment |
| Formula / method | Descriptive counts and percentages |
| Primary validation | 227 structures surveyed in 12 watersheds according to executive summary |
| Result | About 5.55 lakh structures constructed till March 2018; North Gujarat 20% of structures, Kachchh 5%; 72% sampled structures in Saurashtra Coastal and 68% in ETB reported non-functional |
| Cross-parameter relation | Structure functionality ↔ recharge/storage benefit ↔ village institutions/maintenance |
| Limitation | Earlier project record flags narrative/table count inconsistency; do not silently reconcile |

### Recorded interpretation
Infrastructure stock is not equivalent to effective water supply. Maintenance and local governance determine realized storage/recharge performance.

---

# 3. Irrigation Infrastructure

## 3.1 Source-wise irrigation transition

| Matrix field | Record |
|---|---|
| Parameter | Irrigation Infrastructure |
| Sub-parameter | Canal / tubewell / open-well / other irrigation source trends |
| Variables | Irrigated area by source |
| Data source | **Detailed report confirmation required**; executive summary does not name the temporal source dataset |
| Unit | lakh ha; % change |
| Spatial scale | District → region → state |
| Time period | 2008–09 to 2017–18 |
| Processing | Source-wise temporal comparison and district mapping |
| GIS/statistical technique | Canal-vs-tubewell comparative mapping; trend/change analysis |
| Result | Tubewell area 19.8→27.5 lakh ha (+39%); canal 11.21→18.13 lakh ha (+62%); other sources 2.9→5.9 lakh ha (+103%); open-well area −18% |
| Regional result | Kachchh and Central Gujarat recorded the largest open-well declines (44% and 42%) |
| Cross-parameter relation | Canal growth compared with tubewell dependence and groundwater depletion |

### Recorded interpretation
Canal expansion did not automatically substitute groundwater pumping. Conjunctive-use systems can expand both surface-water access and groundwater abstraction.

## 3.2 Micro irrigation

| Matrix field | Record |
|---|---|
| Sub-parameter | Drip/sprinkler coverage |
| Data source | GGRC Report 2019–20 |
| Variables | Micro-irrigation area; micro-irrigation area as % of GCA |
| Unit | ha; % of Gross Cropped Area |
| Scale | District/state |
| Result | State total 16.7 lakh ha; Banaskantha about 3.4 lakh ha; Junagadh 29% GCA; Banaskantha 25%; Tapi and Sabarkantha 20%; Anand 1% |
| Cross-parameter relation | MIS coverage ↔ groundwater-level trend ↔ expansion of Rabi/Summer irrigated area |
| Limitation | Installed/covered area is not the same as actual device use or net aquifer saving |

### Recorded interpretation
Per-hectare efficiency can be offset by expansion in irrigated area, cropping intensity or crop choice; MIS coverage alone should not be treated as basin/aquifer water saving.

---

# 4. Groundwater

## 4.1 Aquifer setting

| Matrix field | Record |
|---|---|
| Parameter | Groundwater |
| Sub-parameter | Geology / aquifer framework |
| Variables | Aquifer type; storage character; well-yield variability; shallow/deep source dependence |
| Data source | **Detailed report confirmation required** for geology/aquifer layers |
| Spatial scale | District/region/state |
| GIS method | Geology was used with rainfall and soil in static/fundamental regionalization |
| Regional results | North/Central: thick extensive alluvial aquifers; ETB: low-storage crystalline systems with local variability; Saurashtra: mixed basalt/alluvial/sedimentary/limestone systems; South Gujarat: alluvial + basalt contrasts |
| Cross-parameter relation | Aquifer setting ↔ groundwater availability ↔ response to pumping ↔ recharge from canals/watershed structures ↔ groundwater quality |

## 4.2 Groundwater development status

| Matrix field | Record |
|---|---|
| Data source | CGWB 2019 Annual Report |
| Variables | Groundwater-development category |
| Scale | District |
| Result | Over-exploited: Mehsana, Patan, Banaskantha, Gandhinagar; semi-critical: Kachchh, Aravalli, Porbandar, Sabarkantha, Ahmedabad; remainder reported safe |
| Limitation | Category is a district-level status and can conceal local aquifer stress |

## 4.3 Groundwater level and rainfall relationship

| Matrix field | Record |
|---|---|
| Variables | Groundwater level; rainfall; temporal change |
| Unit | groundwater depth in metres; rainfall mm |
| Time period | 1995–2020 |
| Method | Correlate rainfall and groundwater trends by region |
| Result | North Gujarat: rainfall 547→657 mm while groundwater level 23→35 m depth; Central Gujarat: rainfall 685→825 mm while groundwater level 21→25 m depth |
| Regional classification | NG/Kachchh/CG: rainfall increasing but groundwater decreasing; ETB/SG: rainfall increasing, groundwater broadly constant; SH/SC: both increasing |
| Limitation | Executive summary gives directional correlation, not full regression/statistical diagnostics |

## 4.4 Groundwater availability

| Matrix field | Record |
|---|---|
| Variables | Groundwater/supply volume; per-hectare water availability |
| Unit | MCM; MCM/ha |
| Source | **Detailed report confirmation required** |
| Processing | Absolute supply values later normalized by Gross Cropped Area |
| State result | State water availability benchmark reported as 0.0038 MCM/ha |
| Selected low values | Dahod 0.0012; Dang 0.0014; Amreli 0.0018; Banaskantha 0.0019 MCM/ha |
| Interpretation | High absolute resource does not equal security when demand/extraction is also high |

## 4.5 Groundwater quality

| Matrix field | Record |
|---|---|
| Variables | EC/TDS; nitrate; arsenic; fluoride; iron |
| Data source | Secondary quality data + household/watershed primary water testing; detailed dataset names require confirmation |
| Spatial scale | District/region; primary sample watersheds/households |
| Method | Contamination mapping; comparison of primary vs secondary data; threshold-based dynamic-quality classification |
| Result | EC and nitrate contamination reported in all districts except Valsad and Dangs; arsenic/fluoride/iron contamination absent only in Narmada, Surat, Tapi, Valsad; all five contamination types reported in Kachchh, Patan, Amreli, Bharuch and Dahod |
| Cross-parameter relation | Quality ↔ geology/depth of pumping ↔ agriculture/fertilizer use ↔ groundwater depletion |
| Limitation | District averages can mask local contamination hotspots |

---

# 5. Soil

## 5.1 Soil type as static parameter

| Matrix field | Record |
|---|---|
| Parameter | Soil |
| Sub-parameter | Soil type / physical setting |
| Variables | Soil type/texture and associated infiltration, retention and drainage behaviour |
| Data source | **Detailed report confirmation required** |
| Spatial scale | GIS layer used with rainfall + geology for seven-region typology |
| Method | Static GIS synthesis/overlay |
| Cross-parameter relation | Soil ↔ runoff/recharge ↔ irrigation requirement ↔ waterlogging/salinity ↔ crop suitability |

## 5.2 Soil health / quality

| Matrix field | Record |
|---|---|
| Variables | EC; Organic Carbon; N; P; K |
| Unit | EC mmhos/cm; nutrient measures including kg/ha / categorical status as reported |
| Source | Secondary soil-quality data + primary household soil tests; exact secondary dataset requires detailed report |
| Method | Regional status comparison; primary-vs-secondary comparison |
| Result | Nitrogen generally low across most regions; phosphorus mostly medium; potassium mostly high. Primary data showed higher EC in Kachchh and Saurashtra Hinterland, lower OC in most regions except South Gujarat, higher P across regions, and similar K except lower K in Kachchh. |
| Cross-parameter relation | Fertilizer use ↔ soil health ↔ nitrate/groundwater contamination |

## 5.3 Waterlogging, salinity and land degradation

| Matrix field | Record |
|---|---|
| Time period | 2015–16 land-degradation dataset |
| Variables | Salinization, water erosion, waterlogging, other degradation classes |
| Unit | ha; % of total geographical area / command area |
| Result | State: salinization 3,648,338 ha (19.4% TGA); water erosion 1,557,616 ha (8.3%); waterlogging 82,067 ha (0.4%). Command-area examples: NG 16% salt affected; SG ~14% waterlogged; CG ~15% waterlogged and 8% salt affected; SH ~31% salt affected and 15% waterlogged. |
| Limitation | Source itself notes 2015–16 data may not represent current condition |

---

# 6. Agriculture

## 6.1 Cropping-area trend

| Matrix field | Record |
|---|---|
| Parameter | Agriculture |
| Sub-parameter | Seasonal/horticulture area growth |
| Variables | Kharif, Rabi, Summer, horticulture area |
| Source | **Detailed report confirmation required** for the underlying agriculture statistics |
| Unit | lakh ha; % change |
| Time period | 2008–09 to 2017–18 |
| Method | Temporal district/region comparison |
| State result | Kharif 55→59 lakh ha (+7%); Rabi 12→15 lakh ha (+25%); Summer 2.8→3.3 lakh ha (+18%); horticulture 13→18 lakh ha (+38%) |
| Regional result | About half the districts showed medium-to-high agricultural growth; several districts exceeded 40% growth in Rabi/Summer |
| Cross-parameter relation | Cropping intensity/area growth ↔ irrigation expansion ↔ agricultural water demand ↔ groundwater stress |

## 6.2 Actual crop water utilization vs SIP requirement

| Matrix field | Record |
|---|---|
| Variables | Actual field irrigation use; recommended/ideal crop-water requirement |
| Reference source | State Irrigation Plan (SIP) 2016–20 for ideal requirement; primary farmer field-use assessment for actual use |
| Unit | water use by crop; executive summary reports % excess; detailed volume units require confirmation |
| Method stated in executive summary | Compare actual farmer use with SIP requirement |
| Recorded detailed-review calculation chain | Pump HP + head + pump/motor efficiency → discharge → discharge × pumping hours → water per irrigation → × irrigation events/days → crop-period volume → convert to m³ → divide by crop area → actual use/ha. **This chain is preserved from the earlier detailed review but requires re-verification against the detailed report.** |
| Result | Overall farmers reported as using ~21% more water than SIP recommendation; examples: CG paddy +118%, NG wheat up to +170%, Kachchh pomegranate +250% |
| Limitation | Executive summary later recommends larger samples for actual crop-water-utilization research |

## 6.3 Crop economics × water demand

| Matrix field | Record |
|---|---|
| Variables | Sales price; crop water demand |
| Sales-price source | APMC 2021 |
| Unit | Rs/qtl; MCM/ha as stated |
| Method | Classify price and water demand High/Low, then assign crops to four quadrants |
| Quadrants | Q1 High Return–High Demand; Q2 High Return–Low Demand; Q3 Low Return–High Demand; Q4 Low Return–Low Demand |
| Result | Wheat/paddy commonly fall in Q3; pulses/spices/vegetables frequently Q2; fruits/oilseeds often high-return/high-demand; millets low-return/low-demand |
| Limitation | APMC prices fluctuate yearly; classification can change with market conditions |

### Recorded interpretation
Agriculture is the dominant demand-side lever. Growth in Rabi/Summer/horticulture area can offset gains from irrigation-efficiency technology.

---

# 7. Animal Husbandry

## 7.1 Dairy growth

| Matrix field | Record |
|---|---|
| Parameter | Animal Husbandry |
| Sub-parameter | Milk procurement / dairy intensification |
| Variables | District milk procurement/production growth |
| Data source | **Detailed report confirmation required** for the underlying dairy dataset |
| Unit | % temporal change; absolute milk units not exposed in recovered summary |
| Time period | 2008–09 to 2017–18 |
| Method | Temporal district comparison + comparison with district water demand–supply gap |
| Result | Kachchh, Banaskantha, Surendranagar, Kheda, Panchmahal and Dang >90% growth; among 14 districts with >60% demand–supply gap, 10 also had >60% milk-procurement growth |
| Cross-parameter relation | Dairy growth ↔ livestock/fodder demand ↔ irrigated fodder/cropping expansion ↔ groundwater demand |
| Limitation | Executive summary itself calls for further study of dairy intensification and groundwater crisis |

## 7.2 Direct + indirect livestock water demand

**Recorded interpretation from earlier detailed review:**
Livestock population × species-wise unit requirement → direct livestock demand; dairy growth → fodder requirement → irrigated fodder area → indirect agricultural water demand.

**Status:** detailed formula/data source must be re-verified from the full report before treating this as a final source-derived method.

---

# B. Cross-parameter synthesis and dynamic scenario construction

## B1. Water Demand and Supply

| Field | Source-derived record |
|---|---|
| Demand reference year | 2017–18 |
| Demand components | Agriculture + Animal Husbandry + Domestic + Industry |
| Supply components | Surface Water + Groundwater |
| Comparison | Demand vs Supply; district gap analyzed |
| State message | 9/33 districts had >90% gap; 7 districts had 60–90% gap; agriculture + animal husbandry contribute 92% of total demand |
| Unresolved issue | Gap-percentage denominator must still be independently reconstructed from absolute demand/supply values |

## B2. Normalization and High/Low classification

### Supply and demand
**Absolute MCM value ÷ Gross Cropped Area (ha) = MCM/ha.**

Then:
**33-district average = threshold.**

District above state average → **High**; below state average → **Low**.

### Water & Soil Quality composite
Three variables explicitly stated:
1. % district area with TDS > 1500 ppm
2. % district area with Fluoride > 1.0 mg/l
3. % district area with Nitrogen < 280 kg/ha

The three values were averaged; state average used as threshold for High/Low classification.

**Important validation item:** the semantic direction of “High/Low Quality” should be checked carefully because the component variables are framed as contamination/deficiency burdens. Preserve the report labels exactly before translating them into a modern index.

## B3. Final scenario

**Water Supply status + Water/Soil Quality status + Water Demand status → dynamic water-security scenario.**

Worst-case condition stated in the summary:
**Low Water Supply + Low Soil & Water Quality + High Water Demand.**

This condition was reported in **10 of 33 districts**.

---

# C. Source cautions now confirmed / carried forward

1. **Primary sample discrepancy remains open:** executive summary = 12 watersheds / 108 villages / 877 HH; earlier detailed-methodology record = 10 watersheds / 838 HH.
2. **Water-harvesting-structure count issue remains open:** executive summary states 227 structures in 12 watersheds, while the prior review already flagged a narrative/table inconsistency.
3. **Water-gap denominator remains open:** do not reuse published percentages until the gap formula is reconstructed from absolute demand and supply values.
4. **Mixed-year datasets are fundamental to the study:** rainfall 1995–2020; irrigation/cropping/dairy 2008–09 to 2017–18; land degradation 2015–16; SIP 2016–20; WRD structures to March 2018; CGWB 2019; GGRC 2019–20; APMC 2021; demand reference year 2017–18.
5. **Executive summary is insufficient for full provenance:** several underlying datasets, formulas and GIS/statistical details still require the detailed report.

---

# D. Next analytical actions

1. Recover/reopen the **full detailed research report**, not only the executive summary.
2. Replace every **Detailed report confirmation required** field with exact source agency, table/map reference, year, unit and method.
3. Reconstruct the demand–supply gap formula from the report’s absolute values and test all published percentages.
4. Reconstruct the exact normalization equations and confirm the direction of the Water/Soil Quality index.
5. Reconcile — without silently overwriting — the primary-sample and water-harvesting-structure count discrepancies.
6. Extend this matrix from parameter level to a formal **data dictionary + formula register + source-page register**.
