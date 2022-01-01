# 국내 연휴기간의 해외 지수 변동률을 통한 KOSPI 지수 변동 예측
해외와 국내의 시차로 인해, KOSPI의 휴장기간동안의 이슈로 해외 지수의 변동이 생김,  
이러한 변동을 통한 개장일의 KOSPI 지수 변동 예측

## 프로젝트 기간
2021-11-19 ~ 2021-11-26  

## 사용기술
- Python
- Pandas
- scikit-learn
- Keras LSTM  

## 활용 데이터
- 지수 시계열 데이터 (2001-01-01 ~ 2021-11-11)
  - NASDAQ : investing.com
  - S&P500 : Python FinanceDataReader
  - FTSE100 : Yahoo Finance
  - DAX50 : investing.com
  - NIKKEI : investing.com
  - HANGSENG : investing.com
  - SANGHAI : investing.com
  - KOSPI : Python FinanceDataReader
