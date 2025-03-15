![API TEST CI](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2/api-test-ci.yaml?branch=main&label=API%20TEST%20CI&style=flat-square)

![FRONTEND CICD](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-front-office/test-ci.yaml?branch=main&label=FRONTEND&style=flat-square)

![BACK OFFICE CICD](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/test-ci.yaml?branch=main&label=BACK%20OFFICE%20CICD&style=flat-square)


![FE CICD](https://github.com/Check-Data-Out/velog-dashboard-v2-fe/actions/workflows/docker-publish.yaml/badge.svg)

![BACK OFFICE CICD](https://github.com/Check-Data-Out/velog-dashboard-v2-back-office/actions/workflows/test-ci.yaml/badge.svg)



# Velog Dashboard V2

> 해당 레포는 총 4개의 레포를 통합해서 공개하는 레포입니다.
> **`Velog Dashboard Project`**, velog의 모든 게시글, 통계 데이터를 한 눈에 편하게 확인하기
> ***https://velog-dashboard.kro.kr***

![서비스메타이미지](https://velog-dashboard.kro.kr/opengraph-image.png)
![서비스예시이미지](https://velog.velcdn.com/images/qlgks1/post/d2e824ed-2d25-4292-83ac-167efb2af50f/image.png)


## 1. HOW TO USE

- ***[velog dashboard v2 - 베타 오픈!!](https://velog.io/@qlgks1/velog-dashboard-v2-%EB%B2%A0%ED%83%80-%EC%98%A4%ED%94%88-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EA%B5%AC%EC%9D%B8)*** 글에서 그림과 같이 사용법을 확인할 수 있습니다. 


1. https://velog.io/ 에 접속해서 내 벨로그에 들어가주세요. (ex - https://velog.io/@qlgks1)
2. 개발자 도구 -> 어플리케이션 -> 쿠키 -> velog 부분에서 `access_token` 값과 `refresh_token` 값을 확인해 주세요.
3. 해당 값을 가지고 login 진행해 주시면 됩니다. 
4. 데이터 스크레이핑 batch 가 최대 30분 텀으로 루프를 돕니다. 그렇기 때문에 최초 데이터 이니셜라이징에 시간이 소요될 수 있습니다.
5. (과거 영상 주의) 영상으로 보기! -> https://youtu.be/Ab8c4kmGhQA


## 2. Local Setting (contribute)

- 아래의 3개 섹터로 이뤄져 있습니다.
- ***[api, server-side](https://github.com/Check-Data-Out/velog-dashboard-v2-api)***
- ***[fe, client-side](https://github.com/Check-Data-Out/velog-dashboard-v2-fe)***
- ***[back-office, batch, modeling](https://github.com/Check-Data-Out/velog-dashboard-v2-back-office)***
- 각 레포의 `README file` 을 참조해 주세요!
- 저희 전체 인프라 개괄도는 아래와 같습니다. 

![인프라 이미지](https://velog.velcdn.com/images/qlgks1/post/8b446ed9-7b56-43f7-a161-e5e8c562a3ef/image.png)



## 3. 참조

- [velog dashboard v2 - 베타 오픈!!](https://velog.io/@qlgks1/velog-dashboard-v2-%EB%B2%A0%ED%83%80-%EC%98%A4%ED%94%88-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EA%B5%AC%EC%9D%B8)
- [velog dashboard v2 - 딸깍으로 전체 통계 보기](https://velog.io/@qlgks1/velog-dashboard-v2-%EB%94%B8%EA%B9%8D%EC%9C%BC%EB%A1%9C-%EC%A0%84%EC%B2%B4-%ED%86%B5%EA%B3%84-%EB%B3%B4%EA%B8%B0)
- (과거글, vd v1)[velog dashboard 제작기 (1) - 벨로그 통계를 편하게 보고 싶어요 ㅠ](https://velog.io/@qlgks1/velog-dashboard-%EC%A0%9C%EC%9E%91%EA%B8%B0-%EB%B2%A8%EB%A1%9C%EA%B7%B8-%ED%86%B5%EA%B3%84%EB%A5%BC-%ED%8E%B8%ED%95%98%EA%B2%8C-%EB%B3%B4%EA%B3%A0-%EC%8B%B6%EC%96%B4%EC%9A%94-%E3%85%A0)