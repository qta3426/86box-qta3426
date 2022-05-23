86Box [![Build Status](http://ci.86box.net/job/86Box/badge/icon)](http://ci.86box.net/job/86Box)
=====
**86Box**는 1981년부터 PCI 버스를 기반으로 하는 최근의 시스템까지 IBM PC와 호환 가능하도록 설계된 오래된 OS 및 소프트웨어를 실행하는 저수준 x86 에뮬레이터 입니다.

기능
--------
* 유명한 하이퍼바이저와 비슷한 사용하기 쉬운 인터페이스
* 정확도에 중점을 둔 Pentium 까지의 8086 기반 프로세서의 저수준 에뮬레이션
* 가상 머신의 다양한 사용자 정의 기능
* 1981년 최초의 IBM PC 5150 또는 Micro Channel Architecture를 기반으로 하는 보다 모호한 IBM PS/2 시스템 라인과 같은 사용 가능한 시스템
* 그래픽 카드, 사운드 카드, 네트워크 어댑터, 하드 디스크 컨트롤러 및 SCSI 어댑터 등의 많은 주변 장치 지원
* Windows 내장 MIDI 지원, FluidSynth 또는 에뮬레이트 된 Roland 신디사이저로 MIDI 출력
* MS-DOS, 오래된 Windows 버전, OS/2, 다양한 Linux 배포판, BeOS, NEXTSTEP과 같은 시스템 및 이 시스템용 소프트웨어 실행 지원

시스템 요구 사항 및 권장 사항
---------------------------------------
* 인텔 Core 2 Duo 및 AMD 애슬론64 X2 이상
* Windows 버전: Windows 7 서비스 팩 1, Windows 8.1 또는 Windows 10
* Linux 버전: 우분투 16.04, 데비안 9.0 또는 2016년 이후 다른 배포판
* 4GB RAM 이상

성능은 호스트 및 게스트 구성에 따라 다를 수 있습니다. 대부분의 에뮬레이션 로직은 단일 스레드에서 실행되므로 일반적으로 더 나은 IPC(클럭당 명령 수)인 CPU를 사용중인 시스템은 더 높은 클럭 속도를 에뮬레이트 할 수 있습니다.

또한 여러 가상 머신을 보다 쉽게 관리할 수 있도록 86Box와 함께 관리자 소프트웨어(**Windows 전용**)를 사용하는 것이 좋습니다.
* [WinBox for 86Box](https://github.com/86Box/WinBox-for-86Box) by Laci bá'
  * 향상된 새로운 사용자 경험을 제공하는 관리 프로그램, 에뮬레이터 바이너리의 자동 업데이트 등.
  * 개발이 일시 중단되었지만 저장소가 유지중이기 때문에 아직까지 사용 가능합니다.
* [86Box Manager](https://github.com/86Box/86BoxManager) by [daviunic](https://github.com/daviunic) (Overdoze)
  * 간단한 인터페이스를 가진 기본적인 86Box 관리 프로그램.

그러나 '--vmpath'/'-P' 명령줄 옵션과 함께 86Box를 단독으로 사용할 수도 있습니다.

시작하기
---------------
에뮬레이터의 기능 및 사용자 인터페이스에 대한 개요는 [86Box 문서](https://86box.readthedocs.io/en/latest/index.html)를 참조하세요.

커뮤니티
---------
86Box 개발 및 레트로 컴퓨팅과 관련된 모든 것을 논의하기 위한 IRC 채널과 디스코드 서버를 운영 중입니다. 여러분의 의견을 기다립니다.

[![IRC 채널 방문](https://kiwiirc.com/buttons/irc.ringoflightning.net/86Box.png)](https://kiwiirc.com/client/irc.ringoflightning.net/?nick=86box|?#86Box)

[![디스코드 서버 방문](https://discordapp.com/api/guilds/262614059009048590/embed.png)](https://discord.gg/QXK9XTv)

라이선싱
---------
86Box는 [GNU Gerneral Public License, version 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 이상으로 배포 되었습니다. 자세한 내용은 저장소 루트의 'COPYING' 파일을 참조하세요.

에뮬레이터는 선택적으로 [munt](https://github.com/munt/munt), [FluidSynth](https://www.fluidsynth.org/), [Ghostscript](https://www.ghostscript.com/) 및 [Discord Game SDK](https://discord.com/developers/docs/game-sdk/sdk-starter-guide)는 해당 라이선스에 따라 배포됩니다.