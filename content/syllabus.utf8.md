---
title: "Syllabus"
slug: syllabus
citeproc: false
bibliography: ../static/bib/references.bib
csl: ../static/bib/chicago-syllabus-no-bib.csl
---




# 스터디 목표

<span class="newthought">본 `Rstudy2020` 스터디는 </span> 선형회귀분석을 가지고 변수들 간의 관계를 측정 및 해석하는 통계기법을 살펴보는 것을 목적으로 한다. 구체적으로 `R`에 관한 기본적인 작동 원리 및 코딩을 위한 팁 등을 함께 살펴보며, 나아가 통계학적 기본 지식들(확률, 분포, 추론 등)에 대한 리뷰 및 유의성 검정, 최소자승법(ordinary least squres, OLS)을 이용한 선형회귀모형 추정에 관한 내용들을 개략적으로 훑어볼 것이다. 

만약 시간이 허락한다면, 비연속적 종속변수를 추정하기 위한 일반화 선형모형(generalized linear models, GLM)과 어떤 통계 모형을 사용할 것인지에 관한 선택의 문제(모델 진단, 모델 선택 과정, 결측치 문제)도 함께 다루어 볼 것이다. 이 스터디는 단순히 통계학적 지식을 이론적으로 학습하기보다는 재생산 가능한 자료를 이용하여 `R`을 이용한 통계분석 및 프로그래밍을 실습하고, 나아가 그 분석 결과를 실제 활용할 수 있는 방식으로 보여줄 수 있는 능력을 함양하는 데 목적이 있다. 

스터디를 마치게 되었을 때, 구성원들은 선형 회귀를 이용하여 경험적 관계를 평가하고, 이후 보다 고급 통계 모델 및 기법들을 이해하는 기초를 마련할 수 있게 될 것으로 기대한다.

이 스터디는 `R`을 사용하기 위한 컴퓨터를 필요로 하며, 정기적으로 [*Zoom*](https://us02web.zoom.us/j/9013379527?pwd=akhTd0poRnNudUt5OGovejlWcW91QT09)을 통한 온라인 미팅을 실시한다. 스터디는 다음과 같은 주교재를 중심으로 운영된다:

  + Fox Jr., John. 2016. [*Applied Regression Analysis and Generalized Linear Models, Third Edition*](https://www.dropbox.com/s/x4h76g5j3657m3w/John%20Fox%20-%20Applied%20Regression%20Analysis%20and%20Generalized%20Linear%20Models.pdf?dl=0). Thousand Oaks, CA: SAGE Publications.

`R`은 프로그래밍 언어이면서 컴퓨팅과 그래픽을 통해 통계적 분석을 할 수 있도록 하는 환경이라고 할 수 이다. `R` 과 관련된 자료는 다음의 링크롤 통해 확인할 수 있다.

  + `R` 다운로드: https://www.r-project.org/.
  
  + `RStudio`는 `R`이라는 프로그래밍 언어를 좀 더 사용자 친화적인 방식으로 제공하는 인터페이스이다: https://rstudio.com/products/rstudio/download/


이외에 통계학 이론에 관해서는 다음의 자료를 참고한다.

  + Jeffrey M. Wooldridge. [*Introductory Econometrics: A Modern Approach, 5th (or later) edition*](https://www.dropbox.com/s/iq7hyck25xji1mv/Jeffrey%20M.%20Wooldridge-Introductory%20Econometrics_%20A%20Modern%20Approach-South-Western%20College%20Pub%20%282012%29.pdf?dl=0). Cengage Learning.

  + Andrew Gelman and Jennifer Hill. 2007. [*Data Analysis Using Regression and Multilevel  Hierarchical Models*](https://www.dropbox.com/s/1xa7l5l60x0hfgh/Andrew%20Gelman%20-%20Data%20Analysis%20Using%20Regression%20and%20Multilevel_Hierarchical%20Models-Cambridge%20University%20Press%20%282008%29.pdf?dl=0). Cambridge University Press.

`R` 프로그래밍 및 코딩과 관련된 자료는 아래를 참고할 것을 권한다.

  + Hadley Wickham and Garrett Grolemund. [*R for Data Science*](https://r4ds.had.co.nz/)

  + Hadley Wickam. [*Advanced R 2nd Edition*](https://adv-r.hadley.nz/)

  + Hadley Wickam. [*ggplot2: Elegant Graphics for Data Analysis*](https://ggplot2-book.org/)

[^courseinfo]: {-}
  preservee88ab6c3ec703d2d


<span class="newthought">스터디를 통해 구성원들은 다음과 같은 성과를 얻을 것으로 기대한다:
  1. `R`을 이용해 데이터를 불러오고, 변형하여 통계적 검정을 수행하고, 나아가 선형모델을 추정할 수 있게 될 것이다.
  
  2. OLS 접근법의 가정들을 이해하고, OLS를 통해 얻은 결과를 해석할 수 있게 될 것이다.
  
  3. 모델 특정(specification), 혹은 모델 특정(misspecification)의 오류와 관련된 문제들을 진단하고, 바로잡을 수 있게 될 것이다.
  
  4. 모델 특정과 연구설계(research design)에 관련하여 제기될 수 있는 문제들을 설명할 수 있게 될 것이다.


    
## 논문 및 기타 참고자료

주마다 참고할 만한 리딩자료는 드랍박스의 `Textbook` 폴더에, 스터디에 활용할 슬라이드 자료는 `Documents (Slides)` 폴더에 주차별로 추가될 예정이다. 또한, [R Weekly newsletter](https://rweekly.org/)를 구독할 것을 추천하는데, 매우 유용한 튜토리얼과 **R**에 관련된 자료들이 주마다 메일로 제공된다.