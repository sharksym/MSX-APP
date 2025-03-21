------------------------------------------------------------
    FontPack Tool Package (2023.03.11)
        By Yeongman Seo <email:sharksym@hitel.net>
------------------------------------------------------------

[ STARTUP.ROM, BIOS.ROM]

- 변경없음


[ FONTPACK.COM v2.01 ]

- 변경 없음


[ FontPackTool.exe v2.2 ]

- 0 문자가 사선을 포함하는 옵션을 추가 (TTF 전용)

- 원(KRW) 문자를 백슬래쉬로 바꾸는 옵션을 추가 (TTF 전용)


[ ROM 업데이트 가이드 ]

1. 윈도 FontPack_Tool 프로그램으로 ROM 생성

2. FONTPACK.COM 및 생성된 ROM을 MSX 용 디스크에 복사

3. MSX-DOS 부팅 후, FONTPACK W FILENAME.ROM 명령으로 다운로드

4. 다운로드 완료 후 시스템 리셋

5. 끝


[ FontPackTool.exe 설정 가이드 ]

  TTF 폰트로 롬 생성 시,
  12pt.로 설정하면 16x16 크기가 되며,
   9pt.로 설정하면 12x12 크기가 됩니다.

  유니코드를 제대로 지원하는 비트맵 폰트는 아래 4종류입니다.
  윈도 내장된 굴림체, 돋움체, 바탕체, 궁서체
  16x16, 12x12 사이즈가 모두 가능합니다.

  참고)
  GNU Unifont는 16x16 용 비트맵 유니코드 폰트입니다.
  http://unifoundry.com/unifont/index.html
  

[ 첨부 파일 ]

- FONTPACK.COM

  MSX-DOS/DOS2 용 프로그램입니다.
  롬 업뎃 및 IME, ANSI 스크린 모드를 설정하기 위해 쓰입니다.
  H/W V1, V2를 모두 지원합니다.


- STARTUP.ROM, BIOS.ROM

  FontPack의 내장 BIOS 롬입니다.
  H/W V1, V2 공용입니다.


- FontPackTool.exe

  FontPack 다운로드 용 롬을 생성하는 윈도 프로그램입니다.
  16x16 비트맵 폰트(FNT 및 TTF)를 변환해줍니다.


- 0000_00FF_ASCII.FNT

  1바이트 문자 용 16x16 폰트파일입니다.
  FontPack Tool에서 CP949롬 생성 시 사용가능합니다.


- JOHAB_844.FNT

  2바이트 한글 용 16x16 폰트파일(조합형 844 둥근모꼴)입니다.
  FontPack Tool에서 CP949롬 생성 시 사용가능합니다.


- A1A1_AEFE_SPE.FNT

  2바이트 특수문자 용 16x16 폰트파일입니다.
  FontPack Tool에서 CP949롬 생성 시 사용가능합니다.


- CAA1_FDFE_HANJA.FNT

  2바이트 한자 용 16x16 폰트파일입니다.
  FontPack Tool에서 CP949롬 생성 시 사용가능합니다.
