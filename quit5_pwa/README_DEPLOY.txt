금연 5분 전환 — PWA 배포 안내
==================================
이 폴더를 그대로 웹서버(정적 호스팅)에 업로드하면, iOS/Android에서
"홈 화면에 추가"로 앱처럼 설치할 수 있습니다. (오프라인 지원)

A) GitHub Pages
---------------
1) GitHub 새 저장소(ex. quit5) 만들기
2) 이 폴더의 모든 파일을 저장소 루트에 업로드
3) Settings → Pages → Deploy from branch → main / root
4) 주소 예: https://<username>.github.io/quit5/
5) Safari/Chrome에서 열기 → 공유 → '홈 화면에 추가'

B) 내 도메인 연결 (myfunnyvalenfile.com)
---------------------------------------
- 사용 중인 호스팅(Nicepage 또는 GitHub Pages)에 /quit5 경로로 이 폴더 업로드
- 접속: https://myfunnyvalenfile.com/quit5/
- iOS Safari: 공유 → '홈 화면에 추가'

로컬 테스트(선택)
-----------------
- Mac/PC에서 터미널: python -m http.server 8080
- 브라우저 http://localhost:8080 접속
