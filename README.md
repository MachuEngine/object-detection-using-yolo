# Object Detection Using YOLOv5 🚀

이 프로젝트는 YOLOv5를 활용한 객체 검출 학습 및 실험을 기록한 것입니다.

## 프로젝트 소개
- YOLOv5 모델을 사용하여 커스텀 데이터셋으로 객체 검출을 학습하고, 추론을 수행함.
- 학습 과정에서 하이퍼파라미터 조정, 데이터 증강 기법 등을 실험함.

## 환경 설정
1. YOLOv5 레포지토리 클론 및 의존성 설치
2. 데이터셋 준비 및 YAML 파일 구성

## 학습 및 추론 실험
- **학습 명령어**: `python train.py --img 640 --batch 16 --epochs 3 --data data/coco128.yaml --weights yolov5s.pt`
- **추론 테스트**: `python detect.py --weights yolov5s.pt --img 640 --conf 0.25 --source data/images/bus.jpg`

## 실험 결과 및 분석
- 학습 도중 발견한 문제와 해결 방법
- 하이퍼파라미터 튜닝 결과 및 성능 향상 사례

## 참고 자료
- [YOLOv5 원본 레포지토리](https://github.com/ultralytics/yolov5)
- 관련 논문 및 튜토리얼 링크
  - [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)
  - [YOLO9000: Better, Faster, Stronger](https://arxiv.org/abs/1612.08242)
  - [YOLOv3: An Incremental Improvement](https://arxiv.org/abs/1804.02767)
  - [YOLOv4: Optimal Speed and Accuracy of Object Detection](https://arxiv.org/abs/2004.10934)
