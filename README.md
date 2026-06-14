# Singapore Mortality & Leading Causes of Death
### A historical analysis of shifting epidemiological trends | 2006 - 2022
---
Created by: Jennifer Sing  
Connect with me: [LinkedIn](https://linkedin.com/in/jennifer-p-sing/)  
📊 Live Interactive Visuals: [[ View Live Tableau Dashboard](https://public.tableau.com/shared/JWHB8XXSC?:display_count=n&:origin=viz_share_link)]

## 📑 Project Overview
This project presents a historical data analysis of shifting healthcare and epidemiological trends in Singapore. By combining macro-level mortality data (2006–2022) with multi-decade gender-specific cancer incidence cohorts (1976–2015), this analysis uncovers how rapid modernization, systemic healthcare framework upgrades, an aging demographic, and global crises have fundamentally reshaped Singapore's public health landscape.

The final deliverable is an interactive Tableau dashboard designed to transform complex, multi-source government medical registries into clear, actionable visual insights for public health researchers and non-expert stakeholders alike.

---

## ❓ Key Business & Research Questions
To guide this analysis, the project addresses several core public health and data integrity questions:
1. **Epidemiological Shifts:** What are the leading causes of death in Singapore, and how have their proportional shares evolved over a 16-year period?
2. **The Pandemic Inflection:** What underlying demographic dynamics drove the sudden, aggressive acceleration in annual mortality counts between 2020 and 2022?
3. **Gender-Specific Oncological Trends:** How do long-term incidence rates for specific cancers (Lung, Prostate, Breast, Colorectal) diverge by biological sex, and what behavioral or diagnostic factors explain these trajectories?
4. **Data Integrity & Governance:** How do administrative, backend system migrations (such as framework transitions) manifest as anomalies in open-source longitudinal datasets, and how can they be structurally explained?

---

## 🛠️ Tech Stack & Data Sources
* **Data Visualization & Analytics:** Tableau
* **Programming Language:** Python
* **Development Environment:** Google Colab
* **Data Libraries:** Pandas
* **Data Source Portal:** [data.gov.sg](https://data.gov.sg) (Singapore Open Data Government Portal)
  * **Dataset 1:** [Singapore Ministry of Health (MOH) Mortality Profiles](https://data.gov.sg/collections/516/view)
  * **Dataset 2:** [Health Promotion Board (HPB) Historical Cancer Incidence](https://data.gov.sg/datasets/d_75673c9d6c4efdcd08530b55e6003976/view)
> 📌 **Data Scope Note:** Historical cancer incidence tracking relies on 5-year cohort metrics available up to 2015, while overall mortality trends capture annualized data up to 2022.

---

## 💡 Key Insights & Analysis
### 1. Cancer is Consistently the Top # 1 Leading Cause of Death in Singapore
<img width="1527" height="472" alt="Chart # 1 Mortality Trends Over Time" src="https://github.com/user-attachments/assets/7b0b3bc8-521e-4a3f-a779-f267725e03ed" />

*Figure 1: Mortality Trends Overtime - Cancer Highlighted*

* **Observation:** Cancer consistently remains the #1 cause of death in Singapore from 2006 to 2022. While its percentage share of total deaths shows a slight downward trend from 2020 to 2022, the actual volume of cancer-related deaths remained critically high.

* **Possible Causes:** The slight drop in percentage share between 2020 and 2022 is caused by the global pandemic, rather than a decline in cancer severity. The total volume of all-cause mortality in Singapore spiked dramatically during the COVID-19 pandemic years; cancer's proportional share appears smaller on the chart. In reality, absolute cancer volume remained critically high.


### 2. Male Cancer Profiles - (Lung Cancer incidence Decrease vs. Prostate Cancer Increase)
<img width="1486" height="517" alt="Chart # 2 Male Female Cancer Trend" src="https://github.com/user-attachments/assets/93d3eac2-553f-4456-9480-3b7d2b901d18" />

*Figure 2: Top 3 Cancer Profile per Gender*

* **Observation:** Within male cancer incidence trends, lung cancer has been on a prominent, long-term downward trajectory (effectively cutting risk in half). Conversely, prostate cancer has experienced a steep, five-fold upward march over the same 40-year window.
* **Possible Causes:**
  * The decline in lung cancer strongly correlates with Singapore's anti-smoking/ anti-tobacco control which included public smoking prohibitions, advertising bans, and higher tax rates (Amul & Pang, 2018).
  * The rise in tracked prostate cancer may be driven by diagnostic evolution. The clinical introduction and widespread adoption of Prostate-Specific Antigen (PSA) blood testing as a primary screening and diagnostic tool effectively captured asymptomatic cases that were not captured previously (Kouriefs, 2009). Secondary factors include demographic aging and shifting population habits toward a Westernised diet high in red meat and dairy fats (Teo et al., 2016).

### 3. The Long-Term Rise in Female Breast Cancer

* **Observation:** Female breast cancer incidence rates showed a continuous, long-term upward trend from 1976 to 2015, with the rate nearly tripling from 24.7 to 64.5 per 100,000 women. *(refer to Figure 2)*
* **Possible Causes:** This steady increase reflects Singapore's rapid modernization and changing societal roles. Societal shifts led to delayed childbearing and lower overall fertility rates, increasing lifetime cumulative exposure to estrogen (Singapore Cancer Society, 2024). Additionally, transitioning into a global financial hub shifted lifestyles toward processed foods, animal fats, and more sedentary corporate routines (HealthXchange.sg, 2024).

### 4. Colorectal Cancer: The Shared Gender Threat

* **Observation:** Colorectal cancer has climbed steadily to become the Top #2 type of cancer for both genders. *(refer to Figure 2)*
* **Possible Causes:** 

### 5. Pneumonia as a Rising Cause of Death and Singapore’s Aging Demographics
<img width="1557" height="897" alt="Chart #5 Pneumonia" src="https://github.com/user-attachments/assets/0c7dd621-a08d-4b5a-a1d2-1f2ff69680d8" />

*Figure 3: Pneumonia*

* **Observation:** Pneumonia mortality share has steadily climbed to occupy the number 2 and number 3 spots on the leaderboard  from 13.7% to 20.0% share of all deaths). This rise runs completely parallel to a sharp, aggressive increase in Singapore’s total annual death counts.
* **Possible Causes:** Pneumonia frequently serves as a secondary or end-stage medical complication among the elderly. Data shows that pneumonia mortality rates climbing from 7.3% in the younger population to 16.1% in citizens aged 65–84, and peaking higher at 29.7% for those aged 85 and older (Young et al., 2018). This upward trend corresponds directly to Singapore's transition into a "super-aged" society. According to data from the National Population and Talent Division (NPTD), the citizen demographic aged 65 and older is surging from 13.1% in 2015 to 20.7% by 2025 (Human Resources Online, 2025).

### 6. The Sudden Mortality Spike for 2020-2022
<img width="1480" height="257" alt="Chart # 4 Total Deaths Over Time" src="https://github.com/user-attachments/assets/3f95f594-be3d-4245-978f-40c7dac4f1cf" />

*Figure 4: Mortality Count Over Time*

* **Observation:** Looking at the *Total Deaths Over Time* line chart, Singapore's annual mortality rose predictably by a stable margin year-over-year. However, between 2020 and 2022, the curve aggressively accelerates upward, jumping from 22,054 to 26,891 annual deaths.
* **Possible Causes:** This vertical spike in the graph directly captures the peak period and aftermath of the global COVID-19 pandemic. As highlighted by the Ministry of Health (2022) in Chart 2, younger age brackets remained completely stable, while deaths were heavily concentrated among aged 70 and above.These individuals were highly vulnerable, and complications from their pre-existing chronic conditions were accelerated during the COVID-19 pandemic period. 

### 7. Where Did the "Accidents" Data Go? 
<img width="1487" height="451" alt="Chart #3 Mortality Trends Overtime" src="https://github.com/user-attachments/assets/dd6ade1e-71c1-43f8-9e05-ccdf4c5cc07f" />

*Figure 5: Mortality Trends Overtime - ICD9 to ICD 10-AM*

* **Observation:** The  category "Accidents, Poisoning & Violence" stopped recording data around 2011, while new categories like "Hypertension" and "External Causes of Morbidity and Mortality" suddenly appeared on the dashboard in 2012.

* **Possible Causes:** This represents a systemic reclassification rather than a sudden medical miracle or a sudden disappearance of accidents. 
This reclassification aligns directly with Singapore's national migration from a legacy ICD-9 framework to the localized ICD-10-AM system, which officially went live across public hospitals in 2012 (Dimitropoulos et al., 2014). According to the report, this administrative transition was designed to update clinical data mapping and capture more granular health statistics. In this restructuring, legacy umbrella categories like "Accidents, Poisoning & Violence" were retired and remapped into modern terms like "External Causes of Morbidity and Mortality.

* *Note on Data Preprocessing:* The raw datasets initially contained complex ICD codes. To optimize the data for a layman audience and ensure clear dashboard presentation, these technical codes were removed

---

## 📚 References
* Amul, G. G. H., & Pang, T. (2018). Progress in tobacco control in singapore: Lessons and challenges in the implementation of the framework convention on tobacco control. *Asia & the Pacific Policy Studies*, 5(1), 102-121. https://doi.org/10.1002/app5.222
* Dimitropoulos, V., Cumerlato, M., Chowdhury, S., & Madden, R. (2014). REPORT: Singapore's migration to a new classification system. *HIM-Interchange*, 4(1), 32-35. https://him-i.himaa.org.au/wp-content/uploads/4-1-32-Dimitropoulos-et-al.pdf
* HealthXchange.sg. (2024). *Breast cancer: Risks, symptoms & treatments*. SingHealth Group. https://www.healthxchange.sg/cancer/breast-cancer/breast-cancer-risks-symptoms-treatments
* Human Resources Online / NPTD. (2025). *Singapore's citizen population aged 65 and above is growing faster than in the previous decade*. https://www.humanresourcesonline.net/singapore-s-citizen-population-aged-65-and-above-is-growing-faster-than-in-the-previous-decade-nptd
* Kouriefs, C. (2009). Prostate specific antigen through the years. *Archivio Italiano di Urologia e Andrologia*, 81(4), 195-198. https://pubmed.ncbi.nlm.nih.gov/20608139/
* Ministry of Health, Singapore. (2022). *Report on excess mortality during the COVID-19 pandemic up to June 2022*. https://isomer-user-content.by.gov.sg/3/5c4186c3-8d40-41a5-8908-5f2d54ec1f9b/report-on-excess-mortality-during-the-covid-pandemic-18sep2022.pdf
* Singapore Cancer Society. (2024). *Breast cancer: Understanding the risk factors*. https://singaporecancersociety.org.sg/breast-cancer/
* Teo, C. H., Ng, C. J., & Booth, A. (2016). Barriers and facilitators to prostate cancer screening in Asian countries: A systematic review. *Singapore Medical Journal*, 57(3), 121-129. https://pmc.ncbi.nlm.nih.gov/articles/PMC4800713/
* Young, B. E., Ong, C. W., & Lim, A. Y. (2018). Prognostic factors for mortality due to pneumonia among adults from different age groups in Singapore. *Singapore Medical Journal*, 59(4), 190-198. https://pmc.ncbi.nlm.nih.gov/articles/PMC5915635/
