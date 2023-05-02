# 국내 외국인 범죄자의 현황_데이터 분석

## 프로젝트 소개
* 대주제
코로나 이후, 국내 범죄가 줄어들고 있으나 SNS/마약 관련 범죄가 늘어나고 있는 추세이다.    
이러한 사회 현상에 따라 변화하는 범죄 및 범죄율을 분석하고 개선할 수 있는 방법을 고민하기 위해 해당 프로젝트를 진행   

* 소주제
1. CCTV 
2. 국내에서 발생한 외국인 범죄 현황 분석 
3. 
4. 


* 인원: 4명
* 역할: 기획, 데이터 전처리 및 분석
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

* [데이터 출처]()
* 2018.01 ~ 2023.04 의 구글 플레이 앱 스토어 리뷰 크롤링
* 외국인_범죄현황.csv

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

* '외국인_범죄현황.csv' 소스 파일 다운로드

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
* 범죄 종류 중 마약류 범죄 증가. 마약의 수요와 공급

!![image](https://user-images.githubusercontent.com/122415320/235565134-b6578f28-aea2-4b4a-89b8-4f803381d05e.png)


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
