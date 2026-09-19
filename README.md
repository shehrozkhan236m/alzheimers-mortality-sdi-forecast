# alzheimers-mortality-sdi-forecast
Global Inequalities in Age-Standardized Alzheimer's Mortality Across SDI Groups (1990–2030): Joinpoint &amp; Demographic Forecasts
# Global Inequalities in Age-Standardized Alzheimer’s Disease Mortality Across Socio-Demographic Index (SDI) Groups (1990–2030)

[![GBD 2023](https://img.shields.io/badge/Data-GBD%202023-blue.svg)](https://vizhub.healthdata.org/gbd-results/)
[![Software: Stata | Joinpoint](https://img.shields.io/badge/Tools-Stata%20%7C%20Joinpoint-success.svg)]()
[![Presentation: TDK Conference](https://img.shields.io/badge/Delivered-TDK%20Conference-orange.svg)]()

> 📄 **[Download / View Conference Slide Deck (PDF)](./Alzheimers_Global_Mortality_TDK_Presentation.pdf)**

An ecological demographic study investigating geographic patterns, temporal paradoxes, and 2030 mortality forecasts for Alzheimer's disease and other dementias across 204 countries and territories stratified by Socio-Demographic Index (SDI).

---

## Authorship & Affiliation
* **Primary Researcher:** Shehroz Khan, BSc Public Health
* **Institution:** Faculty of Health Sciences, University of Debrecen
* **Academic Supervisors:** Dr. Tóth Ágnes, Dr. Ghanem Amr Sayed
* **Forum:** Scientific Students’ Association (TDK) Conference

---

## Core Methodological Highlights

* **Study Cohort & Harmonization:** Global Burden of Disease (GBD 2023) panel examining Age-Standardized Mortality Rates (ASMR per 100,000) across 204 countries from 1990 through 2023 ($N = 6,936$ country-year observations).
* **Statistical Modeling:**
  * **Normality & Non-Parametric Profiling:** Shapiro-Wilk testing ($p < 0.001$) confirming severe skewness, justifying non-parametric Kruskal-Wallis omnibus testing ($\chi^2(4) = 682.032, p = 0.0001$) and Dunn's pairwise comparisons.
  * **SDI Association:** Linear regression establishing significant positive association between SDI and ASMR ($\beta = 6.30, 95\%\text{ CI: } 5.70\text{--}6.90, p < 0.001$), identifying a persistent "diagnostic divide" where higher-income systems identify and certify dementia cases at markedly higher rates ($R^2 = 0.0577$).
  * **Pandemic Inflection Detection:** Segmented joinpoint regression identifying a post-2020 acceleration ($\text{APC}_{2020-2023} = +0.91\%$) driven by pandemic-era healthcare disruptions and vulnerable geriatric baseline care.
  * **Central European Positioning:** Hungary identified as mid-range within Central Europe (2023 ASMR: 21.13 per 100,000; rank 6/8).
  * **2030 Projection Pipeline:** Time-series forecasting projecting global ASMR to 25.8 per 100,000 (95% CI: 24.2–27.4) by 2030.

---

## Individual Contribution Statement
* Extracted and cleaned multi-country ecological panels from the GBD 2023 results database.
* Executed all inferential statistics, Kruskal-Wallis testing, and segmented Joinpoint models in Stata and Joinpoint Regression Program.
* Designed all epidemiological charts, scatter distributions, and conference slide visuals.
