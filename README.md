# Research
## **Total number of publications**: **![5](https://img.shields.io/badge/5-8a2be2?style=flat&color=8a2be2&labelColor=8a2be2&logoColor=white)**

| **Journal name** | Journal category (SCImago) | Impact Factor (year) | CiteScore |**Number of papers published*** |
| ---------------- | -------------------------- | -------------------: | -------------------: | ------------------------------: |
| **Science of The Total Environment (STOTEN)** | Q1 | 8.0 (2024 JCR) |16.4| **![1](https://img.shields.io/badge/1-8a2be2?style=flat&color=8a2be2&labelColor=8a2be2&logoColor=white)** |
| **Journal of Contaminant Hydrology** | Q1 | 4.4 (2024 JCR) |  8.0 |**![1](https://img.shields.io/badge/1-8a2be2?style=flat&color=8a2be2&labelColor=8a2be2&logoColor=white)** |
| **Marine Pollution Bulletin (MPB)** | Q1 | 4.9 (2024 JCR) | 9.7| **![2](https://img.shields.io/badge/2-8a2be2?style=flat&color=8a2be2&labelColor=8a2be2&logoColor=white)** |

# Publications
## 1. Predicting groundwater phosphate levels in coastal multi-aquifers: A geostatistical and data-driven approach
**Authors**: Md. Abdullah-Al Mamun, Abu Reza Md Towfiqul Islam, Mst. Nazneen Aktar, Md Nashir Uddin, Md. Saiful Islam, Subodh Chandra Pal, Aznarul Islam, A.B.M. Mainul Bari, Abubakr M. Idris, Venkatramanan Senapathi

### Abstract
The groundwater (GW) resource plays a central role in securing water supply in the coastal region of Bangladesh and therefore the future sustainability of this valuable resource is crucial for the area. However, there is limited research on the driving factors and prediction of phosphate concentration in groundwater. In this work, geostatistical modeling, self-organizing maps (SOM) and data-driven algorithms were combined to determine the driving factors and predict GW phosphate content in coastal multi-aquifers in southern Bangladesh. The SOM analysis identified three distinct spatial patterns: K+single bondNa+single bondpH, Ca2+single bondMg2+single bondNO₃−, and HCO₃−single bondSO₄2−single bondPO43−single bondF−. Four data-driven algorithms, including CatBoost, Gradient Boosting Machine (GBM), Long Short-Term Memory (LSTM), and Support Vector Regression (SVR) were used to predict phosphate concentration in GW using 380 samples and 15 prediction parameters. Forecasting accuracy was evaluated using RMSE, R2, RAE, CC, and MAE. Phosphate dissolution and saltwater intrusion, along with phosphorus fertilizers, increase PO43− content in GW. Using input parameters selected by multicollinearity and SOM, the CatBoost model showed exceptional performance in both training (RMSE = 0.002, MAE = 0.001, R2 = 0.999, RAE = 0.057, CC = 1.00) and testing (RMSE = 0.001, MAE = 0.002, R2 = 0.989, RAE = 0.057, CC = 0.998). Na+, K+, and Mg2+ significantly influenced prediction accuracy. The uncertainty study revealed a low standard error for the CatBoost model, indicating robustness and consistency. Semi-variogram models confirmed that the most influential attributes showed weak dependence, suggesting that agricultural runoff increases the heterogeneity of PO43− distribution in GW. These findings are crucial for developing conservation and strategic plans for sustainable utilization of coastal GW resources.

### Key Highlights:
- A dataset of 15 hydrochemical parameters from 380 wells was presented.
- SOM and multicollinearity testing enhanced ML model performance in coastal aquifers.
- CatBoost combined with geostatistics and SOM predicted PO43− with high accuracy (R2 = 0.99).
- Na+ and K+ showed high spatial autocorrelation, impacting PO43− prediction.

## Citation  
If you use any part of this research, please cite:

> Mamun, M. A.-A., Islam, A. R. M. T., Aktar, M. N., Uddin, M. N., Islam, M. S., Pal, S. C., Islam, A., Bari, A. B. M. M., Idris, A. M., & Senapathi, V. (2024). Predicting groundwater phosphate levels in coastal multi-aquifers: A geostatistical and data-driven approach. *Science of The Total Environment*, 953, 176024. [https://doi.org/10.1016/j.scitotenv.2024.176024](https://doi.org/10.1016/j.scitotenv.2024.176024)

## Graphical abstract
![Grahical_Abstract_PO4](https://github.com/user-attachments/assets/eca13f50-b547-49fe-9639-72c03b784096)
-----

## 2.  Optimizing coastal groundwater quality predictions: A novel data mining framework with cross-validation, bootstrapping, and entropy analysis

**Authors**: Abu Reza Md Towfiqul Islam, Md. Abdullah-Al Mamun, Mehedi Hasan, Mst. Nazneen Aktar, Md Nashir Uddin, Md. Abu Bakar Siddique, Mohaiminul Haider Chowdhury, Md. Saiful Islam, A.B.M. Mainul Bari, Abubakr M. Idris, Venkatramanan Senapathi

### Abstract

Investigating the potential of novel data mining algorithms (DMAs) for modeling groundwater quality in coastal areas is an important requirement for groundwater resource management, especially in the coastal region of Bangladesh where groundwater is highly contaminated. In this work, the applicability of DMA, including Gaussian Process Regression (GPR), Bayesian Ridge Regression (BRR) and Artificial Neural Network (ANN), for predicting groundwater quality in coastal areas was investigated. The optuna-based optimized hyperparameter is proposed to improve the accuracy of the models, including optuna-GPR and optuna-BRR as benchmark models. Combined cross-validation (CV) and bootstrapping (B) methods were used to build six predictive models. The entropy-based coastal groundwater quality index (ECWQI) was converted into a normalized index (ECWQIn), which was divided into five classes from very poor to excellent. The self-organizing map (SOM), spatial autocorrelation and fuzzy logic model were used to identify spatial groundwater quality patterns based on 12 physicochemical variables collected from 67 groundwater wells. The SOM analysis identified four distinct spatial patterns, including EC-TDS-Cl−, Mgsingle bondpH, Ca2+single bondK+single bondNO₃−, and HCO₃−single bondSO₄2−single bondNa+single bondF−. The results showed that both the ANN (CV) and ANN (B) models performed better than other optuna-based models during the test phase (RMSE = 0.041, MAE = 0.026, R2 = 0.971, RAE = 0.15 = 21 and CC = 0.986) and (RMSE = 0.041, MAE = 0.025, R2 = 0.969, RAE = 0.119 and CC = 0.975), respectively. SO42−, Cl− and F− played an important role in the prediction accuracy. F- and SO42− showed higher spatial autocorrelation, which affected groundwater quality degradation. In addition, the ANN (CV) and ANN (B) models showed a Gaussian distribution of model errors (small standard error, <1 %), indicating the stability of the model. These results indicate the efficiency of the ANN model in predicting groundwater quality in coastal areas, which would help regional water managers in real-time monitoring and management of sustainable groundwater resources.

### ✨ Key Highlights

  - The models ANN (CV) and ANN (B) outperformed other data mining approaches.
  - The normalized ECWQI was adopted to interpret coastal groundwater quality areas.
  - SO42−, Cl−, and F− had a significant role in predictive accuracy.
  - The Moran's I index for F−, and SO42− demonstrate strong spatial autocorrelation and imply clustering of similar origins.

### 📚 Citation

If you use this work, please cite the original publication:

> Islam, A. R. M. T., Mamun, M. A.-A., Hasan, M., Aktar, M. N., Uddin, M. N., Siddique, M. A. B., Chowdhury, M. H., Islam, M. S., Bari, A. B. M. M., Idris, A. M., & Senapathi, V. (2025). Optimizing coastal groundwater quality predictions: A novel data mining framework with cross-validation, bootstrapping, and entropy analysis. *Journal of Contaminant Hydrology, 269*, 104480. [https://doi.org/10.1016/j.jconhyd.2024.104480](https://doi.org/10.1016/j.jconhyd.2024.104480)


## 🖼️ Graphical abstract

![Grahical Abstract, (coastal_water_qualityML) - final after review](https://github.com/user-attachments/assets/1543b729-6c2d-413d-aa55-9f12a57b3697)

## 📑3. Tracing source footprints of heavy metal(oid)s in coastal soils using traditional statistical techniques and machine learning data-driven models

### 🌊🧪 Tracing source footprints of heavy metal(oid)s in coastal soils using traditional statistical techniques and machine learning data-driven models

[https://doi.org/10.1016/j.marpolbul.2025.118701](https://doi.org/10.1016/j.marpolbul.2025.118701)

**👥 Authors**: Abu Reza Md Towfiqul Islam, Memet Varol, Javed Mallick, **Md. Abdullah-Al Mamun**, Md. Yousuf Mia, Md. Abu Bakar Siddique, **Md. Saiful Islam**, **Mst. Nazneen Aktar**. 

### Abstract
We integrate traditional statistics (PCA, PCoA) with machine-learning tools (Self-Organizing Maps, Conditional Inference Trees, Ridge Regression, SHAP) to trace sources of heavy metal(oid)s (As, Pb, Zn, Cd, Cu, Ni, Cr, Mn, Fe, U) in coastal soils along the northeast Bay of Bengal. Several metals (Pb, Cd, Mn, As) exceed average shale values, with clear spatial patterns separating industrial/shipbreaking hotspots from geogenic backgrounds. Ridge models achieve high predictive accuracy and SHAP explains the controlling roles of soil pH, texture (sand/silt/clay), elevation, and organic matter. Findings support targeted pollution control and sustainable coastal management. 

### ✨ Key Highlights

* **📍 Study area & scope**: Northeast coast of Bangladesh; spatial source-tracing of heavy metal(oid)s in coastal soils. 
* **🧪 Methods**: PCA, PCoA, SOM, CIT, Ridge Regression (Bayesian-optimized), SHAP, and GIS mapping (IDW). 
* **⚠️ Exceedances**: Pb, Cd, Mn, and As exceed average shale/background values in parts of the study region. 
* **🔄 Source signals**: SOM & CIT indicate **shipbreaking/industrial** signatures (Cu, Zn, Pb) vs **geogenic** controls (As, Ni, Cr, Mn, Fe). 
* **📈 Model performance**: Ridge shows very strong fits—e.g., **Ni R² ≈ 0.998**, **Fe R² ≈ 0.995**, **Cd R² ≈ 0.977**, **Mn R² ≈ 0.898**—aligning with CIT/SHAP drivers. 
* **🗺️ Spatial structure**: PCoA explains **~75.46%** of spatial variation; industrial hotspots (e.g., Patenga/Sonadia/Kutubdia) contrast with lower-impact islands (e.g., St. Martin’s). 

## 🗂️ Dataset Description

* **Sampling**: **78** surface-soil samples (0–10 cm) from **6 sites** — St. Martin’s, Matarbari, Kutubdia, Sonadia, Sandwip, Patenga — collected **March–April 2023**. 
* **Analytes**: As, Pb, Zn, Cd, Cu, Ni, Cr, Mn, Fe, U (AAS; QA/QC with reference materials; recoveries ~95–110%). 
* **Soil properties**: pH, organic matter, sand/silt/clay fractions, elevation; used as predictors in ML models. 

## 📊 Results

* **Source tracing**: SOM clusters and CIT thresholds separate **anthropogenic** (shipbreaking, battery/industrial waste, fertilizer runoff) from **geogenic** patterns. 
* **Explained variation**: PCoA axis pair explains **75.46%** of spatial differences in metal profiles. 
* **Model + XAI**: Ridge predictions align with SHAP—**pH**, **texture (silt/clay)**, **OM**, **elevation** are dominant drivers; metals show site-specific hotspots consistent with industry/agriculture. 

## 📚 Citation

If you use any part of this research, please cite:

> Islam, A. R. M. T., Varol, M., Mallick, J., **Mamun, M. A.-A.**, Mia, M. Y., Siddique, M. A. B., **Islam, M. S.**, **Aktar, M. N.** (2026). Tracing source footprints of heavy metal(oid)s in coastal soils using traditional statistical techniques and machine learning data-driven models. *Marine Pollution Bulletin, 222*, 118701. [https://doi.org/10.1016/j.marpolbul.2025.118701](https://doi.org/10.1016/j.marpolbul.2025.118701) 

## 🖼️ SOM component planes and clustering for heavy metals in coastal regions, Bangladesh

![Picture1](https://github.com/user-attachments/assets/a7eda584-ea12-494d-852d-19d6fdcef21f)

Here is a clean, corrected, fully **final-published** version for your GitHub.
I removed “in press,” updated the DOI to the **real 2026 MPB citation**, and fixed grammar/styling so it looks professional.

---

## 4. First probabilistic radiological risk appraisal of Bay of Bengal beach sands: Explicit spatial hot-spot analysis

**Authors:** Jahanara Habib Zesha, **Md. Abdullah-Al Mamun**, Abu Reza Md. Towfiqul Islam, Md. Ahosan Habib, Rahat Khan

**Status:** Published (2026). DOI: [https://doi.org/10.1016/j.marpolbul.2025.118966](https://doi.org/10.1016/j.marpolbul.2025.118966)

### **Key highlights**

* Developed the first integrated **PCA–GIS–Monte Carlo** framework to assess radiological risk in Bay of Bengal (BoB) beach sands.
* Activity concentrations of **²²⁶Ra** and **²³²Th** exceeded global averages by **2.2×** and **4.1×**, respectively.
* **PCA** indicated that natural mineralogical sources are the dominant controls on radionuclide enrichment.
* **Probabilistic risk modeling** showed radiological indices exceeding international safety limits by **8–23×**.
* **²³²Th (75%)** and **²²⁶Ra (24%)** were identified as the major contributors to total radiological risk.
---
## 📚 Citation

Zesha, J. H., Mamun, M. A., Islam, A. R. M. T., Habib, M. A., & Khan, R. (2026).
*First probabilistic radiological risk appraisal of Bay of Bengal beach sands: Explicit spatial hot-spot analysis.*
**Marine Pollution Bulletin, 223**, 118966. [https://doi.org/10.1016/j.marpolbul.2025.118966](https://doi.org/10.1016/j.marpolbul.2025.118966)

---

## 🖼️ Fig. 1. Multi-scale geological and sampling framework of the study area

<img src="https://raw.githubusercontent.com/Abdullah-TU/Images-for-Other-Files/main/Fig.%201%20Final.jpg"
  alt="Fig. 1. Multi-scale geological and sampling framework of the study area." width="900">




