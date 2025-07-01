# 📦 Qt Client

Smart SafetyNet의 데스크탑 클라이언트 프로그램입니다.  
Raspberry Pi에서 전송되는 RTSP 영상과 이벤트 정보를 수신하여  
영상 출력, 경고 팝업, 로그 기록, 설정 제어 등의 기능을 제공합니다.

## 주요 기능
- 실시간 RTSP 영상 스트리밍
- 이벤트 팝업 표시 및 SQLite 로그 저장
- 사용자 설정(ROI, 모자이크 등) 관리 UI

## 사용 기술
- Qt5 (C++)
- OpenCV
- SQLite3
- HTTPS (OpenSSL)
