# 전공활용 프로젝트

프로젝트 주제 : 서울의 대중교통 사각지대 분석과 PM 도입 지역 선정



프로젝트 수행 방향 :

1. 대중교통 취약지 분석

   - 시간: 자차 대비 대중교통 이용 시간이 긴 지역 선정 

   - 접근성: 가장 근접한 지하쳘 역까지 접근성이 안 좋은 지역 선정 

   - 출발지는 서울시 동 단위로 PM보급률이 낮은 지역 중 

   - 거주 인원이 많은 지역 10개 선정

   - 도착지는 강남, 사당, 여의도, 종로와 같은 업무지구로 선정

   - 대중교통은 지하철로 제한함

2. PM 도입 가능 지역 선정을 위한 변수

   - 대중교통 이용객수 
   - 생산가능인구(20세~60세) 
   - 평균경사도
   - 공공자전거 이용자 수 대비 거치대 수 
   - 지하철 출입구와의 거리 
   - 자전거도로의 길이

3. PM 도입이 필요한 지역을 선정

4. PM 도입 지역에서 얻을 수 있는 개선 효과



담당 업무 : 지하철 보행접근가능성 / 생산인구별 교통 이용률 

# ====================================================================



### 1일차 : 데이터 수집 및 전처리

- 서울시 지하철 데이터 확보 및 서울권 내 지하철 역 전처리
- 서울시 행정동 단위 지도 시각화 json 파일 확보 및 전처리
- 서울시 행정동 단위 인구데이터 확보 ==> 전처리 필요

@@ 1일차 상황 : 현재 인구데이터 전처리가 문제 / 보행접근성을 어떻게 구할 지?



### 2일차 : 데이터 수집 및 전처리

- 서울시 행정동 단위 면적 데이터 확보
- 서울시 행정동 단위 인구데이터 전처리

@@ 2일차 상황 : 인구데이터를 지도에 적용해야하는데 오류 / 동단위 써클을 어떻게 만들지 / 써클 내 마커를 어떻게 파악할지 / 



### 3일차 : 데이터 수집 및 전처리

- 서울시 행정동 단위 써클 마커 형성
- 서울시 지하철 마커 클러스터링 형성

@@@ 3일차 상황 : 행정동 단위 지도 데이터와 인구데이터가 일치하지 않아, 경계선이 그려지지 않음 / 클러스터링은 끝냈지만 해당 숫자를 어떻게 이끌어낼지