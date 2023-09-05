## Data_Campus_Team_H2O
거래추적 솔루션의 시계열 성능 데이터  이상 탐지 모델

## 프로토타입 설계
![image](https://github.com/Jedo0224/Data_Campus_Team_H2O/assets/90050514/cb9de6b3-cc8b-46be-a87c-8623dec31dc6)

TPS(Total Processing Speed) 예측 및 관리, 그리고 TPS와 응답시간 간의 관계를 통한 서버 문제 감지. 이를 통해 카프카(Kafka)와 PostgreSQL을 활용한 머신러닝 모델을 구축하였으며, xgboost 알고리즘을 이용하여 이상치 탐지 및 경고 시스템을 구현하였다.

## 주 기능
1) 매 시간대에 예측 해 놓은 TPS에서 벗어나는 경우 관리자에게 경고 출력

2) TPS가 일정 수준(임계치)을 넘기면 ELPS_TIME이 급격하게 늘어나다 서버 문제 발생 후 급감하는 경향을 보임
   따라서 TPS의 크기에 따라 응답시간이 크게 증감하는 경우를 이상치로 정해서 경고 출력


## 관련 발표자료
https://docs.google.com/presentation/d/16haGfVx19PkDDDsHA6PEPNpgjt1gpxDJvUB4E1ZLp4M/edit?usp=sharing
