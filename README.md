# Data Analysis Portforlio 1

- Data :
- Visualization
- Statistical Analysis
- Conclusion
- Action Insight

## 앱 방문 분석

1. 개요

- 새로운 앱이 출시 되었다고 가정 한 후, 출시 후 사용자들의 방문 데이터를 이용하여 사용 패턴을 분석

2. Dataset

- app_data.csv 데이터는 총 8개의 features 를 가지고 있다.

  - user_id = unique ID
  - provider = 통신사 (S, K, L)
  - AB_test = A/B test를 진행한 그룹 (A, B)
  - version = 앱 버전 (V1, V2)
  - join_date = 가입날짜
  - visits = 앱 방문 회수
  - avg_loding_time = 평균 앱 로딩타임
  - sum_loading_time = 누적 앱 로딩타임

3. 목표

- 그룹간에 방문수의 차이가 존재하는지 확인
- 그룹간에 방문수의 차이가 통신사별로 존재하는지 확인
- 방문수와 다른 features 사이의 관계 모델링
