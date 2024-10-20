--------------------------------------------------
MMC/SD Drive(tm) V3/V4 - BIOS & Tool
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------


[ BIOS & Tool v5.75 ]

- MMC/SD BIOS

  MMCSD Tool에 BIOS 롬이 내장됨. (MMCSD.OVL에 포함)
  -> 기기와 Tool의 BIOS 버전이 차이나는 경우,
     옵션없이 MMCSD.COM을 실행하면 BIOS 업데이트가 진행됨.
     '/U' 옵션으로 강제 업데이트도 가능함.


- SUB-ROM

  롬 다운로드 시, 최대 28문자의 제목을 추가 가능.
  -> '/S' 대신 '/S:' 옵션 사용.
     예) MMCSD RC749.ROM /S:THE_MAZE_OF_GALIOUS


[ 업데이트 가이드 ]

1. MMCSD.COM, MMCSD.OVL 두개 파일을 SD카드에 복사.
   기존 파일을 덮어쓰면 됩니다.(예:UTILS 디렉토리)

2. MMCSD.COM 프로그램을 실행.

3. 'Update BIOS-ROM? [y/N]' 메시지가 나오면 Y키 누름.

4. 다운로드 완료 후 RETURN키 눌러서 재부팅.

4. 끝
