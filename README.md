# Singapore Mortality & Leading Causes of Death
### A historical analysis of shifting epidemiological trends | 2006 - 2022
Created by: Jennifer Sing  
Connect with me: [LinkedIn](https://linkedin.com/in/jennifer-p-sing/)  
Live Interactive Visuals: [[📊 View Live Tableau Dashboard](https://public.tableau.com/shared/JWHB8XXSC?:display_count=n&:origin=viz_share_link)]
---

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
* **Data Source Portal:** [data.gov.sg](https://data.gov.sg) (Singapore Open Data Government Portal)
  * **Dataset 1:** [Singapore Ministry of Health (MOH) Mortality Profiles](https://data.gov.sg/collections/516/view)
  * **Dataset 2:** [Health Promotion Board (HPB) Historical Cancer Incidence](https://data.gov.sg/datasets/d_75673c9d6c4efdcd08530b55e6003976/view)

> 📌 **Data Scope Note:** Historical cancer incidence tracking relies on 5-year cohort metrics available up to 2015, while overall mortality trends capture annualized data up to 2022.

---

## 💡 Key Insights & Analysis

### 1. Cancer Chronology: The Persistent #1 Threat
* **Observation:** Cancer consistently remains the #1 cause of death in Singapore from 2006 to 2022 (holding a 28.5% share in 2006). While its *percentage share* shows a slight downward trend from 2020 to 2022, the actual volume of cancer-related deaths remained critically high.
* **Contextual Driver:** The minor drop in percentage share between 2020 and 2022 is a mathematical byproduct of the pandemic rather than a decline in cancer severity. Because all-cause mortality spiked dramatically during COVID-19, cancer's proportional share appears smaller, though absolute volumes remained severe.

### 2. Diverging Male Oncological Profiles (Lung vs. Prostate)
* **Observation:** Within male cancer incidence trends, lung cancer has been on a prominent, long-term downward trajectory (effectively cutting risk in half). Conversely, prostate cancer has experienced a steep, five-fold upward march over the same 40-year window.
* **Contextual Driver:** 
  * The lung cancer decline strongly correlates with Singapore's aggressive national anti-tobacco control measures, including public smoking prohibitions, advertising bans, and high taxation (Amul & Pang, 2018).
  * The rise in recorded prostate cancer is largely driven by diagnostic evolution—specifically, the widespread clinical adoption of Prostate-Specific Antigen (PSA) blood testing which captured previously asymptomatic cases (Kouriefs, 2009). Secondary factors include population aging and a shift toward a Westernized diet high in red meat and dairy fats (Teo et al., 2016).

### 3. The Long-Term Rise in Female Breast Cancer
* **Observation:** Female breast cancer incidence rates showed a continuous, long-term upward trend from 1976 to 2015, with the rate nearly tripling from 24.7 to 64.5 per 100,000 women.
* **Contextual Driver:** This steady increase reflects Singapore's rapid modernization and changing societal roles. Societal shifts led to delayed childbearing and lower overall fertility rates, increasing lifetime cumulative exposure to estrogen (Singapore Cancer Society, 2024). Additionally, transitioning into a global financial hub shifted lifestyles toward processed foods, animal fats, and more sedentary corporate routines (HealthXchange.sg, 2024).

### 4. Colorectal Cancer: The Shared Gender Threat
* **Observation:** Colorectal cancer has climbed steadily to become the Top #2 type of cancer for both genders.
* **Contextual Driver:** This sustained baseline is heavily driven by rapid urbanization and the widespread adoption of modern dietary habits rich in red meat, animal fats, and highly processed foods. Encouragingly, age-standardized rates among older cohorts (over 65) have stabilized in recent years—a direct footprint of the Health Promotion Board's (HPB) subsidized Fit Kit (Faecal Immunochemical Test) distribution initiatives launched in 2011.

### 5. Pneumonia & Singapore's Super-Aged Demographics
* **Observation:** Pneumonia mortality share steadily climbed to occupy the #2 and #3 spots on the leaderboard (rising from 13.7% to 20.0% share of all deaths), running completely parallel to a sharp increase in Singapore's total annual death counts.
* **Contextual Driver:** Pneumonia frequently serves as an end-stage medical complication among the elderly. Data shows pneumonia mortality climbing from 7.3% in younger populations to 29.7% for those aged 85+ (Young et al., 2018). This trend mirrors Singapore's transition into a "super-aged" society, where the citizen demographic aged 65 and older is surging from 13.1% in 2015 to 20.7% by 2025 (National Population and Talent Division, 2025).

### 6. The 2020-2022 Sudden Mortality Spike
* **Observation:** Looking at the *Total Deaths Over Time* line chart, Singapore's annual mortality rose predictably by a stable margin year-over-year. However, between 2020 and 2022, the curve aggressively accelerates upward, jumping from 22,054 to 26,891 annual deaths.
* **Contextual Driver:** This vertical acceleration directly captures the peak period and aftermath of the COVID-19 pandemic. As highlighted by the Ministry of Health (2022), younger age brackets remained completely stable, while excess deaths were heavily concentrated among individuals aged 70 and above whose pre-existing chronic conditions were accelerated by the virus.

### 7. Data Integrity Insight: Where Did the "Accidents" Data Go?
* **Observation:** The category *"Accidents, Poisoning & Violence"* stopped recording data around 2011, while new categories like *"Hypertension"* and *"External Causes of Morbidity and Mortality"* suddenly appeared on the dashboard in 2012.
* **Contextual Driver:** This represents a systemic administrative reclassification rather than a clinical shift. This change aligns directly with Singapore's national migration from a legacy ICD-9 data framework to the localized ICD-10-AM system in 2012 to capture more granular health statistics (Dimitropoulos et al., 2014). Legacy umbrella categories were retired and remapped into modern terms like *"External Causes of Morbidity and Mortality"*. 
* *Note on Data Preprocessing:* The raw datasets initially contained complex ICD codes. To optimize the data for a layman audience and ensure clear dashboard presentation, these technical codes were programmatically mapped and simplified.

---

## 📚 References
* Amul, G. G. H., & Pang, T. (2018). Progress in tobacco control in singapore: Lessons and challenges in the implementation of the framework convention on tobacco control. *Asia & the Pacific Policy Studies*, 5(1), 102-121.
* Dimitropoulos, V., Cumerlato, M., Chowdhury, S., & Madden, R. (2014). REPORT: Singapore's migration to a new classification system. *HIM-Interchange*, 4(1), 32-35.
* HealthXchange.sg. (2024). *Breast cancer: Risks, symptoms & treatments*. SingHealth Group.
* Human Resources Online / NPTD. (2025). *Singapore's citizen population aged 65 and above is growing faster than in the previous decade*.
* Kouriefs, C. (2009). Prostate specific antigen through the years. *Archivio Italiano di Urologia e Andrologia*, 81(4), 195-198.
* Ministry of Health, Singapore. (2022). *Report on excess mortality during the COVID-19 pandemic up to June 2022*.
* Singapore Cancer Society. (2024). *Breast cancer: Understanding the risk factors*.
* Teo, C. H., Ng, C. J., & Booth, A. (2016). Barriers and facilitators to prostate cancer screening in Asian countries: A systematic review. *Singapore Medical Journal*, 57(3), 121-129.
* Young, B. E., Ong, C. W., & Lim, A. Y. (2018). Prognostic factors for mortality due to pneumonia among adults from different age groups in Singapore. *Singapore Medical Journal*, 59(4), 190-198.
