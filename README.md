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
