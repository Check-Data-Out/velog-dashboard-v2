![API TEST CI](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-api/test-ci.yaml?branch=main&label=API%20Test%20CI&style=for-the-badge&logo=nodedotjs&color=5A9AFD)

![FRONTEND CD](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-fe/docker-publish.yaml?branch=main&label=Frontend%20CD&style=for-the-badge&logo=nextdotjs&logoColor=white&color=000000)

![BACK OFFICE CI&CD](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/test-ci.yaml?branch=main&label=Back%20Office%20CI%2FCD&style=for-the-badge&logo=python&logoColor=white&color=3776AB)

# Velog Dashboard V2

> 해당 레포는 총 4개의 레포를 통합해서 공개하는 레포입니다.
> **`Velog Dashboard Project`**, velog의 모든 게시글, 통계 데이터를 한 눈에 편하게 확인하기
> ***https://velog-dashboard.kro.kr***

![서비스메타이미지](https://velog-dashboard.kro.kr/opengraph-image.png)
![서비스예시이미지](https://velog.velcdn.com/images/qlgks1/post/d2e824ed-2d25-4292-83ac-167efb2af50f/image.png)

## 1. HOW TO USE

- **_[velog dashboard v2 - 베타 오픈!!](https://velog.io/@qlgks1/velog-dashboard-v2-%EB%B2%A0%ED%83%80-%EC%98%A4%ED%94%88-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EA%B5%AC%EC%9D%B8)_** 글에서 그림과 같이 사용법을 확인할 수 있습니다.

1. https://velog.io/ 에 접속해서 내 벨로그에 들어가주세요. (ex - https://velog.io/@qlgks1)
2. 개발자 도구 -> 어플리케이션 -> 쿠키 -> velog 부분에서 `access_token` 값과 `refresh_token` 값을 확인해 주세요.
3. 해당 값을 가지고 login 진행해 주시면 됩니다.
4. 데이터 스크레이핑 batch 가 최대 30분 텀으로 루프를 돕니다. 그렇기 때문에 최초 데이터 이니셜라이징에 시간이 소요될 수 있습니다.
5. (과거 영상 주의) 영상으로 보기! -> https://youtu.be/Ab8c4kmGhQA

## 2. Contributor

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://avatars.githubusercontent.com/u/33516349?v=4" width="48" height="48" alt="nuung" />
      <br>
      <i><a herf="https://github.com/nuung">Nuung</a></i>
    </td>
    <td align="center" width="96">
      <img src="https://avatars.githubusercontent.com/u/107257423?v=4" width="48" height="48" alt="six-standard" />
      <br>
      <i><a herf="https://github.com/six-standard">six-standard</a></i>
    </td>
    <td align="center" width="96">
      <img src="https://avatars.githubusercontent.com/u/105155269?v=4" width="48" height="48" alt="Jihyun3478" />
      <br>
      <i><a herf="https://github.com/Jihyun3478">Jihyun3478</a></i>
    </td>
  </tr>
  <tr>
    <td align="center" width="96">
      <img src="https://avatars.githubusercontent.com/u/146878715?s=64&v=4" width="48" height="48" alt="ooheunda" />
      <br>
      <i><a herf="https://github.com/ooheunda">ooheunda</a></i>
    </td>
    <td align="center" width="96">
      <img src="https://avatars.githubusercontent.com/u/154482801?v=4" width="48" height="48" alt="HA0N1" />
      <br>
      <i><a herf="https://github.com/HA0N1">HA0N1</a></i>
    </td>
    <td align="center" width="96">
      <img src="https://avatars.githubusercontent.com/u/88363672?v=4" width="48" height="48" alt="BDlhj" />
      <br>
      <i><a herf="https://github.com/BDlhj">BDlhj</a></i>
    </td>
  </tr>
</table>

## 3. Local Setting (contribute)

- 아래의 3개 섹터로 이뤄져 있습니다.
- **_[api, server-side](https://github.com/Check-Data-Out/velog-dashboard-v2-api)_**
- **_[fe, client-side](https://github.com/Check-Data-Out/velog-dashboard-v2-fe)_**
- **_[back-office, batch, modeling](https://github.com/Check-Data-Out/velog-dashboard-v2-back-office)_**
- 각 레포의 `README file` 을 참조해 주세요! (참고, 해당 레포는 `git submodule update` 으로 서브 모듈에 대한 주기적인 업데이트 필요)
- 저희 전체 인프라 개괄도는 아래와 같습니다.

![인프라 이미지](https://velog.velcdn.com/images/qlgks1/post/8b446ed9-7b56-43f7-a161-e5e8c562a3ef/image.png)

## 4. 참조

- [velog dashboard v2 - 베타 오픈!!](https://velog.io/@qlgks1/velog-dashboard-v2-%EB%B2%A0%ED%83%80-%EC%98%A4%ED%94%88-%EA%B7%B8%EB%A6%AC%EA%B3%A0-%EA%B5%AC%EC%9D%B8)
- [velog dashboard v2 - 딸깍으로 전체 통계 보기](https://velog.io/@qlgks1/velog-dashboard-v2-%EB%94%B8%EA%B9%8D%EC%9C%BC%EB%A1%9C-%EC%A0%84%EC%B2%B4-%ED%86%B5%EA%B3%84-%EB%B3%B4%EA%B8%B0)
- (과거글, vd v1)[velog dashboard 제작기 (1) - 벨로그 통계를 편하게 보고 싶어요 ㅠ](https://velog.io/@qlgks1/velog-dashboard-%EC%A0%9C%EC%9E%91%EA%B8%B0-%EB%B2%A8%EB%A1%9C%EA%B7%B8-%ED%86%B5%EA%B3%84%EB%A5%BC-%ED%8E%B8%ED%95%98%EA%B2%8C-%EB%B3%B4%EA%B3%A0-%EC%8B%B6%EC%96%B4%EC%9A%94-%E3%85%A0)

### 🔥 Daily Batch Job Status

| Batch    | Status                                                                                                                                                                                                                     |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Batch 1  | ![Batch 1](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set1.yaml?branch=main&label=Batch%201&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 2  | ![Batch 2](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set2.yaml?branch=main&label=Batch%202&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 3  | ![Batch 3](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set3.yaml?branch=main&label=Batch%203&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 4  | ![Batch 4](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set4.yaml?branch=main&label=Batch%204&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 5  | ![Batch 5](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set5.yaml?branch=main&label=Batch%205&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 6  | ![Batch 6](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set6.yaml?branch=main&label=Batch%206&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 7  | ![Batch 7](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set7.yaml?branch=main&label=Batch%207&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 8  | ![Batch 8](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set8.yaml?branch=main&label=Batch%208&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 9  | ![Batch 9](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set9.yaml?branch=main&label=Batch%209&style=flat-square&logo=githubactions&color=8A2BE2)    |
| Batch 10 | ![Batch 10](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set10.yaml?branch=main&label=Batch%2010&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 11 | ![Batch 11](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set11.yaml?branch=main&label=Batch%2011&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 12 | ![Batch 12](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set12.yaml?branch=main&label=Batch%2012&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 13 | ![Batch 13](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set13.yaml?branch=main&label=Batch%2013&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 14 | ![Batch 14](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set14.yaml?branch=main&label=Batch%2014&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 15 | ![Batch 15](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set15.yaml?branch=main&label=Batch%2015&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 16 | ![Batch 16](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set16.yaml?branch=main&label=Batch%2016&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 17 | ![Batch 17](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set17.yaml?branch=main&label=Batch%2017&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 18 | ![Batch 18](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set18.yaml?branch=main&label=Batch%2018&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 19 | ![Batch 19](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set19.yaml?branch=main&label=Batch%2019&style=flat-square&logo=githubactions&color=8A2BE2) |
| Batch 20 | ![Batch 20](https://img.shields.io/github/actions/workflow/status/Check-Data-Out/velog-dashboard-v2-back-office/run-daily-aggre-set20.yaml?branch=main&label=Batch%2020&style=flat-square&logo=githubactions&color=8A2BE2) |


### 깃헙 서브모듈 업데이트

```shell
# 1. 서브모듈 원격 최신 커밋 가져오기
git submodule update --remote --merge

# 2. 변경된 서브모듈 커밋 상태 확인
git status

# 3. 변경된 서브모듈을 상위 레포에 add
git add path/to/submodule1 path/to/submodule2 ...

# 모든 서브모듈을 한 번에 add 하려면
git add .

# 4. 커밋
git commit -m "Update all submodules to latest remote commit"

# 5. 푸시
git push
```
