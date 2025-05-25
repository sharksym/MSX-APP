--------------------------------------------------
WAU Terminal v1.03
    By Yeongman Seo <sharksym@hitel.net>
--------------------------------------------------

@ UPDATE

- Added PAC-V support for ANSI Music

- Added ANSI File viewer mode (/F option)

--------------------------------------------------

@ WTERM.COM

- Terminal for WAU Wi-Fi


@ Requirements: MSX-DOS2, Memory Mapper 32KB


@ Feature

- Telnet
- ANSI File viewer
- ANSI Color
- ANSI Music
- YMODEM downloader
- SCREEN7 interlaced mode
- SCREEN7 progressive mode for CP437 only
- EUC-KR, CP949 Hangul
- Monochrome display emulation (Green, White)
- Vsync 50Hz/60Hz
- Local Echo


@ Special Key

STOP:  Exit
SPACE: Scroll stop (File viewer only)

GRAPH + V: V-Sync 60Hz/50Hz
GRAPH + I: Interlace/Progressive display
GRAPH + M: Monochrome display
GRAPH + E: Local Echo
GRAPH + Y: YMODEM Download

GRAPH + UP   : Page up
GRAPH + DOWN : Page down
GRAPH + LEFT : Home
GRAPH + RIGHT: End


@ Usage

Telnet: WTERM telnet_address [port] [option]

eg) WTERM bbs.hispamsx.org /P
    WTERM jpmud.duckdns.org 5555 /K /E


File viewer: WTERM filename /F [option]

eg) WTERM ansi-mus.ams /F
