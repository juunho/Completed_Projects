# AI 신용평가모형 기반 챗봇 서비스 구현
**대출 신청자의 상환 능력을 정확히 평가하고, 대출 거절에 따른 피드백이 가능한 새로운 개인화 대출 프로세스를 구현하였습니다.**

본 프로젝트는 하나금융그룹과 함께하였고, Python 및 Pytorch 환경에서 개발되었습니다.

</br>

<div align="center">
    <img src="https://github.com/juunho/Completed_Projects/assets/81394769/3f73d167-d45c-489f-af4b-34932d02f8f7" width="43%">
</div>

## 개요
~~~
Partner: 하나금융그룹
Date : 2022.10 ~ 2023.06
Team: 3명 (Data Scientist 2 | UX Desinger 1)

My Roles:
- 프로젝트 리딩 및 그룹사 의견 조율
- 딥러닝 기반 신용 평가 모형 구축
- 프롬프트 엔지니어링을 통한 대출 거절 피드백 주입
~~~


## 문제 정의
> 많은 대출 신청자들은 금융 이력이 부족하다는 이유로 제대로된 신용 평가를 받지 못해 대출을 거절당하고 있습니다.
> 
> 그 뿐 아니라, 거절에 대한 이유 설명과 대안 상품 추천이 이루어지지 않아 대출 과정에서 부정적인 경험을 겪고 있는 것으로 나타났습니다.

</br>


## 접근 방법

- 그래프 네트워크 기반의 신용평가 모형 개발을 통한 고객 프로파일링 정밀화

- 다각화된 XAI 기법, 대출자 간 연결 정보를 활용한 대출 거절 피드백 구현

- 대화형 AI 프롬프트 엔지니어링을 통한 챗봇 서비스 개발

</br>


## 프레임워크

<p align="center">
  <img src="https://github.com/juunho/Completed_Projects/assets/81394769/a5b693a0-1f5f-47a0-bc6e-afd3b0b4550a" width="80%">
</p>

</br>

## 상세 내용
하나 ONE-FIT 모델 결과를 바탕으로  씬 파일러 고객 특성 추론


<p align="center">
  <img src="https://github.com/juunho/Completed_Projects/assets/81394769/ba1dbb48-9151-49bc-b981-8baf98d17d9b" width="80%">
</p>

</br>

## 성과
그룹 서비스 ‘하나원큐’에 적용 가능한 대출 거절 피드백 챗봇 개발
그룹사 내 대안 상품 추천을 통한 고객 락인(Lock-In) 효과

## 개선 방향
