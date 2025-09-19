# Equality Imperative: Gender Inequality, HDI, and Maternal Mortality  
*AOL – Data Mining and Visualization Project (Semester 2, 2024)*  

![Infographic Preview](./Infographic_AOL.png)

---

## Overview  
This project explores the relationship between the **Gender Inequality Index (GII)**, the **Human Development Index (HDI)**, and **maternal mortality** across countries, with a specific focus on Indonesia. It was developed as part of the **AOL Data Mining and Visualization course** at BINUS University.  

The work combines data mining in R, statistical analysis, and visualization into an infographic that highlights key findings related to gender equality and development (SDG 10: Reduced Inequalities).  

---

## Key Insights  
- Indonesia’s Gender Inequality Index (GII) declined by **35% between 1990 and 2021**:contentReference[oaicite:0]{index=0}.  
- **1 in 30 teenage girls** in Indonesia experience pregnancy, highlighting challenges in reproductive health:contentReference[oaicite:1]{index=1}.  
- Only **21% of seats in parliament** are held by women:contentReference[oaicite:2]{index=2}.  
- Countries with **low and medium HDI** levels show significantly higher maternal mortality rates.  
- In 2021, Indonesia ranked **110th out of 190 countries** in the Gender Inequality Index:contentReference[oaicite:3]{index=3}.  

---

## Files in this Repository  
- **[`datamining_script_aol.Rmd`](./datamining_script_aol.Rmd)**  
  R Markdown script used for data processing, statistical analysis, and generating visualizations.  

- **[`Infographic_AOL.png`](./Infographic_AOL.png)**  
  Final infographic summarizing the project’s findings in a visual and impactful format.  

- **[`Infographic Description.pdf`](./Infographic%20Description.pdf)**  
  Report providing the project narrative, context, and supporting explanations for the analysis.  

---

## Methods  
1. **Data Sources**  
   - Gender Inequality Index (UNDP)  
   - Human Development Index (UNDP)  
   - Maternal mortality statistics (World Bank / UN datasets)  
   - Indonesia demographic indicators  

2. **Tools & Techniques**  
   - **R** with `tidyverse`, `plotly`, `dplyr` for analysis and visualization.  
   - Descriptive statistics and correlation analysis between GII, HDI, and maternal mortality.  
   - Comparative bar charts, pie charts, and scatter plots to visualize insights.  
   - Infographic design combining generated plots with key textual highlights.  

---

## Results  
- **Correlation**: Higher GII ranks (greater inequality) correlate with **higher maternal mortality**.  
- **HDI Connection**: Countries with low HDI consistently face worse maternal health outcomes.  
- **Policy Signal**: Increasing women’s representation in leadership and improving reproductive health services are essential for progress toward gender equality in Indonesia.  

---

## How to Reproduce  
### Requirements  
- R (≥ 4.0)  
- R packages: `tidyverse`, `plotly`, `dplyr`, `readr`  

### Steps  
1. Clone this repository:  
   ```bash
   git clone https://github.com/arieltarliman/Data-Mining-and-Visualization-about-Equality-Imperative.git
   cd Data-Mining-and-Visualization-about-Equality-Imperative
