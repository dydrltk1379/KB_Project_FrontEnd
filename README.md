# 🚀 FInNS
> 자산 관리, 금융상품 추천·비교, 커뮤니티 기능을 제공하는 금융 SNS 플랫폼의 프론트엔드

<img width="1209" height="563" alt="FInNS 대표 이미지" src="https://github.com/user-attachments/assets/36c4ee31-945a-4af9-8648-6190780337c0" />

## 🔗 Related Repository  
> **[백엔드 Repository](https://github.com/dydrltk1379/KB_project_Back)**
  
---
<br>

## 📝 1. 프로젝트 개요
FInNS는 금융상품 정보 탐색, 자산 관리, 커뮤니티 기능을 제공하는 금융 SNS 플랫폼입니다.  
본 저장소는 **FInNS의 프론트엔드 레포지토리**로, 사용자가 금융상품을 탐색하고 비교하며,  
커뮤니티에서 게시글을 작성·조회하고, 개인화된 금융 콘텐츠를 확인할 수 있도록  
**직관적인 UI/UX와 API 연동 기반 화면**을 구현했습니다.

## 🏆 2. 수상 이력
> **KB국민은행 It's Your Life 5기 부트캠프 최우수상 수상작**

---
<br>

## 📸 2. 프로젝트 시연 및 상세 설명 (8분)
[![영상 제목](https://youtube.com/_Iy-TbOYK5g?si=qVYitZqX0zQie3XZ)](https://youtu.be/_Iy-TbOYK5g?si=qVYitZqX0zQie3XZ)
> 💡 위 이미지를 클릭하면 1080p 고화질 전체 영상(유튜브)으로 연결됩니다.

---
<br>

## 🛠 3. 기술 스택
| 분류 | 기술 | 도입 목적 |
| :--- | :--- | :--- |
| 언어 | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Vue 기반 화면 로직 구현 및 사용자 상호작용 처리 |
| 프레임워크 | ![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) | 컴포넌트 기반 UI 개발 및 SPA 프론트엔드 구현 |
| 빌드 도구 | ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) | 빠른 개발 서버 실행 및 프론트엔드 번들링 |
| 라우팅 | ![Vue Router](https://img.shields.io/badge/Vue_Router-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) | 페이지 이동 및 화면 라우팅 구성 |
| 상태 관리 | ![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logoColor=black) | 인증 상태 및 전역 상태 관리 |
| API 통신 | ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white) | 백엔드 API 요청 및 응답 데이터 처리 |
| UI 스타일 | ![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat-square&logo=bootstrap&logoColor=white) ![Vuetify](https://img.shields.io/badge/Vuetify-1867C0?style=flat-square&logo=vuetify&logoColor=white) | 반응형 레이아웃 및 사용자 친화적인 UI 구성 |
| 캘린더 | ![FullCalendar](https://img.shields.io/badge/FullCalendar-000000?style=flat-square&logoColor=white) | 일정·달력 형태의 UI 구성 |
| 파일 업로드 | ![Dropzone](https://img.shields.io/badge/Dropzone-0087F7?style=flat-square&logoColor=white) | 이미지 및 파일 업로드 UI 처리 |
| 시각화 / UI 보조 | ![vue3-carousel](https://img.shields.io/badge/vue3--carousel-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![CountUp](https://img.shields.io/badge/CountUp-222222?style=flat-square&logoColor=white) | 캐러셀, 수치 애니메이션 등 사용자 경험 강화 |
---
<br>

## 👥 4. 팀 구성 및 담당 역할
**6인 팀 프로젝트 | Frontend**
- Vue 3 기반 주요 화면 구현
- Vue Router 기반 페이지 라우팅 구성
- Axios 기반 백엔드 API 연동
- 댓글 기능 및 댓글 목록 조회 구현
- 금융상품 관련 화면 데이터 연결 및 UI 구성

---
<br>

## ✨ 5. 주요 기능
### [1]. 메인 홈 - SNS 피드
금융 SNS 서비스의 메인 화면으로, 게시글을 직관적으로 탐색할 수 있는 피드형 UI를 구현했습니다.  
카드형 레이아웃과 콘텐츠 중심 화면 구성을 통해 서비스의 핵심 흐름이 자연스럽게 이어지도록 설계했습니다.

<img src="https://github.com/user-attachments/assets/2b0a001f-ef5f-4124-a738-aa72b9a22d67" width="40%">

---

### [2]. 유저 검색
사용자 검색 기능을 통해 다른 유저를 탐색하고, 관심 있는 사용자를 빠르게 확인할 수 있는 화면을 구현했습니다.  
입력과 결과 확인이 자연스럽게 이어지도록 구성해 서비스 내 탐색 경험을 강화했습니다.

<img src="https://github.com/user-attachments/assets/27c1a33a-3afe-4fe0-9f32-fb203b88591a" width="40%">

---

### [3]. 금융상품 조회 및 비교
예금, 적금, 카드 상품을 가로로 구성하여 다양한 금융상품을 한눈에 탐색할 수 있는 화면을 구현했습니다.  
상품 유형별 데이터를 직관적으로 연결하고, 정보 중심 UI를 통해 비교 흐름이 자연스럽게 이어지도록 구성했습니다.

| 예금 | 적금 | 카드 |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/9a3e0053-faa6-4623-8e99-b0084694011b" width="300"> | <img src="https://github.com/user-attachments/assets/f6c5e619-f89d-4ea1-abf6-ee256f8e260c" width="300"> | <img src="https://github.com/user-attachments/assets/5320de55-1cde-4e9a-9d6b-3726db448082" width="300"> |

---
<br>

## 🗂️ 6. 프로젝트 구조

```bash
KB_Project_FrontEnd
├── public                  # 파비콘, 정적 리소스
├── src
│   ├── assets              # 공통 이미지 및 스타일 리소스
│   ├── components          # 재사용 가능한 UI 컴포넌트
│   ├── pages               # 메인 홈, 유저 검색, 금융상품 등 화면 단위 페이지
│   ├── router              # 페이지 라우팅 설정
│   ├── store               # 인증 및 전역 상태 관리
│   ├── App.vue             # 전체 레이아웃을 구성하는 루트 컴포넌트
│   └── main.js             # Vue 앱 생성 및 초기 설정
├── index.html              # 애플리케이션 엔트리 HTML
├── package.json            # 프로젝트 의존성 및 실행 스크립트
├── vite.config.js          # 번들링 및 개발 서버 설정
└── jsconfig.json           # 경로 alias 및 개발 편의 설정
```

---
<br>

## ⚙️ 7. 실행 방법
### 📋 Prerequisites
- Node.js 18 이상
- npm 9 이상

### 🚀 Installation
프로젝트를 로컬 환경에서 실행하기 위한 기본 설치 과정입니다.

```bash
git clone https://github.com/dydrltk1379/KB_Project_FrontEnd.git
cd KB_Project_FrontEnd
npm install
```
