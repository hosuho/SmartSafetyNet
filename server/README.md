# 📡 Raspberry Pi Server

Smart SafetyNet의 엣지 디바이스 서버 역할을 수행합니다.  
카메라로부터 영상 프레임을 수신하고 YOLO 기반 분석을 통해  
PPE 미착용, 야간 침입 등을 탐지하고 클라이언트에 알림을 전송합니다.

## 주요 기능
- RTSP 영상 송출 (GStreamer 또는 FFmpeg)
- YOLOv5 모델 추론
- HTTPS 알림 전송

## 사용 기술
- Python 3 / C++
- Flask / FastAPI
- YOLOv5 + ONNX Runtime
- GStreamer / FFmpeg
