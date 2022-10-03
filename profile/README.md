
# 🍇[포도알] 극장 좌석 리뷰사이트🍇


## 🎉 포도알 소개 | About WEat

### 극장 좌석?! 좋은 자리는 없는 상태에 최선의 선택은?
![KakaoTalk_20221003_034649228](https://user-images.githubusercontent.com/109055420/193470896-90e12165-8d97-4437-becd-624c4b39415a.png)

👉 나만 알고 있던 좋은 좌석이나 꿀 같은 좌석을 공유하고 싶으신 분! </br>
👉 키 큰 사람도 키 작은 사람도 공연이 다 보이는 자리를 공유하고 싶으신 분 !</br>
👉 극장 좌석이 어떻게 보일지 모르겠다면 포도알에서 확인하세요! </br>

- 포도알은 숨겨진 꿀 자리나 최선의 좌석 선택을 도울 수 있는 웹 사이트 입니다.

### 🌎 웹사이트 | Website  [포도알 바로가기](https://podoal.net)


<br>

## 🔭목차 | Contents
1. [개발기간 | Project Period](#-개발기간--project-period)
2. [아키텍쳐 | Architecture](#-아키텍쳐--architecture)
3. [주요 API 기능 | Main API](#-주요-api-기능--main-api)
4. [개발환경 | Development Enviornment](#-개발환경--development-environment)
5. [라이브러리 | Library](#-라이브러리--library)
6. [ERD](#-erd)
7. [기술적 챌린지 | Trouble shooting](#-기술적-챌린지--trouble-shooting)
8. [백엔드 팀원 | BE TEAM](#-백엔드-팀원--be-team)
9. [More Info](#-more-info)
<br>



## ⌚ 개발기간 | Project Period
2022.08.26 ~ 2022.10.03 (6주간)

<br>

## 🛠 아키텍쳐 | Architecture
![KakaoTalk_20221003_032628588](https://cdn.discordapp.com/attachments/457223932244656128/1026435122318290994/Architecture.png)


## ⚔ 주요 기능 | Main Function
### FE
- 소셜 로그인 (트위터 / 카카오)
- 실시간 리뷰 확인 (메인 페이지 실시간 리뷰 SECTION)
- 리뷰 후기 (CRUD) / 리뷰 댓글 / 좋아요 기능 / 리뷰 페이지 무한스크롤
- 태그, 필터, 검색어를 통한 검색 기능
- 프로필 수정
- 프로필 내에서 내가 쓴 리뷰 확인
- 극장 정보 인포 MODAL (KAKAO MAP)
- 반응형

### BE
- 간편한 소셜 로그인 트위터, 카카오톡 지원
- 다양한 경우의 검색 요청 일괄 처리 (QueryDSL)
- 자주 조회하는 데이터 캐싱 처리 (Redis, Spring Cache)
- 배포된 서버의 에러 로그를 쉽게 확인 가능 (Slack Webhook, Logback)
- RefreshToken 토큰을 사용하여 로그인 정보 자동 갱신 (JWT)
- S3 스토리지에 저장되는 이미지 리사이징 처리 (Imgscalr)
- CI/CD 자동 배포 (Githib Action, S3, CodeDeploy)
- 무중단 배포 (NGINX)


## ⛏ 개발환경 | Development Environment




## 🎨 라이브러리 | Library

     "@fortawesome/react-fontawesome": "^0.2.0",
     "axios": "^0.27.2",
     "file-loader": "^6.2.0",
     "json-server": "^0.17.0",
     "moment": "^2.29.4",
     "react": "^18.2.0",
     "react-dom": "^18.2.0",
     "react-hook-form": "^7.34.2",
     "react-intersection-observer": "^9.4.0",
     "react-query": "^3.39.2",
     "react-router-dom": "^6.3.0",
     "react-scripts": "5.0.1",
     "react-select": "^5.4.0",
     "react-toastify": "^9.0.8",
     "recoil": "^0.7.5",
     "styled-components": "^5.3.5",
     "sweetalert2": "^11.4.33",
     "sweetalert2-react-content": "^5.0.3",
     "swiper": "^8.3.2",
     

    

<br>

## 🔑 ERD 

![erd](https://cdn.discordapp.com/attachments/457223932244656128/1026447296243695697/unknown.png)


<br>


## 🛠 트러블 슈팅 | Trouble shooting

<br>

## 🤸🏻‍ 팀원 | TEAM

|  ![kimhun](https://cdn.discordapp.com/attachments/457223932244656128/1026470579328520222/Untitled-3_0001_Layer-5.png) | ![RIM](https://cdn.discordapp.com/attachments/457223932244656128/1026470580913971200/Untitled-3_0000_Layer-4.png)  | ![yelim](https://cdn.discordapp.com/attachments/457223932244656128/1026470579764736050/Untitled-3_0002_Layer-6.png) | ![suweon](https://cdn.discordapp.com/attachments/457223932244656128/1026470580138016839/Untitled-3_0003_Layer-7.png) | ![yongwon](https://cdn.discordapp.com/attachments/457223932244656128/1026470580473577483/Untitled-3_0004_Layer-3.png) |![YURI](https://cdn.discordapp.com/attachments/457223932244656128/1026476377265930301/Untitled-3_0000_Layer-5.png) |
|--|--|--|--|--|--|
|  김 훈| 김휘림  | 김예림  | 박수원 | 박용원 | 김유리 |
| BE(리더) | BE | FE(부리더) | FE | FE | DESINGER |
| [🔗](https://github.com/hunkim00) | [🔗](https://github.com/kimilm)| [🔗](https://github.com/97yelim) | [🔗](https://github.com/kksltv123) | [🔗](https://github.com/ParkYongWon) |[🔗](http://yurikim.net) |
