--------------------------------------------------
SLT-Turbo - BIOS & Tool
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------


[ BIOS & Tool v2.10 ]

- BIOS 롬

  GT 모드 및 X2 모드 BIOS가 통합되어 있습니다.
  SLTT /U 명령으로 업데이트합니다.


- FontPack 폰트롬

  CP949 및 Unicode 폰트를 업데이트합니다.
  FontPack v2용 8MB 폰트롬을 사용하면 됩니다.
  예) SLTT FONTPACK.ROM


- 시스템 폰트롬

  KANJI_P.FNT  -> 파나소닉 Kanji 폰트
  KANJI_S.FNT  -> 소니 Kanji 폰트
  HANGUL_D.FNT -> 대우 한글/한자 폰트
  HANGUL_J.FNT -> 둥근모 한글 및 한자 폰트

  GT 모드용 Kanji 폰트(JIS1/2)를 업데이트합니다.
  예) SLTT KANJI_P.FNT /K

  X2 모드용 한글/한자 폰트를 업데이트합니다.
  예) SLTT HANGUL_J.FNT /H



[ 업데이트 가이드 ]

1. SLTT.COM, SLTT.OVL 두개 파일을 SD카드에 복사.
   기존 파일을 덮어쓰면 됩니다.(예:UTILS 디렉토리)

2. SLTT /U 실행

3. 'Update BIOS-ROM? [y/N]' 메시지가 나오면 Y키 누름.

4. 다운로드 완료 후 재부팅.

5. 끝
