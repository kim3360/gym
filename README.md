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

