--------------------------------------------------
WAU Terminal v1.03
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------

@ UPDATE

- ANSI Music 플레이 시, PAC-V 비주얼라이저 지원

- ANSI 파일 뷰어 모드 추가 (/F)
  텔넷 서버 주소 대신 로컬의 파일명을 입력합니다.
  SPACE 키를 눌러서 화면 스크롤을 멈출 수 있습니다.

--------------------------------------------------

@ WTERM.COM

- WAU Wi-Fi를 이용하는 터미널 프로그램입니다.


@ 요구사항: MSX-DOS2, 메모리매퍼 32KB


@ 기능

- 텔넷 접속
- ANSI 파일 뷰어
- ANSI 컬러
- ANSI 뮤직
- YMODEM 다운로드
- 스크린7 인터레이스 모드
- 스크린7 프로그레시브 모드 (CP437 전용)
- EUC-KR, CP949 한글
- 모노크롬 모니터 에뮬레이션 (앰버, 그린, 화이트)
- Vsync 50Hz/60Hz
- 로컬 에코(ECHO)


@ 단축키

STOP:  종료
SPACE: 스크롤 멈춤 (파일 뷰어 모드 전용)

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

텔넷 모드: WTERM 텔넷주소 [포트] [옵션]

포트 설정이 없으면 기본 포트(23)을 사용합니다.

예) WTERM bbs.hispamsx.org /P
    WTERM jpmud.duckdns.org 5555 /K /E


파일 뷰어 모드: WTERM 파일명 /F [옵션]

예) WTERM ansi-mus.ams /F
