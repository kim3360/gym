## React Native 환경 설정 

## 리액트 네이티브 라이브러리
### 📌1. 네비게이션
- react-native-screens : 네이티브 화면 성능 최적화
- @react-navigation/bottom-tabs : 	Bottom Tab Navigation (하단 탭)

### 📌2. API 요청 및 데이터 관리
- react-query : API 데이터 캐싱 및 관리 
- axios : API 요청 라이브러리

### 📌3. UI 컴포넌트 및 스타일링
- react-native-vector-icons : 아이콘 라이브러리
- tailwind-rn : Tailwind CSS 스타일링

### 📌4. 파일 시스템 및 권한 관리
- react-native-permissions : 앱 권한 관리 (카메라, 위치 등)
- react-native-maps : 지도 기능 (Google Maps, Apple Maps)
## 📂 프로젝트 폴더 구조

```plaintext
/src
 ├── components/   # 재사용 가능한 UI 컴포넌트
 ├── screens/      # 앱 화면 (페이지)
 ├── layout/       # 공통 레이아웃 관련 컴포넌트
 ├── navigation/   # React Navigation 설정
 ├── hooks/        # 커스텀 훅 (상태 관리, API 요청 등)
 ├── contexts/     # Context API 관리 (예: 테마, 인증)
 ├── services/     # API 호출 및 비즈니스 로직
 ├── assets/       # 이미지, 폰트, 아이콘, 로고 등 정적 파일
 ├── utils/        # 유틸리티 함수 모음
 ├── styles/       # 전역 스타일 정의
 ├── App.tsx       # 앱의 진입점 (최상위 컴포넌트)
 └── index.tsx     # 앱 실행 (React Native 엔트리 포인트)
```

## 📝 Git Commit 컨벤션

커밋 메시지는 아래의 형식을 따른다.

| 태그      | 설명 | 예시 |
|-----------|---------------------------------|-----------------------------------|
| `feat`    | 새로운 기능 추가               | `feat: 로그인 기능 추가` |
| `fix`     | 버그 수정                      | `fix: 로그인 예외 처리 버그 수정` |
| `refactor`| 코드 리팩토링 (기능 변경 없음) | `refactor: 로그인 처리 로직 개선` |
| `perf`    | 성능 개선                      | `perf: API 응답 속도 최적화` |
| `style`   | 코드 스타일 변경 (포맷팅 등)   | `style: 코드 포맷 적용 (Prettier)` |
| `docs`    | 문서 수정 (README, API 명세)  | `docs: API 명세 업데이트` |
| `test`    | 테스트 코드 추가/수정          | `test: JWT 인증 테스트 케이스 추가` |
| `chore`   | 패키지 관리, 기타 잡다한 수정  | `chore: eslint 규칙 업데이트` |
| `comment` | 주석 추가/수정                 | `comment: 불필요한 주석 제거` |
| `hotfix`  | 긴급 패치                      | `hotfix: 서버 Timezone 설정 변경` |
| `rename`  | 파일/클래스 이름 변경         | `rename: UserController -> AuthController 변경` |
| `remove`  | 불필요한 코드/파일 삭제       | `remove: 사용하지 않는 DTO 제거` |
| `build`   | 빌드 시스템 변경               | `build: Webpack 설정 업데이트` |
| `ci`      | CI/CD 설정 변경                | `ci: Github Actions workflow 추가` |
| `security`| 보안 관련 수정                 | `security: JWT 토큰 검증 강화` |
| `deps`    | 의존성 업데이트                 | `deps: react-router-dom 최신 버전으로 업그레이드` |




### SEMBOT - 사내 규정 챗봇 서비스

<div align="center">
  <h1>SEMBOT - 사내 규정 챗봇 서비스</h1>
  <p>🔍 LLM 기반 사내 규정 챗봇 서비스 🔍</p>
</div>

<br/>

<div align="center">
  <img src="./assets/Main.png" alt="Main" style="border-radius: 10px;"/>
</div>

<br/>

<div align="center">
  <a href="">홈페이지</a>
    |  
  <a href="">Swagger</a>
</div>

---

## ✍️ 프로젝트 개요

- **프로젝트명:** SEMBOT
- **프로젝트 기간:** 2024.10 ~ 2024.11.19
- **프로젝트 형태:** 기업 연계 프로젝트
- **목표:** 기존 키워드 기반 챗봇의 한계를 극복하고, 사내 업무 규정 및 절차에 대한 정확하고 유연한 정보를 제공하는 LLM 기반 챗봇 서비스 개발
- **주요 타겟 사용자:** 사내 직원 

---

## ✍️ 프로젝트 소개

### 프로젝트 배경

사내에서 업무 절차 및 규정을 확인하는 기존 프로세스는 다음과 같은 문제점이 있었습니다:

1. **비효율적인 정보 탐색** 

2. **기존 챗봇의 한계** 

3. **규정 관리의 비효율성** 

**SEMBOT**은 위 문제를 해결하기 위해 LLM(Large Language Model)과 RAG(Retrieval-Augmented Generation) 기술을 활용하여 자연어를 이해하고, 최신 규정 정보를 기반으로 신뢰도 높은 답변을 제공하는 서비스입니다.

---

## 🚀 프로젝트 목표

1. **업무 효율성 향상** 

2. **사용자 경험 강화** 

3. **확장 가능성 확보** 

---

## 📌 주요 기능

### **0. 회원가입 | 로그인**

#### **회원가입**

<div align="center">
<img src="./assets/회원가입.gif" alt="회원가입" style="border-radius: 10px; width: 700px;"/>
</div>

---

## 🧑‍💻 팀원 소개

| **이름**    | **역할**        | 
|:-----------:|:---------------:|
| 이서빈      | BE/FE           | 

---

## ⚙️ 기술 스택

<table>
  <thead>
    <tr>
      <th>분류</th>
      <th>기술 스택</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>프론트엔드</td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white"/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
      </td>
    </tr>
  </tbody>
</table>


---

## 📂 문서 자료

- [포팅 메뉴얼](https://github.com/SSAFY-Sembot/Sembot/blob/develop/exec/%ED%8F%AC%ED%8C%85%EB%A7%A4%EB%89%B4%EC%96%BC.md)

---

