86Box
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

사전 설치 환경
--
이 프로그램이 처음이거나 시스템 구성이 어려운 분들을 위한 MS-DOS와 Windows 95가 사전 설치된 환경을 제공합니다. 해당 사전 설치 환경은 다른 머신을 이용할 수 없지만 해당 메인보드에 사용 가능한 주변 장치들은 마음대로 변경 및 사용이 가능합니다. 이 머신으로 다른 운영 체제를 설치하고 싶으면 그렇게 해도 됩니다. 본인이 사용하는 CPU에 따라 퍼포먼스 하락이 있을 수도 있지만 랩탑이 아닌 데스크탑이라면 충분히 돌아갈 것입니다.

OS와 구동에 필요한 프로그램을 제외한 게임 또는 기타 소프트웨어는 설치되어 있지 않습니다. 사용에 참고하시기 바랍니다.

시작하기
---------------
에뮬레이터의 기능 및 사용자 인터페이스에 대한 개요는 [86Box 문서](https://86box.readthedocs.io/en/latest/index.html)를 참조하세요.

라이선싱
---------
86Box는 [GNU Gerneral Public License, version 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html) 이상으로 배포 되었습니다. 자세한 내용은 저장소 루트의 'COPYING' 파일을 참조하세요.

에뮬레이터는 선택적으로 [munt](https://github.com/munt/munt), [FluidSynth](https://www.fluidsynth.org/), [Ghostscript](https://www.ghostscript.com/) 및 [Discord Game SDK](https://discord.com/developers/docs/game-sdk/sdk-starter-guide)는 해당 라이선스에 따라 배포됩니다.
