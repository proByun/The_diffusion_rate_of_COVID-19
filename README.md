# The_diffusion_rate_of_COVID-19
Forecasting the Diffusion Rate of Coronavirus in Korea with 2020.01.20-2020.06.01 data 

kaggle에서 datartist가 제공한 한국의 코로나 데이터 셋 중 PatientRoute.csv파일만을 이용했습니다.

코로나의 확산속도는 유클리디안 거리를 이용해서 clustering 후 cluster 별 weight를 줘서 formulation 했고,
ARIMA알고리즘을 이용해서 확산속도를 예측했습니다. 

