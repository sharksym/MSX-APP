--------------------------------------------------
MMC/SD Drive(tm) V3/V4 - BIOS & Tool
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------


[ BIOS & Tool v5.76 ]

- MegaRAM

  FMPAC BIOS가 로딩된 PAC-V를 MSX-MUSIC으로 인식하는 문제 수정.
  -> FMPAC 슬롯의 우선순위가 낮으면 SOUND 포트가 OFF되는 문제입니다.
     PAC-V에 BASIC'n 롬이 로딩된 경우는 상관없습니다.


- FDD_EMU

  ONE-Drive 모드에서, FDD 슬롯 디텍션 개선.
  예: MMC/SD 포함 디스크 인터페이스가 3개 이상 동작하는 경우 등


- WAU 지원

  MegaRAM, FDD_EMU 구동 시 WAU의 DiskROM(리모트 드라이브)은 항상 OFF됩니다.
  기본적으로 WAU BIOS, SERIAL BIOS도 OFF됩니다.
  /W 옵션 사용 시, WAU BIOS 및 SERIAL BIOS가 ON상태를 유지합니다.


[ 업데이트 가이드 ]

1. MMCSD.COM, MMCSD.OVL 두개 파일을 SD카드에 복사.
   기존 파일을 덮어쓰면 됩니다.(예:UTILS 디렉토리)

2. MMCSD.COM 프로그램을 실행.

3. 'Update BIOS-ROM? [y/N]' 메시지가 나오면 Y키 누름.

4. 다운로드 완료 후 RETURN키 눌러서 재부팅.

4. 끝
