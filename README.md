# 서울 구별 아파트 값 요인 분석
## 🔥분석 동기 
서울 내 아파트 가격상승의 구체적인 원인이 무엇인지 알고 싶어서 머신러닝을 이용해서 분석해보게 되었다
## Data Collection
KOSIS(국가통계포털) , 서울 열린데이터 광장, 서울 부동산 정보광장 등에서 데이터 수집
## Data Preprocessing
* 결측치 채우기
* 데이터 type 통일
* standardization
## Model & Algorithm
![image](https://user-images.githubusercontent.com/43260658/152319405-f09585fd-9563-4602-99d4-f07060dde84c.png)  
1. K-Nearest-Neighbor  
    서울 전체 구를 k개의 그룹으로 나누어서 각 그룹에 대한 특징을 알기 위함
  
2. Random Forest Regression  
    그룹별로 진행하면서 각 그룹마다 아파트 가격에 영향을 미치는 원인들 분석 
## Result(Insight)
1. 서울 구는 크게 3개의 그룹으로 나누어 졌고 이는 정확히 각 구별 인구수 순위대로 묶였다(인구수가 많은 그룹, 중간 그룹, 적은 그룹)
2. 예상대로 그룹마다 아파트 가격에 영향을 가장 많이 미치는 원인이 각각 달랐다

## 나의 역할
* 분석을 위한 알고리즘 설계
* 데이터 수집 및 전처리
* KNN을 바탕으로 인사이트 도출
