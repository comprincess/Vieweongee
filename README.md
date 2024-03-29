# 🦉 뷰엉이 - 온라인 면접 스터디 서비스 
#### SSAFY 8기 공통프로젝트 - 웹 기술
![타이틀이미지](./exec/images/logo.png)

<!-- 필수 항목 -->

## 🦉 **뷰엉이** - 개요
    "면접스터디가 처음이다! 그라운드 룰 정하는 시간이 아깝다!, 스터디장이 부담스럽다!"

**뷰엉이가 해결해드립니다.**

**'뷰엉이'는 면접 프로세스를 자동으로 제공하고, 스터디 피드백을 아카이빙해주는 온라인 면접 스터디 플랫폼입니다.**

## 🦉 **뷰엉이** - 주요 기능


#### 1. 면접 스터디 모집
![스터디글작성](./exec/captures/스터디글작성.png)
- 스터디 모집 게시판에서 원하는 기업/직무의 스터디 모집
- 기본으로 제공되는 채점표 확인 가능

#### 2. 면접 스터디 신청
![스터디상세조회](./exec/captures/스터디상세조회.png)
- 원하는 스터디 신청 후, 자기소개서 파일 업로드

#### 3. 화상 미팅 참석
- 마이페이지 참여 예정 스터디 - 참여 버튼으로 입장

#### 3-1. 면접관/면접자 자동 전환
![면접순서지정](./exec/captures/화상미팅_순서저장.png)
- 면접관/면접자 역할 자동 설정 및 변경

#### 3-1. 채점 및 피드백 작성
![면접순서지정](./exec/captures/화상미팅_자기소개서.png)
- 면접관은 면접자의 자기소개서와 채점표를 보며 채점, 피드백 가능

#### 4. 면접 스터디 피드백 아카이빙
#### 4-1. 누적 점수 기록
![마이페이지메인](./exec/captures/마이페이지메인.png)
- 면접자는 받은 피드백을 마이페이지에서 확인 가능 (회차별/역량별 통계)

#### 4-2. 면접 스터디 피드백 아카이빙 - 누적 피드백 기록
![마이페이지데이터](./exec/captures/마이페이지_data.png)
- 참여했던 스터디들의 정보 확인
- 'Data' 탭에서 참여 스터디의 개별 피드백 조회

## 개발 환경

| Application | Domain | Language | Front | Back | DB |
| ---- | ---- | ---- | ---- | ---- | ---- |
| Desktop Web | WebRTC | JavaScript, Java | Vue | Spring Boot | MySql |

### **Frontend**
- Language : JavaScript, HTML, CSS
- Framework : Vue.js, Vuex


### **Backend**
- Language : Java
- Framework : Spring Boot
- DB : MySQL
- Server : AWS EC2, Nginx
- WebRTC : openvidu
- CI/CD : Docker, Jenkins


### **주요 기술**
  - WebRTC
  - JWT Authentication
  - REST API

### **참조 리소스**
  * Vuetify: 디자인 전반 적용
  * Vue Argon Design System: 디자인 전반 적용
  * Vue Black Dashboard Pro(유료): 캘린더 컴포넌트 사용
  * AR Core: 구글에서 제공하는 AR 지원 라이브러리. 이미지 인식 및 오버레이 영상에 활용
  * Color Thief: 이미지 색상 추출 라이브러리. 커버 사진 색상 추출 및 배경 변경에 활용
  * Animation.css: CSS 애니메이션 지원 라이브러리. 메인 페이지 진입 애니메이션에 활용

* 배포 환경
  - URL: https://vieweongee.kro.kr:
  - 테스트 계정: ID-test / PW-test, 소셜 로그인 (네이버, 카카오)


<!-- 자유 양식 -->

## 팀 소개
  * 민동주: **팀장**, 백엔드 개발, 기술 고문

  * 강윤주: 프론트엔드 개발, UX/UI

  * 박은정: 프론트엔드 개발, 디자인

  * 이리나: 백엔드 개발, Git 관리

  * 이윤주: 백엔드 개발, 문서 관리

  * 함정빈: **부팀장**, 백엔드 개발, Jira 관리

### 그라운드 룰
    - 몰라도 수줍어하지 않고 물어보기
    - 매일 본인이 한 일 업데이트 하기
    - 개인 일정 미리 공유하기
    - 코어타임(pm. 10~11) 연락 꼭 확인
    - 못하겠으면 못한다고 말하고, 대안 생각하기
    - 컨디션 관리 잘 하고 너무 무리하지 않기

## 프로젝트 산출물
- [기능명세서](./exec/기능명세서.md)
- [와이어프레임](./exec/와이어프레임.md)
- [API 명세서](./exec/API명세서.md)
- [시스템 구성도](./exec/시스템구성도.md)
- [ERD](./exec/ERD.md)


## 컨벤션
- [코드 컨벤션](./exec/코드컨벤션.md)
- [Git 컨벤션](./exec/깃컨벤션.md)



