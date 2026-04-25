# rnd_platform
1. claude code 입문부터 고급과정까지 내용 정리 <br>
2. 관련 자료 정리

## node.js 란?
1. 정의 : javascript를 브라우저 밖(서버 등)에서도 실행할 수 있게 해주는 환경(Runtime)
- 과거에 js는 chrome, safari 등의 웹 브라우저 안에서 화면을 움직이게 하는 용도로만 쓰였으나, Node.js의 등장으로 서버 구축, DB 조작, 터미널 도구 조작 등 활용 범위가 비약적으로 넓어짐

2. 핵심 특징
- V8 엔진 기반 : 구글 크롬의 고성능 JS 엔진인 V8을 사용하여 코드 실행 속도가 매우 빠릅니다
- 이벤트 기반, 논블로킹 I/O (Event-Driven, Non-blocking I/O)
- Single Thread : 한 번에 하나의 작업 줄기만 처리하지만, None-blocking 방식 덕분에 수많은 동시 접속을 가볍게 처리할 수 있습니다
  
3. 활용 예시
- 웹 서버 및 API 개발 : Express.js나 NestJS 같은 프레임워크를 사용해 빠르고 확장성 있는 서버를 구축합니다
- 워크플로우 자동화 : 
- Front-end build tool : React, Vue 같은 현대적인 웹 라이브러리를 실행하고 빌드하는 환경 자체가 Node.js 위에서 돌아간다

## Claude 란?
- 교육 URL : https://www.youtube.com/watch?v=1_bRmkUvjHA&list=PL3o4sx7PIgDSlIkmF_ORJuPS01d94SEXE

1. Claude 기본 명령어
- Ubuntu 환경 내 
2. To-Do list
- claude는 code 생성 뿐만 아니라, 스스로 to-do list를 만드는 모델<br>
(3D 계산기 개발 예시)
- 완성했습니다. 적용된 3D 효과들:

  시각적 3D
  - 계산기 본체에 translateZ 레이어 — 두께감 있는 측면
  렌더링
  - 버튼에 box-shadow: 0 6px 0 — 눌리는 입체감
  - 버튼 누를 때 translateY(3px) 애니메이션 — 물리적
  클릭감
  - 상단/버튼마다 반사광 레이어 (::after 하이라이트)

  환경 효과
  - 원근감 있는 배경 그리드 (원근 변환)
  - 마우스 움직임에 따라 계산기가 틸트 (gyroscope 느낌)
  - 계산기가 천천히 떠다니는 float 애니메이션
  - 보라빛 파티클이 떠오르는 배경

  디스플레이
  - CRT 스캔라인 효과
  - 숫자에 네온 글로우 (text-shadow)
  - = 누를 때 플래시 펄스
 
2. CLAUDE.md 활용
- 설계 지침 저장 용도 (claude 총괄 지침 파일, 장기 기억 파일)
- /init : claude.md의 기본 틀
3. 
