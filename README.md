Mangrove Area Classification Using Synthetic Data

A machine learning pipeline for classifying mangrove vs non-mangrove areas using satellite imagery and synthetic data. This project combines 
 ![Mangrove](https://img.shields.io/badge/Mangrove-Classification-green)
 ![Python](https://img.shields.io/badge/Python-3.8%252B-blue)
 ![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
 ![Geospatial Analysis](https://img.shields.io/badge/Geospatial-Analysis-blueviolet)
for environmental monitoring.


🔹 Methodology

Generated and processed synthetic satellite datasets simulating mangrove and non-mangrove regions.

Engineered key vegetation and water indices (NDVI, NDWI) for effective feature representation.

Developed and evaluated machine learning models: Random Forest, Logistic Regression, and Support Vector Machine for pixel-based classification.

Produced interactive geospatial visualizations, including choropleth maps, prediction probability maps, and spectral signature comparisons.

Integrated geospatial coordinates to analyze mangrove coverage across regions.


🔹 Key Findings

Random Forest achieved the highest performance (~92% accuracy) on synthetic data, demonstrating strong classification capability.

Spectral indices (NDVI, NDWI) effectively differentiate mangrove areas from other land cover types.

Visualizations revealed spatial patterns of mangrove coverage, highlighting ecologically significant regions.

Synthetic data can provide reliable training for ML models when real-world datasets are limited.

Confussion Matrix
<img width="689" height="525" alt="Screenshot 2025-12-14 221628" src="https://github.com/user-attachments/assets/22423801-1b79-41e0-9ad7-463335175892" />

Average Spectral Signature
<img width="1507" height="379" alt="Screenshot 2025-12-14 221654" src="https://github.com/user-attachments/assets/78bace03-9a46-4500-b9cc-4b566ae75fde" />

Mangrove Coverage By Region
<img width="1497" height="435" alt="Screenshot 2025-12-14 221729" src="https://github.com/user-attachments/assets/cc22631b-bca9-462c-9d5a-95369c577bf6" />

Mangrove Probabilty Map in Sundarban Region
<img width="1495" height="412" alt="Screenshot 2025-12-14 221745" src="https://github.com/user-attachments/assets/87c9a6bc-cbe1-4964-a1a1-d4d3537c3cdd" />



🔹 Impact

Demonstrates a scalable approach for mangrove monitoring and coastal ecosystem assessment.

Provides a reproducible ML pipeline combining geospatial analysis, modeling, and visualizat
