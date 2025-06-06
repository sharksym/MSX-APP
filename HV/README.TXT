----------------------------------------------------------------
    HV v1.6 (MSX-DOS2용 한글 텍스트 뷰어 2022.01.07)
        By 서영만 <sharksym@hitel.net>
----------------------------------------------------------------


* 개선 사항 v1.6

- FontPack V2 카트리지의 Unicode 폰트 처리추가.


* 한글 텍스트 뷰어

  MSX-DOS2에서 영문 및 한글 텍스트를 보여주는 프로그램입니다.
  최대 6만5천라인의 텍스트를 표시할 수 있습니다.

  UCS2 유니코드 LE/BE를 자동인식합니다.
  ISS 가사파일을 표시가능합니다.

  2바이트 KS 완성형 및 조합형 한글: 부가기기 없이 표시가능.
  CP949 확장한글 및 한자: FontPack 카트리지 필요.
  Unicode BMP: FontPack V2 카트리지가 필요.

  참고)
  FontPack V1으로 Unicode 문서를 볼 때,
  CP949에 존재하는 폰트는 코드변환으로 표시가 가능합니다.
  변환불가능한 폰트는 빈칸 문자로 대체됩니다.


* 요구 사항

  MSX-DOS2가 구동되는 MSX2 이상의 기종.
  메모리 매퍼 80KB 이상 필요하며, TSR로 동작합니다.
  (옵션) FontPack V1 및 V2 카트리지.


* 사용법

  HV FILENAME.EXT [리턴] 하면 됩니다.

  텍스트 뷰어 상에서는 아래의 키를 사용가능합니다.
  ESC       - 뷰어 종료
  SPACE     - 자동 읽기모드 (3초당 1라인 스크롤)
  TAB       - 완성/조합/ASCII 코드 전환
  SHIFT     - 12x12 / 16x16 폰트 크기 전환 (FontPack 전용)
  커서 UP   - 위로 스크롤
  커서 DOWN - 아래로 스크롤
  커서 RIGHT- 페이지 다운
  커서 LEFT - 페이지 업


* 환경 변수

  HV_CODE 이름으로 마지막 선택된 한글 코드를 기록합니다.
  환경 변수가 없는 경우, 기본은 완성형으로 처리합니다.


* 폰트 크기

  자체 영문/한글 폰트를 내장하고 있습니다.
  폰트 크기는 영문 8x16, 한글 16x16 입니다.
  한글의 경우 초중종 8x4x4벌식 조합폰트를 사용합니다.
  FontPack 카트리지가 있으면,
   영문 6x12, 한글 12x12 폰트를 쓸 수 있습니다.


* 화면 모드

  문자 출력은 인터레이스 스크린7 모드를 사용합니다.
  한 화면에서
  영문(8x16)의 경우 64 x 25개 문자를 출력가능합니다. 
  영문(6x12)의 경우 82 x 34개 문자를 출력가능합니다. 

  한라인이 최대 컬럼 수를 넘는 경우는,
    다음 라인으로 넘겨서 표시합니다. (Word wrap)


