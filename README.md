smi 자막 srt 변환 스크립트
=====================

[참고사이트](http://naclepark.blogspot.com/2015/03/smi2srt-converter-for-nas.html)

### 설명
- **targetdir** 로 설정한 디렉토리 (하위폴더 포함)의 smi 파일을 검색 후 같은 폴더에 srt 자막파일 생성해 주는 스크립트
- srt 자막파일 2개 생성: *.srt, *.kor.srt

### 사용법
1. smi2srt.sh 파일 아래 내용을 본인의 시스템에 맞게 수정합니다.
> ```bash
> targetdir='/volume1/_inbox_/download/manual'
> smidir='/volume1/docker/script'
> ```
> **targetdir** 은 smi 파일이 저장된 디렉토리
> **smidir** 은 smi2srt, smi2srt.sh 파일 위치 디렉토리
2. 시놀로지 작업스케쥴에서 smi2srt.sh 을 등록합니다.
