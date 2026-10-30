# 메모리 닥터 (MemDoctor)

Windows PC의 메모리 사용량을 진단하고 정리하는 도구입니다. 프로세스·커널 풀·핸들 누수 추적, CPU·GPU·네트워크·저장소 모니터링, 임시 파일 정리 등을 제공합니다.

이 저장소는 **실행 파일 배포 전용**입니다. 소스 코드는 공개하지 않습니다.

## 설치

1. [최신 릴리스](https://github.com/Sunya0804/memdoctor/releases/latest)에서 `MemDoctor.exe`를 받습니다.
2. 원하는 폴더에 두고 실행합니다. (관리자 권한을 요청합니다.)

요구 사항: Windows 10/11 (x64), .NET Framework 4.8 (Windows에 기본 포함)

## 자동 업데이트

앱이 실행 중일 때 이 저장소의 최신 릴리스를 주기적으로 확인하고, 새 버전이 있으면 알려 줍니다. 설정 화면에서 끌 수 있습니다.

업데이트 파일은 앱에 내장된 공개 키로 서명을 확인한 뒤에만 설치됩니다. 각 릴리스의 자산:

- `MemDoctor.exe` — 실행 파일
- `MemDoctor.exe.sig` — 실행 파일의 RSA-SHA256 서명
- `version.txt` — 버전 번호
