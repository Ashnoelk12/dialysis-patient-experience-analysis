# Dialysis Patient Experience Analysis
### Comparing DaVita and Fresenius Medical Care Using CMS ICH-CAHPS Data

**Tools:** Google Sheets (PivotTables, data analysis, visualization) | Canva (stakeholder presentation)  
**Data Source:** CMS ICH-CAHPS Dialysis Facility Dataset | July 2026 Release

## Project Overview

This independent healthcare analytics project examines patient-reported experiences across U.S. dialysis facilities, with a focused comparison of DaVita and Fresenius Medical Care.

The analysis uses publicly available CMS In-Center Hemodialysis Consumer Assessment of Healthcare Providers and Systems (ICH-CAHPS) data to identify comparative performance gaps, assess data limitations, and recommend areas for further investigation.

### Business Question

**How does DaVita's patient-reported experience compare with other dialysis organizations, and which areas of the patient experience present the strongest opportunities for improvement?**

## Data & Methodology

- **Dataset:** 7,490 dialysis facility records from the July 2026 CMS release.
- **Analytical population:** 2,594 facilities (34.6%) with reportable ICH-CAHPS results.
- **Primary measure:** Facility-level Linearized Scores across six patient-experience domains.
- **Method:** Google Sheets PivotTables were used to calculate unweighted organization-level averages.
- **Benchmark:** Fresenius Medical Care was selected as DaVita's primary comparator based on industry competition and substantial representation in the dataset.
- **Additional analysis:** Chain representation, data availability, and facility-level score distributions for Nephrologist Communication & Caring.

The analysis is descriptive. It does not establish causation or statistical significance.

## Key Findings

DaVita and Fresenius demonstrated broadly similar patient-experience performance.

| Patient Experience Domain | DaVita | Fresenius | Difference |
|---|---:|---:|---:|
| Rating of Nephrologist | 83.7 | 84.5 | -0.8 |
| Nephrologist Communication & Caring | 80.1 | 80.8 | -0.7 |
| Quality of Dialysis Center Care & Operations | 80.5 | 80.9 | -0.4 |
| Rating of Dialysis Center Staff | 86.6 | 86.8 | -0.2 |
| Rating of Dialysis Facility | 87.6 | 87.7 | -0.1 |
| Providing Information to Patients | 79.8 | 78.9 | +0.9 |

**Key takeaway:** DaVita scored slightly below Fresenius in five of six domains, with its largest observed gap in Rating of Nephrologist (-0.8 points). DaVita outperformed Fresenius in Providing Information to Patients (+0.9 points).

These small differences identify potential areas for investigation rather than demonstrating meaningful performance differences or underlying causes.

## Recommendations

1. **Investigate nephrologist ratings:** Examine facility-level variation and potential factors associated with DaVita's lower Rating of Nephrologist score.
2. **Explore comparative strengths:** Investigate practices associated with DaVita's higher Providing Information to Patients score.
3. **Expand facility-level analysis:** Identify facilities and patterns that may warrant targeted follow-up.

Future analysis could incorporate additional reporting periods and internal operational information, where available.

## Limitations

- Only 34.6% of facilities had reportable results, limiting generalizability.
- Organization-level averages were not weighted by patient or survey-response counts.
- Differences were not tested for statistical significance.
- Publicly available data do not establish the operational causes of observed differences.
- Facility-level distribution analysis was limited to Nephrologist Communication & Caring.

## Project Deliverables

**[View Stakeholder Presentation (PDF)](ICH-CAHPS_Patient_Experience_Analysis.pdf)**  
Six-slide presentation covering the business question, methodology, key findings, implications, and recommendations.

**[View Analysis Workbook (Google Sheets)](https://docs.google.com/spreadsheets/d/1c03or4C4_kJHornHoQA1R_xP4SXINZN0VlG2FSB6pWo/edit?usp=sharing)**  
Includes original source data, working data, PivotTable analyses, stakeholder summary, analysis log, and references.

## Data Sources & References

- [CMS — Patient Survey (ICH CAHPS), Facility](https://data.cms.gov/provider-data/dataset/59mq-zhts)
- [DaVita — 2025 Form 10-K](https://www.sec.gov/Archives/edgar/data/927066/000092706626000012/dva-20251231.htm)
- [Fresenius Medical Care — 2025 Form 20-F](https://www.sec.gov/Archives/edgar/data/1333141/000110465926019005/fms-20251231x20f.htm)

---

*Independent portfolio analysis using publicly available information. This project is not affiliated with or endorsed by DaVita, Fresenius Medical Care, or CMS.*
