# 목차
- 목차의 프로젝트를 클릭하시면 상세페이지로 이동합니다. 

## BI 툴을 활용한 시각화 대시보드 프로젝트

> ### [온라인 쇼핑몰 시장 동향 대시보드](https://lookerstudio.google.com/reporting/0b2f9f23-2757-45c0-b990-a6fb5933ac57)  
> ### 사용 Tool : Python, Google Spreadsheets, Looker Studio
> #### 통계청의 온라인 시장 동향 조사 데이터를 활용하여, 운영 형태별 비교, 연도 및 월별 매출 변화 추이를 확인할 수 있는 대시보드를 제작함.
> ### 배운점 
> #### 향후 현업에서 시장 동향을 파악해야하는 의사결정권자에게 빠르고 정확한 정보를 제공할 수 있는 역량과
> #### 지속적인 데이터 모니터링 및 트렌드 분석 역량을 발전시켰음.  

--------------------------------------------

## Python ML/DL 기반의 데이터 분석 프로젝트

> ### [압연공정 불량 원인 도출 프로젝트](https://github.com/0cars0903/ScalingSimulation)
> ### 문제정의
> ##### 압연 공정에서 발생하는 불량의 원인을 데이터 분석을 통해 파악하고, 공정 개선을 위한 주요 변수를 도출함.
> 
> ### 주요성과
> 
> ##### 압연온도의 최적조건 달성 시, 불량률으 급감하는 것을 확인함.
> ##### 가열로 공정에서는 온도가 매우 높아 화학적 결합 반응에 의한 Scale이 발생하더라도,
> ##### 가역 반응으로 인하여 Scale 발생 확률이 낮지만, 비교적 낮은 온도인 압연 공정에서는 화학적 결합 반응에 의한 Scale 생성 가능성이 높음.
> 
> ### 배운점
> ##### 프로젝트를 통해 데이터 기반의 원인 파악을 통해 불량 감소와 생산성 향상을 기대할 수 있었음.

-------------------------------------

> ### [이차전지 화성공정 불량 최적화 프로젝트](https://www.notion.so/0cars/BigData-ba77a6e979324edc9b9609f6ade9aa74?pvs=4)
> ### 문제정의
> ##### 이차전지의 화성 공정 중 발생하는 불량률을 최소화하기 위해 공정 데이터를 분석하여 주요 변수들을 도출하고, 이를 바탕으로 공정을 최적화하는 방안을 마련함.
> 
> ### 주요성과
> ##### 불량률 감소: Decision Tree 모델을 통해 주요 인자들을 분석한 결과, 특정 온도 범위에서 불량률이 급감하는 것을 확인함.
> ##### 설비 간 유의차 분석: 분산분석(ANOVA)과 카이제곱 검정을 통해 설비 간의 차이를 통계적으로 확인하고, 이를 기반으로 공정 개선에 필요한 변수들을 파악함.
> ##### 공정 최적화: 불량률을 2.38%에서 0.62%로 크게 감소시켜, 공정 효율성을 높이고 생산성을 향상시킴.
> ##### 수상 : 포스코 청년 Ai BigData 아카데미 20기 프로젝트 우수상 수상  
> 
> ### 배운점
> ##### 데이터를 기반으로 한 공정 개선을 통해 불량률을 효과적으로 감소시킬 수 있었고, 데이터 기반 의사결정의 중요성을 깨달음.
> ##### 제조 공정에서의 도메인 지식이 데이터를 해석하고 최적화 방안을 마련하는 데 매우 중요한 요소임을 확인함.

------------------------------------------------

> ### [온라인 채널 제품 판매량 예측 해커톤](https://www.notion.so/0cars/LG-Aimers-8004ecd18da442929d438e4c6f3aa84f?pvs=4) 
> ### 프로젝트 소개 및 문제 정의 
> ##### 목표: 특정 온라인 쇼핑몰의 일별 제품별 판매 데이터를 바탕으로 향후 약 3주간의 제품별 판매량을 예측하는 AI 모델을 개발함.
> ##### 문제 정의: 제품 판매량의 시계열 데이터를 분석하고, 제품의 계절성, 주기성, 판매 트렌드를 고려한 예측 모델을 구축하는 것이 주요 목표임.
> 
> ### 주요성과
> ##### 제품 특성 분석: 온라인 판매 채널의 특징과 시장 경제 원리를 활용하여 제품의 고유 특성을 파악함.  
> ##### 특히 상위 20% 브랜드 및 대량 판매 제품을 분석하여 파생 변수를 생성함.  
> ##### 그 외에도 대량 판매 제품 분석, 주기성 분석, 요일별 판매 추이를 활용한 파생 변수를 생성.   
> ##### 모델 설계: LSTM 모델을 사용해 제품 판매량을 예측하였고, 제품의 일별 판매량에 가중치를 적용한 RMSE 기반 Loss Function을 자체적으로 제작함.   
> ##### 수상 : LG Aimers 3기 해커톤 최우수상 수상 
> 
> ### 배운점
> ##### 데이터에서 파생 변수를 만들어 모델 성능을 개선하는 과정에서 다양한 기법을 활용해 볼 수 있었음.   
> ##### 도메인 지식의 중요성:
> 온라인 쇼핑몰 판매 데이터는 단순한 수치가 아닌, 경제 원리와 시장의 특성을 반영한다는 점을 깨달음.    
> 제품군별 특성과 주기성을 이해하는 것이 데이터 분석 및 모델링 성능을 극대화하는 데 큰 도움이 되었음.  
> ##### 맞춤형 모델링 기법의 필요성:    
> 데이터 특성에 맞춘 모델링 기법을 적용하고, 상황에 맞는 Loss Function을 개발하는 과정에서    
> 문제 해결의 유연성이 매우 중요하다는 것을 알게 되었음.  
> ##### 협업의 힘:  
> 프로젝트를 진행하며 팀원들과 긴밀히 협력해 다양한 아이디어를 반영하는 것이 성과에 큰 영향을 미쳤으며,    
> 데이터 분석 프로젝트에서 협업의 중요성을 다시 한 번 깨닫게 됨.  

