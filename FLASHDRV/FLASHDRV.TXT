--------------------------------------------------
Flash Drive(tm) Tool v1.05 for MSX-DOS2
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------

* 업데이트

  DSK 이미지의 크기가 720KB를 초과하는 경우,
  /DO 및 /D2 옵션이 자동으로 설정됨.


* 요구 사항

  MSX-DOS2


* 사용법

FLASHDRV [Filename] [Option]

        /DO: Disable ONE-Drive
        /D2: Enable DOS2 kernel
        /T : Enable WX/WSX/turboR Turbo
        /E : Erase DiskROM

Eg:     FLASHDRV YS1.DSK
        FLASHDRV ASO_2022.DSK /D2
        FLASHDRV /E
