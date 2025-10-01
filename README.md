# Crime Mapping: Violent Crime vs. CCTV in Seoul (2023)

This project analyses the relationship between violent crime, CCTV density, and clearance rates across Seoul’s 25 districts.

## Key Insights
- **Weak link (R² ≈ 0.20)** between CCTV density and violent crime → cameras are deployed reactively where crime is already high.  
- **Moderate link (R² ≈ 0.57)** between CCTV density and clearance rates → CCTV is more effective for investigations than prevention.  
- Outliers highlight gaps in coverage:  
  - **Jung-gu & Gwanak-gu** – high crime but relatively low CCTV coverage.  
  - **Yangcheon-gu & Geumcheon-gu** – stronger coverage relative to crime.  

## Files
- `seoul_crime.qmd` – Quarto analysis code.  
- `Violent_Crime_vs_CCTV_in_Seoul_2023.pdf` – final written report.  
- `seoul_crime.html` – interactive report with maps.  
- `raw_*` – original translated datasets.  
- `*_csv` – cleaned and translated datasets for analysis.  

## Methods
- Data: Police-recorded violent crime & CCTV data (2023); population data (2024).  
- Tools: R (`tidyverse`, `sf`, `leaflet`, `ggplot2`, `gt`) and Quarto.  
- Translation: Original datasets were in Korean; I translated & standardised them into English for reproducibility.  

## Reproducibility
Warning messages and a Generative AI declaration are included in the report.  
All code and interpretations are my own; I used ChatGPT 5 to clarify functions and fix minor rendering issues.  

---

📍Author: **Seoyoung (Luna) Ko**  
BSc Crime and Security Science, University College London (Class of 2027)  
[LinkedIn]((https://www.linkedin.com/in/luna-ko-a92633283/))
