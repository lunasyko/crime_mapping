# Raw Data
This folder contains the original datasets in Korean and the translated versions before cleaning.
## Violent Crime (Seoul, 2023)
- **Publisher:** Seoul Open Data Plaza (서울 열린데이터 광장)/ Police (official government dataset, originally in Korean).
- **Original URL:** https://data.seoul.go.kr/dataList/316/S/2/datasetView.do
- **Snapshot version:** 2023
- **Files in repo:** `/data/raw/raw_seoul_crime.csv` (original), `/data/processed/seoul_crime.csv` (cleaned & translated).
- **Notes:** Preserved copy included here for reproducibility. Live portals now show updated 2024 values.

## CCTV Deployment by District (2016–Present, annual)
- **Source:** Seoul Open Data Plaza (서울 열린데이터 광장)  
- **Dataset name (KR):** 서울시 자치구 (연도별) CCTV 설치현황  
- **Dataset name (EN):** CCTV installations by Seoul district (annual, before 2015–present)  
- **Publisher:** Seoul Metropolitan Government  
- **Original URL:** https://data.seoul.go.kr/dataList/OA-2734/F/1/datasetView.do  
- **File type:** Excel (.xlsx) — one sheet, CCTV installation by district × year   
- **Files in this repo:** `/data/raw/raw_cctv_by_district.xlsx` (downloaded from portal, includes before 2015–2025 data), `/data/processed/cctv_by_district.csv` (translated & cleaned)  
- **Subset used in analysis:** before 2015 - 2023
