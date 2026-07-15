# Ocala Wintering Green-winged Teal Data Analysis

This repository contains the data cleaning and filtering pipeline used for a field study analyzing wintering populations of the Green-winged Teal (*Anas crecca*) in Ocala, Florida. 

## Study Overview
* **Study Period:** November 1, 2024 – March 31, 2025
* **Target Species:** Green-winged Teal (*Anas crecca*)
* **Locations:** 
  * Ocala Wetland Recharge Park (Locality ID: L9783145) - Engineered Ecosystem
  * Tuscawilla Park (Locality ID: L35493207) - Managed Urban Park

## Methodology
The script filters raw eBird Basic Dataset (EBD) files for Marion County, Florida. It restricts data to standard stationary (P21) and traveling (P22) checklists. Search effort is standardized by calculating **Birds Per Party Hour (BPPH)** per location per month. 

## Findings
* **Ocala Wetland Recharge Park:** Documented a winter peak in January 2025 yielding **0.69 BPPH** across 10.17 party hours.
* **Tuscawilla Park:** Documented **0.00 BPPH** across the entire study period. 
* These findings support the hypothesis that engineered wetlands offer superior foraging opportunities (such as Duckweed cover) compared to traditional urban parks during peak migration.

## How to Run
1. Upload your eBird Basic Dataset `.txt` file to the root directory.
2. Execute the `extract_ocala_teal_data.ipynb` script via Google Colab.
3. The cleaned results will export automatically to an Excel spreadsheet (`Ocala_Teal_Winter_Data.xlsx`).

## Credits & Acknowledgments
* **Data Source:** eBird Basic Dataset (EBD) provided by the Cornell Lab of Ornithology.
* **Code Development:** Python extraction pipeline generated with assistance from Google Gemini AI to ensure reproducible data filtering workflows.
