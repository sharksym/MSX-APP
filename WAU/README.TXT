--------------------------------------------------
WAU(tm) - BIOS & Tool
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------


[ BIOS & Tool v1.01 ]

첫 릴리스입니다.


[ 업데이트 가이드 ]

1. WAU.COM, WAU_BIOS.ROM 두개 파일을 디스크에 복사.
   기존 파일을 덮어쓰면 됩니다.(예:UTILS 디렉토리)

2. WAU WAU_BIOS.ROM 명령 실행.

3. 다운로드 완료 후 재부팅.

4. 끝



[ 사용예 ]

- 무선 AP 설정
  검색된 AP 리스트가 표시되어 접속할 수 있습니다.
  Time zone도 함께 설정됩니다.
  WAU /W 명령 사용
  
- RTC 시각을 SNTP 서버와 동기화.
  WAU /T 명령 사용

  AUTOEXEC.BAT에 명령을 넣을 때는 /Q 옵션을 활용하세요.
  WAU /T /Q

- LPT-UART 드라이버
  DOS 및 BASIC에서 프린터 출력 시, WAU의 USB-UART가 동작합니다.
  WAU /LPT 명령 사용

- AUX-UART 드라이버
  DOS의 AUX 디바이스를 WAU의 USB-UART로 설정합니다.
  WAU /AUX 명령 사용

- sharksym github의 MSX-APP 다운받기
  WAU /A 명령으로 앱의 리스트를 확인합니다.

  MMCSD 툴을 다운받으려면, 아래처럼 입력합니다.
  WAU /A:MMCSD

- PC 리모트 드라이브 연결
  PC Windows에 WAU Server가 실행된 상태에서, 리모트 드라이브를 연결합니다.
  PC의 IP 주소를 /D 옵션으로 설정합니다.
  예) WAU /D:192.168.0.101

- http 및 https로 데이터 다운받기
  받을 URL을 /G 옵션으로 설정합니다.
  예) WAU /G:https://www.msx.com/FILE.BIN

- USB-UART로 파일 다운받기
  USB-C 케이블을 연결하여, PC에서 MSX로 파일을 전송합니다.
  PC에서 MSX_FX 프로그램을 실행하여 송신을 설정합니다.
  그 후, MSX에서 WAU /RX 명령을 실행하면 파일 수신이 진행됩니다.

