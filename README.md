# 국내 외국인 범죄자의 현황_데이터 분석 (작성 중)

## 프로젝트 소개
* 배경 및 대주제
1. 코로나 이후, 국내 범죄가 줄어들고 있으나 SNS/마약 관련 범죄가 증가하는 추세, 이러한 사회 현상에 따라 변화하는 범죄추이 및 범죄유형을 분석하여 범죄의 예방 대책을 수립하기 위해 해당 프로젝트를 진행하게 됨
2. 범죄 발생량 현황과 요인 분석


* 소주제
1. CCTV 
2. 국내에서 발생한 외국인 범죄 현황 분석 
3. 서울시 구별 범죄발생량 통계 분석 & 유동인구와 범죄발생률의 관계성 


* 인원: 4명
* 역할: 소주제(2) 국내에서 발생한 외국인 범죄 현황 분석
* 개발 기간: 23.02.07-10
<br>

**분석 방향 및 목표는 아래와 같다.**
1. 소주제에 따른 분석 결과 및 인사이트 도출
2. 분석 종합 후 결론 도출
<br>

## 작업 순서
* 데이터 분석
  * 전처리
  * 분석 및 시각화
  * 인사이트 도출
* 종합 결론
 
 <br>

## 데이터 구조

* [데이터 출처](https://data.seoul.go.kr/dataList/321/S/2/datasetView.do) : 서울 열린데이터 광장
* 분석 기간: 2015 ~ 2021 
* 범위: 서울시
* 외국인_범죄현황.csv
* 서울시 외국인 범죄의 범죄유형별 현황


* 'CrimeDF2'   

|항목명|항목설명|데이터타입|
|------|---|---|
|시점|2015-2021|int64|
|살인||int64|
|강도||int64|
|절도||int64|
|폭력||int64|
|지능범|각종문서위·변조,공정증서원본불실기재, 사기, 횡령, 통화위조 등|int64|
|성범죄||int64|
|마약류||int64|

* 'TotalDF'   

|항목명|항목설명|데이터타입|
|------|---|---|
|시점|2015-2021|int64|
|합계|전체 범죄 유형의 합|int64|




<br>

## 기술 스택
#### Environment
<img src="https://img.shields.io/badge/Google Colab-F9AB00?style=for-the-badge&logo=Google Colab&logoColor=white"/> <img src="https://img.shields.io/badge/windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"/>
 
<br>
  
## Prerequisite

import pandas as pd   
import matplotlib.pyplot as plt         
from matplotlib import font_manager, rc

<br>

---
<br>

## 목차
1. [사용법](#사용법)
3. [결과](#결과)
4. [배운점 & 아쉬운 점](#배운점-&-아쉬운-점)
5. [이후의 계획](#이후의-계획)
<br>

## 사용법

* '외국인_범죄현황.csv' 파일 불러오기

```
import pandas as pd

# 1. 국내에서 발생한 외국인 범죄 통계 자료
FILE1 = '외국인_범죄현황.csv'
CrimeDF=pd.read_csv(FILE1)
```


<br>

## 결과
1. 데이터 분석
* 마약류는 코로나 시점과 관계없이 꾸준히 증가하는 추세이다.
* 범죄 유형 중 마약류 범죄 증가하는 것으로보아 국내에서 마약의 수요와 공급이 잘 이루어지는 것으로 보임

![image](https://user-images.githubusercontent.com/122415320/235565134-b6578f28-aea2-4b4a-89b8-4f803381d05e.png)


<br> 


2) 코로나 이전/이후 시점의 범죄율 추세 그래프 확인

* 코로나 이전 - 전체 범죄량이 증가 혹은 평균을 유지함
* 코로나 이후 - 전체 범죄량 급격히 감소
* 단기 체류하는 외국인의 범죄량이 높지 않고 장기 체류하는 외국인의 범죄가 높을 것이다.

![image](https://user-images.githubusercontent.com/122415320/235565143-aab559b3-fe57-44a4-9657-521eac31d012.png)



## 배운점 & 아쉬운 점
<br>
  

<br>


## 이후의 계획

<br>
