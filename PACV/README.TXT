----------------------------------------------------------------
    PAC-V Tool v1.10 (2024-06-19)
        By Yeongman Seo <sharksym@hitel.net>
----------------------------------------------------------------

* UPDATE

  SRAM/FRAM 구조가 변경되었습니다.
  FMPAC.ROM을 다운로드하면, 새로운 BIOS로 동작합니다.

  기존 Dummy BIOS 모드가 삭제되고, BASIC'n 2.1 롬이 탑재됩니다.
  참고) BASIC'n 모드에서도 PAC 카트리지로 정상 인식됩니다.

  PAC SRAM 8KB 영역이 두개로 늘어났습니다.
  부팅 시, P키를 눌러서 동작모드 및 SRAM 영역 선택이 가능합니다.
  커서 좌/우로 모드 선택 후 RETURN 키를 눌러 적용합니다.

  동작모드는 아래 4가지입니다.
  BASIC'n 2.1 [PAC SRAM #0]
  BASIC'n 2.1 [PAC SRAM #1]
  FMPAC BIOS [PAC SRAM #0]
  FMPAC BIOS [PAC SRAM #1]


* PACV.COM

  PAC-V 카트리지의 SRAM을 관리하는 프로그램입니다.
  MSX-DOS1 및 MSX-DOS2 에서 동작합니다.
  BIOS롬, LED패턴을 카트리지에 다운로드 할 수 있으며,
  파나소닉 PAC 데이터를 SAVE/LOAD 할 수 있습니다.


* 요구 사항

  PAC-V 카트리지
  MSX-DOS1 또는 MSX-DOS2


* 파일 목록

  PACV.COM     - 카트리지 관리 프로그램
  PACV.INI     - LED 패턴 (기본 수직 막대)
  PACV_1.INI   - LED 패턴 샘플#1
  PACV_2.INI   - LED 패턴 샘플#2
  PACV_3.INI   - LED 패턴 샘플#3
  README_K.TXT - 한글 설명서


* 사용법

  PACV W|P|S|L Filename [Slot[SubSlot]]

    W: FMPAC BIOS 다운로드   (영어 및 한글 패치버전 가능)
    P: LED 패턴 데이터 다운로드       (슬롯번호 생략가능)
    S: PAC 데이터 덤프 및 디스크 저장 (슬롯번호 생략가능)
    L: PAC 데이터 다운로드            (슬롯번호 생략가능)

  예) PACV W FMPAC.ROM 1
      PACV P PACV.INI
      PACV S SRAM.PAC
      PACV L SRAM.PAC


* 주의 사항

  PACV.COM 프로그램은 PAC-V 카트리지 전용 툴입니다.
  파나소닉의 PAC 및 FM-PAC 카트리지에서는 동작하지 않습니다.

  S 또는 L 커맨드로 PAC 데이터 SAVE/LOAD 시,
  현재 설정된 SRAM 8KB 영역 한개만 적용됩니다.