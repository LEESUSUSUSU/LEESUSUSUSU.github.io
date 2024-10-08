#### 1. 기차 소음 분석 프로젝트

**프로젝트 배경:**
- **프로젝트명:** 기차 소음 분석 프로젝트
- **수행 기간:** 4주 (2023년 10월 - 2023년 11월)
- **목적:** 기차 소음을 분석하여 공공 교통안전 현안을 해결하는 AI 알고리즘 설계

**결과:**
- **데이터 수집:** 7일 동안 수집된 215개의 TDMS 파일과 82개의 JSON 파일
- **최고 성능 모델:** 오토인코더 모델, 이상 소음 탐지
- **결론:** 소리 데이터를 활용한 AI 알고리즘의 가능성을 확인하였으며, 다양한 주파수 도메인 분석 기법의 유효성을 검증했습니다.

#### 2. 유퀴즈 데이터 분석

**프로젝트 배경:**
- **프로젝트명:** 유퀴즈 데이터 분석
- **수행 기간:** 4주 (2024년 1월 - 2024년 2월)
- **목적:** 유퀴즈 프로그램의 시청률 및 유튜브 조회수를 예측하기 위한 모델 개발

**결과:**
- **데이터 수집:** 나무위키, 유튜브 API, 직접 수집한 시즌, 에피소드, 날짜, 주제, 출연자, 시청률, 직업, 성별, 연령, 수상 및 인정 정보를 포함한 데이터
- **최고 성능 모델:** GradientBoostingRegressor, MAE: 0.28, MAPE: 6.38%
- **결론:** 효과적인 특징 공학 및 데이터 전처리가 예측 모델 구축에 중요함을 확인했습니다.

#### 3. 대구 교통사고 피해 예측 AI

**프로젝트 배경:**
- **프로젝트명:** 대구 교통사고 피해 예측 AI
- **수행 기간:** 4주 (2023년 11월 - 2023년 12월)
- **목적:** 교통사고 피해를 예측하는 AI 모델을 개발하여 안전한 교통환경 조성

**결과:**
- **사용된 모델:** XGBoost, RandomForestRegressor, GradientBoostingRegressor
- **최고 성능 모델:** XGBoost, 최적화된 파라미터로 RMSE 3.1597566362011293 달성
- **결론:** 앙상블 모델의 예측 과제에서의 효과를 확인하였으며, 파라미터 최적화의 중요성을 경험했습니다.

#### 4. 시각 장애 보조를 위한 딥러닝 기반 장애물 인식

**프로젝트 배경:**
- **프로젝트명:** 시각 장애 보조를 위한 딥러닝 기반 장애물 인식
- **수행 기간:** 4주 (2024년 3월 - 2024년 4월)
- **목적:** 딥러닝 기법을 사용하여 시각 장애인을 돕기 위한 장애물 인식 모델 개발

**결과:**
- **데이터 수집:** 23가지 클래스에 대해 각 최소 1,000개의 샘플을 수집하고 라벨링
- **최고 성능 모델:** YOLOv8, Precision(B): 0.80254, Recall(B): 0.68715, mAP50(B): 0.90292, mAP50-95(B): 0.72743
- **결론:** 객체 탐지 모델의 튜닝 및 성능 평가에 대한 이해를 높였으며, 데이터 라벨링과 클래스 균형 조정의 중요성을 확인했습니다.

#### 5. 신용카드 사기 탐지

**프로젝트 배경:**
- **프로젝트명:** 신용카드 사기 탐지
- **수행 기간:** 4주 (2024년 4월 - 2024년 5월)
- **목적:** 대중의 안전한 신용카드 사용을 보장하기 위한 사기 탐지 모델 개발

**결과:**
- **사용된 모델:** 로지스틱 회귀, CNN, K-최근접 이웃, 의사결정 나무, 서포트 벡터 머신 (SVM)
- **최고 성능 모델:** SVM, AUC 0.98
- **결론:** 효과적인 데이터 전처리와 클래스 불균형 처리가 모델 성능을 크게 향상시켰습니다. 전통적인 머신러닝 모델이 주로 사용되는 구조적 표 형식 데이터에서도 CNN 모델이 우수한 성능을 발휘할 수 있음을 확인했습니다.

---