------------------------------------------------

> ### [보험 관심 고객 분석을 통한 응답률 개선 프로젝트]()
> ### 프로젝트 소개 및 문제 정의 
> ##### 목표:
> 보험 상품에 관심을 보일 가능성이 높은 고객을 식별하기 위한 분류 모델을 구축
> 이를 기반으로 고객 응답률을 개선하는 전략을 도출
> ##### 문제 정의:
> 기존 고객 데이터에서 보험에 대한 관심을 나타내는 지표를 도출
> 불균형한 데이터(Imbalance)를 처리한 후, 효율적인 고객 접근 전략을 세워 응답률을 개선
> 
> ### 주요성과  
> ##### 응답률 개선: 고객 접근 채널을 변경한 후 응답 비율을 11.14%에서 19.14%로 8% 이상 개선함. 
> ##### LightGBM 기반 분류 모델: SMOTE 처리 후 LightGBM 모델을 사용하여 정확도와 응답률 예측 성능을 크게 향상시킴. 
> ##### A/B 테스트: 응답률이 높은 채널로 고객을 이동시킨 후 A/B 테스트를 진행하여 전환 효과를 확인함.
> 
> ### 배운점
> ##### 데이터 불균형 해결의 중요성:  
> SMOTE와 같은 오버샘플링 기법을 사용하여 불균형한 데이터를 처리함으로써, 모델의 성능을 크게 개선할 수 있음을 배웠습니다.
> ##### 채널별 전략적 접근의 효과:  
> 고객의 특성과 판매 채널의 응답률을 분석함으로써, 적합한 채널로 고객을 유도할 때 응답률과 전환율이 크게 향상될 수 있음을 확인하였습니다.
> ##### 모델 성능 향상을 위한 변수 선택:  
> 주요 변수를 선택하고 이를 바탕으로 지표를 생성하는 과정에서 모델의 예측 정확도를 높이는 방법을 익혔습니다.

------------------------------------------------

> ### [고객군별 소비 패턴 분석을 통한 전환 효과 분석]()
> ### 프로젝트 소개 및 문제 정의 
> ##### 목표:
> 고객 군집별 소비 패턴을 파악하여, 이탈 가능성이 높은 고객을 전환시키고 이탈률을 줄이는 것
> ##### 문제 정의:  
> 신용카드 고객 데이터를 바탕으로 고객의 가입 기간, 사용 금액 등을 분석하여 RFM 지표를 선정  
> 계층적 군집 분석을 통해 각 고객군의 소비 패턴을 파악한 후, 이를 기반으로 이탈 고객 전환 효과를 분석  
> 
> ### 주요성과  
> ##### RFM 지표 기반 전환 분석:
> RFM 지표를 활용하여 고객의 소비 패턴을 정량적으로 분석하고, 이를 통해 효과적인 전환 전략을 도출했습니다.
> ##### 계층적 군집 분석:
> 계층적 군집 분석을 통해 고객을 세분화하여 각 군집의 소비 패턴을 명확히 파악하고, 이탈 고객과의 차이를 분석했습니다.
> ##### 이탈 고객 감소:
> 기존 1627명 중 54명으로 이탈 고객을 감소시켜 이탈률을 16.06%에서 0.53%로 크게 줄였습니다.
> 
> ### 배운점
> ##### 모델 성능 향상을 위한 변수 선택:  
> RFM 지표와 같은 정량적 지표를 활용하여 고객의 소비 패턴을 평가하는 것이 효과적인 것을 알게됨. 
> ##### 군집 분석의 효과:   
> 군집 분석을 통해 고객을 세분화하여 맞춤형 전환 전략을 수립함으로써, 고객 이탈률을 크게 줄일 수 있다는 점을 배움.
> ##### A/B 테스트의 중요성:
> 데이터 기반으로 이탈 고객을 식별하고, 맞춤형 전략을 적용한 후 A/B 테스트를 통해 그 효과를 검증하는 과정이 매우 중요하다는 것을 깨달음.

------------------------------------------------
