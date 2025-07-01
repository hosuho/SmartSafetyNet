# Smart SafetyNet 🔐

AI 기반 산업 현장 안전 모니터링 시스템

## 📦 구성 디렉토리

- `client/`: Qt 기반 GUI 클라이언트 (RTSP + 알림 + 로그)
- `server/`: Raspberry Pi 서버 (영상 처리 + 이벤트 생성)
- `embedded/`: ARM 보드 제어 코드 (부저, LED 등)
- `ai_model/`: YOLOv5 기반 PPE 감지 및 추론 모델
- `docs/`: 시스템 설계서, 요구사항 문서, PPT 등
- `shared/`: 공통 설정 파일, 아이콘, JSON 스키마 등

## 🤼 R&R
| 이름   | GitHub ID  | 역할               |
| ---- | ---------- | ---------------- |
| 서호 민 | `shmin`   | 팀장 / Front-end / 문서 관리 |
| 김현석  | `blank` | Board Support Package (BSP)        |
| 정현구  | `blank`  | Computer Vision (AI, YOLO)     |
| 홍정원  | `blank` |  Back-end    |


## 🚀 빠른 실행

```bash
cd client/
mkdir build && cd build
cmake ..
make
./SmartSafetyNetClient
