--------------------------------------------------
WAU Terminal v1.01
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------

@ UPDATE

- ANSI 커맨드 개선
- 한글 입력기 추가
- 모노크롬 앰버 추가

--------------------------------------------------

@ WTERM.COM

- WAU Wi-Fi를 이용하는 터미널 프로그램입니다.


@ 요구사항: MSX-DOS2, 메모리매퍼 32KB


@ 기능

- 텔넷 접속
- ANSI 컬러
- YMODEM 다운로드
- 스크린7 인터레이스 모드
- 스크린7 프로그레시브 모드 (CP437 전용)
- EUC-KR, CP949 한글
- 모노크롬 모니터 에뮬레이션 (앰버, 그린, 화이트)
- Vsync 50Hz/60Hz
- 로컬 에코(ECHO)


@ 단축키

STOP: 종료

GRAPH + V: V-Sync 60Hz/50Hz
GRAPH + I: 인터레이스/프로그레시브 디스플레이
GRAPH + M: 모노크롬 모니터 에뮬
GRAPH + E: 로컬 에코(ECHO)
GRAPH + Y: YMODEM 다운로드

GRAPH + UP   : Page up
GRAPH + DOWN : Page down
GRAPH + LEFT : Home
GRAPH + RIGHT: End


@ 사용법

WTERM 텔넷주소 [포트] [옵션]

포트 설정이 없으면 기본 포트(23)을 사용합니다.

예) WTERM bbs.hispamsx.org /P
    WTERM jpmud.duckdns.org 5555 /K /E
