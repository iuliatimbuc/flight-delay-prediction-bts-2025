# Flight Delay Prediction - BTS 2025

## Dataset
- Sursa: https://www.transtats.bts.gov
- 7.7 milioane zboruri SUA 2025
- 10 companii aeriene, 364 aeroporturi

## Modele
- Clasificare 1: Va intarzia zborul? (XGBoost, F1=52%)
- Clasificare 2: Va fi anulat? (Random Forest, F1=87%)
- Regresie V3: Cat va intarzia la plecare? (RF, R2=8%)
- Regresie V2: Cat va intarzia la sosire? (LightGBM, R2=98%)

## Instalare
pip install -r requirements.txt

## Cum sa descarci datele
1. Mergi la https://www.transtats.bts.gov
2. Descarca On-Time Performance 2025
3. Pune fisierele in folderul /data
