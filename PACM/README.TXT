--------------------------------------------------
PAC-M(tm) - BIOS & Tool v1.00 (2026-06-28)
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------

[ BIOS & MSX-AID ]

- PAC-M BIOS에 MSX-AID가 통합되어 있습니다.
  PACM /U 명령으로 업데이트 가능합니다.


[ PAC S-RAM ]

- MMC/SD Drive 연동
  MMCSD.COM가 실행하는 ROM/DSK에 맞춰 S-RAM이 자동으로 설정됩니다.

- PAC 리스트
  PACM /L 명령으로 저장된 S-RAM 리스트를 표시합니다.

- PAC 임포트 (PAC 커맨더 데이터 호환)
  PACM /I 명령으로 외부 *.PAC 파일을 임포트합니다.
  예) PACM YS2.DSK /I
      YS2.PAC 파일을 YS2.DSK용 S-RAM 데이터로 로딩합니다.

- PAC 익스포트 (PAC 커맨더 데이터 호환)
  PACM /E 명령으로 S-RAM 데이터를 *.PAC 파일로 익스포트합니다.
  예) PACM YS2.DSK /E
      YS2.DSK용 S-RAM 데이터가 YS2.PAC 파일로 저장합니다.

- PAC 삭제
  PACM /D 명령으로 S-RAM 데이터를 삭제합니다.
  예) PACM YS2.DSK
      YS2.DSK용 S-RAM 데이터가 삭제되며, PAC 리스트에서 제거됩니다.

- PAC 전체 백업
  PACM /S 명령으로 전체 데이터를 백업(SAVE)합니다.
  PACM.COM 프로그램이 있는 디렉토리에 PACM.DAT(2MB) 파일로 저장됩니다.


- PAC 전체 복원
  PACM /L 명령으로 전체 데이터를 복원(LOAD)합니다.
  PACM.COM 프로그램이 있는 디렉토리의 PACM.DAT(2MB) 파일을 로딩합니다.


[ User ROM ]

- ASCII 16K (최대 4MB 롬) 및 ASCII-X 매퍼(최대 8MB 롬)을 지원합니다.
  PACM /F 명령으로 다운로드합니다.
  주의) 유저롬을 다운로드하면, 내장된 PAC 리스트가 삭제됩니다.
        PACM /S 명령으로 PAC S-RAM 데이터를 백업 후 User ROM 모드를 사용하세요.

  예) PACM ASCII16X.ROM /F

- 부팅 시, 커서 DOWN 키를 누르고 있으면 User ROM이 실행됩니다.



[ BIOS 업데이트 가이드 ]

1. PACM.COM, PACM.OVL 두개 파일을 SD카드에 복사.
   기존 파일을 덮어쓰면 됩니다.(예:UTILS 디렉토리)

2. PACM /U 실행

3. 'Update BIOS-ROM? [y/N]' 메시지가 나오면 Y키 누름.

4. 다운로드 완료 후 재부팅.

5. 끝
