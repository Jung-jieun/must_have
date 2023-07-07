# must_have 머신러닝 딥러닝 문제해결 전략

범주형 데이터 이진분류(Categorical Feature Encoding Challenge)
- 타깃값 1에 속할 확률 예측
- 로지스틱 회귀
- ROC-AUC
- 피처별 분포도

안전 운전자 에측(Porto Seguro's Safe Driver Prediction)
  - 보험사에서 제공한 고객 데이터를 활용해 운전자가 보험을 청구할 확률 예측
  - XGBoost, LightGBM
  - 정규화된 지니계수

향후 판매량 예측(Predict Future Sales)
  - 2013년 1월부터 2015년 10월까지 판매 데이터를 기반으로 2015년 11월 판매량 예측(시계열 문제)
  - LightGBM
  - RMSE
  - 변수 조합하여 새로운 변수 생성(시차 변수)
  - 데이터 다운캐스팅 및 가비지 컬렉션 사용
  - 직접적인 타깃값을 제공하지 않음
