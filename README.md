# UIA × 서울관광재단 온라인 3D 컨퍼런스 플랫폼 (2020)

[![Watch the video](assets/virtual_seoul2.gif)](https://wclf2021.miceworld.or.kr/)

> 26개국 대상, DAU 3000~5000명 웹 기반 국제 행사 플랫폼 


## Tech Stack

Expressjs, Socket.io, Reactjs, Babylon.js, MySQL   
AWS (EC2, RDS, S3, CloudFront)


## Role & Responsibility

- Express.js 기반 REST API 구현
- 유저 인증 인가 기능 구현
- MySQL 데이터베이스 관리
- 소켓 기반 푸시 알림 구현
- React 웹페이지 개발
- Webpack, Babel 환경 커스텀
- 사이트 최적화 (Webpack, Code Splitting, Lazy Load, SWR, CDN) 
- 브라우저 호환성 검사 (Chrome, Safari, Firefox, MS Edge, IE11)
- 반응형 디자인 (모바일 기기, 태블릿 지원)
- 유저, 컨텐츠 로깅 & DB 로그 산출
- 컨텐츠 영문 번역
- 외국인 유저 기술 지원 & 상담

> 프로젝트 관리는 지라 보드를 사용했습니다.   
> 메인 개발자로 참여했고, 지라 이슈 총 325개 중 146개를 완료했을만큼 성실히 임했습니다. (실무자 4명)

![jira](assets/jira3.jpg)



## Project Description

[국제협회연합(UIA)](https://uia.org/) [서울관광재단(STO)](http://www.sto.or.kr/english/index)의 온라인 컨퍼런스 플랫폼입니다.   
행사장 3D UI, 라이브와 비디오 스트리밍, 맴버십 카드, 스탬프 등 여러 서비스를 제공합니다.

- 개발 기간: 2020.06 ~ 2020.09
- 유지보수 기간: 2020.09 ~ 2021.04
- Daily Active User: 3,000 ~ 5,000
- 접속 국가: 26개의 국가
- 브라우저: Chrome, IE, Firefox, Safari, Edge



## Demo

#### [아리랑뉴스 소개](https://www.youtube.com/watch?v=ksBnRT1f2Ak&t=2s)  

[![Watch the video](assets/news.jpg)](https://www.youtube.com/watch?v=ksBnRT1f2Ak&t=2s)


#### 데모 영상

- [서울맵](https://www.youtube.com/watch?v=gk_nKkCsTk4)
- [라이브 스트리밍](https://www.youtube.com/watch?v=8vVmP6UIFrc)
- [화상 채팅](https://youtu.be/PVcj9uIvixo)


## Main features

### Video chat

![assets/many_to_many_video_chat.png](assets/video_chat.jpg)

### Stamp Event

![stamp_tour.png](assets/stamp_tour.png)

### 3D Virtual Seoul tour

![virtual_seoul.png](assets/virtual_seoul.png)

### Live And VOD Streaming

![streaming](assets/live_streaming.jpg)

### Seoul Membership Card Event

![membership.png](assets/membership.png)



# Achievement

### 이후 수주 성과
온라인 행사 솔루션 기업으로 진출하는 발판이 되었고, B2B 클라이언트 온라인 플랫폼을 연이어 개발하게 되었습니다.

이후 클라이언트
- [IOHA2021 국제 온라인 학술대회 & 전시회](https://ioha2021conference.org/)
- [유네스코 국제 3D 온라인 컨퍼런스](https://iclc2021.govent.io/)
- [한국병원협회 온라인 컨퍼런스 & 전시회](https://khc2020.salin.co.kr) 
- [지멘스 온라인 컨퍼런스 & 전시회](https://siemens-evavconference.govent.io) 
- Asia TEFL 국제 온라인 컨퍼런스
- 인천국제공항공사 온라인 컨퍼런스
- 티맥스소프트 온라인 홍보관

### 기술 성과

#### 오픈소스 라이브러리 제작
프로젝트를 진행하며 받은 동기로 리액트 오픈소스를 제작하였습니다. [Crontab library](https://www.npmjs.com/package/reactjs-crontab)
프론트엔드에서 Crontab (Job Scheduling) 기능이 필요로 했는데, 다른 앱에서도 필요할 거라고 생각했고 오픈소스 형태로 제작해 NPM 커뮤니티에 기여하였습니다.   
최대 주 다운로드 수: 3000회   
지금은 관리하고 있지 않습니다.

#### 컴포넌트 모듈화
재사용 가능한 컴포넌트를 모듈화하여 여러 애플리케이션에서 사용함으로서 작업 공수를 줄이고 유지보수를 용이하게 했습니다.


## 소스코드 관련 안내
회사 보안 정책상 코드는 공개할 수 없습니다. 양해 부탁드립니다.
