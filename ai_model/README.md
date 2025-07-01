# 🧠 AI Model (YOLOv5)

Smart SafetyNet의 객체 감지 기반 AI 추론 엔진입니다.  
PPE 착용 여부 판단, 사람 인식, 야간 침입 감지 등에 사용됩니다.

## 구성
- 학습된 YOLOv11 모델 (PyTorch/ONNX)
- 추론 스크립트 (`inference.py`)
- 클래스 매핑 및 후처리 로직

## 사용 기술
- YOLOv11
- ONNX Runtime / PyTorch
- OpenCV
