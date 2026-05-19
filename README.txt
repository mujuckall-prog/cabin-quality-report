# 객실품질심사원 현장시정 보고서 PWA

## 사용 방식
이 패키지는 iPhone/Android/PC에서 URL 접속 후 앱처럼 사용할 수 있는 PWA 구조입니다.

## 파일 구성
- index.html: 보고서 작성 화면
- manifest.json: 앱 설치 정보
- service-worker.js: 캐시/오프라인 실행 보조
- icons/: 홈 화면 아이콘

## iPhone 사용 조건
로컬 파일 앱에서 직접 열면 버튼 기능이 제한될 수 있습니다. 반드시 HTTPS 웹주소로 접속해야 합니다.

## 배포 예시
1. 이 폴더 전체를 사내 웹서버, GitHub Pages, Netlify, Cloudflare Pages 등에 업로드
2. Safari에서 배포 URL 접속
3. 공유 버튼 → 홈 화면에 추가
4. 생성된 아이콘으로 실행

## 주의
Service Worker와 PWA 설치 기능은 일반적으로 HTTPS 주소에서 정상 동작합니다.
