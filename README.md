# Stock_Pjt 🧨

## Data Collection
- Investing.com 활용 Data Crawling
- 한국, 미국, 중국, 일본 대표 지수 약 30년치 데이터 수집
- 그 외 소비자 물가 지수, 기준 금리, 환율, 실업률, 국고채 수익률, 유가, 금, 비트코인 데이터 수집
  
## EDA
- KOSPI 지수와 수집한 요소들의 상관관계 분석
- 유의미한 연관성 분석을 위한 공적분 분석 진행
- Scatter Plot 활용, 시각적 분석

## Data Preprocessing
- 시계열 데이터 정상성 확인 및 차분
- 단변량, 다변량 시계열 데이터 제작
- XGBoost 학습을 위해 시계열 데이터를 회귀 분석용 데이터로 변환

## Modeling
- ARIMA, Prophet, VAR, XGBoost 모델 학습 및 KOSPI 지수 예측
- XGBoost 활용, Feature Importance 추출 후 다변량 시계열 변수 변경하며 학습
- SHAP 활용, Feature 별 기여도 확인

## Result
- 항생 지수, 금, 일본 국채 수익률이 가장 높은 연관성을 가진 요소로 판단됐지만 완벽하게 설명 가능한 패턴을 가진다고 보기 어려움
- 금 지수와 KOSPI 지수는 보통 같은 추세를 보이는데 세계 경제 이슈가 있기 전 3개월 이상 반대 추세를 보이는 패턴 발견
- 일본 국채 수익률 같은 경우 학습 모델들에서 중요 변수로 자주 추출됐지만, 시각적 분석 결과 유의미한 해석을 하기 어려움
